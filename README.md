<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page - Venta Contraentrega</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }

        a {
            text-decoration: none;
            color: #fff;
        }

        header {
            background: #4CAF50;
            color: #fff;
            padding: 20px 10px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        section {
            padding: 20px;
        }

        .hero {
            background: #f4f4f4;
            text-align: center;
            padding: 40px 20px;
        }

        .hero img {
            max-width: 100%;
            height: auto;
        }

        .cta-button {
            background: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .cta-button:hover {
            background: #45a049;
        }

        .benefits {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .benefit {
            flex: 1 1 calc(33.333% - 20px);
            box-sizing: border-box;
            margin: 10px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
        }

        .testimonials {
            background: #f9f9f9;
            padding: 20px;
        }

        .testimonial {
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
        }

        .form-section input, .form-section button {
            width: 100%;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        footer a {
            color: #4CAF50;
        }
    </style>
</head>
<body>

<header>
    <h1>Protege tu hogar con energía solar – Sin cables, sin complicaciones.</h1>
    <p>Fácil instalación, resistente al clima, y 100% autónoma. ¡Paga al recibir por solo 299 soles!</p>
</header>

<section class="hero">
    <img src="placeholder.jpg" alt="Cámara de Seguridad en Exterior">
    <p>
        <button class="cta-button">¡Quiero mi cámara ahora!</button>
    </p>
</section>

<section class="benefits">
    <div class="benefit">
        <h3>Energía Solar Integrada</h3>
        <p>Funciona día y noche sin conexión eléctrica.</p>
    </div>
    <div class="benefit">
        <h3>Resistencia a la Intemperie</h3>
        <p>Ideal para cualquier clima.</p>
    </div>
    <div class="benefit">
        <h3>Fácil Instalación</h3>
        <p>Sin técnicos, hazlo tú mismo en minutos.</p>
    </div>
    <div class="benefit">
        <h3>Monitoreo en Tiempo Real</h3>
        <p>Compatible con dispositivos móviles.</p>
    </div>
    <div class="benefit">
        <h3>Sin Cables, Sin Complicaciones</h3>
    </div>
</section>

<section>
    <h2>Oferta Especial</h2>
    <p><strong>Precio Regular: 399 soles – ¡HOY solo 299 soles!</strong></p>
    <p><strong>Incluye 3 meses de garantía sin costo adicional.</strong></p>
    <div>
        <h3>Oferta válida hasta hoy a las 11:59 PM</h3>
    </div>
</section>

<section class="testimonials">
    <h2>Testimonios de Clientes</h2>
    <div class="testimonial">
        <p>"La instalación fue tan fácil como dijeron, ¡y funciona de maravilla incluso en días nublados!" – Ana G.</p>
    </div>
    <div class="testimonial">
        <p>"Nunca imaginé una cámara de seguridad tan asequible y eficiente. ¡Gracias!" – Carlos P.</p>
    </div>
</section>

<section class="form-section">
    <h2>Reserva tu Cámara Ahora</h2>
    <form action="/submit" method="post">
        <input type="text" name="name" placeholder="Nombre Completo" required>
        <input type="tel" name="phone" placeholder="Número de Teléfono" required>
        <input type="text" name="address" placeholder="Dirección de Entrega" required>
        <input type="number" name="quantity" placeholder="Cantidad (default: 1)" min="1" value="1" required>
        <button type="submit">Reservar mi cámara ahora</button>
    </form>
</section>

<section>
    <h2>Preguntas Frecuentes</h2>
    <p><strong>¿Cuánto demora la entrega?</strong> Normalmente entre 2 y 5 días hábiles.</p>
    <p><strong>¿Qué incluye la caja?</strong> Una cámara solar, un manual y accesorios de instalación.</p>
    <p><strong>¿Cómo se realiza el pago?</strong> Paga al recibir tu producto en efectivo.</p>
</section>

<footer>
    <p>Contáctanos al <a href="tel:+51999999999">+51 999 999 999</a> o por WhatsApp.</p>
    <p><a href="#">Política de privacidad</a> | <a href="#">Términos y condiciones</a></p>
</footer>

</body>
</html>
