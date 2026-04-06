🐾 La Colita Feliz – Web de Centro de Mascotas

Proyecto web desarrollado en equipo como parte del bootcamp de desarrollo Front-End de Eurofirms.
Consiste en el diseño y maquetación de una web corporativa para un centro de cuidado de mascotas, con múltiples páginas informativas, formularios interactivos y una sección de tienda.

El proyecto pone el foco en la maquetación con HTML y CSS, la coherencia visual y el trabajo colaborativo.

🚀 Tecnologías utilizadas
- HTML5
- CSS3
- Flexbox (para layout y distribución de elementos)
- Google Fonts

📁 Estructura del proyecto:

/project  

│
├── index.html  

├── servicios.html  

├── equipo.html  

├── sobre.html  

├── contacto.html  

├── tienda.html  

├── newsletter.html  

├── suscripcion.html  

├── politicaprivacidad.html  

│
├── styles.css  

|__ docs/  

├── images/  

└── .git/

⚙️ Decisiones técnicas:

1. Diseño previo con Lucid.app
Antes de comenzar la maquetación, se realizó la planificación visual del proyecto mediante un tablero colaborativo en Lucid.app.
En él se definieron la estructura de las páginas, distribución de contenidos, estilo visual y organización general del sitio.

📎 Ver diseño completo:
👉 https://github.com/atroyano6/proyecto-html-css-animales/blob/main/docs/dise%C3%B1o-lucid.pdf

2. Uso de una paleta de colores consistente
Se estableció una paleta de colores definida desde el inicio del proyecto, aplicada de forma coherente en todas las páginas mediante variables CSS (:root).
Esto permite mantener una identidad visual uniforme y facilita la escalabilidad y mantenimiento del código.

3. Desarrollo de marca y uso de identidad visual propia
Se ha trabajado una identidad visual propia para el proyecto, incluyendo logo, iconografía y estilo gráfico.
Los elementos visuales (logo, colores y tipografía) se integran en todas las páginas para reforzar la coherencia de marca.

4. Distribución de contenido basada en Flexbox
Se ha utilizado Flexbox como sistema principal de maquetación para organizar los elementos en todas las páginas.
Esto ha permitido construir layouts estructurados, alineaciones complejas y una distribución clara del contenido sin necesidad de frameworks externos.

5. Separación de estilos por contexto mediante clases en el <body>
Cada página incluye una clase específica en la etiqueta <body> (por ejemplo: .servicios, .contacto, .newsletter), lo que permite aplicar estilos independientes sin interferencias entre secciones.

6. Diseño de flujo de navegación y experiencia de usuario (UX).
Se ha diseñado un flujo de navegación guiado con el objetivo de facilitar la experiencia del usuario y dirigirlo hacia las acciones clave dentro de la web. Desde la página de inicio, el usuario es conducido mediante llamadas a la acción claras (como “Descubre nuestros servicios”), además de contar con una navegación global accesible en todo momento mediante el menú principal y el footer.

A lo largo del sitio, se han incorporado accesos directos estratégicos:
- En la página de servicios, el usuario puede navegar directamente entre secciones (veterinaria, peluquería, residencia, etc.).
- Se incluyen botones de contacto en puntos clave para evitar fricción (por ejemplo, dudas sobre servicios o procesos de adopción).
- Desde distintas secciones se puede acceder a la tienda o a la newsletter sin necesidad de volver al menú principal.

Además, se han diseñado flujos cerrados en acciones importantes, como:
- Envío del formulario de contacto.
- Suscripción a la newsletter.
- En estas páginas finales se elimina la barra de navegación para centrar la atención del usuario en una única decisión (finalizar la acción o volver al inicio), evitando distracciones.

Este enfoque permite:
1. Mejorar la claridad del recorrido del usuario.
2. Reducir la sobrecarga de opciones en momentos clave.
3. Reforzar los objetivos principales del sitio (contacto, conversión y navegación intuitiva).

👩‍💻 Equipo

Proyecto desarrollado por:

- Rozilene Amorim
- Estefanía Molina
- Andrea Troyano

▶️ Cómo ejecutar el proyecto
Descargar o clonar el repositorio
Abrir la carpeta del proyecto
Ejecutar el archivo index.html en el navegador

No se requiere instalación ni dependencias adicionales.

📸 Capturas

![captura-index](https://github.com/user-attachments/assets/e345517f-9f0f-4d86-8d32-c748f5c4d7da)

![captura-servicios](https://github.com/user-attachments/assets/26c48c4f-7f7f-4c30-8e1c-01959a859dca)

![captura-equipo](https://github.com/user-attachments/assets/aa7d13a4-e763-458f-be4c-72fd510e665e)

![captura-sobre](https://github.com/user-attachments/assets/9f470d87-8dd0-493e-8ef0-9e15bef1d50b)

![captura-contacto](https://github.com/user-attachments/assets/9092154e-e087-42c9-8660-9d066ec16ad9)

![captura-tienda](https://github.com/user-attachments/assets/0f01a587-a699-4464-b26d-1ff0af73bd6f)

![captura-newsletter](https://github.com/user-attachments/assets/75551087-ebb5-444d-a703-64a61df95a70)

![captura-suscripcion](https://github.com/user-attachments/assets/11c255ec-3b27-449e-a272-1a70e6137d20)


📌 Notas
El proyecto está optimizado para visualización en escritorio
No se ha implementado diseño responsive debido a limitaciones de tiempo
Los formularios funcionan como simulación de flujo (sin backend)
