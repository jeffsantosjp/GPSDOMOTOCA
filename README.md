<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPS do Motoca | Business Plan</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        :root {
            --primary: #FFD700; /* Amarelo Vibrante */
            --bg-dark: #0a0a0b;
            --card-bg: rgba(255, 255, 255, 0.03);
            --card-border: rgba(255, 255, 255, 0.08);
            --accent: #ffa500;
        }

        body {
            background-color: var(--bg-dark);
            color: #ffffff;
            font-family: 'Poppins', sans-serif;
            overflow-x: hidden;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: radial-gradient(circle at 50% 50%, #1a1a1d 0%, #0a0a0b 100%);
            text-align: center;
            border-bottom: 1px solid var(--card-border);
        }

        .badge-premium {
            background: rgba(255, 215, 0, 0.1);
            color: var(--primary);
            border: 1px solid var(--primary);
            padding: 5px 20px;
            border-radius: 50px;
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 20px;
            display: inline-block;
        }

        h1.main-title {
            font-size: clamp(2.5rem, 8vw, 5rem);
            font-weight: 800;
            line-height: 1.1;
            margin-bottom: 20px;
        }

        .highlight {
            color: var(--primary);
            text-shadow: 0 0 20px rgba(255, 215, 0, 0.3);
        }

        /* Cards Estilo LogDev */
        .glass-card {
            background: var(--card-bg);
            backdrop-filter: blur(10px);
            border: 1px solid var(--card-border);
            border-radius: 24px;
            padding: 40px;
            height: 100%;
            transition: all 0.4s ease;
        }

        .glass-card:hover {
            border-color: var(--primary);
            transform: translateY(-10px);
            background: rgba(255, 215, 0, 0.02);
        }

        .icon-box {
            width: 60px;
            height: 60px;
            background: var(--primary);
            color: #000;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 16px;
            font-size: 1.5rem;
            margin-bottom: 25px;
        }

        /* Pricing Section */
        .price-card {
            background: #111;
            border: 1px solid var(--card-border);
            border-radius: 30px;
            padding: 50px 30px;
            text-align: center;
            position: relative;
        }

        .price-card.featured {
            border: 2px solid var(--primary);
            transform: scale(1.05);
            z-index: 2;
        }

        .price-amount {
            font-size: 3.5rem;
            font-weight: 800;
            color: var(--primary);
            margin: 20px 0;
        }

        /* Pitch Banner */
        .pitch-banner {
            background: var(--primary);
            color: #000;
            padding: 80px 40px;
            border-radius: 40px;
            margin-top: 100px;
            position: relative;
            overflow: hidden;
        }

        .pitch-banner h2 {
            font-weight: 800;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        /* Botão */
        .btn-cta {
            background: var(--primary);
            color: #000;
            padding: 15px 40px;
            border-radius: 50px;
            font-weight: 700;
            text-transform: uppercase;
            text-decoration: none;
            transition: 0.3s;
            display: inline-block;
        }

        .btn-cta:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(255, 215, 0, 0.4);
            color: #000;
        }

        footer {
            padding: 60px 0;
            border-top: 1px solid var(--card-border);
            text-align: center;
            color: #555;
        }

    </style>
</head>
<body>

    <section class="hero">
        <div class="container" data-aos="zoom-in">
            <span class="badge-premium">Guarulhos - Centro</span>
            <h1 class="main-title">GPS DO <span class="highlight">MOTOCA</span></h1>
            <p class="lead text-secondary mx-auto" style="max-width: 600px;">
                Unindo o trecho com inteligência compartilhada. O aplicativo feito por quem entrega para quem entrega.
            </p>
            <div class="mt-5">
                <a href="#plano" class="btn-cta">Explorar Plano</a>
            </div>
        </div>
    </section>

    <section id="plano" class="py-5">
        <div class="container py-5">
            <div class="row mb-5" data-aos="fade-up">
                <div class="col-12 text-center">
                    <h2 class="display-4 fw-bold mb-4">Estratégia <span class="highlight">Core</span></h2>
                </div>
            </div>

            <div class="row g-4">
                <div class="col-md-4" data-aos="fade-up" data-aos-delay="100">
                    <div class="glass-card">
                        <div class="icon-box"><i class="fa-solid fa-rocket"></i></div>
                        <h3>Resumo Executivo</h3>
                        <p class="text-secondary">O GPS do Motoca foca exclusivamente na produtividade do entregador profissional. Unimos dados em tempo real com uma rede de benefícios local.</p>
                    </div>
                </div>

                <div class="col-md-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="glass-card">
                        <div class="icon-box"><i class="fa-solid fa-users"></i></div>
                        <h3>Persona: Jorge</h3>
                        <p class="text-secondary">Motoboy profissional de Guarulhos. Sua dor é a ociosidade. Ele quer saber onde "está tocando" para não queimar gasolina à toa.</p>
                    </div>
                </div>

                <div class="col-md-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="glass-card">
                        <div class="icon-box"><i class="fa-solid fa-map-location-dot"></i></div>
                        <h3>MVP (Produto)</h3>
                        <p class="text-secondary">Mapa de calor preciso, alertas de segurança via dupla confirmação e clube de pontos para descontos em parceiros B2B.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-5 bg-black">
        <div class="container py-5">
            <div class="row mb-5 text-center" data-aos="fade-up">
                <div class="col-12">
                    <h2 class="display-4 fw-bold mb-4">Planos de <span class="highlight">Acesso</span></h2>
                </div>
            </div>

            <div class="row g-4 justify-content-center">
                <div class="col-md-4" data-aos="fade-right">
                    <div class="price-card">
                        <h5>Semanal</h5>
                        <div class="price-amount">R$ 4,90</div>
                        <p class="text-secondary">Acesso total por 7 dias</p>
                    </div>
                </div>

                <div class="col-md-4" data-aos="fade-up">
                    <div class="price-card featured">
                        <span class="badge bg-warning text-dark mb-3">RECOMENDADO</span>
                        <h5>Mensal</h5>
                        <div class="price-amount">R$ 14,90</div>
                        <p class="text-secondary">Equivalente a uma única entrega</p>
                    </div>
                </div>

                <div class="col-md-4" data-aos="fade-left">
                    <div class="price-card">
                        <h5>B2B</h5>
                        <div class="price-amount">R$ 100</div>
                        <p class="text-secondary">Mensais por oficina/posto (PIN)</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <div class="container mb-5" data-aos="zoom-in-up">
        <div class="pitch-banner">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <h2>"Papo de Visão" 🎙️</h2>
                    <p class="lead fw-bold">
                        "O GPS do Motoca é a união da categoria. Mostramos onde o pedido tá saindo e onde a blitz tá pegando. Se paga na primeira entrega que você não perderia."
                    </p>
                </div>
                <div class="col-lg-4 text-center">
                    <i class="fa-solid fa-motorcycle fa-8x" style="opacity: 0.2;"></i>
                </div>
            </div>
        </div>
    </div>

    <section class="py-5">
        <div class="container py-5">
            <div class="row g-4">
                <div class="col-md-4" data-aos="fade-up">
                    <h4 class="text-primary fw-bold">30 DIAS</h4>
                    <p>Fechar 5 parceiros (Mecânica/Posto) e lançar versão Beta no Centro de Guarulhos.</p>
                </div>
                <div class="col-md-4" data-aos="fade-up" data-aos-delay="100">
                    <h4 class="text-primary fw-bold">60 DIAS</h4>
                    <p>Ação massiva nos Shoppings Maia/Internacional para bater 200 assinantes.</p>
                </div>
                <div class="col-md-4" data-aos="fade-up" data-aos-delay="200">
                    <h4 class="text-primary fw-bold">90 DIAS</h4>
                    <p>Escala para 500 assinantes e consolidação como o "Waze dos Entregadores".</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>GPS DO MOTOCA &copy; 2026 | Desenvolvido para o Trecho</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 800,
            once: true
        });
    </script>
</body>
</html>
