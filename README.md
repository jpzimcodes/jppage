<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Student - Halloween Edition | Portfólio de IA & Machine Learning</title>
    <!-- SEO Meta Tags -->
    <meta name="description" content="Desvende os mistérios da IA com um estudante apaixonado. Portfólio de Machine Learning e Deep Learning com projetos e habilidades.">
    <meta name="keywords" content="Estudante IA, Machine Learning Iniciante, Portfólio Python, Deep Learning, Halloween Tech">

    <!-- Load Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Load Google Fonts: Creepster for titles, Inter for body -->
    <link href="https://fonts.googleapis.com/css2?family=Creepster&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        /* Define custom Tailwind configuration */
        :root {
            --color-primary-orange: #FF6600;
            --color-secondary-purple: #4B0082;
            --color-spooky-green: #00FF00;
            --color-black-subtle: #0a0a0a;
        }

        .bg-black-subtle { background-color: var(--color-black-subtle); }
        .text-primary-orange { color: var(--color-primary-orange); }
        .text-spooky-green { color: var(--color-spooky-green); }
        .border-secondary-purple { border-color: var(--color-secondary-purple); }
        .shadow-spooky-green { box-shadow: 0 0 15px var(--color-spooky-green); }
        .font-creepster { font-family: 'Creepster', cursive; }
        .font-inter { font-family: 'Inter', sans-serif; }

        /* Custom glow effect for CTAs */
        .cta-glow {
            box-shadow: 0 0 10px var(--color-primary-orange), 0 0 20px rgba(255, 102, 0, 0.5);
            transition: all 0.3s ease;
        }
        .cta-glow:hover {
            box-shadow: 0 0 15px var(--color-spooky-green), 0 0 30px rgba(0, 255, 0, 0.7);
        }

        /* Custom spider web divider (SVG background/mask) */
        .spider-divider {
            height: 20px;
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 20'%3E%3Cpath fill='none' stroke='%234B0082' stroke-width='1' d='M0 10 Q 25 0, 50 10 T 100 10'/%3E%3Ccircle cx='50' cy='10' r='2' fill='%23FF6600'/%3E%3C/svg%3E");
            background-repeat: repeat-x;
            background-size: 50px 20px;
            opacity: 0.7;
        }

        /* Simple animated code background for the hero section */
        #hero-visual {
            position: relative;
            overflow: hidden;
            min-height: 250px;
            border-radius: 0.75rem;
        }
        #hero-visual::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><text x="0" y="10" font-size="10" fill="%2300FF00" opacity="0.1">01010101</text><text x="50" y="30" font-size="10" fill="%234B0082" opacity="0.1">11011100</text><text x="25" y="70" font-size="10" fill="%23FF6600" opacity="0.1">00110011</text></svg>');
            background-size: 100px 100px;
            animation: matrix-scroll 30s linear infinite;
        }
        @keyframes matrix-scroll {
            from { background-position: 0 0; }
            to { background-position: 100px 100px; }
        }

        /* Avatar/Silhueta Placeholder */
        .avatar-sil {
            background-color: var(--color-secondary-purple);
            border: 3px solid var(--color-spooky-green);
            box-shadow: 0 0 10px var(--color-spooky-green);
        }

        /* Custom Cursor Style - JS required, but demonstrating concept via CSS */
        body { cursor: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 24 24'><path fill='%23FF6600' d='M20.25 15.65l-2.43 2.43-1.63-1.63L14.7 18.2l-1.32-1.32-1.63 1.63-2.43-2.43v5.35H24v-5.35zM.05 15.65v5.35h9.72v-5.35l-2.43 2.43-1.63-1.63L4.7 18.2l-1.32-1.32-1.63 1.63L.05 15.65z'/></svg>") 10 10, pointer; }

    </style>
</head>
<body class="bg-black-subtle text-gray-200 font-inter min-h-screen">
    <main class="max-w-4xl mx-auto px-4 py-8">

        <!-- 1. 👻 Hero Section (A Dobra) -->
        <section id="hero" class="mb-20 pt-8 sm:pt-16">
            <div id="hero-visual" class="p-8 rounded-xl relative">
                <!-- Visual: Avatar Placeholder/Silhueta -->
                <div class="flex flex-col md:flex-row items-center justify-between z-10 relative">
                    <div class="md:w-3/5 text-center md:text-left mb-8 md:mb-0">
                        <h1 class="font-creepster text-5xl sm:text-7xl leading-tight mb-4 text-primary-orange shadow-sm">
                            A Magia da Machine Learning
                        </h1>
                        <p class="text-xl sm:text-2xl mb-6 text-gray-300">
                            Estudante de Engenharia de IA | Transformando Dados em <span class="text-spooky-green">'Feitiços' Poderosos</span>
                        </p>

                        <!-- CTA Principal -->
                        <a href="#footer" class="inline-block px-8 py-3 bg-primary-orange text-black text-xl font-bold rounded-full cta-glow border border-secondary-purple hover:text-white transition duration-300">
                            <!-- Ícone de Morcego (Emoji) -->
                            &#x1F987; Convide-me para a Sua Próxima Missão (Colaboração/Estágio)
                        </a>
                    </div>

                    <!-- Mock Visual/Avatar -->
                    <div class="md:w-2/5 flex justify-center">
                        <div class="w-48 h-48 sm:w-64 sm:h-64 rounded-full avatar-sil flex items-center justify-center text-5xl text-spooky-green font-creepster" aria-label="Avatar misterioso de estudante de IA">
                            AI
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Divisor de Seção Estilizado -->
        <div class="spider-divider mb-16"></div>

        <!-- 2. 🎃 Sobre Mim (A Origem do Aprendiz) -->
        <section id="sobre-mim" class="mb-20">
            <h2 class="font-creepster text-4xl mb-8 text-center text-primary-orange">
                A Lenda Começa: Por que IA?
            </h2>

            <div class="bg-black p-6 sm:p-8 rounded-xl shadow-lg border border-secondary-purple shadow-spooky-green">
                <p class="text-lg mb-6 leading-relaxed font-inter">
                    Desde criança, fui fascinado por desvendar mistérios e construir. A Inteligência Artificial me permite combinar essas paixões, transformando fluxos de dados complexos em soluções tangíveis para os desafios de amanhã. Na Universidade de <span class="text-spooky-green">[Nome da Universidade]</span>, estou imerso em <span class="text-spooky-green">Visão Computacional e NLP</span>, buscando 'engeyar' máquinas para auxiliar a sociedade.
                </p>

                <!-- Boas Práticas: Bullet Points -->
                <ul class="space-y-3 text-lg text-gray-300 ml-4 list-none">
                    <li class="flex items-center">
                        <span class="text-primary-orange mr-3 text-xl">&#x1F50E;</span> Curiosidade Infinita (Adoro investigar dados)
                    </li>
                    <li class="flex items-center">
                        <span class="text-primary-orange mr-3 text-xl">&#x1F40D;</span> Amor por Python/R (Minhas linguagens de feitiço favoritas)
                    </li>
                    <li class="flex items-center">
                        <span class="text-primary-orange mr-3 text-xl">&#x1F4A1;</span> Foco em Solução de Problemas (Transformando enigmas em código)
                    </li>
                </ul>
            </div>
        </section>

        <!-- Divisor de Seção Estilizado -->
        <div class="spider-divider mb-16 rotate-180"></div>

        <!-- 3. 🧪 Habilidades (O Arsenal do "Alquimista") -->
        <section id="habilidades" class="mb-20">
            <h2 class="font-creepster text-4xl mb-12 text-center text-primary-orange">
                O Laboratório Secreto: Habilidades Técnicas
            </h2>

            <!-- Grid Responsivo de Cards de Habilidades -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">

                <!-- Card 1: Linguagens -->
                <div class="p-5 bg-black rounded-xl border border-primary-orange hover:shadow-spooky-green transition duration-500">
                    <span class="text-5xl mb-2 block text-center text-spooky-green">&#x1F40D;</span>
                    <h3 class="font-bold text-xl mb-3 text-primary-orange text-center">Linguagens</h3>
                    <p class="text-center font-inter">Python, R, SQL, Bash</p>
                </div>

                <!-- Card 2: Frameworks/Bibliotecas -->
                <div class="p-5 bg-black rounded-xl border border-secondary-purple hover:shadow-spooky-green transition duration-500">
                    <span class="text-5xl mb-2 block text-center text-primary-orange">&#x1F9E0;</span>
                    <h3 class="font-bold text-xl mb-3 text-primary-orange text-center">Frameworks</h3>
                    <p class="text-center font-inter">TensorFlow, PyTorch, Scikit-learn, Pandas, NumPy</p>
                </div>

                <!-- Card 3: Conceitos -->
                <div class="p-5 bg-black rounded-xl border border-primary-orange hover:shadow-spooky-green transition duration-500">
                    <span class="text-5xl mb-2 block text-center text-spooky-green">&#x1F30C;</span>
                    <h3 class="font-bold text-xl mb-3 text-primary-orange text-center">Conceitos</h3>
                    <p class="text-center font-inter">Deep Learning, NLP, Data Mining, Estatística, MLOps Básico</p>
                </div>

                <!-- Card 4: Ferramentas -->
                <div class="p-5 bg-black rounded-xl border border-secondary-purple hover:shadow-spooky-green transition duration-500">
                    <span class="text-5xl mb-2 block text-center text-primary-orange">&#x1F4BB;</span>
                    <h3 class="font-bold text-xl mb-3 text-primary-orange text-center">Ferramentas</h3>
                    <p class="text-center font-inter">Jupyter Notebook, VS Code, Git/GitHub, Docker</p>
                </div>
            </div>
        </section>

        <!-- Divisor de Seção Estilizado -->
        <div class="spider-divider mb-16"></div>

        <!-- 4. 📚 Projetos (Os "Feitiços" Testados) -->
        <section id="projetos" class="mb-20">
            <h2 class="font-creepster text-4xl mb-12 text-center text-primary-orange">
                Os Tomos Antigos: Projetos Recentes
            </h2>

            <!-- Grid de Cards de Projetos (Mínimo 3) -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

                <!-- Projeto 1 -->
                <div class="p-6 bg-black rounded-xl border-2 border-spooky-green shadow-spooky-green hover:scale-[1.02] transition duration-500">
                    <h3 class="text-2xl font-bold mb-3 text-spooky-green">Detector de Fantasmas Digitais</h3>
                    <p class="text-sm font-light text-gray-400 mb-4">Modelo CNN para Visão Computacional</p>
                    <p class="mb-4 text-gray-300">
                        Modelo de Visão Computacional treinado para identificar entidades fantasmagóricas (objetos anômalos) em imagens com alta precisão. Foco em otimização de inferência.
                    </p>
                    <p class="text-sm font-bold text-primary-orange mb-6">Tecnologias: Python, TensorFlow, CNNs, NumPy</p>
                    <a href="#" class="block w-full text-center px-4 py-2 mb-3 bg-primary-orange text-black font-bold rounded-lg hover:bg-spooky-green hover:text-black transition duration-300">
                        Ver Código no GitHub
                    </a>
                </div>

                <!-- Projeto 2 -->
                <div class="p-6 bg-black rounded-xl border-2 border-primary-orange shadow-lg hover:scale-[1.02] transition duration-500">
                    <h3 class="text-2xl font-bold mb-3 text-primary-orange">Elixir de Linguagem NLP</h3>
                    <p class="text-sm font-light text-gray-400 mb-4">Análise de Sentimento com Spacy e NLTK</p>
                    <p class="mb-4 text-gray-300">
                        Assistente que utiliza técnicas de NLP para analisar o 'sentimento' em textos e gerar 'poções' de resumo criativas. Demonstração interativa.
                    </p>
                    <p class="text-sm font-bold text-spooky-green mb-6">Tecnologias: Python, NLTK, spaCy, Streamlit (Demo)</p>
                    <a href="#" class="block w-full text-center px-4 py-2 mb-3 bg-spooky-green text-black font-bold rounded-lg hover:bg-primary-orange transition duration-300">
                        Ver Código no GitHub
                    </a>
                </div>

                <!-- Projeto 3 -->
                <div class="p-6 bg-black rounded-xl border-2 border-secondary-purple shadow-lg hover:scale-[1.02] transition duration-500">
                    <h3 class="text-2xl font-bold mb-3 text-secondary-purple">Oráculo de Dados Assombrado</h3>
                    <p class="text-sm font-light text-gray-400 mb-4">Dashboard Interativo de Anomalias</p>
                    <p class="mb-4 text-gray-300">
                        Dashboard interativo construído com R/Shiny que 'prevê' e visualiza padrões ocultos e anomalias (assombrações) em dados financeiros simulados.
                    </p>
                    <p class="text-sm font-bold text-primary-orange mb-6">Tecnologias: R, Shiny, SQL, Data Mining/Análise Exploratória</p>
                    <a href="#" class="block w-full text-center px-4 py-2 mb-3 bg-primary-orange text-black font-bold rounded-lg hover:bg-secondary-purple hover:text-white transition duration-300">
                        Ver Código no GitHub
                    </a>
                </div>
            </div>
        </section>

        <!-- Divisor de Seção Estilizado -->
        <div class="spider-divider mb-16 rotate-180"></div>

        <!-- 5. ⭐️ Testemunhos (As Profecias de Quem Viu o Futuro) -->
        <section id="testemunhos" class="mb-20">
            <h2 class="font-creepster text-4xl mb-12 text-center text-primary-orange">
                As Profecias de Quem Viu o Futuro
            </h2>

            <div class="flex flex-col items-center">
                <blockquote class="p-8 bg-black border-l-4 border-spooky-green rounded-r-xl max-w-2xl shadow-xl">
                    <p class="text-xl italic mb-6 text-gray-300">
                        <span class="text-6xl text-spooky-green mr-2 float-left leading-none">&ldquo;</span>
                        O conhecimento e a dedicação de [Nome do Estudante] à Inteligência Artificial são verdadeiramente notáveis. Sua abordagem criativa para resolver problemas complexos o destaca como um futuro líder na área.
                        <span class="text-6xl text-spooky-green ml-2 float-right leading-none">&rdquo;</span>
                    </p>
                    <footer class="text-right mt-4 pt-4 border-t border-secondary-purple">
                        <cite class="font-bold text-lg text-primary-orange not-italic">Dr. Alistir Crowley</cite>
                        <p class="text-sm text-gray-400">Mentor & Professor de IA na Universidade de Eldoria</p>
                    </footer>
                </blockquote>
            </div>
        </section>

    </main>

    <!-- 6. 📞 Rodapé (Contatos e Rastreio) -->
    <footer id="footer" class="bg-black border-t-2 border-secondary-purple p-8 text-center">
        <h2 class="font-creepster text-3xl mb-8 text-spooky-green">
            A Rede Secreta: Conecte-se
        </h2>

        <div class="flex justify-center space-x-8 mb-8">
            <!-- LinkedIn -->
            <a href="https://linkedin.com/in/seuperfil" target="_blank" class="text-gray-300 hover:text-primary-orange transition duration-300" aria-label="LinkedIn">
                <span class="text-5xl">&#x1F9DF;</span> <!-- Emoji de Mago/Feiticeiro para o LinkedIn -->
            </a>

            <!-- GitHub -->
            <a href="https://github.com/seuusuario" target="_blank" class="text-gray-300 hover:text-spooky-green transition duration-300" aria-label="GitHub">
                <span class="text-5xl">&#x1F987;</span> <!-- Emoji de Morcego para o GitHub -->
            </a>

            <!-- Email de Contato -->
            <a href="mailto:seu.email@exemplo.com" class="text-gray-300 hover:text-primary-orange transition duration-300" aria-label="Email de Contato">
                <span class="text-5xl">&#x1F4E7;</span> <!-- Emoji de Email para Contato -->
            </a>
        </div>

        <!-- Selo de Profissionalismo -->
        <p class="text-sm text-gray-500 mt-4 font-inter">
            <span class="text-spooky-green font-bold">Construído com Paixão</span> e <span class="text-primary-orange font-bold">Em Constante Aprendizado.</span>
        </p>
        <p class="text-xs text-gray-600 mt-2 font-inter">
            &copy; 2023 [Nome do Estudante]. Todos os 'Feitiços' Reservados.
        </p>
    </footer>

</body>
</html>
