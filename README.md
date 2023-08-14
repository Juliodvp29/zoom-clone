# Video Llamada App con Node.js

Esta es una aplicación simple de video llamada desarrollada en Node.js que utiliza WebRTC y Socket.io para habilitar la comunicación en tiempo real entre usuarios.

## Características

- Inicia y únete a salas de video llamada.
- Comparte video y audio en tiempo real.
- Muestra una cuadrícula de videos de los participantes en la sala.
- Permite a los usuarios desconectarse y reconectarse.

## Requisitos Previos

- Node.js y npm instalados en tu máquina.

## Instalación

1. Clona este repositorio o descarga los archivos.
2. Abre una terminal y navega hasta el directorio de la aplicación.
3. Ejecuta el siguiente comando para instalar las dependencias:


## Uso

1. Ejecuta el servidor Node.js con el siguiente comando: `npm run devStart`

2. Abre tu navegador y navega a `http://localhost:3000`.
3. Serás redirigido a una sala de video llamada única. Comparte el enlace con otros participantes para unirse a la misma sala.
4. Asegúrate de permitir el acceso a tu cámara y micrófono cuando se te solicite.

## Estructura del Proyecto

- `server.js`: El servidor Node.js que configura Express y Socket.io para la aplicación.
- `views/room.ejs`: La plantilla EJS para renderizar la interfaz de la sala de video llamada.
- `public/script.js`: El archivo JavaScript para el cliente que maneja la lógica de la video llamada.
.
## Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar esta aplicación, siéntete libre de hacer un fork del repositorio y enviar un pull request.



