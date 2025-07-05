<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>E'Pizza</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body { font-family: 'Roboto', sans-serif; }
    .hero {
      background-image: url('assets/italia-mapa-vintage.jpg'); /* Mapa vintage de Italia */
      background-size: cover;
      background-position: center;
      height: 60vh;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.7);
    }
    .gallery img { border-radius: 8px; margin-bottom: 1rem; }
    .footer { background: #333; color: #fff; padding: 20px 0; }
    .navbar-brand img { height: 50px; }
  </style>
</head>
<body>
  <!-- Navbar con logo -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#"><img src="assets/epizza-logo.png" alt="E'Pizza Logo"></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#about">Sobre Nosotros</a></li>
          <li class="nav-item"><a class="nav-link" href="#estetica">Estética</a></li>
          <li class="nav-item"><a class="nav-link" href="#menu">Menú</a></li>
          <li class="nav-item"><a class="nav-link" href="#reservaciones">Reservaciones</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="hero">
    <h1>Bienvenidos a E'Pizza</h1>
  </header>

  <!-- About Section -->
  <section id="about" class="py-5">
    <div class="container">
      <h2>Sobre Nosotros</h2>
      <p>En E'Pizza combinamos recetas tradicionales italianas con ingredientes frescos y locales. ¡Ven a disfrutar de nuestra pasión por la pizza auténtica!</p>
    </div>
  </section>

  <!-- Estética Section -->
  <section id="estetica" class="py-5 bg-light">
    <div class="container">
      <h2>Nuestra Estética</h2>
      <p>Inspírate con la esencia de Italia que guía cada detalle de nuestro restaurante.</p>
      <div class="row gallery">
        <div class="col-md-4">
          <img src="assets/decorative-italy-text.jpg" class="img-fluid" alt="Decorative Italy">
        </div>
        <div class="col-md-4">
          <img src="assets/via-dell-amore.jpg" class="img-fluid" alt="Via dell'Amore">
        </div>
        <div class="col-md-4">
          <img src="assets/mapa-italia-vintage2.jpg" class="img-fluid" alt="Mapa Vintage Italia">
        </div>
      </div>
    </div>
  </section>

  <!-- Menu Section -->
  <section id="menu" class="py-5">
    <div class="container">
      <h2>Menú Completo</h2>
      <img src="https://i.ibb.co/5hGdpD1/Menu-Epizza-2023-WEB.png" class="img-fluid" alt="Menú E'Pizza">
    </div>
  </section>

  <!-- Reservations Section -->
  <section id="reservaciones" class="py-5 bg-light">
    <div class="container">
      <h2>Reservaciones</h2>
      <form>
        <div class="mb-3">
          <label for="name" class="form-label">Nombre</label>
          <input type="text" class="form-control" id="name" placeholder="Tu nombre">
        </div>
        <div class="mb-3">
          <label for="date" class="form-label">Fecha</label>
          <input type="date" class="form-control" id="date">
        </div>
        <div class="mb-3">
          <label for="people" class="form-label">Personas</label>
          <input type="number" class="form-control" id="people" placeholder="Número de personas">
        </div>
        <button type="submit" class="btn btn-primary">Reservar</button>
      </form>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5">
    <div class="container">
      <h2>Contacto</h2>
      <div class="row">
        <div class="col-md-6">
          <h4>Sucursal Périban de Ramos</h4>
          <p>Dirección: Los Reyes - Péribán 4, Chirimoyo, 60440 Peribán de Ramos, Mich.</p>
          <p>Tel: <a href="tel:3521152225">352 115 2225</a></p>
          <div class="mb-4">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18...P%C3%A9riban" width="100%" height="200" style="border:0;" allowfullscreen loading="lazy"></iframe>
          </div>
        </div>
        <div class="col-md-6">
          <h4>Matriz Los Reyes de Salgado</h4>
          <p>Dirección: 16 de Septiembre 18, Centro, 60300 Los Reyes de Salgado, Mich.</p>
          <p>Tel:
            <a href="tel:3545426946">354 542 6946</a>,
            <a href="tel:3545424730">354 542 4730</a>,
            <a href="tel:3541155533">354 115 5533</a>
          </p>
          <div class="mb-4">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18...Los%20Reyes%20de%20Salgado" width="100%" height="200" style="border:0;" allowfullscreen loading="lazy"></iframe>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer text-center">
    <div class="container">
      <p>&copy; 2025 E'Pizza. Todos los derechos reservados.</p>
      <p>
        Síguenos en redes sociales:
        <a href="https://www.facebook.com/share/16quGsq8Jt/?mibextid=qi2Omg" target="_blank">Facebook</a> |
        <a href="#">Instagram</a>
      </p>
    </div>
  </footer>

  <!-- Bootstrap JS Bundle -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
