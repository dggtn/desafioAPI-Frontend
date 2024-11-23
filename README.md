<header>
<h1>Desafío de Desarrollo Backend y Frontend: Frases Aleatorias de Películas y Series</h1>
</header>

<div class="container">
<section class="description">
   <h2>Introducción</h2>
   <p>
       Este desafío tiene como objetivo poner en práctica los conocimientos adquiridos durante el curso, enfocándonos en el desarrollo de una aplicación completa que involucra tanto el frontend como el backend. A través de mini desafíos, aprenderemos a conectar las rutas del frontend con los endpoints del backend, y cómo hacer uso de una base de datos para almacenar y gestionar información.
   </p>
   <p>
       En esta ocasión, vamos a construir una aplicación que no solo presentará las frases aleatorias de películas y series, sino que también se basará en una API REST desarrollada con Spring Boot. Los datos, como las frases, los personajes y las series, se almacenarán en una base de datos PostgreSQL. ¡Un desafío muy interesante!
   </p>
</section>

<section class="challenge-details">
   <h2>Detalles del Desafío</h2>
   <p>Las características clave de la aplicación son las siguientes:</p>
   <ul>
       <li>La aplicación presentará frases aleatorias de películas y series, como "Que la fuerza te acompañe" de Star Wars, o "Los Amigos No Mienten" de Stranger Things.</li>
       <li>Los datos de las frases, personajes y series estarán almacenados en una base de datos PostgreSQL, que gestionaremos dentro de nuestra propia infraestructura.</li>
       <li>Usaremos **Spring Boot** para crear un **backend robusto** que expondrá un **API REST** para el frontend.</li>
       <li>El frontend se encargará de consumir estas rutas de la API y mostrar las frases aleatorias de manera dinámica.</li>
       <li>El proyecto será creado desde cero usando **Spring Initializr** para inicializar la estructura del proyecto Spring Boot.</li>
   </ul>
</section>

<section class="tech-stack">
   <h2>Tecnologías Utilizadas</h2>
   <p>Este desafío involucra el uso de diversas tecnologías para cubrir tanto el frontend como el backend:</p>
   <ul>
       <li><strong>Java</strong>: Lenguaje de programación principal para el desarrollo del backend con Spring Boot.</li>
       <li><strong>Spring Boot</strong>: Framework de Java para crear la API REST, manejar la configuración, y exponer las rutas que consumirá el frontend.</li>
       <li><strong>PostgreSQL</strong>: Base de datos relacional donde almacenaremos las frases, personajes y series. La conexión a la base de datos se gestionará desde Spring Boot.</li>
       <li><strong>API REST</strong>: Creamos endpoints RESTful que devolverán las frases aleatorias, junto con información relacionada (personaje, serie, etc.).</li>
       <li><strong>Frontend (HTML, CSS, JavaScript)</strong>: El frontend se encargará de consumir las rutas de la API REST y mostrar las frases aleatorias al usuario, con una interfaz sencilla.</li>
   </ul>
</section>
