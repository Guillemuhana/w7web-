# W-7 · Landing

Sitio estático (un solo `index.html`, sin build).

## Antes de publicar
Editá el bloque `CONFIG` al final de `index.html`:
- `whatsapp`: número con código de país, sin `+` ni espacios.
- `loginUrl`: URL de la consola.
- `formEndpoint` (opcional): webhook que recibe `{nombre, barrio, telefono}`. Vacío = abre WhatsApp con los datos.

## Ver en local
Abrí `index.html` en el navegador, o con la extensión Live Server de VS Code.

## Deploy en Vercel
1. Subí la carpeta a un repo de GitHub.
2. En Vercel: Add New → Project → importás el repo.
3. Framework Preset: **Other**. Sin build command ni output directory.
4. Deploy.
