<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cámara de Vigilancia con Panel Solar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #ff5722;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header img {
            max-width: 100%;
            height: auto;
        }
        section {
            padding: 20px;
        }
        .hero {
            text-align: center;
        }
        .hero h1 {
            font-size: 2rem;
        }
        .hero p {
            margin: 10px 0;
            font-size: 1.2rem;
        }
        .cta-button {
            background: #ffc107;
            color: #333;
            padding: 10px 20px;
            border: none;
            font-size: 1rem;
            cursor: pointer;
            margin-top: 10px;
        }
        .benefits {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .benefit {
            border: 1px solid #ddd;
            padding: 10px;
            border-radius: 5px;
            width: 300px;
            text-align: center;
        }
        .benefit img {
            max-width: 50px;
            margin-bottom: 10px;
        }
        .offer {
            background: #ffc107;
            text-align: center;
            padding: 20px;
        }
        .offer h2 {
            margin: 0;
        }
        .testimonials {
            text-align: center;
        }
        .testimonial {
            margin: 10px 0;
        }
        .form {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .form input, .form textarea, .form button {
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form button {
            background: #ff5722;
            color: #fff;
            font-size: 1rem;
            cursor: pointer;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Protege tu hogar con energía solar</h1>
        <p>Sin cables, sin complicaciones. ¡Paga al recibir por solo <strong>299 soles</strong>!</p>
        <img src="camara-solar.jpg" alt="Cámara de vigilancia con panel solar">
        <button class="cta-button">¡Quiero mi cámara ahora!</button>
    </header>

    <section class="benefits">
        <div class="benefit">
            <img src="solar-icon.png" alt="Energía solar">
            <p><strong>Energía Solar Integrada:</strong> Funciona día y noche sin conexión eléctrica.</p>
        </div>
        <div class="benefit">
            <img src="weather-icon.png" alt="Resistencia al clima">
            <p><strong>Resistencia a la Intemperie:</strong> Ideal para cualquier clima.</p>
        </div>
        <div class="benefit">
            <img src="installation-icon.png" alt="Fácil instalación">
            <p><strong>Fácil Instalación:</strong> Sin técnicos, hazlo tú mismo en minutos.</p>
        </div>
        <div class="benefit">
            <img src="mobile-icon.png" alt="Monitoreo en tiempo real">
            <p><strong>Monitoreo en Tiempo Real:</strong> Compatible con dispositivos móviles.</p>
        </div>
    </section>

    <section class="offer">
        <h2>Precio Regular: 399 soles – <strong>¡HOY solo 299 soles!</strong></h2>
        <p>Incluye 3 meses de garantía sin costo adicional.</p>
    </section>

    <section class="testimonials">
        <h2>Clientes Satisfechos</h2>
        <div class="testimonial">
            <p>"Esta cámara me ha dado tranquilidad, funciona perfectamente y no tengo que preocuparme por cables." - Juan Pérez</p>
        </div>
        <div class="testimonial">
            <p>"La instalación fue tan sencilla que no lo podía creer. Muy recomendada." - María López</p>
        </div>
    </section>

    <section class="form">
        <h2>Reserva tu cámara ahora</h2>
        <form action="#" method="POST">
            <input type="text" name="nombre" placeholder="Nombre completo" required>
            <input type="tel" name="telefono" placeholder="Número de teléfono" required>
            <textarea name="direccion" placeholder="Dirección de entrega (distrito, ciudad, referencias)" required></textarea>
            <input type="number" name="cantidad" placeholder="Cantidad" min="1" value="1" required>
            <button type="submit">Reservar mi cámara ahora</button>
        </form>
    </section>

    <footer>
        <p>Contacto: +51 987 654 321 | WhatsApp</p>
        <p><a href="#" style="color: #ffc107;">Política de Privacidad</a> | <a href="#" style="color: #ffc107;">Términos y Condiciones</a></p>
    </footer>
</body>
</html>

