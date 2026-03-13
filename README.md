<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPS do Motoca | Plano de Negócios</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary-color: #ffcc00; /* Amarelo Motoca */
            --secondary-color: #1a1a1a; /* Preto Carbono */
            --accent-color: #ff4444; /* Vermelho Alerta */
            --bg-dark: #0f0f0f;
            --text-light: #f8f9fa;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-light);
            overflow-x: hidden;
        }

        /* Hero Section Estilo Logdev */
        .hero {
            padding: 100px 0 60px;
            background: radial-gradient(circle at top right, #333, #0f0f0f);
            border-bottom: 2px solid var(--primary-color);
        }

        .hero h1 {
            font-size: 3.5rem;
            font-weight: 800;
            color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: -1px;
        }

        .hero p {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 700px;
            margin: 0 auto;
        }

        /* Cards Estilizados */
        .custom-card {
            background: #1a1a1a;
            border: 1px solid #333;
            border-radius: 20px;
            padding: 30px;
            height: 100%;
            transition: all 0.3s ease;
        }

        .custom-card:hover {
            border-color: var(--primary-color);
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(255, 204, 0, 0.1);
        }

        .card-icon {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 20px;
        }

        .section-title {
            color: var(--primary-color);
            text-transform: uppercase;
            font-weight: 800;
            margin-bottom: 40px;
            text-align: center;
        }

        /* Tabela de Preços Premium */
        .pricing-card {
            background: linear-gradient(180deg, #222 0%, #111 100%);
            border: 2px solid #333;
            padding: 40px;
            border-radius: 30px;
            text-align: center;
        }

        .pricing-card.popular {
            border-color: var(--primary-color);
            transform: scale(1.05);
        }

        .price {
            font-size: 3rem;
            font-weight: 800;
            color: var(--primary-color);
        }

        /* Pitch Section */
        .pitch-container {
            background-color: var(--primary-color);
            color: #000;
            padding: 50px;
            border-radius: 30px;
            margin-top: 50px;
        }

        /* Badge Estilo Logdev */
        .badge-custom {
            background-color: var(--primary-color);
            color: #000;
            padding: 8px 20px;
            border-radius: 50px;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 0.8rem;
        }

        /* Footer */
        footer {
            padding: 50px 0;
            border-top: 1px solid #333;
            text-align: center;
            opacity: 0.6;
        }

        /* Mobile Adjustments */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .pricing-card.popular { transform: none; }
        }
    </style>
</head>
<body>

    <section class="hero text-center">
        <div class="container">
            <span class="badge-custom mb-3">Guarulhos - Marco Zero</span>
            <h1>GPS do Motoca 🛵</h1>
            <p class="mt-3">Transformando o tempo ocioso em faturamento real. O sistema de inteligência coletiva que devolve o poder para quem está no trecho.</p>
            <div class="mt-4">
                <a href="#pitch" class="btn btn-warning btn-lg fw-bold px-5 py-3 rounded-pill">VER ESTRATÉGIA</a>
            </div>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <div class="row g-4">
                <div class="col-md-6">
                    <div class="custom-card">
                        <i class="fa-solid fa-file-lines card-icon"></i>
                        <h3>A) Resumo Executivo</h3>
                        <p>O GPS do Motoca foca exclusivamente na produtividade do entregador. Unimos faturamento com uma rede de descontos local, transformando o "tempo morto" em economia e lucro.</p>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="custom-card">
                        <i class="fa-solid fa-user-group card-icon"></i>
                        <h3>C) Persona: Jorge</h3>
                        <p><strong>Dilema:</strong> Motoboy de Guarulhos cansado de "rodar no escuro".<br>
                        <strong>JTBD:</strong> "Preciso saber onde está tocando pedido agora para não gastar gasolina à toa."</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-5 bg-black">
        <div class="container text-center">
            <h2 class="section-title">Engrenagens do Negócio</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="custom-card">
                        <i class="fa-solid fa-map-location-dot card-icon"></i>
                        <h4>MVP & Produto</h4>
                        <p class="small">Mapa de calor em tempo real (20 min), reporte rápido e cadastro via CPF para segurança total da comunidade.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="custom-card">
                        <i class="fa-solid fa-bolt card-icon"></i>
                        <h4>Go-To-Market</h4>
                        <p class="small">Abordagem física nos Shoppings Maia/Internacional. Marketing de guerrilha com distribuição de brindes úteis.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="custom-card">
                        <i class="fa-solid fa-handshake card-icon"></i>
                        <h4>Parcerias B2B</h4>
                        <p class="small">Pins patrocinados (Oficina/Posto) de R$ 50 a R$ 100/mês. Fidelização real de quem faz a economia girar.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <h2 class="section-title">I) Planos de Assinatura</h2>
            <div class="row g-4 justify-content-center">
                <div class="col-md-3">
                    <div class="pricing-card">
                        <h5>Semanal</h5>
                        <div class="price">R$ 4,90</div>
                        <p class="small text-muted">Ideal para o fluxo semanal</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="pricing-card popular">
                        <span class="badge bg-warning text-dark mb-2">MAIS VENDIDO</span>
                        <h5>Mensal</h5>
                        <div class="price">R$ 14,90</div>
                        <p class="small">Menos que uma entrega!</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="pricing-card">
                        <h5>Quinzenal</h5>
                        <div class="price">R$ 10,90</div>
                        <p class="small text-muted">Equilíbrio perfeito</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="pitch" class="py-5">
        <div class="container">
            <div class="pitch-container shadow-lg">
                <div class="row align-items-center">
                    <div class="col-md-2 text-center">
                        <i class="fa-solid fa-bullhorn" style="font-size: 4rem;"></i>
                    </div>
                    <div class="col-md-10">
                        <h2 class="fw-800">N) O PITCH DE 2 MINUTOS</h2>
                        <p class="fs-4 italic">"Você já sentiu que o iFood te esqueceu na calçada? Enquanto você espera 1h, a gasolina e o tempo vão embora. O GPS do Motoca é a união da categoria: a gente mostra onde o pedido tá saindo, onde tem blitz e onde a marmita é barata. Custa menos que um café por semana e se paga na primeira entrega que você não perderia. Sou entregador, conheço o trecho e vim pra mudar o jogo em Guarulhos. Vamos rodar juntos?"</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-5 bg-black">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h4 class="text-warning mb-4">M) Plano 30/60/90 Dias</h4>
                    <ul class="list-unstyled">
                        <li class="mb-3"><i class="fa-solid fa-check text-warning me-2"></i> <strong>30:</strong> Fechar 5 parceiros e lançar Beta.</li>
                        <li class="mb-3"><i class="fa-solid fa-check text-warning me-2"></i> <strong>60:</strong> Bater 200 assinantes em Guarulhos.</li>
                        <li class="mb-3"><i class="fa-solid fa-check text-warning me-2"></i> <strong>90:</strong> Escalar para 500 assinantes.</li>
                    </ul>
                </div>
                <div class="col-md-6">
                    <h4 class="text-warning mb-4">L) Matriz de Riscos</h4>
                    <div class="custom-card p-3">
                        <p class="mb-2"><strong>Baixa Adesão:</strong> Mitigação via brindes e prova social.</p>
                        <p class="mb-0"><strong>Informação Falsa:</strong> Regra de 2 confirmações + Ban automático.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>GPS do Motoca - Plano de Marketing Estratégico &copy; 2026</p>
            <p class="small">Desenvolvido sob o conceito de Inteligência Coletiva para Guarulhos.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
