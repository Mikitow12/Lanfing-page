<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cámara de Vigilancia Solar</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <style>
        /* CSS para estilo de tienda virtual */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
        }

        header {
            background: #ff5722;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        header .logo {
            font-size: 2rem;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 1rem;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 3rem;
            background: linear-gradient(to right, #ff5722, #ffc107);
            color: white;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
        }

        .hero .cta {
            display: inline-block;
            margin: 1rem 0;
            padding: 0.8rem 1.5rem;
            background: #ffc107;
            color: #333;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .features, .benefits, .pricing, .contact {
            padding: 2rem;
            text-align: center;
        }

        .features h2, .benefits h2, .pricing h2, .contact h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
            color: #ff5722;
        }

        .features .feature-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1.5rem;
        }

        .feature {
            background: white;
            padding: 1rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            text-align: left;
        }

        .feature h3 {
            color: #ff5722;
        }

        .price {
            font-size: 2.5rem;
            font-weight: bold;
            color: #ff5722;
        }

        .promo {
            background: #ff5722;
            color: white;
            padding: 1rem;
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }

        form {
            max-width: 400px;
            margin: 0 auto;
            text-align: left;
        }

        form label {
            display: block;
            margin-bottom: 0.5rem;
        }

        form input, form textarea, form button {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        form button {
            background: #ff5722;
            color: white;
            border: none;
            cursor: pointer;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">SolarGuard Store</div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#caracteristicas">Características</a></li>
                <li><a href="#beneficios">Beneficios</a></li>
                <li><a href="#precio">Precio</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="hero">
        <div class="promo">¡Oferta limitada! Compra antes de que termine la semana y obtén un 10% de descuento.</div>
        <h1>Cámara de Vigilancia con Panel Solar</h1>
        <p>Seguridad sostenible con tecnología avanzada. ¡No pierdas esta oportunidad!</p>
        <a href="#precio" class="cta">Ver Precio</a>
    </section>

    <section id="caracteristicas" class="features">
        <h2>Características Destacadas</h2>
        <div class="feature-list">
            <div class="feature">
                <h3>Panel Solar</h3>
                <p>Carga continua con energía solar para ahorro máximo.</p>
            </div>
            <div class="feature">
                <h3>Resolución HD</h3>
                <p>Imágenes claras y nítidas en cualquier momento.</p>
            </div>
            <div class="feature">
                <h3>Conexión Inteligente</h3>
                <p>Controla todo desde tu smartphone.</p>
            </div>
        </div>
    </section>

    <section id="beneficios" class="benefits">
        <h2>¿Por qué elegir nuestra cámara?</h2>
        <ul>
            <li>Ahorro energético con panel solar integrado.</li>
            <li>Instalación sin cables ni complicaciones.</li>
            <li>Soporte técnico 24/7.</li>
        </ul>
    </section>

    <section id="precio" class="pricing">
        <h2>¡Compra Ahora!</h2>
        <p class="price">S/ 799.00</p>
        <a href="#contacto" class="cta">Solicitar Información</a>
    </section>

    <section id="contacto" class="contact">
        <h2>Contáctanos</h2>
        <p>Llena el formulario para más detalles o realizar tu compra.</p>
        <form id="contact-form">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" required>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" rows="4"></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 SolarGuard Store. Todos los derechos reservados.</p>
    </footer>

    <script>
        // JavaScript para alertas de tiempo
        document.addEventListener('DOMContentLoaded', () => {
            setTimeout(() => {
                alert('¡No dejes pasar esta oferta! Compra ahora con un 10% de descuento.');
            }, 5000);
        });
    </script>
</body>
</html>

