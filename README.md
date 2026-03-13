<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPS do Motoca | Plano de Marketing Profissional</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>

    <style>
        :root {
            --primary: #ffcc00; /* Amarelo Vibrante */
            --bg: #0a0a0a;
            --card-bg: #141414;
            --text: #ffffff;
            --accent: #ff9900;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: 'Poppins', sans-serif;
            overflow-x: hidden;
        }

        /* Hero Section igual ao LogDev */
        .hero-section {
            padding: 120px 0 80px;
            background: radial-gradient(circle at top right, #222, #0a0a0a);
            text-align: center;
        }

        .hero-title {
            font-size: clamp(2.5rem, 8vw, 4.5rem);
            font-weight: 800;
            color: var(--primary);
            text-transform: uppercase;
            margin-bottom: 20px;
        }

        .badge-main {
            background: var(--primary);
            color: #000;
            padding: 8px 25px;
            border-radius: 50px;
            font-weight: 700;
            font-size: 0.9rem;
            display: inline-block;
            margin-bottom: 20px;
        }

        /* Grid de Cards Interativos */
        .card-box {
            background: var(--card-bg);
            border: 1px solid #222;
            border-radius: 20px;
            padding: 35px;
            height: 100%;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            position: relative;
            overflow: hidden;
        }

        .card-box:hover {
            transform: translateY(-12px);
            border-color: var(--primary);
            box-shadow: 0 15px 40px rgba(255, 204, 0, 0.15);
        }

        .card-box i {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 25px;
            display: block;
        }

        .card-box h3 {
            font-weight: 700;
            margin-bottom: 15px;
            color: var(--primary);
        }

        .card-box p {
            color: #ccc;
            font-size: 0.95rem;
            line-height: 1.6;
        }

        /* Seção de Planos (Pricing) */
        .price-card {
            background: #111;
            border: 2px solid #222;
            border-radius: 25px;
            padding: 40px;
            text-align: center;
            transition: 0.3s;
        }

        .price-card.featured {
            border-color: var(--primary);
            background: linear-gradient(145deg, #181818, #0a0a0a);
            transform: scale(1.05);
        }

        .price-val {
            font-size: 3.5rem;
            font-weight: 800;
            margin: 20px 0;
            color: var(--primary);
        }

        /* Pitch Section High-Contrast */
        .pitch-banner {
            background: var(--primary);
            color: #000;
            padding: 60px;
            border-radius: 40px;
            margin: 80px 0;
        }

        .pitch-banner h2 {
            font-weight: 800;
            text-transform: uppercase;
        }

        /* Footer */
        footer {
            border-top: 1px solid #222;
            padding: 60px 0;
            text-align: center;
            color: #666;
        }

        /* Scroll Animation Simulator */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease-out;
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        .btn-custom {
            background: var(--primary);
            color: #000;
            font-weight: 700;
            padding: 15px 40px;
            border-radius: 50px;
            text-transform: uppercase;
            text-decoration: none;
            transition: 0.3s;
            display: inline-block;
        }

        .btn-custom:hover {
            background: #fff;
            transform: scale(1.05);
        }

    </style>
</head>
<body>

    <section class="hero-section animate__animated animate__fadeIn">
        <div class="container">
            <span class="badge-main">PROJETO GUARULHOS - MARCO ZERO</span>
            <h1 class="hero-title">GPS DO MOTOCA</h1>
            <p class="lead mb-5">Unindo o trecho com inteligência. O mapa que faz o seu dinheiro render mais através da colaboração.</p>
            <a href="#conteudo" class="btn-custom">Ver Plano Completo</a>
        </div>
    </section>

    <div class="container py-5" id="conteudo">
        
        <div class="text-center mb-5 reveal">
            <h2 class="display-5 fw-bold text-uppercase">O Mapa da Mina 🗺️</h2>
            <div style="width: 80px; height: 4px; background: var(--primary); margin: 20px auto;"></div>
        </div>

        <div class="row g-4 mb-5">
            <div class="col-md-4 reveal">
                <div class="card-box">
                    <i class="fa-solid fa-rocket"></i>
                    <h3>Resumo Executivo</h3>
                    <p>Foco total na produtividade. Unimos a necessidade de faturamento com rede de descontos, eliminando o tempo morto e otimizando o lucro real.</p>
                </div>
            </div>
            <div class="col-md-4 reveal">
                <div class="card-box">
                    <i class="fa-solid fa-users-viewfinder"></i>
                    <h3>Público Alvo</h3>
                    <p>O "Jorge", 28 anos, motoboy profissional. Ele quer parar de gastar gasolina rodando à toa e precisa de suporte real da comunidade.</p>
                </div>
            </div>
            <div class="col-md-4 reveal">
                <div class="card-box">
                    <i class="fa-solid fa-map-location-dot"></i>
                    <h3>O Produto (MVP)</h3>
                    <p>Mapa de calor de alta precisão (dados de 20 min). Clique longo para reportar, alertas de segurança e sistema de pontos.</p>
                </div>
            </div>
        </div>

        <div class="row g-4 justify-content-center my-5 reveal">
            <div class="col-md-4">
                <div class="price-card">
                    <h4>Semanal</h4>
                    <div class="price-val">R$ 4,90</div>
                    <p>Ideal para validar o trecho</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="price-card featured">
                    <span class="badge bg-warning text-dark mb-2">MAIS POPULAR</span>
                    <h4>Mensal</h4>
                    <div class="price-val">R$ 14,90</div>
                    <p>Menos de uma entrega por mês!</p>
                </div>
            </div>
        </div>

        <div class="pitch-banner reveal">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <h2>O Papo é de Visão! 🎙️</h2>
                    <p class="fs-4 italic">"O GPS do Motoca é a união da categoria. A gente mostra onde o pedido tá saindo, onde tem blitz e onde a marmita é barata. Se paga na primeira entrega que você não perderia."</p>
                </div>
                <div class="col-lg-4 text-center">
                    <i class="fa-solid fa-motorcycle" style="font-size: 8rem; opacity: 0.2;"></i>
                </div>
            </div>
        </div>

        <div class="row mb-5 reveal">
            <div class="col-12 text-center">
                <h2 class="mb-5 text-uppercase">Plano 30 / 60 / 90 Dias</h2>
            </div>
            <div class="col-md-4">
                <div class="card-box">
                    <span class="badge bg-primary mb-3">MÊS 01</span>
                    <p>Fechar 5 parceiros e lançar o Beta para amigos de Guarulhos.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card-box">
                    <span class="badge bg-primary mb-3">MÊS 02</span>
                    <p>Ação nos Shoppings Maia e Internacional para bater 200 assinantes.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card-box">
                    <span class="badge bg-primary mb-3">MÊS 03</span>
                    <p>Escalar para 500 assinantes e dominar o Centro de Guarulhos.</p>
                </div>
            </div>
        </div>

    </div>

    <footer>
        <div class="container">
            <p>GPS DO MOTOCA &copy; 2026 | ESTRATÉGIA LOGÍSTICA</p>
            <p class="small">Desenvolvido sob o conceito de economia colaborativa.</p>
        </div>
    </footer>

    <script>
        function reveal() {
            var reveals = document.querySelectorAll(".reveal");
            for (var i = 0; i < reveals.length; i++) {
                var windowHeight = window.innerHeight;
                var elementTop = reveals[i].getBoundingClientRect().top;
                var elementVisible = 150;
                if (elementTop < windowHeight - elementVisible) {
                    reveals[i].classList.add("active");
                }
            }
        }
        window.addEventListener("scroll", reveal);
        reveal(); // Inicializar
    </script>
</body>
</html>
