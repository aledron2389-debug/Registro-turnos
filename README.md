# Turno · Atención al cliente

Aplicación web responsive para organizar turnos presenciales. Permite asignar turnos a tres mesas de atención, llamar al siguiente desde una mesa, finalizar atenciones, consultar la fila de espera y revisar conteos por servicio.

## Publicación

Proyecto estático conectado al repositorio público de GitHub y a Vercel; los cambios en `main` despliegan automáticamente. No requiere comando de build. Incluye un tono al crear turnos y anuncios de voz al llamar a una persona; el audio se puede silenciar desde el panel.

> Los datos actuales viven en el navegador del dispositivo (localStorage); para uso multiusuario hace falta conectar una base de datos y autenticación.
