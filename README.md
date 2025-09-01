<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salah Eddine Khazri - Développeur Full-Stack</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .container {
            background-color: #161b22;
            border-radius: 16px;
            padding: 30px;
            margin-bottom: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }
        
        header {
            text-align: center;
            padding: 30px 0;
        }
        
        h1 {
            color: #58a6ff;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        h2 {
            color: #f0f6fc;
            margin: 25px 0 15px 0;
            padding-bottom: 10px;
            border-bottom: 2px solid #30363d;
        }
        
        h3 {
            color: #58a6ff;
            margin: 20px 0 10px 0;
        }
        
        p {
            margin-bottom: 15px;
        }
        
        .profile-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin: 15px 0;
        }
        
        .info-item {
            display: flex;
            align-items: center;
            gap: 8px;
            background-color: #21262d;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .skill-item {
            background-color: #21262d;
            border-radius: 16px;
            padding: 15px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        
        .skill-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        
        .skill-icon {
            width: 50px;
            height: 50px;
            margin-bottom: 10px;
            object-fit: contain;
        }
        
        .skill-name {
            font-size: 0.85rem;
            font-weight: 500;
        }
        
        .project {
            background-color: #21262d;
            border-radius: 16px;
            padding: 20px;
            margin-bottom: 20px;
        }
        
        .project-header {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 15px;
        }
        
        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin: 10px 0;
        }
        
        .tech-badge {
            background-color: #30363d;
            padding: 4px 10px;
            border-radius: 12px;
            font-size: 0.8rem;
        }
        
        .contact-buttons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .contact-btn {
            display: flex;
            align-items: center;
            gap: 8px;
            background-color: #238636;
            color: white;
            text-decoration: none;
            padding: 12px 20px;
            border-radius: 8px;
            font-weight: 500;
            transition: background-color 0.3s ease;
        }
        
        .contact-btn:hover {
            background-color: #2ea043;
        }
        
        .language-badges {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        
        .language-badge {
            background-color: #21262d;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            color: #8b949e;
        }
        
        @media (max-width: 768px) {
            .skills-grid {
                grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
            }
            
            .skill-icon {
                width: 40px;
                height: 40px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 Bonjour, je suis Salah Eddine Khazri</h1>
            <p><strong>Développeur Web Full-Stack | Étudiant Ingénieur en Logiciels et Systèmes Intelligents</strong></p>
            
            
        </header>
    </div>

    <div class="container">
        <h2>🚀 À Propos de Moi</h2>
        <p>Étudiant passionné en cycle d'ingénieur, spécialisé en développement web et technologies émergentes. Je suis motivé, créatif et adaptable, toujours à la recherche de nouveaux défis techniques et opportunités d'apprentissage. Actuellement à la recherche d'un stage PFA pour les mois de juillet et août.</p>
    </div>

    <div class="container">
        <h2>💻 Stack Technique</h2>
        
        <h3>🛠️ Langages de Programmation</h3>
        <div class="skills-grid">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" class="skill-icon" alt="C">
                <span class="skill-name">C</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="skill-icon" alt="C++">
                <span class="skill-name">C++</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" class="skill-icon" alt="Java">
                <span class="skill-name">Java</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" class="skill-icon" alt="Python">
                <span class="skill-name">Python</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" class="skill-icon" alt="PHP">
                <span class="skill-name">PHP</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" class="skill-icon" alt="JavaScript">
                <span class="skill-name">JavaScript</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" class="skill-icon" alt="TypeScript">
                <span class="skill-name">TypeScript</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" class="skill-icon" alt="SQL">
                <span class="skill-name">SQL</span>
            </div>
        </div>

        <h3>🌐 Technologies Web</h3>
        <div class="skills-grid">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" class="skill-icon" alt="HTML5">
                <span class="skill-name">HTML5</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" class="skill-icon" alt="CSS3">
                <span class="skill-name">CSS3</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" class="skill-icon" alt="Bootstrap">
                <span class="skill-name">Bootstrap</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" class="skill-icon" alt="Tailwind CSS">
                <span class="skill-name">Tailwind</span>
            </div>
        </div>

        <h3>⚡ Frameworks & Bibliothèques</h3>
        <div class="skills-grid">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" class="skill-icon" alt="Angular">
                <span class="skill-name">Angular</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" class="skill-icon" alt="React">
                <span class="skill-name">React</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" class="skill-icon" alt="Django">
                <span class="skill-name">Django</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/symfony/symfony-original.svg" class="skill-icon" alt="Symfony">
                <span class="skill-name">Symfony</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-plain.svg" class="skill-icon" alt="Laravel">
                <span class="skill-name">Laravel</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" class="skill-icon" alt="Node.js">
                <span class="skill-name">Node.js</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" class="skill-icon" alt="Express.js">
                <span class="skill-name">Express.js</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" class="skill-icon" alt="Flask">
                <span class="skill-name">Flask</span>
            </div>
        </div>

        <h3>🗄️ Bases de Données</h3>
        <div class="skills-grid">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" class="skill-icon" alt="MySQL">
                <span class="skill-name">MySQL</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" class="skill-icon" alt="PostgreSQL">
                <span class="skill-name">PostgreSQL</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" class="skill-icon" alt="MongoDB">
                <span class="skill-name">MongoDB</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" class="skill-icon" alt="Redis">
                <span class="skill-name">Redis</span>
            </div>
        </div>

        <h3>🔧 Outils & Concepts</h3>
        <div class="skills-grid">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/shopify/shopify-original.svg" class="skill-icon" alt="Shopify">
                <span class="skill-name">Shopify</span>
            </div>
            <div class="skill-item">
                <img src="https://img.icons8.com/fluency/48/000000/design.png" class="skill-icon" alt="Design Patterns">
                <span class="skill-name">Design Patterns</span>
            </div>
            <div class="skill-item">
                <img src="https://img.icons8.com/color/48/000000/uml.png" class="skill-icon" alt="UML">
                <span class="skill-name">UML</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" class="skill-icon" alt="Git">
                <span class="skill-name">Git</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" class="skill-icon" alt="Docker">
                <span class="skill-name">Docker</span>
            </div>
        </div>
    </div>

   
    <div class="container">
        <h2>📫 Contactez-moi</h2>
        <div class="contact-buttons">
            <a href="mailto:salahkhazri917@gmail.com" class="contact-btn">
                📧 Email
            </a>
            <a href="https://www.linkedin.com/in/khazri-salah-eddine-b42070294/" class="contact-btn">
                💼 LinkedIn
            </a>
            <a href="tel:+212616120396" class="contact-btn">
                📞 Téléphone
            </a>
        </div>
    </div>

</body>
</html>
