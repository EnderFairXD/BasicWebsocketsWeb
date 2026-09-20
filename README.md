# WebSocket Broadcast Server

Un servidor de WebSockets básico construido con Node.js y la librería `ws`. Incluye un cliente HTML/JS nativo para demostrar el envío y recepción de mensajes en tiempo real (Broadcasting).

## Características
* **Servidor en Node.js:** Utiliza la librería `ws` para gestionar múltiples conexiones en el puerto 8080.
* **Cliente Vanilla JS:** Interfaz simple integrada en `index.html` para monitorear el estado del túnel y ver los registros (logs) del sistema sin frameworks adicionales[cite: 8].
* **Broadcasting:** Cualquier mensaje enviado por un cliente se retransmite automáticamente a todos los usuarios conectados[cite: 8].

## Instalación y Uso

1. Asegúrate de tener instalado [Node.js](https://nodejs.org/).
2. Clona este repositorio en tu máquina local.
3. Abre una terminal en la carpeta del proyecto e instala las dependencias:
   ```bash
   npm install