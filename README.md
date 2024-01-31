<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="robots" content="index,follow">
  <meta name="keywords" content="desarrollo web, seguridad informática, inteligencia artificial">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="language" content="es">
  <meta name="author" content="Edward Espinosa Hernandez">

  <title>Edward Espinosa Hernández</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">

  <style>
    /* Estilos van aquí */
  </style>
</head>
<body>
  <header>
    <h1>Edward Espinosa Hernández</h1>
    <p>Experto en soluciones digitales, seguridad informática e inteligencia artificial con más de 10 años innovando digitalmente y más de 500 emprendimientos.</p>
  </header>
  <nav>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contáctenos</a>
    <a href="#perfil">Perfil</a>
    <a href="#aporte-social">Aporte Social</a>
  </nav>
  <main>
    <section id="servicios" class="servicios">
      <h2>Servicios</h2>
      <!-- Etiqueta for debe coincidir con el id del select -->
      <label for="servicios">Selecciona un servicio:</label>
      <!-- Añadido un id único para evitar conflictos con JavaScript -->
      <select id="serviciosSelect">
        <option value="desarrollo-web">Desarrollo web</option>
        <option value="seguridad-informatica">Seguridad informática</option>
        <option value="inteligencia-artificial">Inteligencia artificial</option>
      </select>
      <div class="descripcion">
        <p id="descripcion-servicio">Selecciona un servicio para ver la descripción.</p>
      </div>
    </section>
    <section id="contacto" class="contacto">
      <h2>Contacto</h2>
      <p>Teléfono: +57 300 555 5555</p>
      <p>Correo electrónico: edward.espinosa@example.com</p>
    </section>
    <section id="perfil" class="acerca-de">
      <h2>Perfil</h2>
      <!-- Cambiado "imagen" por una ruta de ejemplo -->
      <img src="ruta/de/la/imagen.jpg" alt="Edward Espinosa" />
      <p>Soy un apasionado por la tecnología y especialista en soluciones digitales. Con experiencia en desarrollo web, seguridad informática y el fascinante mundo de la inteligencia artificial, mi objetivo es brindar soluciones innovadoras y seguras para satisfacer las necesidades de mis clientes.</p>
    </section>
    <section id="aporte-social" class="aporte-social">
      <h2>Aporte Social</h2>
      <!-- Incluye aquí contenido relacionado con tu aporte social -->
    </section>
    <div class="redes-sociales">
      <a href="https://www.facebook.com/tu-facebook" target="_blank"><i class="fab fa-facebook"></i></a>
      <a href="https://wa.me/tunumerodewhatsapp" target="_blank"><i class="fab fa-whatsapp"></i></a>
    </div>
  </main>
  <footer>
    <p>Copyright &copy; 2023 Edward Espinosa Hernández</p>
  </footer>

  <script>
    // Cambiado el id para evitar conflictos
    document.getElementById("serviciosSelect").addEventListener("change", function() {
      var descripcionServicio = document.getElementById("descripcion-servicio");
      switch (this.value) {
        case "desarrollo-web":
          descripcionServicio.innerText = "Desarrollo de sitios web a medida con las últimas tecnologías.";
          break;
        case "seguridad-informatica":
          descripcionServicio.innerText = "Asesoramiento y implementación de medidas de seguridad informática.";
          break;
        case "inteligencia-artificial":
          descripcionServicio.innerText = "Desarrollo de soluciones basadas en inteligencia artificial y machine learning.";
          break;
        default:
          descripcionServicio.innerText = "Selecciona un servicio para ver la descripción.";
      }
    });
  </script>
</body>
</html>

