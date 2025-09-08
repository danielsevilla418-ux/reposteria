# reposteria
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Repostería Celestial del Espíritu</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Encabezado -->
  <header>
    <img src="https://sdmntprcentralus.oaiusercontent.com/files/00000000-5f7c-61f5-a3d9-746b843d7676/raw?se=2025-09-08T02%3A16%3A32Z&sp=r&sv=2024-08-04&sr=b&scid=f9416992-5c82-5770-b145-ff5ed4ec4498&skoid=ec8eb293-a61a-47e0-abd0-6051cc94b050&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-09-07T13%3A25%3A30Z&ske=2025-09-08T13%3A25%3A30Z&sks=b&skv=2024-08-04&sig=51S8B3hvWq1vXqoBU%2BAzF9ltOGUD5UWap8cFguHEPbk%3D" alt="Logo" class="logo">
    <h1>Repostería Celestial del Espíritu</h1>
    <p>Gobernados por el Espíritu Santo, elaboramos cada dulce con amor, fe y propósito. ¡Endulza tu vida con delicias que vienen del cielo!</p>
  </header>

  <!-- Pedido -->
  <section class="pedido">
    <h2>Haz tu pedido</h2>
    <input type="text" id="nombreCliente" placeholder="Escribe tu nombre aquí">
  </section>

  <!-- Productos -->
  <section class="productos">
    <div class="producto">
      <img src="https://tse2.mm.bing.net/th/id/OIP.JFSYvdTU1xhBxxHlzshM8gHaE8?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Brownies">
      <h3>Brownies</h3>
      <p>$10.00 USD</p>
      <input type="number" id="cantidad-Brownies" min="1" value="1">
      <button onclick="hacerPedido('Brownies', 10, 'cantidad-Brownies')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="https://tse1.mm.bing.net/th/id/OIP.kP9JvEBmlcHXbWSMTNw1FgHaEK?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Galletas">
      <h3>Galletas</h3>
      <p>$8.00 USD</p>
      <input type="number" id="cantidad-Galletas" min="1" value="1">
      <button onclick="hacerPedido('Galletas', 8, 'cantidad-Galletas')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="https://tse4.mm.bing.net/th/id/OIP.c3IKPuurWOaWwFv2jqDtgQHaEK?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Pie de Limón">
      <h3>Pie de Limón</h3>
      <p>$9.00 USD</p>
      <input type="number" id="cantidad-PieLimon" min="1" value="1">
      <button onclick="hacerPedido('Pie de Limón', 9, 'cantidad-PieLimon')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="https://tse3.mm.bing.net/th/id/OIP.-MU0B1bX_IWyIWdEkjeQ5AHaHa?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Flan">
      <h3>Flan</h3>
      <p>$12.00 USD</p>
      <input type="number" id="cantidad-Flan" min="1" value="1">
      <button onclick="hacerPedido('Flan', 12, 'cantidad-Flan')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="https://th.bing.com/th/id/OIP.znkh_vKbwsyoA_ltku2hMQHaHa?r=0&o=7rm=3&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Churros Cheesecake">
      <h3>Churros Cheesecake</h3>
      <p>$18.00 USD</p>
      <input type="number" id="cantidad-Cheesecake" min="1" value="1">
      <button onclick="hacerPedido('Churros Cheesecake', 18, 'cantidad-Cheesecake')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="https://tse2.mm.bing.net/th/id/OIP.Oe2Gl4SE3vanPyNGrFb-NAHaE6?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Roles de Canela">
      <h3>Roles de Canela</h3>
      <p>$14.00 USD</p>
      <input type="number" id="cantidad-Roles" min="1" value="1">
      <button onclick="hacerPedido('Roles de Canela', 14, 'cantidad-Roles')">🛒 Pedir por WhatsApp</button>
    </div>

    <div class="producto">
      <img src="https://tse1.explicit.bing.net/th/id/OIP.XIQsGM5dT6jg9T0Ujcd5yQHaE8?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Fresa con Crema">
      <h3>Fresa con Crema</h3>
      <p>$11.00 USD</p>
      <input type="number" id="cantidad-Fresa" min="1" value="1">
      <button onclick="hacerPedido('Fresa con Crema', 11, 'cantidad-Fresa')">🛒 Pedir por WhatsApp</button>
    </div>
  </section>

  <!-- Contacto -->
  <section class="contacto">
    <h2>Contáctanos</h2>
    <div class="iconos">
      <a href="https://wa.me/18323622303" target="_blank">📱 WhatsApp</a>
      <a href="https://instagram.com/tuusuario" target="_blank">📸 Instagram</a>
    </div>
  </section>

  <!-- Pie de página -->
  <footer>
    © 2025 Repostería Celestial del Espíritu - Hecho con fe y dulzura 🕊
  </footer>

  <!-- Script WhatsApp -->
  <script>
    function hacerPedido(producto, precio, inputId) {
      let nombre = document.getElementById("nombreCliente").value.trim();
      if (nombre === "") { alert("Escribe tu nombre antes de hacer el pedido."); return; }
      let cantidad = parseInt(document.getElementById(inputId).value);
      if (isNaN(cantidad) || cantidad <= 0) { alert("Cantidad inválida."); return; }
      let total = (precio * cantidad).toFixed(2);
      let mensaje = `Hola, soy ${nombre} y quiero pedir ${cantidad} ${producto}(s) por un total de $${total} USD.`;
      window.open("https://wa.me/18323622303?text=" + encodeURIComponent(mensaje), "_blank");
    }
  </script>

