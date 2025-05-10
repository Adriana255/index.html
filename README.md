<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Launchfy - Tu socio digital</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      position: relative;
      height: 100vh;
      background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }

    .overlay-text {
      max-width: 800px;
      z-index: 1;
    }

    .overlay-text h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .overlay-text p {
      font-size: 1.2rem;
    }

    nav {
      background-color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }

    nav .logo {
      font-weight: bold;
      font-size: 1.5rem;
      color: #2575fc;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #2575fc;
    }

    main {
      padding: 100px 2rem 4rem 2rem;
    }

    section {
      margin-bottom: 3rem;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #2575fc;
    }

    footer {
      background-color: #f1f1f1;
      padding: 2rem;
      text-align: center;
      border-top: 1px solid #ddd;
    }

    footer .socials a {
      margin: 0 10px;
      text-decoration: none;
      color: #2575fc;
      font-weight: bold;
    }

    footer .socials a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <!-- Menú de navegación -->
  <nav>
    <div class="logo">Launchfy</div>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#sobrenosotras">Sobre nosotras</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <!-- Portada -->
  <header id="inicio">
    <div class="overlay-text">
      <h1>Ayudamos a emprendedoras a destacar en internet</h1>
      <p>Especialistas en desarrollo web y gestión de redes sociales para hacer crecer tu negocio.</p>
    </div>
  </header>

  <!-- Sección Sobre Nosotras -->
  <main>
    <section id="sobrenosotras">
      <h2>Sobre nosotras</h2>
      <p>Somos Launchfy, una empresa especializada en ayudar a emprendedoras a construir una presencia digital efectiva. Ofrecemos asesoría personalizada en el desarrollo de páginas web modernas y la correcta administración de redes sociales para conectar con su audiencia ideal.</p>
    </section>

    <!-- Sección Contacto -->
    <section id="contacto">
      <h2>Contacto</h2>
      <p>¿Listo para llevar tu negocio al siguiente nivel? ¡Contáctanos hoy mismo!</p>
      <p>Email: contacto@launchfy.com</p>
      <p>Teléfono: 922 123 456</p>
    </section>
  </main>

  <!-- Pie de página -->
  <footer>
    <div class="socials">
      <p>Síguenos en nuestras redes:</p>
      <a href="https://facebook.com " target="_blank">Facebook</a> |
      <a href="https://instagram.com " target="_blank">Instagram</a> |
      <a href="https://linkedin.com " target="_blank">LinkedIn</a>
    </div>
    <p>&copy; 2025 Launchfy. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
