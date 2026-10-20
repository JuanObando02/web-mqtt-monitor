# Monitor MQTT (web)

Pagina estatica que se suscribe al broker por WebSocket y muestra los datos del ESP32.

- Cambia `DEFAULT_URL` y `DEFAULT_TOPIC` en `index.html` (tambien se pueden editar en la propia pagina).
- Si la pagina se sirve por **https**, el broker debe usarse con **wss://** (el navegador bloquea ws:// desde https).

## Despliegue en Coolify
Nuevo recurso desde este repo, Build Pack **Dockerfile**, puerto **80**.
