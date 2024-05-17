<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Barbería "El Corte Perfecto"</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    header {
        background-color: #333;
        color: #fff;
        padding: 20px;
        text-align: center;
    }
    nav {
        background-color: #444;
        color: #fff;
        text-align: center;
        padding: 10px 0;
    }
    nav a {
        text-decoration: none;
        color: #fff;
        padding: 10px 20px;
    }
    nav a:hover {
        background-color: #555;
    }
    section {
        padding: 20px;
    }
    h2 {
        color: #333;
    }
    .container {
        max-width: 800px;
        margin: 0 auto;
    }
    .servicio {
        margin-bottom: 20px;
    }
    .servicio img {
        max-width: 100%;
    }
</style>
</head>
<body>

<header>
    <h1>Barbería "El Corte Perfecto"</h1>
    <p>Tu lugar para el mejor estilo</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Servicios</a>
    <a href="#ubicacion">Ubicación</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
    <div class="container">
        <h2>Bienvenido a Barbería "El Corte Perfecto"</h2>
        <p>Somos expertos en cortes de cabello, afeitado de barba y cuidado personal para hombres.</p>
        <p>¡Ven y descubre cómo podemos mejorar tu estilo!</p>
    </div>
</section>

<section id="servicios">
    <div class="container">
        <h2>Nuestros Servicios</h2>
        <div class="servicio">
            <img src="corte.jpg" alt="Corte de Cabello">
            <h3>Corte de Cabello</h3>
            <p>Te ofrecemos una amplia variedad de cortes de cabello para todos los estilos y preferencias.</p>
        </div>
        <div class="servicio">
            <img src="afeitado.jpg" alt="Afeitado de Barba">
            <h3>Afeitado de Barba</h3>
            <p>Nuestros barberos expertos te brindarán un afeitado profesional para que luzcas impecable.</p>
        </div>
        <!-- Agrega más servicios según sea necesario -->
    </div>
</section>
</html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reserva de Citas</title>
<style>
    body {
        font-family: Arial, sans-serif;
    }
    form {
        max-width: 500px;
        margin: 0 auto;
    }
    label, input, textarea {
        display: block;
        margin-bottom: 10px;
    }
    input[type="submit"] {
        background-color: #4CAF50;
        color: white;
        padding: 10px 20px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
    }
    input[type="submit"]:hover {
        background-color: #45a049;
    }
</style>
</head>
<body>

<h2>Reserva de Citas</h2>

<form action="procesar_cita.php" method="POST">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>

    <label for="telefono">Teléfono:</label>
    <input type="tel" id="telefono" name="telefono" required>

    <label for="fecha">Fecha de la Cita:</label>
    <input type="date" id="fecha" name="fecha" required>
    
    <label for="fecha">Fecha de la Cita:</label>
    <input type="date" id="fecha" name="fecha" required>

    <label for="mensaje">Mensaje Adicional:</label>
    <textarea id="mensaje" name="mensaje" rows="4"></textarea>

    </body>
</html>
PHP para procesar la reserva (procesar_reserva.php):

<form action="procesar_reserva.php" method="POST">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>

    <label for="telefono">Teléfono:</label>
    <input type="tel" id="telefono" name="telefono" required>

    <label for="fecha">Fecha del Turno:</label>
    <input type="date" id="fecha" name="fecha" required>

    <label for="hora">Hora del Turno:</label>
    <input type="time" id="hora" name="hora" required>

    <input type="submit" value="Reservar">
</form>
php
Copy code
<?php
// Datos de la barbería
$numero_whatsapp = "NUMERO_DE_TELEFONO";

$nombre = $_POST['nombre'];
$telefono = $_POST['telefono'];
$fecha = $_POST['fecha'];
$hora = $_POST['hora'];


    <input type="submit" value="Apartar Cita">
</form>

</body>
</html>

<section id="ubicacion">
    <div class="container">
        <h2>Ubicación</h2>
        <p>Estamos ubicados en el corazón de la ciudad, en la siguiente dirección:</p>
        <p>123 Calle Principal, Ciudad, País</p>
    </div>
</section>

<section id="contacto">
    <div class="container">
        <h2>Contacto</h2>
        <p>Para reservar una cita o cualquier consulta, no dudes en contactarnos:</p>
        <p>Teléfono: 123-456-789</p>
        <p>Correo Electrónico: info@elcorteperfecto.com</p>
    </div>
</section>

</body>
</html>

<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reserva de Turno</title>
</head>
<body>

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScMlH8hCbadeOkenHBcXqBQyyiIUTKz0CFAYjWggK4saFtDZA/viewform?embedded=true" width="640" height="2040" frameborder="0" marginheight="0" marginwidth="0">Cargando…</iframe>
