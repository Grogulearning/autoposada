# Autoposada 2026

Invitación digital de la posada de Autopaquete.

Link: https://grogulearning.github.io/autoposada/

## Buzones

- Cualquiera con el link agrega su buzón con **Agregar mi buzón** (nombre, hasta 3 artículos con enlace y foto) y crea un **PIN** de 4 dígitos.
- Para cambiarlo: abre su sobre → **Editar** (o **Borrar buzón**) y escribe su PIN. Al editar puede cambiar o quitar artículos y fotos.
- Tras 10 intentos con PIN incorrecto, el buzón se bloquea y solo la organizadora puede cambiarlo.
- La organizadora tiene un PIN que funciona en todos los buzones (no está en este repo).

Los datos viven en Supabase, proyecto **autoposada** (tabla `buzones`, fotos en Storage → `fotos`).

`buzones.json` sigue disponible para agregar buzones a mano (no se pueden editar desde la invitación).
