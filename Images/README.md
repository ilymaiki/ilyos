# Images

Carpeta de recursos del playbook (se empaqueta dentro del `.apbx`).

## Fondo de pantalla personalizado

1. Coloca aquí tu imagen con el nombre **`wallpaper.jpg`** (también valen `.png` y `.bmp`).
2. Si prefieres otro nombre, edita en `Configuration/Tasks/personalization.yml` la línea `$src = 'Images\wallpaper.jpg'` y cámbiala por el tuyo.
3. No hace falta nada más: si el fichero no existe, la task se salta ese bloque **sin fallar**, así que puedes empaquetar y probar el playbook antes de tener el fondo listo.
