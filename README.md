<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lux Ecuador</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #002147;
      color: white;
      padding: 20px 40px;
      text-align: center;
    }
    nav {
      background-color: #013a63;
      padding: 10px 0;
      display: flex;
      justify-content: center;
      gap: 30px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      text-align: center;
    }
    .product {
      margin-top: 30px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 30px;
    }
    .card {
      background-color: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #002147;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Lux Ecuador</h1>
    <p>Soluciones inteligentes para limpieza y purificación</p>
  </header>

  <nav>
    <a href="#productos">Productos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="productos">
    <h2>Nuestros Productos</h2>
    <div class="product">
      <div class="card">
        <h3>Aspiradoras Inteligentes</h3>
        <p>Poderosas, silenciosas y con tecnología de filtración avanzada.</p>
      </div>
      <div class="card">
        <h3>Brilladores de Piso</h3>
        <p>Para dejar tus pisos como nuevos con el menor esfuerzo.</p>
      </div>
      <div class="card">
        <h3>Purificadores de Aire</h3>
        <p>Respira aire puro gracias a nuestros sistemas de alta eficiencia.</p>
      </div>
      <div class="card">
        <h3>Purificadores de Agua</h3>
        <p>Agua limpia y segura en todo momento, para ti y tu familia.</p>
      </div>
    </div>
  </section>

  <section id="nosotros">
    <h2>¿Quiénes Somos?</h2>
    <p>En Lux Ecuador trabajamos con innovación, compromiso y calidad para brindarte lo mejor en limpieza y purificación. Nos enfocamos en ofrecer soluciones modernas tanto para adultos mayores como para jóvenes.</p>
  </section>

  <section id="contacto">
    <h2>Contáctanos</h2>
    <p>Correo: contacto@luxecuador.com</p>
    <p>Teléfono: +593 99 999 9999</p>
  </section>

  <footer>
    <p>&copy; 2025 Lux Ecuador. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
