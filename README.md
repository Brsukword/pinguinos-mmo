🐧 Mundo Pingüino MMO

Un juego multijugador masivo en tiempo real donde cada jugador es un pingüino.
Desarrollado con Node.js (Socket.io), Nginx y Docker.

🚀 Cómo jugar en tu PC

Requisitos

Tener Docker Desktop instalado.

Tener Git instalado.

Instalación Rápida

Abre tu terminal (PowerShell, CMD o Bash) y ejecuta:

# 1. Descargar el juego
git clone [https://github.com/Brsukword/pinguinos-mmo.git](https://github.com/Brsukword/pinguinos-mmo.git)

# 2. Entrar a la carpeta
cd pinguinos-mmo

# 3. Iniciar el servidor
docker compose up --build


Abre tu navegador y entra a:
👉 http://localhost

🎮 Controles

Flechas del teclado: Moverse.

Click en pantalla: Moverse hacia el punto.

Chat: Escribe en la caja inferior y presiona Enter.

Móvil: Usa la cruceta táctil en pantalla.

🛡️ Características Técnicas

Anti-Lag: Sistema de predicción de movimiento del lado del cliente.

Censura: Filtro de palabras ofensivas en nombres y chat.

Dockerizado: Frontend (Nginx) y Backend (Node) totalmente aislados.

Responsive: Funciona en PC y Celulares.

Hecho por Brsukword