</body>
</html>

/* General */
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background-color: #fff8f0;
  color: #5a3e36;
}

/* Encabezado */
header {
  background: linear-gradient(135deg, #f9e3e3, #ffe0e0);
  text-align: center;
  padding: 50px 20px;
}

header .logo {
  width: 200px;
  border-radius: 20px;
}

header h1 {
  font-size: 2.5em;
  color: #d16d6d;
  margin: 15px 0;
}

header p {
  font-size: 1.2em;
  max-width: 600px;
  margin: 0 auto;
}

/* Pedido */
.pedido {
  text-align: center;
  padding: 30px 20px;
}

.pedido input {
  padding: 12px;
  font-size: 1em;
  border-radius: 8px;
  border: 1px solid #ccc;
  width: 280px;
}

/* Productos */
.productos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
  padding: 40px;
}

.producto {
  background-color: #fff;
  border-radius: 15px;
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
  padding: 20px;
  text-align: center;
  transition: transform 0.3s, box-shadow 0.3s;
}

.producto:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.15);
}

.producto img {
  width: 160px;
  height: 120px;
  object-fit: cover;
  border-radius: 12px;
  margin-bottom: 15px;
}

.producto h3 {
  color: #d16d6d;
  margin-bottom: 8px;
}

.producto p {
  font-size: 1.1em;
  margin-bottom: 12px;
}

.producto input {
  width: 60px;
  padding: 5px;
  margin-bottom: 10px;
  text-align: center;
  border-radius: 6px;
  border: 1px solid #ccc;
}

.producto button {
  background-color: #d16d6d;
  color: #fff;
  border: none;
  padding: 10px 20px;
  border-radius: 8px;
  cursor: pointer;
  font-size: 1em;
  transition: background 0.3s;
}

.producto button:hover {
  background-color: #b14f4f;
}

/* Contacto */
.contacto {
  background-color: #fff;
  text-align: center;
  padding: 40px 20px;
}

.contacto h2 {
  color: #d16d6d;
  margin-bottom: 20px;
}

.iconos a {
  margin: 10px 15px;
  text-decoration: none;
  color: #5a3e36;
  font-weight: bold;
  font-size: 1.1em;
}

.iconos a:hover {
  color: #d16d6d;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background-color: #f3dcdc;
 

