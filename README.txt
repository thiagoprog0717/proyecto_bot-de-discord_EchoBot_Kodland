2. Título y descripción del proyecto
Título: EcoBot: Concientización sobre el Calentamiento Global
Autor: Thiago Corrales
Descripción: Un bot interactivo para Discord desarrollado en Python que educa, evalúa y concientiza a los usuarios sobre la crisis climática actual mediante comandos informativos, recursos visuales y síntesis de voz.

3. Descripción del proyecto
El propósito principal de este proyecto es visibilizar y educar sobre la problemática del calentamiento global de una manera accesible y dinámica. A través de Discord, una plataforma muy popular, el bot busca transformar información científica y ambiental en un formato fácil de entendar.

4. Funciones y características
Cuenta con una amplia variedad de comandos (como =PEP, =CELC, =QHDC) que explican desde las causas del efecto invernadero hasta qué es la huella de carbono y cómo las energías renovables ayudan a mitigar el problema.

conntiene un minijuego de 15 preguntas con botones interactivos (estilo Kahoot) usando la interfaz de usuario de Discord, permitiendo a los usuarios poner a prueba sus conocimientos de forma divertida.

Utiliza la biblioteca pyttsx3 para leer en voz alta las respuestas y explicaciones proporcionadas por el bot, haciendo el proyecto más accesible y llamativo.

Los comandos informativos están acompañados de infografías e imágenes enviadas directamente al chat para complementar el aprendizaje y retener la atención del usuario.

Incluye un comando dedicado (=detener) para detener la síntesis de voz en caso de ser necesario, otorgando control al usuario sobre la experiencia auditiva.

5. Demostración del funcionamiento del proyecto
A continuación, se presentan las capturas de pantalla que demuestran cómo interactúa el bot con los usuarios en el servidor de Discord:

Comando de inicio y saludo: El bot respondiendo al comando =start con su saludo inicial, la breve explicación y la infografía introductoria.
Enlace/ID de la imagen: image_5c6cbe.jpg

Cuestionario interactivo: Demostración del comando =quiz mostrando la primera pregunta y los botones interactivos (A, B, C, D) listos para que el usuario responda.
Enlace/ID de la imagen: image_5c6c62.png



6. Instalación y uso del proyecto
Para ejecutar este bot en tu propia máquina o servidor, sigue estos pasos:

Requisitos previos: Asegúrarse de tener Python 3.8 o superior instalado.

Instalación de dependencias: Abre tu terminal y ejecuta los siguientes comandos para instalar las bibliotecas necesarias:

pip install discord.py

pip install pyttsx3



Abre el código y reemplaza el texto al final ("hola desarrollador o usuario, pon tu token aca") con el Token real de tu aplicación proporcionado por el Portal de Desarrolladores de Discord.

Corre el script en tu editor de código o terminal.

 Ve a tu servidor de Discord y escribe =help para ver la lista completa de comandos disponibles.

7. Comentarios
¡La retroalimentación es clave para mejorar! Si tienes sugerencias para agregar nuevas preguntas al quiz, actualizar la información sobre el cambio climático, o encuentras algún error en la síntesis de voz, puedes contactarme directamente a través de Discord o dejar un comentario en el repositorio del proyecto. Las contribuciones para añadir más idiomas o nuevas infografías son siempre bienvenidas.

8. Conclusión
El calentamiento global es un desafío urgente que nos afecta a todos, y la educación es el primer paso para enfrentarlo. Este proyecto demuestra cómo la programación en Python puede ser utilizada no solo para crear herramientas técnicas, sino también para generar un impacto social positivo. Al automatizar la difusión de información vital y hacerla interactiva, este bot facilita que cualquier comunidad en Discord comience a tomar conciencia sobre su impacto en el planeta y las acciones que podemos tomar hoy para proteger nuestro futuro.