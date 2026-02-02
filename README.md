<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- Título que aparece en la pestaña del navegador -->
  <title>Esteban González Osso | Portfolio</title>

  <style>
    /* ================================
       ESTILOS GENERALES DE LA PÁGINA
    ================================= */

    body {
      font-family: Arial, sans-serif; /* Fuente simple y profesional */
      margin: 0;
      padding: 0;
      background: #ffffff;
      line-height: 1.5;
    }

    /* Contenedor principal centrado */
    .container {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }

    /* Caja tipo tarjeta */
    .card {
      border: 1px solid #e5e5e5;
      border-radius: 12px;
      padding: 25px;
    }

    /* ================================
       HEADER: FOTO + NOMBRE
    ================================= */

    .header {
      display: flex;              /* Foto y texto en fila */
      align-items: center;        /* Centrado vertical */
      gap: 20px;                  /* Espacio entre foto y texto */
    }

    /* Foto de perfil */
    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;         /* Hace la foto circular */
      object-fit: cover;          /* Ajusta la imagen sin deformar */
      border: 2px solid #ddd;
    }

    /* Nombre grande */
    .name {
      font-size: 34px;
      margin: 0;
    }

    /* Subtítulo */
    .role {
      margin: 4px 0 0;
      font-weight: bold;
      color: #444;
    }

    /* ================================
       INFORMACIÓN DE CONTACTO
    ================================= */

    .contact {
      margin-top: 15px;
    }

    .contact a {
      color: #0b5fff;
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    /* ================================
       SECCIÓN ABOUT
    ================================= */

    h2 {
      margin-top: 25px;
      font-size: 18px;
    }

    footer {
      margin-top: 20px;
      font-size: 12px;
      color: gray;
    }
  </style>
</head>

<body>
  <main class="container">

    <!-- TARJETA PRINCIPAL -->
    <section class="card">

      <!-- HEADER CON FOTO + TEXTO -->
      <div class="header">

        <!-- FOTO (reemplaza "foto.jpg" por tu archivo real) -->
        <img src="foto.jpg" alt="Foto de Esteban" class="profile-pic">

        <!-- TEXTO PRINCIPAL -->
        <div>
          <h1 class="name">Esteban González Osso</h1>
          <p class="role">Business Intelligence Analyst | Data Analysis</p>
        </div>
      </div>

      <!-- CONTACTO -->
      <div class="contact">
        <p>📞 <a href="tel:+573222350974">+57 322 235 0974</a></p>
        <p>📧 <a href="mailto:esteban0sso@outlook.com">esteban0sso@outlook.com</a></p>
        <p>💼 <a href="https://www.linkedin.com/in/esteban0sso/" target="_blank">
          LinkedIn: esteban0sso</a></p>
      </div>

      <!-- ABOUT -->
      <h2>About</h2>

      <p>
        Analyst with over 3 years of experience in finance, projects, and process optimization.
        I specialize in transforming data into strategic decisions that help companies reduce costs,
        optimize time, profile customers, and improve profitability.
      </p>

      <p>
        My differentiator is that I do not limit myself to technical analysis; I understand the business
        behind the data. I identify strengths and areas for improvement, using data to enhance what
        already works and correct what limits your company’s growth.
      </p>

    </section>

    <!-- FOOTER -->
    <footer>
      © 2026 Esteban González Osso
    </footer>

  </main>
</body>
</html>


