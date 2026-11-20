# Autoposada 2026

Invitación digital de la posada de Autopaquete.

Link: https://grogulearning.github.io/autoposada/

## Cómo agregar o cambiar un buzón

1. Abre `buzones.json` y toca el lápiz (Edit).
2. Copia un bloque de persona y cambia los datos:

```json
{
  "nombre": "Nombre de la persona",
  "opciones": [
    { "titulo": "Nombre del artículo", "link": "https://...", "foto": "fotos/nombre-1.jpg" },
    { "titulo": "Otro artículo", "link": "https://...", "foto": "fotos/nombre-2.jpg" }
  ]
}
```

- Separa cada persona con una coma `,` (el último bloque no lleva coma).
- `link` y `foto` pueden ir vacíos: `""`.
- Puede tener hasta 3 opciones (o más, si quieres).

3. Toca **Commit changes**. En 1 o 2 minutos se actualiza la invitación.

## Cómo subir una foto

1. Entra a la carpeta `fotos`.
2. **Add file → Upload files** y sube la imagen (una captura del producto sirve).
3. Ponle un nombre sencillo, sin espacios ni acentos, por ejemplo `ana-1.jpg`.
4. En `buzones.json` escribe esa ruta en `"foto": "fotos/ana-1.jpg"`.
