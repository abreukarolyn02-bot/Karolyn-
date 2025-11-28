# Karolyn-
<DOCTYPE html>
<html Long="en">
<head>
    <meta charset="Uff-8">
    <meta name="viewport" content="width-devicewidth", intial-scale-1.0">
    <link rel="stylesheet" href="../static/styles.css">
    <tile>CONTACTO</tile>
</head>
<body>
    <section id="contacto" class="contact-section">
    <h2>Conctacto</h2>
    <form id="contact-form" method="POST" action="/send_email">
        <input type="text"name="nombre"placeholder="Nombre" required>
        <input type="email> name= "correo" placeholder="Correo Electronico" required>
        <button type="submil">Enviar</button>
    </form>
    </section>
 <!-- Contenedor para sensajes flash -->
  <div id="flash-messages" class="flash-messages"></div>
</body>
</html>