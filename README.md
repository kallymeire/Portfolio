<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kallymeire Coelho | Desenvolvedora & Analista de Dados</title>
    <!-- Tailwind CSS para design moderno e responsivo -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- FontAwesome para ícones -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .glass { background: rgba(255, 255, 255, 0.05); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .card-hover:hover { transform: translateY(-5px); transition: all 0.3s ease; }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 antialiased selection:bg-cyan-500 selection:text-slate-950">

    <!-- HEADER / NAVBAR -->
    <header class="fixed top-0 left-0 w-full z-50 glass bg-slate-950/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
            <a href="#" class="text-lg font-bold bg-gradient-to-r from-cyan-400 to-indigo-500 bg-clip-text text-transparent">
                Kallymeire.dev
            </a>
            <nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-300">
                <a href="#sobre" class="hover:text-cyan-400 transition">Sobre</a>
                <a href="#habilidades" class="hover:text-cyan-400 transition">Habilidades</a>
                <a href="#projetos" class="hover:text-cyan-400 transition">Projetos</a>
                <a href="#contato" class="hover:text-cyan-400 transition">Contato</a>
            </nav>
            <a href="https://github.com/kallymeire" target="_blank" class="px-4 py-2 text-xs font-semibold uppercase tracking-wider bg-cyan-500 text-slate-950 rounded-full hover:bg-cyan-400 transition shadow-lg shadow-cyan-500/20">
                <i class="fab fa-github mr-1"></i> GitHub
            </a>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="min-h-screen flex items-center justify-center pt-20 px-6 relative overflow-hidden">
        <!-- Efeito de luz de fundo -->
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-cyan-500/10 rounded-full blur-3xl pointer-events-none"></div>
        <div class="absolute bottom-1/4 right-1/4 w-80 h-80 bg-indigo-500/10 rounded-full blur-3xl pointer-events-none"></div>

        <div class="max-w-3xl text-center z-10">
            <span class="inline-block px-3 py-1 mb-4 text-xs font-semibold tracking-wider text-cyan-400 bg-cyan-500/10 rounded-full border border-cyan-500/20">
                Engenharia de Software & Dados
            </span>
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight mb-6">
                Olá, sou <span class="bg-gradient-to-r from-cyan-400 via-indigo-400 to-purple-500 bg-clip-text text-transparent">Kallymeire Coelho</span>
            </h1>
            <p class="text-lg sm:text-xl text-slate-400 mb-8 leading-relaxed">
                Estudante de Engenharia de Software focada em automações inteligentes, engenharia de dados, integração de APIs e desenvolvimento de soluções escaláveis em Python, SQL e Java.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#projetos" class="px-6 py-3 font-semibold text-sm bg-cyan-500 text-slate-950 rounded-xl hover:bg-cyan-400 transition shadow-lg shadow-cyan-500/20">
                    Ver Projetos
                </a>
                <a href="https://www.linkedin.com/in/kallymeire-coelho-212746263/" target="_blank" class="px-6 py-3 font-semibold text-sm glass text-slate-200 rounded-xl hover:bg-slate-800 transition">
                    <i class="fab fa-linkedin text-cyan-400 mr-2"></i> LinkedIn
                </a>
            </div>
        </div>
    </section>

    <!-- SOBRE MIM -->
    <section id="sobre" class="py-20 px-6 max-w-5xl mx-auto">
        <div class="glass p-8 sm:p-12 rounded-3xl border border-slate-800">
            <h2 class="text-2xl font-bold mb-4 flex items-center text-cyan-400">
                <i class="fas fa-user-astronaut mr-3"></i> Sobre Mim
            </h2>
            <p class="text-slate-300 leading-relaxed text-base sm:text-lg">
                Com forte vivência em suporte avançado, infraestrutura e tratamento de dados, combino lógica rigorosa de backend com eficiência operacional. Atualmente concentro os meus estudos na criação de pipelines de dados em tempo real, automações com n8n e arquitetura de sistemas robustos. Focada em transformar problemas complexos em código limpo e funcional.
            </p>
        </div>
    </section>

    <!-- HABILIDADES -->
    <section id="habilidades" class="py-20 px-6 max-w-5xl mx-auto">
        <h2 class="text-2xl font-bold mb-10 text-center flex items-center justify-center text-cyan-400">
            <i class="fas fa-code mr-3"></i> Competências Técnicas
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- Card 1 -->
            <div class="glass p-6 rounded-2xl border border-slate-800 card-hover">
                <div class="text-cyan-400 text-2xl mb-4"><i class="fas fa-robot"></i></div>
                <h3 class="font-bold text-lg mb-2 text-slate-200">Automação & APIs</h3>
                <p class="text-sm text-slate-400">n8n, Webhooks, Integração de APIs RESTful, automação de fluxos e RPA.</p>
            </div>
            <!-- Card 2 -->
            <div class="glass p-6 rounded-2xl border border-slate-800 card-hover">
                <div class="text-indigo-400 text-2xl mb-4"><i class="fas fa-database"></i></div>
                <h3 class="font-bold text-lg mb-2 text-slate-200">Dados & Backend</h3>
                <p class="text-sm text-slate-400">Python, SQL/MySQL, Pandas, Streamlit, SQLAlchemy, C, Java e C#.</p>
            </div>
            <!-- Card 3 -->
            <div class="glass p-6 rounded-2xl border border-slate-800 card-hover">
                <div class="text-purple-400 text-2xl mb-4"><i class="fas fa-server"></i></div>
                <h3 class="font-bold text-lg mb-2 text-slate-200">DevOps & Ferramentas</h3>
                <p class="text-sm text-slate-400">Docker, Git, GitHub, AWS, Pipelines CI/CD e Linux.</p>
            </div>
        </div>
    </section>

    <!-- PROJETOS -->
    <section id="projetos" class="py-20 px-6 max-w-5xl mx-auto">
        <h2 class="text-2xl font-bold mb-10 text-center flex items-center justify-center text-cyan-400">
            <i class="fas fa-laptop-code mr-3"></i> Principais Projetos
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- Projeto 1 -->
            <div class="glass p-6 rounded-2xl border border-slate-800 card-hover flex flex-col justify-between">
                <div>
                    <h3 class="text-xl font-bold text-slate-100 mb-2">Dashboard de KPIs em Tempo Real</h3>
                    <p class="text-sm text-slate-400 mb-4">Pipeline automatizado em Python (Pandas) para ingestão e limpeza de APIs de vendas, integrado a painel interativo via Streamlit.</p>
                </div>
                <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-800">
                    <span class="px-2.5 py-1 text-xs bg-cyan-500/10 text-cyan-400 rounded-md">Python</span>
                    <span class="px-2.5 py-1 text-xs bg-cyan-500/10 text-cyan-400 rounded-md">Pandas</span>
                    <span class="px-2.5 py-1 text-xs bg-cyan-500/10 text-cyan-400 rounded-md">Streamlit</span>
                </div>
            </div>
            <!-- Projeto 2 -->
            <div class="glass p-6 rounded-2xl border border-slate-800 card-hover flex flex-col justify-between">
                <div>
                    <h3 class="text-xl font-bold text-slate-100 mb-2">Automação de Contratos e Documentos</h3>
                    <p class="text-sm text-slate-400 mb-4">Script em Python (python-docx, FPDF) para preenchimento dinâmico de templates e conversão automatizada disparada por webhooks.</p>
                </div>
                <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-800">
                    <span class="px-2.5 py-1 text-xs bg-indigo-500/10 text-indigo-400 rounded-md">Python</span>
                    <span class="px-2.5 py-1 text-xs bg-indigo-500/10 text-indigo-400 rounded-md">n8n</span>
                    <span class="px-2.5 py-1 text-xs bg-indigo-500/10 text-indigo-400 rounded-md">APIs</span>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTATO / FOOTER -->
    <footer id="contato" class="py-16 px-6 border-t border-slate-800 bg-slate-950 text-center">
        <h2 class="text-xl font-bold mb-4">Vamos Trabalhar Juntos?</h2>
        <p class="text-slate-400 text-sm mb-6">Estou aberta a oportunidades em Desenvolvimento de Software, Ciência e Engenharia de Dados.</p>
        <div class="flex justify-center space-x-6 text-xl mb-8">
            <a href="mailto:okallymeire@gmail.com" class="text-slate-400 hover:text-cyan-400 transition"><i class="fas fa-envelope"></i></a>
            <a href="https://www.linkedin.com/in/kallymeire-coelho-212746263/" target="_blank" class="text-slate-400 hover:text-cyan-400 transition"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/kallymeire" target="_blank" class="text-slate-400 hover:text-cyan-400 transition"><i class="fab fa-github"></i></a>
        </div>
        <p class="text-xs text-slate-600">© 2026 Kallymeire Coelho. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
