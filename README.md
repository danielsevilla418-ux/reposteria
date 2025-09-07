# reposteria
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Repostería Celestial del Espíritu</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff8f0;
      color: #5a3e36;
    }

    header {
      background-color: #f9e3e3;
      text-align: center;
      padding: 40px 20px;
    }

    header img {
      width: 120px;
      margin-bottom: 15px;
    }

    header h1 {
      font-size: 2.8em;
      margin: 10px 0;
      color: #d16d6d;
    }

    header p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 0 auto;
    }

    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      padding: 40px;
    }

    .producto {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      transition: transform 0.3s;
    }

    .producto:hover {
      transform: translateY(-5px);
    }

    .producto img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .producto h3 {
      color: #d16d6d;
      margin-bottom: 8px;
    }

    .producto p {
      font-size: 1.1em;
      margin-bottom: 15px;
    }

    .producto button {
      background-color: #d16d6d;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      border: none;
      cursor: pointer;
      font-size: 1em;
      transition: background 0.3s;
    }

    .producto button:hover {
      background-color: #b14f4f;
    }

    .pedido-nombre {
      text-align: center;
      padding: 20px;
    }

    .pedido-nombre input {
      padding: 10px;
      font-size: 1em;
      border-radius: 6px;
      border: 1px solid #ccc;
      width: 250px;
      margin-bottom: 20px;
    }

    .contacto {
      background-color: #fff;
      padding: 40px 20px;
      text-align: center;
    }

    .contacto h2 {
      color: #d16d6d;
      margin-bottom: 20px;
    }

    .iconos a {
      display: inline-block;
      margin: 10px 20px;
      text-decoration: none;
      color: #5a3e36;
      font-weight: bold;
      font-size: 1.1em;
    }

    .iconos a:hover {
      color: #d16d6d;
    }

    footer {
      background-color: #f3dcdc;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #8b6b65;
    }
  </style>
</head>
<body>

  <!-- Encabezado con logo e info -->
  <header>
    <img src="logo.png" alt="Logo de la repostería" />
    <h1>Repostería Celestial del Espíritu</h1>
    <p>Gobernados por el Espíritu Santo, elaboramos cada dulce con amor, fe y propósito. ¡Endulza tu vida con delicias que vienen del cielo!</p>
  </header>

  <!-- Campo para nombre del cliente -->
  <div class="pedido-nombre">
    <h2>Haz tu pedido</h2>
    <input type="text" id="nombreCliente" placeholder="Escribe tu nombre aquí" required>
  </div>

  <!-- Sección de productos -->
  <section class="productos">
    <div class="producto">
     <img src="imagenes/producto1.jpg" alt="Producto 1">
      <h3>Brownies</h3>
      <p>$10.00 USD</p>
      <button onclick="hacerPedido('Brownies', '10')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="galletas.jpg" alt="Galletas">
      <h3>Galletas</h3>
      <p>$8.00 USD</p>
      <button onclick="hacerPedido('Galletas', '8')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="flan.jpg" alt="Flan">
      <h3>Flan</h3>
      <p>$12.00 USD</p>
      <button onclick="hacerPedido('Flan', '12')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="churros.jpg" alt="Churros">
      <h3>Churros</h3>
      <p>$9.00 USD</p>
      <button onclick="hacerPedido('Churros', '9')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="cheesecake.jpg" alt="Cheesecake">
      <h3>Cheesecake</h3>
      <p>$18.00 USD</p>
      <button onclick="hacerPedido('Cheesecake', '18')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="roles-canela.jpg" alt="Roles de Canela">
      <h3>Roles de Canela</h3>
      <p>$14.00 USD</p>
      <button onclick="hacerPedido('Roles de Canela', '14')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="fresa-crema.jpg" alt="Fresa con Crema">
      <h3>Fresa con Crema</h3>
      <p>$11.00 USD</p>
      <button onclick="hacerPedido('Fresa con Crema', '11')">🛒 Pedir por WhatsApp</button>
    </div>
  </section>

  <!-- Sección de contacto -->
  <section class="contacto">
    <h2>Contáctanos</h2>
    <div class="iconos">
      <!-- WhatsApp -->
      <a href="https://wa.me/18323622303" target="_blank">📱 WhatsApp</a>
      
      <!-- Instagram -->
      <a href="https://instagram.com/tuusuario" target="_blank">📸 Instagram</a>
    </div>
  </section>

  <!-- Pie de página -->
  <footer>
    © 2025 Repostería Celestial del Espíritu - Hecho con fe y dulzura 🕊️
  </footer>

  <!-- Script para enviar a WhatsApp -->
  <script>
    function hacerPedido(producto, precio) {
      let nombre = document.getElementById("nombreCliente").value;
      if(nombre.trim() === "") {
        alert("Por favor escribe tu nombre antes de hacer un pedido.");
        return;
      }
      let mensaje = `Hola, soy ${nombre} y quiero pedir ${producto} por $${precio} USD.`;
      let url = "https://wa.me/18323622303?text=" + encodeURIComponent(mensaje);
      window.open(url, "_blank");
    }
  </script>

</body>
</html>
