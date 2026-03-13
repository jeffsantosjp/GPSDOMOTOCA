# GPSDOMOTOCA
O GPS do Motoca é uma plataforma de inteligência coletiva para entregadores de última milha em Guarulhos. O app usa um mapa de calor atualizado pela comunidade a cada 20 minutos para mostrar onde há mais pedidos, reduzindo ociosidade e aumentando ganhos. A receita vem de assinaturas acessíveis e publicidade de parceiros locais.
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPS do Motoca - Plano de Negócios</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Oswald:wght@500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f4f7f6;
            color: #333;
        }
        .header-section {
            background: linear-gradient(135deg, #ffcc00 0%, #ff9900 100%);
            color: #000;
            padding: 60px 0;
            border-bottom: 5px solid #333;
        }
        .header-title {
            font-family: 'Oswald', sans-serif;
            font-size: 3rem;
            text-transform: uppercase;
        }
        .card {
            border: none;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            margin-bottom: 20px;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card-header {
            background-color: #333;
            color: #fff;
            font-weight: bold;
            border-radius: 15px 15px 0 0 !important;
            padding: 15px;
        }
        .badge-price {
            background-color: #28a745;
            font-size: 1.2rem;
        }
        .sticky-panel {
            position: sticky;
            top: 20px;
        }
        .footer {
            background-color: #333;
            color: #fff;
            padding: 40px 0;
            margin-top: 50px;
        }
        .step-number {
            background-color: #ffcc00;
            color: #000;
            width: 30px;
            height: 30px;
            display: inline-block;
            border-radius: 50%;
            text-align: center;
            font-weight: bold;
            margin-right: 10px;
        }
        .pitch-box {
            background-color: #fff3cd;
            border-left: 5px solid #ffc107;
            padding: 20px;
            font-style: italic;
        }
    </style>
</head>
<body>

    <header class="header-section text-center">
        <div class="container">
            <h1 class="header-title">🛵 GPS do Motoca</h1>
            <p class="lead fw-bold">Ganhe mais, rode menos. O mapa da comunidade.</p>
            <span class="badge bg-dark">ESTRATÉGIA 2026 - GUARULHOS/SP</span>
        </div>
    </header>

    <div class="container mt-5">
        <div class="row">
            <div class="col-lg-8">
                
                <section id="resumo" class="mb-5">
                    <h2 class="mb-4">📄 A) Resumo Executivo</h2>
                    <div class="card p-4">
                        <p class="lead">
                            O <strong>GPS do Motoca</strong> é o primeiro sistema de inteligência coletiva focado exclusivamente na produtividade do entregador. Unimos a necessidade de faturamento com uma rede de descontos local, transformando o "tempo morto" em economia e lucro real para o profissional de duas rodas. 🚀
                        </p>
                    </div>
                </section>

                <section id="etapas">
                    <h2 class="mb-4">🛤️ Roteiro Estratégico</h2>
                    
                    <div class="card">
                        <div class="card-header">🏷️ ETAPAS 1-3: O Coração do Negócio</div>
                        <div class="card-body">
                            <p><strong>💡 Ideia:</strong> Foco no profissional 12h/dia. Substituímos a intuição pela informação real. O app funciona onde o WhatsApp falha.</p>
                            <p><strong>📍 Mercado:</strong> Marco Zero em Guarulhos (Shopping Maia e Internacional). Nicho exclusivo para duas rodas.</p>
                            <p><strong>🗣️ Voz:</strong> "Papo de visão" - informal, direto e focado em combater a solidão do trecho.</p>
                        </div>
                    </div>

                    <div class="card">
                        <div class="card-header">📱 ETAPAS 4-5: Produto e Dinheiro</div>
                        <div class="card-body">
                            <ul>
                                <li><strong>MVP:</strong> Mapa de calor + Clique longo para reportar + Dados de 20 min.</li>
                                <li><strong>Segurança:</strong> Cadastro via CPF para banir "trolls".</li>
                                <li><strong>B2B:</strong> Pins patrocinados para oficinas e postos (R$ 50 - R$ 100/mês).</li>
                            </ul>
                        </div>
                    </div>

                    <div class="card">
                        <div class="card-header">🚀 ETAPAS 6-9: Operação e Crescimento</div>
                        <div class="card-body">
                            <p><strong>🏁 Go-To-Market:</strong> Abordagem em shoppings com brindes (capa de chuva p/ celular).</p>
                            <p><strong>🛠️ Operação:</strong> Suporte via WhatsApp e regra de "Dupla Confirmação" para alertas.</p>
                            <p><strong>📊 Finanças:</strong> Meta de 500 assinantes. Faturamento est. de <strong>R$ 7.450,00/mês</strong>.</p>
                        </div>
                    </div>
                </section>

                <section id="pitch" class="mt-5">
                    <h2 class="mb-4">🎤 N) Roteiro de Pitch (2 Minutos)</h2>
                    <div class="pitch-box shadow-sm">
                        "Você já sentiu que o iFood te esqueceu na calçada? Enquanto você espera 1h, a gasolina e o tempo vão embora. O GPS do Motoca é a união da categoria: a gente mostra onde o pedido tá saindo, onde tem blitz e onde a marmita é barata. Custa menos que um café por semana e se paga na primeira entrega que você não perderia. Sou entregador, conheço o trecho e vim pra mudar o jogo em Guarulhos. Vamos rodar juntos?" 🤜🤛
                    </div>
                </section>
            </div>

            <div class="col-lg-4">
                <div class="sticky-panel">
                    
                    <div class="card bg-dark text-white">
                        <div class="card-header border-light">📊 PAINEL DO PROJETO</div>
                        <div class="card-body">
                            <p><strong>👤 Público:</strong> Entregadores Full-time</p>
                            <p><strong>🎯 Foco:</strong> Guarulhos-Centro</p>
                            <p><strong>💰 Receita:</strong> Assinaturas + B2B</p>
                            <hr>
                            <p><strong>I) PRECIFICAÇÃO:</strong></p>
                            <ul class="list-unstyled">
                                <li>🗓️ Semanal: <span class="badge badge-price">R$ 4,90</span></li>
                                <li>📅 Quinzenal: <span class="badge badge-price">R$ 10,90</span></li>
                                <li>📆 Mensal: <span class="badge badge-price">R$ 14,90</span></li>
                            </ul>
                        </div>
                    </div>

                    <div class="card">
                        <div class="card-header">👤 C) Persona: Jorge</div>
                        <div class="card-body">
                            <p class="small text-muted">28 anos, motoboy em Guarulhos. Quer sustentar a família sem rodar no escuro.</p>
                            <strong>Job To Be Done:</strong>
                            <p class="small italic">"Preciso saber onde está tocando pedido agora para não gastar gasolina à toa."</p>
                        </div>
                    </div>

                    <div class="card">
                        <div class="card-header bg-danger">⚠️ L) Matriz de Riscos</div>
                        <div class="card-body p-2">
                            <table class="table table-sm mb-0">
                                <thead>
                                    <tr><th class="small">Risco</th><th class="small">Mitigação</th></tr>
                                </thead>
                                <tbody>
                                    <tr><td class="small">Baixa adesão</td><td class="small">Brindes úteis</td></tr>
                                    <tr><td class="small">Info Falsa</td><td class="small">Dupla Confirmação</td></tr>
                                </tbody>
                            </table>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>

    <footer class="footer text-center">
        <div class="container">
            <p>© 2026 GPS do Motoca - Plano de Negócios Profissional</p>
            <p class="small">Construído com foco em lucro, comunidade e agilidade. 🏁</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        console.log("GPS do Motoca - Sistema Pronto para o Trecho.");
        // Scripts futuros de interação podem entrar aqui
    </script>
</body>
</html>
