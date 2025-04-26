<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javed - Backend Engineer</title>
    <style>
        :root {
            --primary-color: #0a77b6;
            --secondary-color: #f8f9fa;
            --dark-color: #121212;
            --light-color: #ffffff;
            --accent-color: #ff7e33;
            --text-color: #333333;
            --border-radius: 8px;
            --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--dark-color);
            color: var(--light-color);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            text-align: left;
            margin-bottom: 3rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            padding-bottom: 2rem;
        }
        
        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            color: var(--light-color);
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        header p {
            font-size: 1.5rem;
            color: var(--accent-color);
            font-weight: 500;
        }
        
        section {
            margin-bottom: 4rem;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 10px;
            position: relative;
            overflow: hidden;
        }
        
        h2::after {
            content: '';
            flex-grow: 1;
            height: 1px;
            background-color: rgba(255, 255, 255, 0.1);
            margin-left: 15px;
        }
        
        .skills-container {
            margin-top: 1.5rem;
        }
        
        .skill-category {
            margin-bottom: 2rem;
        }
        
        .skill-category h3 {
            margin-bottom: 1rem;
            font-size: 1.3rem;
            color: var(--accent-color);
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            gap: 1.5rem;
        }
        
        .skill-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: var(--border-radius);
            padding: 1rem;
            transition: var(--transition);
        }
        
        .skill-item:hover {
            transform: translateY(-5px);
            background-color: rgba(255, 255, 255, 0.1);
            box-shadow: var(--box-shadow);
        }
        
        .skill-item img {
            width: 42px;
            height: 42px;
            margin-bottom: 0.5rem;
        }
        
        .skill-item span {
            font-size: 0.85rem;
        }
        
        .contact-links {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
        }
        
        .contact-link {
            display: inline-flex;
            align-items: center;
            background-color: var(--primary-color);
            color: white;
            text-decoration: none;
            padding: 0.7rem 1.2rem;
            border-radius: var(--border-radius);
            font-weight: 500;
            transition: var(--transition);
        }
        
        .contact-link:hover {
            background-color: #0d5c8f;
            transform: translateY(-2px);
        }
        
        .contact-link img {
            margin-right: 8px;
            width: 20px;
        }
        
        .leetcode-stats {
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: var(--border-radius);
            padding: 1.5rem;
            margin-top: 2rem;
        }
        
        .leetcode-stats h3 {
            margin-bottom: 1rem;
            font-size: 1.3rem;
            color: var(--accent-color);
        }
        
        .leetcode-stats img {
            max-width: 100%;
            border-radius: var(--border-radius);
        }
        
        @media (max-width: 768px) {
            .skills-grid {
                grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
                gap: 1rem;
            }
            
            header h1 {
                font-size: 2.5rem;
            }
            
            .container {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi <span>👋</span>, I'm Javed.</h1>
            <p>Backend Engineer</p>
        </header>
        
        <section>
            <h2><span>🚀</span> Languages and Tools I Use</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Programming Languages</h3>
                    <div class="skills-grid">
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" />
                            <span>JavaScript</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" />
                            <span>TypeScript</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" />
                            <span>Python</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" />
                            <span>C++</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" />
                            <span>C</span>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Frontend Technologies</h3>
                    <div class="skills-grid">
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" />
                            <span>HTML5</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" />
                            <span>CSS3</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" />
                            <span>React</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" />
                            <span>Tailwind</span>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Backend & Database</h3>
                    <div class="skills-grid">
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" />
                            <span>Node.js</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" />
                            <span>Express</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" />
                            <span>MongoDB</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" />
                            <span>MySQL</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" />
                            <span>PostgreSQL</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" />
                            <span>SQLite</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" />
                            <span>MS SQL</span>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Tools & Technologies</h3>
                    <div class="skills-grid">
                        <div class="skill-item">
                            <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" />
                            <span>Git</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" />
                            <span>Jest</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" />
                            <span>Postman</span>
                        </div>
                        <div class="skill-item">
                            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" />
                            <span>Linux</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section>
            <h2><span>⚡️</span> Where to find me</h2>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/mohammad-javed-a9a8aab4" target="_blank" class="contact-link">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white" style="margin-right: 8px;">
                        <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/>
                    </svg>
                    LinkedIn
                </a>
            </div>
            
            <div class="leetcode-stats">
                <h3>LeetCode Progress</h3>
                <img src="https://leetcard.jacoblin.cool/mohdjaved291?theme=dark&font=Alegreya&ext=heatmap" alt="LeetCode Stats" />
            </div>
        </section>
    </div>
</body>
</html>
