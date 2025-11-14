<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOHAMMED LAQSOUMI - Developer Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #0d1117;
            color: #c9d1d9;
            font-family: 'Courier New', monospace;
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 2px solid #30363d;
            margin-bottom: 40px;
        }

        .header h1 {
            color: #58a6ff;
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(88, 166, 255, 0.5);
        }

        .header h1::before {
            content: '< ';
            color: #79c0ff;
        }

        .header h1::after {
            content: ' />';
            color: #79c0ff;
        }

        .header h2 {
            color: #8b949e;
            font-size: 1.2em;
            font-weight: normal;
        }

        .profile-views {
            margin-top: 20px;
        }

        .section {
            margin-bottom: 50px;
            padding: 30px;
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
        }

        .section-title {
            color: #58a6ff;
            font-size: 1.8em;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #21262d;
        }

        .section-title::before {
            content: '// ';
            color: #8b949e;
        }

        .about-text {
            color: #c9d1d9;
            margin-bottom: 15px;
            padding-left: 20px;
        }

        .about-text::before {
            content: '→ ';
            color: #58a6ff;
            margin-left: -20px;
        }

        .tech-category {
            margin-bottom: 30px;
        }

        .tech-category h3 {
            color: #79c0ff;
            font-size: 1.3em;
            margin-bottom: 15px;
        }

        .tech-category h3::before {
            content: 'function ';
            color: #ff7b72;
        }

        .tech-category h3::after {
            content: '() { }';
            color: #8b949e;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));
            gap: 20px;
            padding: 20px;
            background: #fff;
            border-radius: 6px;
        }

        .tech-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 10px;
            transition: transform 0.3s;
        }

        .tech-item:hover {
            transform: translateY(-5px);
        }

        .tech-item img {
            width: 50px;
            height: 50px;
            margin-bottom: 8px;
            filter: grayscale(30%);
            transition: filter 0.3s;
        }

        .tech-item:hover img {
            filter: grayscale(0%);
        }

        .tech-item span {
            font-size: 0.8em;
            color: #8b949e;
            text-align: center;
        }

        .skills-list {
            padding: 15px;
            background: #fff;
            border-radius: 6px;
            color: #79c0ff;
        }

        .connect-links {
            display: flex;
            gap: 20px;
            padding: 20px;
            background: #fff;
            border-radius: 6px;
        }

        .connect-links a {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 10px 20px;
            background: #21262d;
            color: #58a6ff;
            text-decoration: none;
            border-radius: 6px;
            border: 1px solid #30363d;
            transition: all 0.3s;
        }

        .connect-links a:hover {
            background: #30363d;
            border-color: #58a6ff;
            transform: translateY(-2px);
        }

        .trophy-section {
            text-align: center;
        }

        .code-block {
            background: #fff;
            padding: 20px;
            border-radius: 6px;
            border-left: 3px solid #58a6ff;
            margin: 20px 0;
        }

        .code-line {
            color: #c9d1d9;
            margin: 5px 0;
        }

        .code-line .keyword {
            color: #ff7b72;
        }

        .code-line .string {
            color: #a5d6ff;
        }

        .code-line .comment {
            color: #8b949e;
        }

        @media (max-width: 768px) {
            .tech-grid {
                grid-template-columns: repeat(auto-fit, minmax(50px, 1fr));
                gap: 15px;
            }

            .header h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>MOHAMMED LAQSOUMI</h1>
            <h2>Full Stack JavaScript & PHP Developer | Building Web, Mobile & Desktop Apps</h2>
            <div class="profile-views">
                <img src="https://komarev.com/ghpvc/?username=medlaq777&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views">
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">Connect</h2>
            <div class="connect-links">
                <a href="https://linkedin.com/in/mohammed-laqsoumi" target="_blank">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" width="30" height="30" alt="LinkedIn">
                    <span>LinkedIn</span>
                </a>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">About Me</h2>
            <div class="code-block">
                <div class="code-line"><span class="keyword">const</span> developer = {</div>
                <div class="code-line">  passion: <span class="string">"Full Stack Development"</span>,</div>
                <div class="code-line">  specialization: [<span class="string">"Node.js"</span>, <span class="string">"React"</span>, <span class="string">"React Native"</span>, <span class="string">"Electron"</span>, <span class="string">"Laravel"</span>],</div>
                <div class="code-line">  focus: <span class="string">"Scalable, Secure & Clean Architecture"</span>,</div>
                <div class="code-line">  platforms: [<span class="string">"Web"</span>, <span class="string">"Mobile"</span>, <span class="string">"Desktop"</span>],</div>
                <div class="code-line">  believes: [<span class="string">"Clean Code"</span>, <span class="string">"UML Design"</span>, <span class="string">"Agile/Scrum"</span>]</div>
                <div class="code-line">};</div>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">Tech Stack</h2>

            <div class="tech-category">
                <h3>Backend Development</h3>
                <div class="tech-grid">
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js">
                        <span>Node.js</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express">
                        <span>Express</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP">
                        <span>PHP</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" alt="Laravel">
                        <span>Laravel</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" alt="WordPress">
                        <span>WordPress</span>
                    </div>
                </div>
            </div>

            <div class="tech-category">
                <h3>Frontend Development</h3>
                <div class="tech-grid">
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
                        <span>React</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/electron/electron-original.svg" alt="Electron">
                        <span>Electron</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
                        <span>JavaScript</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
                        <span>HTML5</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
                        <span>CSS3</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/refs/tags/v2.17.0/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind">
                        <span>Tailwind</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" alt="Figma">
                        <span>Figma</span>
                    </div>
                </div>
            </div>

            <div class="tech-category">
                <h3>Databases</h3>
                <div class="tech-grid">
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL">
                        <span>MySQL</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL">
                        <span>PostgreSQL</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB">
                        <span>MongoDB</span>
                    </div>
                </div>
            </div>

            <div class="tech-category">
                <h3>APIs & Architecture</h3>
                <div class="tech-grid">
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" alt="GraphQL">
                        <span>GraphQL</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" alt="Postman">
                        <span>Postman</span>
                    </div>
                </div>
                <div class="skills-list">
                    REST API • GraphQL • MVC • Clean Architecture • UML (ERD, Use Case, Class Diagrams)
                </div>
            </div>

            <div class="tech-category">
                <h3>Cloud & DevOps</h3>
                <div class="tech-grid">
                    <div class="tech-item">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/refs/tags/v2.17.0/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS">
                        <span>AWS</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" alt="Azure">
                        <span>Azure</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" alt="GCP">
                        <span>GCP</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker">
                        <span>Docker</span>
                    </div>
                </div>
            </div>

            <div class="tech-category">
                <h3>Tools & Workflow</h3>
                <div class="tech-grid">
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git">
                        <span>Git</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub">
                        <span>GitHub</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg" alt="Jira">
                        <span>Jira</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/notion/notion-original.svg" alt="Notion">
                        <span>Notion</span>
                    </div>
                    <div class="tech-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux">
                        <span>Linux</span>
                    </div>
                </div>
                <div class="skills-list">
                    Agile • Scrum • Git Flow • CI/CD
                </div>
            </div>
        </div>

        <div class="section trophy-section">
            <h2 class="section-title">GitHub Trophies</h2>
            <img src="https://github-profile-trophy.vercel.app/?username=medlaq777&theme=monokai" alt="GitHub Trophies">
        </div>
    </div>
</body>
</html>
