<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio Profissional | Geografia para TI</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
            --success: #2ecc71;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .profile-header {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 1rem;
        }
        
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background-color: var(--light);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: var(--primary);
            border: 4px solid white;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            font-weight: 300;
            margin-bottom: 1rem;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin: 1rem 0;
        }
        
        .badge {
            background-color: rgba(255, 255, 255, 0.2);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        section {
            padding: 3rem 0;
        }
        
        section:nth-child(even) {
            background-color: white;
        }
        
        h2 {
            text-align: center;
            margin-bottom: 2rem;
            color: var(--primary);
            position: relative;
        }
        
        h2::after {
            content: '';
            display: block;
            width: 50px;
            height: 3px;
            background-color: var(--secondary);
            margin: 10px auto;
        }
        
        .journey-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .journey-card {
            background: white;
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .journey-card:hover {
            transform: translateY(-5px);
        }
        
        .journey-card h3 {
            color: var(--secondary);
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .skill-category {
            background: white;
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .skill-category h3 {
            color: var(--secondary);
            margin-bottom: 1rem;
            text-align: center;
        }
        
        .skill-list {
            list-style: none;
        }
        
        .skill-list li {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .skill-list li:last-child {
            border-bottom: none;
        }
        
        .goals-container {
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .goals-list {
            list-style: none;
            text-align: left;
            margin-top: 2rem;
        }
        
        .goals-list li {
            padding: 15px;
            margin-bottom: 10px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .contact {
            text-align: center;
            padding: 3rem 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
        }
        
        .contact h2 {
            color: white;
        }
        
        .contact h2::after {
            background-color: white;
        }
        
        .btn {
            display: inline-block;
            background-color: white;
            color: var(--primary);
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 1rem;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .journey-container, .skills-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="profile-header">
                <div class="avatar">🌐</div>
                <h1>Professor & Desenvolvedor em Formação</h1>
                <p class="tagline">Unindo educação e tecnologia para criar soluções inovadoras</p>
                <div class="badges">
                    <span class="badge">Geografia</span>
                    <span class="badge">Análise de Sistemas</span>
                    <span class="badge">Python</span>
                    <span class="badge">Educação</span>
                    <span class="badge">Pesquisa</span>
                </div>
            </div>
        </div>
    </header>

    <section id="journey">
        <div class="container">
            <h2>Minha Jornada</h2>
            <div class="journey-container">
                <div class="journey-card">
                    <h3>🎓 Formação Acadêmica</h3>
                    <p><strong>Licenciatura em Geografia</strong> - IFPE</p>
                    <p><strong>Análise e Desenvolvimento de Sistemas</strong> - SENAC/PE (cursando)</p>
                    <p><strong>Formação complementar</strong> em programação - CTRL+Play (Python, lógica de programação, desenvolvimento web)</p>
                </div>
                
                <div class="journey-card">
                    <h3>🌍 Experiência Internacional</h3>
                    <p><strong>Intercâmbio no Chile</strong> - INACAP Valdivia</p>
                    <p>Estudos em Psicopedagogia e ministração de minicurso em espanhol sobre Processos Cognitivos</p>
                    <p>Pesquisador premiado em congressos nacionais e internacionais com ênfase em internacionalização da educação</p>
                </div>
                
                <div class="journey-card">
                    <h3>👨‍🏫 Trajetória em Educação</h3>
                    <p><strong>Professor de idiomas</strong> - Inglês e Espanhol (CNA)</p>
                    <p><strong>Coordenação pedagógica</strong> - KNN Idiomas</p>
                    <p><strong>Auxiliar de professor</strong> - Prefeitura de Vitória de Santo Antão</p>
                    <p>Vivência em práticas educacionais inclusivas</p>
                </div>
            </div>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <h2>Habilidades</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>🔹 Soft Skills</h3>
                    <ul class="skill-list">
                        <li>Didática e metodologias de ensino</li>
                        <li>Comunicação multicultural</li>
                        <li>Gestão de equipes</li>
                        <li>Pesquisa acadêmica</li>
                        <li>Adaptabilidade</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>🔹 Hard Skills</h3>
                    <ul class="skill-list">
                        <li>Python</li>
                        <li>SQL</li>
                        <li>Lógica de programação</li>
                        <li>Desenvolvimento Web</li>
                        <li>Inglês e Espanhol fluentes</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="goals">
        <div class="container">
            <h2>Objetivos e Direcionamento</h2>
            <div class="goals-container">
                <p>Unindo minha bagagem em educação com tecnologia para atuar em:</p>
                <ul class="goals-list">
                    <li>✔ Desenvolvimento de software ou soluções educacionais (EdTech)</li>
                    <li>✔ Análise de dados aplicada à educação</li>
                    <li>✔ Gestão de projetos tecnológicos com viés pedagógico</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="contact">
        <div class="container">
            <h2>Vamos Conversar?</h2>
            <p>Aberto a oportunidades em TI, colaborações em projetos ou trocas sobre tecnologia e educação!</p>
            <a href="mailto:seuemail@exemplo.com" class="btn">Entrar em Contato</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 - Portfólio Profissional | Desenvolvido com HTML e CSS</p>
        </div>
    </footer>
</body>
</html>
