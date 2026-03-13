<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPS do Motoca | Jornada Interativa</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary-color: #ffcc00;
            --bg-dark: #0f0f0f;
            --card-bg: #1a1a1a;
            --text-light: #f8f9fa;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-light);
            scroll-behavior: smooth;
        }

        .header-premium {
            padding: 80px 0;
            background: linear-gradient(180deg, #1a1a1a 0%, #0f0f0f 100%);
            border-bottom: 2px solid var(--primary-color);
        }

        .section-title {
            font-weight: 800;
            color: var(--primary-color);
            text-transform: uppercase;
            text-align: center;
            margin-bottom: 50px;
        }

        /* Menu de Etapas Lateral/Scroll */
        .nav-pills .nav-link {
            color: var(--text-light);
            background: var(--card-bg);
            margin-bottom: 10px;
            border: 1px solid #333;
            text-align: left;
            padding: 15px 20px;
            border-radius: 12px;
            transition: 0.3s;
        }

        .nav-pills .nav-link.active {
            background-color: var(--primary-color) !important;
            color: #000 !important;
            font-weight: 700;
            border-color: var(--primary-color);
            transform: scale(1.05);
        }

        .nav-pills .nav-link:hover:not(.active) {
            border-color: var(--primary-color);
        }

        /* Conteúdo das Etapas */
        .tab-content {
            background: var(--card-bg);
            padding: 40px;
            border-radius: 20px;
            border: 1px solid #333;
            min-height: 500px;
        }

        .etapa-badge {
            background: var(--primary-color);
            color: #000;
            padding: 5px 15px;
            border-radius: 50px;
            font-weight: 800;
            font-size: 0.8rem;
            margin-bottom: 15px;
            display: inline-block;
        }

        .highlight-box {
            background: #252525;
            padding: 20px;
            border-radius: 15px;
            border-left: 4px solid var(--primary-color);
            margin-top: 20px;
        }

        /* Preços */
        .price-tag {
            color: var(--primary-color);
            font-size: 1.5rem;
            font-weight: 800;
        }

        footer {
            padding: 40px 0;
            text-align: center;
            opacity: 0.5;
            font-size: 0.9rem;
        }

        /* Estilo Mobile */
        @media (max-width: 768px) {
            .nav-pills {
                flex-direction: row !important;
                overflow-x: auto;
                white-space: nowrap;
                display: flex;
                margin-bottom: 20px;
            }
            .nav-pills .nav-link {
                margin-right: 10px;
            }
        }
    </style>
</head>
<body>

    <header class="header-premium text-center">
        <div class="container">
            <h1 class="display-4 fw-800">GPS DO MOTOCA <span style="color:var(--primary-color)">PRO</span></h1>
            <p class="lead">Navegue pelas 10 etapas da construção do negócio em Guarulhos</p>
        </div>
    </header>

    <main class="container my-5">
        <div class="row">
            <div class="col-md-4">
                <div class="nav flex-column nav-pills me-3" id="v-pills-tab" role="tablist" aria-orientation="vertical">
                    <button class="nav-link active" id="tab0" data-bs-toggle="pill" data-bs-target="#content0" type="button">0. Contexto e Metas 🏁</button>
                    <button class="nav-link" id="tab1" data-bs-toggle="pill" data-bs-target="#content1" type="button">1. Ideia e Público 💡</button>
                    <button class="nav-link" id="tab2" data-bs-toggle="pill" data-bs-target="#content2" type="button">2. Mercado e Rivais 🗺️</button>
                    <button class="nav-link" id="tab3" data-bs-toggle="pill" data-bs-target="#content3" type="button">3. Proposta de Valor 💎</button>
                    <button class="nav-link" id="tab4" data-bs-toggle="pill" data-bs-target="#content4" type="button">4. Produto/MVP 📱</button>
                    <button class="nav-link" id="tab5" data-bs-toggle="pill" data-bs-target="#content5" type="button">5. Precificação 💰</button>
                    <button class="nav-link" id="tab6" data-bs-toggle="pill" data-bs-target="#content6" type="button">6. Go-To-Market 🚀</button>
                    <button class="nav-link" id="tab7" data-bs-toggle="pill" data-bs-target="#content7" type="button">7. Operação 🛠️</button>
                    <button class="nav-link" id="tab8" data-bs-toggle="pill" data-bs-target="#content8" type="button">8. Finanças 📈</button>
                    <button class="nav-link" id="tab9" data-bs-toggle="pill" data-bs-target="#content9" type="button">9. Plano 30/60/90 🗓️</button>
                    <button class="nav-link" id="tab10" data-bs-toggle="pill" data-bs-target="#content10" type="button">10. Pitch Final 🎤</button>
                </div>
            </div>

            <div class="col-md-8">
                <div class="tab-content shadow-lg" id="v-pills-tabContent">
                    
                    <div class="tab-pane fade show active" id="content0">
                        <span class="etapa-badge">ETAPA 0</span>
                        <h2>Contexto e Metas</h2>
                        <p>O foco é dominar o setor de logística colaborativa em Guarulhos-SP.</p>
                        <div class="highlight-box">
                            <strong>Meta 90 dias:</strong> Bater 500 usuários pagantes e validar o modelo de troca de informações por descontos.
                        </div>
                    </div>

                    <div class="tab-pane fade" id="content1">
                        <span class="etapa-badge">ETAPA 1</span>
                        <h2>Ideia, Problema e Público</h2>
                        <p><strong>Público:</strong> Entregadores Full-time (12h/dia).</p>
                        <p><strong>Problema:</strong> Ociosidade e o "rodar no escuro" gastando gasolina sem necessidade.</p>
                        <p><strong>JTBD:</strong> O trabalho é encontrar demanda real onde o algoritmo do app de entrega é opaco.</p>
                    </div>

                    <div class="tab-pane fade" id="content2">
                        <span class="etapa-badge">ETAPA 2</span>
                        <h2>Pesquisa e Concorrência</h2>
                        <p>O vilão não é o iFood, é a <strong>intuição falha</strong> do entregador. Nosso diferencial contra o Waze é a hiper-especialização em duas rodas e suporte de parcerias locais.</p>
                    </div>

                    <div class="tab-pane fade" id="content3">
                        <span class="etapa-badge">ETAPA 3</span>
                        <h2>Proposta de Valor</h2>
                        <h3 class="text-warning">"Ganhe mais, rode menos."</h3>
                        <ul class="mt-3">
                            <li>Dados de "Pontos Quentes" atualizados a cada 20 min.</li>
                            <li>Clube de Benefícios (Gasolina, Mecânica, Marmita).</li>
                            <li>Segurança Comunitária (Alertas de Blitz/Enchentes).</li>
                        </ul>
                    </div>

                    <div class="tab-pane fade" id="content4">
                        <span class="etapa-badge">ETAPA 4</span>
                        <h2>Produto / MVP</h2>
                        <p>Interface simples: Um mapa de calor de alta precisão.</p>
                        <div class="highlight-box">
                            <strong>Core:</strong> Clique longo para reportar + Validação por GPS + Dupla confirmação (evita dados falsos).
                        </div>
                    </div>

                    <div class="tab-pane fade" id="content5">
                        <span class="etapa-badge">ETAPA 5</span>
                        <h2>Modelo de Negócio</h2>
                        <div class="row mt-4">
                            <div class="col-6">
                                <h5>B2C (Assinaturas)</h5>
                                <p>Semanal: <span class="price-tag">R$ 4,90</span></p>
                                <p>Mensal: <span class="price-tag">R$ 14,90</span></p>
                            </div>
                            <div class="col-6">
                                <h5>B2B (Parceiros)</h5>
                                <p>Pins no Mapa: <span class="price-tag">R$ 100/mês</span></p>
                            </div>
                        </div>
                    </div>

                    <div class="tab-pane fade" id="content6">
                        <span class="etapa-badge">ETAPA 6</span>
                        <h2>Go-To-Market</h2>
                        <p>Marketing de Guerrilha: Shoppings Maia e Internacional.</p>
                        <p><strong>Isca:</strong> 7 dias grátis + Distribuição de água e capas de celular para gerar prova social.</p>
                    </div>

                    <div class="tab-pane fade" id="content7">
                        <span class="etapa-badge">ETAPA 7</span>
                        <h2>Operação e Qualidade</h2>
                        <ul>
                            <li>Suporte via WhatsApp Business.</li>
                            <li>Sistema de "Ban" automático após 3 denúncias.</li>
                            <li>Dados expiram após 20 minutos para manter o mapa "quente".</li>
                        </ul>
                    </div>

                    <div class="tab-pane fade" id="content8">
                        <span class="etapa-badge">ETAPA 8</span>
                        <h2>Finanças (Unit Economics)</h2>
                        <p><strong>Investimento:</strong> R$ 5k - R$ 10k (MVP).</p>
                        <p><strong>CAC Alvo:</strong> R$ 5,00 (Custo por novo pagante).</p>
                        <p><strong>Faturamento Estimado:</strong> R$ 7.450,00/mês (com 500 usuários).</p>
                    </div>

                    <div class="tab-pane fade" id="content9">
                        <span class="etapa-badge">ETAPA 9</span>
                        <h2>Plano 30/60/90 Dias</h2>
                        <div class="highlight-box">
                            <strong>30 DIAS:</strong> Fechar 5 parceiros e lançar Beta em Guarulhos.<br>
                            <strong>60 DIAS:</strong> Bater 200 assinantes e adesivagem de baús.<br>
                            <strong>90 DIAS:</strong> Bater 500 assinantes e avaliar expansão para SP.
                        </div>
                    </div>

                    <div class="tab-pane fade" id="content10">
                        <span class="etapa-badge">ETAPA 10</span>
                        <h2>Pitch Final</h2>
                        <p class="fs-5 italic">"Sou entregador em Guarulhos. Criei o GPS do Motoca para a gente parar de rodar no escuro. É a união da categoria em forma de tecnologia. Custa menos que um cafezinho e se paga na primeira entrega que você não perde. Vamos dominar o trecho?"</p>
                    </div>

                </div>
            </div>
        </div>
    </main>

    <footer>
        <p>GPS do Motoca &copy; 2026 | Guarulhos/SP - Estratégia de Alto Impacto</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
