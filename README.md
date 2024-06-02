# Tarea 1 Cuatro en Línea - Comunicación de Datos y Redes

Este proyecto es parte de la tarea 1 de programación del curso de Comunicación de Datos y Redes 2024. Implementa el juego "Cuatro en Línea" utilizando el modelo Cliente/Servidor con sockets TCP en C++.

## Estructura del Directorio

El proyecto está organizado en dos subdirectorios para separar las responsabilidades del cliente y del servidor:

Connect4/
├── Cliente/
│ ├── README.md
│ ├── Client.cpp
│ └── Makefile
├── Servidor/
│ ├── README.md
│ ├── Server.cpp
│ └── Makefile
├── README.md

## Compilación y Ejecución

### Servidor

Para compilar y ejecutar el servidor, sigue estos pasos:

1. Navega al directorio `Servidor/`.
2. Ejecuta `make` para compilar el servidor.
3. Inicia el servidor con `./servidor <PUERTO>`, donde `<PUERTO>` es el número de puerto en el que deseas que el servidor escuche.

### Cliente

Para compilar y ejecutar el cliente, sigue estos pasos:

1. Navega al directorio `Cliente/`.
2. Ejecuta `make` para compilar el cliente.
3. Conecta al cliente con `./cliente <IP_SERVIDOR> <PUERTO>`, donde `<IP_SERVIDOR>` es la dirección IP del servidor y `<PUERTO>` es el puerto en el que el servidor está escuchando.

## Funcionalidades

- **Conexión TCP:** Emplea sockets TCP para la comunicación entre cliente y servidor.
- **Gestión de Conexiones Concurrentes:** El servidor puede manejar múltiples partidas simultáneamente utilizando multithreading.

## Requisitos

- Sistema operativo: Linux.
- Compilador de C++ que soporte C++11 o superior (g++, clang++, etc.).

## Autores

- Patricia Gonzalez Caamaño
- Felipe Miranda Rebolledo

Ingeniería Civil en Informática
Universidad del Bio bio