# Travel-website
Project website
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viajes a Cancún</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Descubre Cancún</h1>
        <nav>
            <ul>
                <li><a href="#destinos">Destinos</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <section id="destinos">
        <h2>Destinos Populares en Cancún</h2>
        <div class="destino">
            <h3>Playa Delfines</h3>
            <p>Una de las playas más hermosas de Cancún.</p>
        </div>
        <div class="destino">
            <h3>Isla Mujeres</h3>
            <p>Un paraíso tropical a pocos minutos de Cancún.</p>
        </div>
    </section>
    <section id="galeria">
        <h2>Galería de Fotos</h2>
        <div class="galeria">
            <img src="playa_delfines.jpg" alt="Playa Delfines">
            <img src="isla_mujeres.jpg" alt="Isla Mujeres">
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>© 2024 Viajes a Cancún. Todos los derechos reservados.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>

