
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Edward Espinosa Hernández</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      background-color: #f4f4f4; /* Cambia el color de fondo según tu preferencia */
      font-family: 'Arial', sans-serif; /* Cambia la fuente según tu preferencia */
      color: #333; /* Cambia el color del texto principal según tu preferencia */
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #4285f4; /* Cambia el color de fondo del encabezado según tu preferencia */
      color: #fff; /* Cambia el color del texto del encabezado según tu preferencia */
      text-align: center;
      padding: 20px;
    }

    main {
      padding: 20px;
    }

    .servicios ul {
      list-style: none;
      padding: 0;
    }

    select {
      padding: 10px;
      font-size: 16px;
    }

    .descripcion {
      margin-top: 10px;
    }

    footer {
      background-color: #4285f4; /* Cambia el color de fondo del pie de página según tu preferencia */
      color: #fff; /* Cambia el color del texto del pie de página según tu preferencia */
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Edward Espinosa Hernández</h1>
    <p>Experto en soluciones digitales, seguridad informática e inteligencia artificial</p>
  </header>
  <main>
    <section class="servicios">
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
    <section class="contacto">
      <h2>Contacto</h2>
      <p>Teléfono: +57 300 555 5555</p>
      <p>Correo electrónico: edward.espinosa@example.com</p>
    </section>
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

