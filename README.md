<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samlly - Arreglos Florales a Domicilio</title>
    <style>
        
        body {
            font-family: sans-serif;
            margin: 0;
            background-color: #fcf8f5; 
            color: #333;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #fff; 
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .header .logo {
            font-weight: bold;
            font-size: 24px;
            color: #d17a8e; 
        }
        .header nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        .header nav ul li {
            margin-left: 30px;
        }
        .header nav ul li a {
            text-decoration: none;
            color: #666;
            font-weight: 500;
        }
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-around;
            padding: 80px 50px;
            background-color: #faebee; 
            position: relative;
            overflow: hidden;
        }
        .hero-content {
            flex: 1;
            max-width: 500px;
            text-align: left;
        }
        .hero-content h1 {
            font-size: 3.5em;
            color: #d17a8e; 
            margin-bottom: 20px;
            line-height: 1.1;
        }
        .hero-content .cta-button {
            display: inline-block;
            background-color: #e2a8af; 
            color: white;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.1em;
            margin-top: 20px;
        }
        .hero-image {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .hero-image img {
            max-width: 100%;
            height: auto;
            border-radius: 10px; 
        }

        .popular-section {
            padding: 60px 50px;
            text-align: center;
        }
        .popular-section h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #333;
        }
        .popular-categories {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        .category-item {
            background-color: #fff;
            border: 1px solid #eee;
            border-radius: 10px;
            width: 250px; 
            height: 200px; 
            display: flex;
            justify-content: center;
            align-items: flex-end;
            padding-bottom: 20px;
            font-size: 1.2em;
            font-weight: 600;
            color: #555;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .how-it-works-section {
            padding: 60px 50px;
            text-align: center;
            background-color: #fcf8f5;
        }
        .how-it-works-section h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #333;
        }
        .steps {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
        }
        .step-item {
            display: flex;
            align-items: center;
            font-size: 1.2em;
            color: #555;
            max-width: 300px;
            text-align: left;
        }
        .step-item .step-number {
            font-size: 2em;
            font-weight: bold;
            color: #d17a8e;
        }

        .footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #fff;
            border-top: 1px solid #eee;
        }
        .footer .social-icons a {
            margin-right: 15px;
            color: #666;
            text-decoration: none;
            font-size: 24px; 
        }
        .footer .contact-whatsapp {
            display: flex;
            align-items: center;
            color: #25D366; 
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        .footer .contact-whatsapp img {
            width: 30px; /
            height: 30px;
            margin-left: 10px;
        }

      
        @media (max-width: 768px) {
            .header, .hero, .popular-section, .how-it-works-section, .footer {
                flex-direction: column;
                padding: 20px;
            }
            .header nav ul {
                flex-direction: column;
                margin-top: 15px;
            }
            .header nav ul li {
                margin-left: 0;
                margin-bottom: 10px;
            }
            .hero-content h1 {
                font-size: 2.5em;
                text-align: center;
            }
            .hero-content .cta-button {
                width: 100%;
                text-align: center;
            }
            .hero-image {
                margin-top: 30px;
            }
            .popular-categories, .steps {
                flex-direction: column;
                align-items: center;
            }
            .category-item, .step-item {
                width: 90%;
                max-width: 350px;
            }
            .footer {
                text-align: center;
            }
            .footer .social-icons {
                margin-bottom: 15px;
            }
        }
    </style>
</head>
<body>

    <header class="header">
        <div class="logo">Samlly</div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Catalogo</a></li>
                <li><a href="#">Personaliza tu ramo</a></li>
                <li><a href="#">Sobre nosotros</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Arreglos Florales a Domicilio</h1>
            <a href="#" class="cta-button">Empieza tu test floral</a>
        </div>
        <div class="hero-image">
            <img src="https://images.vexels.com/media/users/3/126597/isolated/preview/304e3ec6fa7355dbabe18496d7366c63-flores-ramo-boda-romance.png?w=360" alt="Bouquet de Rosas">
        </div>
    </section>

    <section class="popular-section">
        <h2>Populares</h2>
        <div class="popular-categories">
            <div class="category-item">Romántico</div>
            <div class="category-item">Cumpleaños</div>
            <div class="category-item">Especial</div>
        </div>
    </section>

    <section class="how-it-works-section">
        <h2>¿Cómo Funciona?</h2>
        <div class="steps">
            <div class="step-item">
                <span class="step-number">1</span> Llena el cuestionario
            </div>
            <div class="step-item">
                <span class="step-number">2</span> Recibe sugerencias personalizadas
            </div>
            <div class="step-item">
                <span class="step-number">3</span> Haz tu pedido
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="social-icons">
            <a href="https://www.instagram.com/dulce_samlly?igsh=MWlsOGxkZm5lMWZuNA==" aria-label="Instagram">📸</a> </div>
        <div>
            <a href="https://wa.me/" class="contact-whatsapp" aria-label="WhatsApp">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" style="width: 72px; height: 72px;">
            </a>
        </div>
    </footer>

</body>
</html>
