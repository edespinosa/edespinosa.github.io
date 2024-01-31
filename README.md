<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Edward Espinosa Hernández</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
  <style>
    body {
      background-color: #2c3e50;
      font-family: 'Roboto', sans-serif;
      color: #ecf0f1;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #3498db;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    nav {
      background-color: #2980b9;
      text-align: center;
      padding: 10px;
    }

    nav a {
      color: #ecf0f1;
      margin: 0 15px;
      text-decoration: none;
      font-size: 18px;
    }

    main {
      padding: 20px;
    }

    .servicios {
      background-color: #34495e;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .servicios h2 {
      color: #ecf0f1;
    }

    select {
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
    }

    .descripcion {
      margin-top: 10px;
    }

    .descripcion p {
      font-size: 16px;
    }

    .contacto {
      background-color: #2ecc71;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .contacto h2 {
      color: #ecf0f1;
    }

    .acerca-de {
      background-color: #e74c3c;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .acerca-de h2 {
      color: #ecf0f1;
    }

    .redes-sociales {
      margin-top: 20px;
      text-align: center;
    }

    .redes-sociales a {
      color: #ecf0f1;
      margin: 0 10px;
      font-size: 20px;
    }

    img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Edward Espinosa Hernández</h1>
    <p>Experto en soluciones digitales, seguridad informática e inteligencia artificial</p>
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
      <label for="servicios">Selecciona un servicio:</label>
      <select id="servicios">
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
      <img src="tu-imagen.jpg" alt="Edward Espinosa" />
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
    document.getElementById("servicios").addEventListener("change", function() {
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
