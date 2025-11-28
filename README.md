# dinogame
🦖 Dino Game Accesible - Control por Voz

Este proyecto consiste en una adaptación del clásico juego "Dino Run" de Google Chrome, modificado para ser controlado mediante comandos de audio (aplausos) en lugar de teclado.

El objetivo principal es ofrecer una alternativa de entretenimiento accesible para personas con discapacidades motrices o dificultades para manipular periféricos físicos como teclados o ratones.

🚀 Demo

Puedes probar el juego abriendo el archivo index.html en tu navegador.

🛠️ Tecnologías Utilizadas

HTML5 / CSS3 / JavaScript: Estructura y lógica del videojuego.

Teachable Machine (Google): Entrenamiento del modelo de Inteligencia Artificial para reconocimiento de audio.

TensorFlow.js: Librería para ejecutar el modelo de Machine Learning directamente en el navegador.

📋 Instrucciones de Instalación y Ejecución

No se requiere una instalación compleja de servidores, ya que el proyecto corre en el cliente (navegador).

Descargar: Clona este repositorio o descarga el archivo ZIP.

Ejecutar: Haz doble clic en el archivo index.html.

Permisos:

Al abrir el juego, el navegador solicitará permiso para utilizar el micrófono.

Haz clic en "Permitir" (Allow).

Jugar:

Presiona el botón "INICIAR MICRÓFONO Y JUEGO".

Espera a que el estado cambie a "Escuchando...".

¡Aplaude fuerte para hacer saltar al dinosaurio!

📂 Estructura del Proyecto

index.html: Contiene todo el código fuente (Front-end y lógica de IA).

README.md: Instrucciones de uso.

docs/: Documentación y reporte del proyecto.

🤖 Modelo de IA

El modelo fue entrenado para reconocer dos clases de audio:

Ruido de fondo: El juego continúa sin acciones.

Aplauso: Activa la función de salto (jump()).

URL del modelo: https://teachablemachine.withgoogle.com/models/SIm4gQPkS/
