

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="robots" content="index,follow">
  <!-- Otras metaetiquetas y enlaces van aquí -->
  <title>{{ page.title }}</title>
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

    /* Otros estilos van aquí */

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
    <h1>{{ page.title }}</h1>
    <p>Experto en soluciones digitales, seguridad informática e inteligencia artificial...</p>
  </header>
  <nav>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contáctenos</a>
    <a href="#perfil">Perfil</a>
    <a href="#aporte-social">Aporte Social</a>
  </nav>
  <main>
    <section id="servicios" class="servicios">
      <!-- Contenido del servicio va aquí -->
    </section>
    <section id="contacto" class="contacto">
      <!-- Contenido del contacto va aquí -->
    </section>
    <section id="perfil" class="acerca-de">
      <!-- Contenido del perfil va aquí -->
    </section>
    <section id="aporte-social" class="aporte-social">
      <!-- Contenido del aporte social va aquí -->
    </section>
    <div class="redes-sociales">
      <a href="https://www.facebook.com/tu-facebook" target="_blank"><i class="fab fa-facebook"></i></a>
      <a href="https://wa.me/tunumerodewhatsapp" target="_blank"><i class="fab fa-whatsapp"></i></a>
    </div>
  </main>
  <footer>
    <p>Copyright &copy; {{ "now" | date: "%Y" }} Edward Espinosa Hernández</p>
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
