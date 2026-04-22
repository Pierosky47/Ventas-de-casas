<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venta de Casas Ficticias</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Sección de encabezado -->
    <header>
        <div class="container">
            <h1>Venta de Casas Ficticias</h1>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#casas">Nuestras Casas</a></li>
                    <li><a href="#acerca">Acerca de</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Sección de Inicio -->
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Encuentra tu hogar ideal</h2>
            <p>Casas exclusivas, cómodas y perfectas para ti.</p>
        </div>
    </section>

    <!-- Sección de Casas -->
    <section id="casas">
        <h2>Las mejores casas disponibles</h2>
        <div class="house-list">
            <div class="house">
                <img src="https://via.placeholder.com/300" alt="Casa 1">
                <h3>Casa en la playa</h3>
                <p>Hermosa casa con vista al mar, 3 habitaciones y jardín.</p>
                <a href="#">Ver más detalles</a>
            </div>
            <div class="house">
                <img src="https://via.placeholder.com/300" alt="Casa 2">
                <h3>Casa moderna</h3>
                <p>Casa con estilo minimalista, 4 habitaciones y piscina.</p>
                <a href="#">Ver más detalles</a>
            </div>
            <!-- Más casas -->
        </div>
    </section>

    <!-- Sección Acerca de -->
    <section id="acerca">
        <h2>Acerca de nosotros</h2>
        <p>Somos una empresa dedicada a la venta de casas de lujo. Nuestra misión es ofrecerte el hogar de tus sueños.</p>
    </section>

    <!-- Sección de Contacto -->
    <section id="contacto">
        <h2>Contacto</h2>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre">
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email">
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Venta de Casas Ficticias</p>
    </footer>
</body>
</html>
