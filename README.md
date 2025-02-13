<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marcos Embeleze</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Tangerine:wght@700&family=Alice&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        body {
            font-family: 'Alice', serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #F9F9F9, #CFCFCF);
            color: #1A1A1A;
        }
        header {
            text-align: center;
            padding: 0;
            background-color: #000000;
        }
        header img {
            width: 100%;
            max-height: 300px;
            object-fit: cover;
        }
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
            padding: 60px 20px;
            background: url('https://via.placeholder.com/1200x500') no-repeat center center/cover;
            color: #F9F9F9;
            animation: fadeIn 1.5s ease-in-out;
        }
        .hero img {
            max-width: 80%;
            max-height: 400px;
            object-fit: cover;
            border-radius: 15px;
            transition: transform 0.3s;
        }
        .hero img:hover {
            transform: scale(1.05);
        }
        .cta-button {
            background-color: #6E5119;
            color: #F9F9F9;
            padding: 15px 30px;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            border-radius: 10px;
            margin-top: 20px;
            transition: 0.3s;
            animation: pulse 1.5s infinite;
        }
        .cta-button:hover {
            background-color: #1A1A1A;
        }
        .section {
            max-width: 1200px;
            margin: 50px auto;
            padding: 20px;
            text-align: center;
        }
        .services, .testimonials, .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .service, .testimonial, .gallery-item {
            background-color: #CFCFCF;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .service:hover, .testimonial:hover, .gallery-item:hover {
            transform: translateY(-5px);
        }
        .service img, .gallery-item img {
            width: 100%;
            border-radius: 10px;
        }
        .testimonial p {
            font-style: italic;
        }
        .about {
            background-color: #6E5119;
            color: #F9F9F9;
            padding: 50px 20px;
            text-align: center;
        }
        .about h2 {
            margin-bottom: 20px;
        }
        footer {
            background-color: #1A1A1A;
            color: #F9F9F9;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
        footer p {
            margin: 5px 0;
        }
        .social-icons {
            margin-top: 10px;
        }
        .social-icons i {
            margin: 0 10px;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        .social-icons i:hover {
            color: #6E5119;
        }
        .register-text {
            color: #6E5119;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        @media (max-width: 768px) {
            header img {
                max-height: 200px;
            }
            .section {
                padding: 10px;
            }
            .service, .testimonial, .gallery-item {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="banner marcos.png" alt="Banner Marcos Embeleze">
    </header>
    <section class="hero">
        <p class="register-text">Realce sua beleza com nossos serviços especializados.</p>
        <button class="cta-button" onclick="window.location.href='https://eagenda.com.br/agendamentos/incluir/me/12403475A/8809861S'">Agendar Agora</button>
    </section>
    <section class="about">
        <h2>Sobre Nós</h2>
        <p>Somos especialistas em realçar sua beleza, oferecendo serviços de alta qualidade para deixar você ainda mais deslumbrante.</p>
    </section>
    <section class="section">
        <h2>Nossos Serviços</h2>
        <div class="services">
            <div class="service"><img src="corte-bob-2.jpg" alt="Corte de cabelo"><p>Cortes modernos e estilosos para você!</p></div>
            <div class="service"><img src="OIP.jpeg" alt="Penteado"><p>Penteados sofisticados para qualquer ocasião!</p></div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Marcos Embeleze. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
# site_do_marcos
