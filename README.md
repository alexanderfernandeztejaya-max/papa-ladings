<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Papa Andina - Natural y Nutritiva</title>

  <style>
    body {
      margin: 0;
      font-family: Verdana, sans-serif;
      background: #f5f5dc;
    }

    header {
      background: #2e7d32;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .hero {
      text-align: center;
      padding: 60px 20px;
    }

    .hero h1 {
      font-size: 2.5em;
      color: #333;
    }

    /* Contenedor de botones */
    .button-container {
      margin-top: 30px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .btn {
      color: white;
      padding: 15px 30px;
      text-decoration: none;
      display: inline-block;
      border-radius: 8px;
      font-weight: bold;
      font-size: 1.1em;
      transition: 0.3s;
    }

    /* Color Marrón para Información */
    .btn-info {
      background: #8d6e63;
    }

    /* Color Verde para Registro */
    .btn-reg {
      background: #2e7d32;
    }

    .btn:hover {
      opacity: 0.9;
      transform: scale(1.05);
    }

    section {
      padding: 40px;
      text-align: center;
    }

    footer {
      background: #2e7d32;
      color: white;
      text-align: center;
      padding: 15px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 1.8em;
      }
      .button-container {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>Papa Andina</h1>
</header>

<main>

<section class="hero">
  <h1>La mejor papa natural de nuestra región</h1>
  <p>Cultivada de forma tradicional, rica en nutrientes y sabor auténtico</p>
  
  <div class="button-container">
    <a href="informacion.html" class="btn btn-info">Quiero más información</a>
    <a href="registro.html" class="btn btn-reg">Regístrate ya</a>
  </div>
</section>

<section>
  <h2>Beneficios</h2>
  <p>✔ Alta en energía natural para el día a día</p>
  <p>✔ Cultivo local sin químicos dañinos</p>
</section>

</main>

<footer>
  <p>© 2026 Papa Andina</p>
</footer>

</body>
</html>
