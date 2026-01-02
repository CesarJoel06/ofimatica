# CFOCAP - Verificación de Certificados (Web estática)

## Estructura
- `index.html`: pantalla simple para ingresar el código y redirigir.
- `c/<CODIGO>/index.html`: página de verificación con el diseño base (según la preforma).
- `c/<CODIGO>/certificado.pdf`: el PDF del certificado (debe llamarse `certificado.pdf`).
- `assets/img/logo.png`: logo.

## Cómo probar localmente
1) En una terminal, ubíquese en la carpeta del proyecto.
2) Levante un servidor local (recomendado):
   - Python: `python -m http.server 8000`
3) Abra:
   - 

## Cómo crear un nuevo certificado
1) Cree carpeta: `c/MI-CODIGO/`
2) Copie el PDF dentro como: `certificado.pdf`
3) Duplique el `index.html` del demo y reemplace:
   - Código en enlaces (MI-CODIGO)
   - Nombre del acreedor
   - Nombre del curso

## QR
Genere el QR apuntando a:
`/c/MI-CODIGO/`
