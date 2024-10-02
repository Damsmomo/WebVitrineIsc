<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImoSmartChain - Plataforma Inmobiliaria Inteligente</title>
    <style>
        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        /* Header */
        header {
            background: #35424a;
            color: #ffffff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            margin: 0;
            list-style: none;
            overflow: hidden;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        header .highlight, header .current a {
            color: #e8491d;
            font-weight: bold;
        }
        header a:hover {
            color: #cccccc;
            font-weight: bold;
        }
        /* Showcase */
        #showcase {
            min-height: 400px;
            background: url('https://images.unsplash.com/photo-1560518883-ce09059eeffa?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1073&q=80') no-repeat 0 -400px;
            text-align: center;
            color: #ffffff;
        }
        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        /* Newsletter */
        #newsletter {
            padding: 15px;
            color: #ffffff;
            background: #35424a;
        }
        #newsletter h1 {
            float: left;
        }
        #newsletter form {
            float: right;
            margin-top: 15px;
        }
        #newsletter input[type="email"] {
            padding: 4px;
            height: 25px;
            width: 250px;
        }
        /* Boxes */
        #boxes {
            margin-top: 20px;
        }
        #boxes .box {
            float: left;
            text-align: center;
            width: 30%;
            padding: 10px;
        }
        #boxes .box img {
            width: 90px;
        }
        /* Sidebar */
        aside#sidebar {
            float: right;
            width: 30%;
            margin-top: 10px;
        }
        /* Main-col */
        article#main-col {
            float: left;
            width: 65%;
        }
        /* Services */
        ul#services li {
            list-style: none;
            padding: 20px;
            border: #cccccc solid 1px;
            margin-bottom: 5px;
            background: #e6e6e6;
        }
        /* Pricing */
        .pricing-plan {
            background: #f4f4f4;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            text-align: center;
        }
        .pricing-plan h3 {
            color: #e8491d;
        }
        .price {
            font-size: 24px;
            font-weight: bold;
            margin: 20px 0;
        }
        .features {
            list-style: none;
            padding: 0;
        }
        .features li {
            margin: 10px 0;
        }
        .cta-button {
            background: #e8491d;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
        }
        /* Footer */
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #ffffff;
            background-color: #e8491d;
            text-align: center;
        }
        /* Media Queries */
        @media(max-width: 768px) {
            header #branding,
            header nav,
            header nav li,
            #newsletter h1,
            #newsletter form,
            #boxes .box,
            article#main-col,
            aside#sidebar {
                float: none;
                text-align: center;
                width: 100%;
            }
            header {
                padding-bottom: 20px;
            }
            #showcase h1 {
                margin-top: 40px;
            }
            #newsletter button, .quote button {
                display: block;
                width: 100%;
            }
            #newsletter form input[type="email"], .quote input, .quote textarea {
                width: 100%;
                margin-bottom: 5px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">ImoSmartChain</span> Plataforma Inmobiliaria</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="#home">Inicio</a></li>
                    <li><a href="#services">Servicios</a></li>
                    <li><a href="#pricing">Precios</a></li>
                    <li><a href="#about">Sobre Nosotros</a></li>
                    <li><a href="#contact">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>Revoluciona tu Experiencia Inmobiliaria</h1>
            <p>Descubre el poder de la tecnología en el sector inmobiliario con ImoSmartChain</p>
        </div>
    </section>

    <section id="newsletter">
        <div class="container">
            <h1>Suscríbete a nuestro boletín</h1>
            <form>
                <input type="email" placeholder="Ingresa tu email...">
                <button type="submit" class="button_1">Suscribirse</button>
            </form>
        </div>
    </section>

    <section id="boxes">
        <div class="container">
            <div class="box">
                <img src="https://img.icons8.com/color/96/000000/house.png" alt="Icono de casa">
                <h3>Estimación de Propiedades</h3>
                <p>Obtén una estimación precisa de tu propiedad en cuestión de minutos.</p>
            </div>
            <div class="box">
                <img src="https://img.icons8.com/color/96/000000/handshake.png" alt="Icono de apretón de manos">
                <h3>Servicios Inmobiliarios</h3>
                <p>Conecta con profesionales y solicita presupuestos de servicios inmobiliarios.</p>
            </div>
            <div class="box">
                <img src="https://img.icons8.com/color/96/000000/sale.png" alt="Icono de venta">
                <h3>Comercialización</h3>
                <p>Vende o alquila tu propiedad con nuestra plataforma potenciada por IA.</p>
            </div>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Nuestros Servicios</h2>
            <ul id="services">
                <li>
                    <h3>Estimación de Propiedades</h3>
                    <p>Utiliza nuestra aplicación móvil para obtener una estimación preliminar de cualquier propiedad en el mundo con solo unos clics.</p>
                </li>
                <li>
                    <h3>Solicitud de Presupuestos</h3>
                    <p>Solicita presupuestos gratuitos para diversos servicios inmobiliarios directamente desde nuestra aplicación o sitio web.</p>
                </li>
                <li>
                    <h3>Servicios Adicionales en España</h3>
                    <p>Para propiedades en España, ofrecemos servicios adicionales como la compra de documentos específicos de la propiedad.</p>
                </li>
                <li>
                    <h3>Comercialización de Propiedades</h3>
                    <p>Publica tu propiedad en venta o alquiler, aprovechando nuestras herramientas potenciadas por IA para una mayor visibilidad.</p>
                </li>
            </ul>
        </div>
    </section>

    <section id="pricing">
        <div class="container">
            <h2>Planes de Precios</h2>
            <div class="pricing-plan">
                <h3>Plan Freemium</h3>
                <p class="price">Gratis</p>
                <ul class="features">
                    <li>Estimaciones de propiedades con anuncios</li>
                    <li>Opción de compras individuales</li>
                    <li>Acceso a funciones básicas</li>
                </ul>
                <a href="#" class="cta-button">Comenzar Gratis</a>
            </div>
            <div class="pricing-plan">
                <h3>Plan PRO</h3>
                <p class="price">€2.49/mes <span style="text-decoration: line-through; color: #888;">€4.99</span></p>
                <ul class="features">
                    <li>10 estimaciones de propiedades por mes</li>
                    <li>Sin anuncios</li>
                    <li>Acceso a funciones avanzadas</li>
                </ul>
                <a href="#" class="cta-button">Obtener PRO</a>
            </div>
            <div class="pricing-plan">
                <h3>Plan Agencia Inmobiliaria</h3>
                <p class="price">€9.99/mes</p>
                <ul class="features">
                    <li>30 estimaciones de propiedades por mes</li>
                    <li>Sin anuncios</li>
                    <li>Listado en resultados de estimación</li>
                    <li>Herramientas exclusivas para agencias</li>
                </ul>
                <a href="#" class="cta-button">Unirse como Agencia</a>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>Sobre ImoSmartChain</h2>
            <p>ImoSmartChain es una startup española innovadora en el sector inmobiliario. Nuestra misión es revolucionar la forma en que las personas interactúan con el mercado inmobiliario, ofreciendo herramientas inteligentes y servicios eficientes tanto para particulares como para profesionales.</p>
            <p>Con nuestra plataforma y aplicación móvil, buscamos simplificar procesos complejos como la estimación de propiedades, la búsqueda de servicios inmobiliarios y la comercialización de propiedades. Utilizamos tecnología de vanguardia, incluyendo inteligencia artificial, para proporcionar soluciones precisas y personalizadas.</p>
            <p>Nuestro objetivo es crecer continuamente, expandiendo nuestros servicios y soluciones para satisfacer las necesidades cambiantes de nuestros usuarios en toda la Unión Europea.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contacto</h2>
            <p>¿Tienes alguna pregunta o comentario? No dudes en ponerte en contacto con nosotros.</p>
            <form>
                <input type="text" name="name" placeholder="Nombre" required>
                <input type="email" name="email" placeholder="Email" required>
                <textarea name="message" placeholder="Tu mensaje" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <footer>
        <p>ImoSmartChain &copy; 2024 | Política de Privacidad | Términos de Servicio</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Newsletter subscription form
        document.querySelector('#newsletter form').addEventListener('submit', function(e) {
            e.preventDefault();
            const email = this.querySelector('input[type="email"]').value;
            // Here you would typically send this email to your server or a service like OneSignal
            console.log('Subscribing email:', email);
            alert('¡Gracias por suscribirte a nuestro boletín!');
            this.reset();
        });

        // Contact form submission
        document.querySelector('#contact form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = this.querySelector('input[name="name"]').value;
            const email = this.querySelector('input[name="email"]').value;
            const message = this.querySelector('textarea[name="message"]').value;
            // Here you would typically send this data to your server
