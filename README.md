<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Fuente personalizada -->
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
  <!-- Íconos Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" 
        integrity="sha512-pVn+7Wn6O0Kly2Nw+1FxXb4RxjPdP/vp3+SW7jCkZCEwZt2z9hFJAZ4xGXwxh6+8ZldLqkVXhT++5IuHnF3n0g==" 
        crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    /* Estilos globales */
    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
      color: #333;
      line-height: 1.6;
    }
    a {
      text-decoration: none;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #0050D0;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: 0 auto;
      padding: 20px;
    }
    /* Encabezado */
    header {
      background-color: #fff;
      border-bottom: 3px solid #0025FC;
      padding: 20px 0;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .logo {
      text-align: center;
      margin-bottom: 10px;
      line-height: 1;
    }
    .logo .logo-title {
      font-size: 4.5em;
      font-weight: 700;
      text-transform: uppercase;
      color: #0025FC;
      margin: 0;
    }
    .logo .logo-subtitle {
      font-size: 1.2em;
      color: #0025FC;
      margin: 0;
    }
    nav {
      text-align: center;
      margin-top: 15px;
    }
    nav a {
      color: #0025FC;
      font-weight: 600;
      margin: 0 15px;
      font-size: 1em;
    }
    /* Sección Hero */
    .hero {
      text-align: center;
      padding: 60px 20px;
      background-color: #0025FC;
      color: #fff;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2em;
    }
    /* Secciones Generales */
    section {
      margin: 60px 0;
    }
    section h2 {
      color: #0025FC;
      font-size: 2em;
      border-bottom: 2px solid #0025FC;
      display: inline-block;
      padding-bottom: 5px;
      margin-bottom: 20px;
    }
    section p {
      font-size: 1.1em;
      margin-bottom: 15px;
    }
    /* Testimonios */
    .testimonios blockquote {
      background: #f9f9f9;
      padding: 25px;
      border-left: 5px solid #0025FC;
      margin: 30px auto;
      max-width: 800px;
      font-style: italic;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .testimonios blockquote strong {
      display: block;
      text-align: right;
      margin-top: 10px;
      font-weight: 600;
    }
    /* Sección Contacto */
    .contacto .contact-info {
      text-align: center;
      margin-bottom: 30px;
    }
    .contacto .contact-info p {
      margin: 10px 0;
      font-size: 1.1em;
    }
    .socials {
      text-align: center;
      margin: 20px 0;
    }
    .socials a {
      margin: 0 10px;
      font-size: 1.3em;
      font-weight: 600;
      color: #0025FC;
      display: inline-flex;
      align-items: center;
      gap: 5px;
    }
    .socials a:hover {
      color: #0050D0;
    }
    .contacto form {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .contacto form input,
    .contacto form textarea {
      padding: 12px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .contacto form button {
      background-color: #0025FC;
      color: #fff;
      border: none;
      padding: 15px;
      font-size: 1.1em;
      border-radius: 4px;
      cursor: pointer;
    }
    /* Mapa de Contacto */
    .mapa {
      margin-top: 40px;
    }
    .mapa iframe {
      width: 100%;
      height: 450px;
      border: 0;
    }
    /* Footer */
    .footer {
      background: #f0f0f0;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
      color: #555;
    }
    /* Responsividad */
    @media (max-width: 768px) {
      .logo .logo-title {
        font-size: 3em;
      }
      .hero h1 {
        font-size: 2em;
      }
      nav a {
        font-size: 0.9em;
        margin: 0 10px;
      }
    }
  </style>
</head>
<body>
  <!-- Encabezado -->
    <div class="container">
            <div class="logo">
        <div class="logo-title">HERSILIA</div>
        <div class="logo-subtitle">CENTRO PSICOLOGICO INTEGRAL</div>
      </div>
      <nav>
        <a href="#inicio">Inicio</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#testimonios">Testimonios</a>
        <a href="#contacto">Contacto</a>
      </nav>
    </div>
  <!-- Sección Hero -->
  <section class="hero" id="inicio">
    <div class="container">
      <h1>Un legado de amor, un futuro de salud</h1>
      <p>En HERSILIA nos dedicamos a brindar apoyo integral en salud mental, con profesionales comprometidos con tu bienestar y el de tu familia.</p>
    </div>
  </section>
  <div class="container">
    <!-- Sección Sobre Nosotros -->
    <section id="nosotros">
      <h2>Sobre Nosotros</h2>
      <p><strong>Nuestra Historia:</strong> HERSILIA nace con la visión de transformar vidas a través de la atención psicológica y el acompañamiento emocional. Durante años, hemos desarrollado programas de salud mental dirigidos a diferentes grupos: niños, adolescentes, adultos y personas de la tercera edad.</p>
      <p><strong>Nuestro Equipo:</strong> Contamos con un equipo multidisciplinario de profesionales con experiencia en terapia individual, de pareja y familiar, así como en talleres de desarrollo personal y capacitación en salud mental.</p>
      <p><strong>Misión:</strong> Brindar atención psicológica de calidad, promoviendo la salud mental y el bienestar integral de las personas a través de un enfoque humano, ético y comprometido con la comunidad.</p>
      <p><strong>Visión:</strong> Ser un referente a nivel nacional en la prevención, cuidado y promoción de la salud mental, impactando de manera positiva en la calidad de vida de las personas y sus familias.</p>
      <p><strong>Valores:</strong> Compasión, Respeto, Honestidad y Excelencia son los pilares que guían nuestro quehacer diario.</p>
    </section>
    <!-- Sección Testimonios -->
    <section class="testimonios" id="testimonios">
      <h2>Testimonios</h2>
      <blockquote>
        "Gracias a HERSILIA, encontré la ayuda que necesitaba para superar mis miedos y recuperar mi confianza."
        <strong>- María, 28 años</strong>
      </blockquote>
      <blockquote>
        "El acompañamiento psicológico fue fundamental para mejorar la comunicación en mi familia. ¡Lo recomiendo al 100%!"
        <strong>- Carlos, 45 años</strong>
      </blockquote>
      <blockquote>
        "Excelente equipo de profesionales, siempre dispuestos a escuchar y a brindar la mejor orientación."
        <strong>- Andrea, 34 años</strong>
      </blockquote>
    </section>
    <!-- Sección Contacto -->
    <section class="contacto" id="contacto">
      <h2>Contacto</h2>
      <div class="contact-info">
        <p><strong>Teléfono:</strong> <a href="https://wa.me/593981811831" target="_blank">0981811831 (WhatsApp)</a></p>
        <p><strong>Email:</strong> <a href="mailto:hersilia.ec@outlook.com">hersilia.ec@outlook.com</a></p>
        <p><strong>Dirección:</strong> Hersilia Centro Psicológico Integral</p>
      </div>
<div class="socials">
  <a href="https://www.facebook.com/people/Centro-Psicol%C3%B3gico-Integral-Hersilia/100064794828756/" target="_blank">
    <i class="fab fa-facebook"></i> Facebook
  </a>
  <a href="https://www.instagram.com/hersilia.ec/" target="_blank">
    <i class="fab fa-instagram"></i> Instagram
  </a>
  <a href="https://www.tiktok.com/@hersilia.ec" target="_blank">
    <i class="fab fa-tiktok"></i> TikTok
  </a>
</div>
<form action="URL_DE_TU_SERVIDOR_O_SCRIPT" method="POST">
        <input type="text" name="nombre" placeholder="Nombre completo" required>
        <input type="email" name="correo" placeholder="Correo electrónico" required>
        <input type="tel" name="telefono" placeholder="Número de teléfono">
        <input type="text" name="asunto" placeholder="Asunto" required>
        <textarea name="mensaje" rows="5" placeholder="Tu mensaje" required></textarea>
        <button type="submit">Enviar Mensaje</button>
      </form>
      <p style="text-align:center; margin-top:15px;">
        O también <a href="https://wa.me/593981811831" target="_blank" style="color:#0025FC; font-weight:600;">Enviar por WhatsApp</a>
      </p>
      <!-- Mapa de Contacto -->
      <div class="mapa">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3989.7537095954717!2d-78.45234842503537!3d-0.32607239967071955!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x91d5bd00024aabd9%3A0x483eb49bac9ebcba!2sHersilia%20Centro%20Psicol%C3%B3gico%20Integral!5e0!3m2!1ses-419!2sec!4v1743294599307!5m2!1ses-419!2sec" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
    </section>
  </div>
  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p>Copyright © 2025 HERSILIA - Centro Psicologico Integral</p>
    </div>
  </footer>
</body>
</html>
