# my-html-css-JS-projects
projects with html, css, JS projects
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ogunmodede Oluwaseyi - Resume</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --accent-color: #3498db;
            --text-color: #333;
            --background-color: #f8f9fa;
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
            background: var(--background-color);
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }

        .header {
            text-align: center;
            margin-bottom: 3rem;
            padding: 2rem;
            background: var(--primary-color);
            color: white;
            border-radius: 8px;
        }

        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .contact-info {
            font-size: 1.1rem;
        }

        .section {
            margin-bottom: 2.5rem;
        }

        .section-title {
            color: var(--accent-color);
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 0.5rem;
        }

        .entry {
            margin-bottom: 1.5rem;
        }

        .entry-title {
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .entry-subtitle {
            color: var(--accent-color);
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }

        .entry-date {
            color: #666;
            font-style: italic;
            margin-bottom: 0.5rem;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 1rem;
        }

        .skill-item {
            background: white;
            padding: 1rem;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }

            .header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>Ogunmodede Oluwaseyi</h1>
            <div class="contact-info">
                <p>Frontend Developer</p>
                <p>📱 Phone: 08131196504</p>
                <p>📧 Email: oluwaseyi564@gma.com</p>
                <p>🔗 LinkedIn: linkedin.com/in/seyiogunmodede</p>
                <p>💻 GitHub: github.com/seyidev</p>
                <p>📍 Lagos, Nigeria</p>
            </div>
        </header>

        <section class="section">
            <h2 class="section-title">Professional Summary</h2>
            <p>Detail-oriented Frontend Developer with 1.5 years of experience specializing in modern JavaScript frameworks and responsive web design. Passionate about creating intuitive user interfaces and optimizing web performance. Strong background in mathematics contributing to problem-solving abilities and analytical thinking.</p>
        </section>

        <section class="section">
            <h2 class="section-title">Education</h2>
            <div class="entry">
                <h3 class="entry-title">Bachelor of Science in Industrial Mathematics</h3>
                <div class="entry-subtitle">Federal University of Technology, Akure</div>
                <div class="entry-date">2015 - 2020</div>
                <ul>
                    <li>Relevant Coursework: Statistical Analysis, Mathematical Modeling, Numerical Computing</li>
                    <li>Applied mathematical concepts to solve complex problems and develop analytical thinking</li>
                </ul>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Work Experience</h2>
            <div class="entry">
                <h3 class="entry-title">Junior Frontend Developer</h3>
                <div class="entry-subtitle">EASYWIN</div>
                <div class="entry-date">August 2023 - December 2023</div>
                <ul>
                    <li>Developed responsive and accessible user interfaces using React.js and Tailwind CSS</li>
                    <li>Implemented modern frontend practices including component-based architecture and state management with Redux</li>
                    <li>Collaborated with UI/UX designers to transform Figma designs into pixel-perfect implementations</li>
                    <li>Improved website performance by 40% through code splitting and lazy loading techniques</li>
                </ul>
            </div>
            
            <div class="entry">
                <h3 class="entry-title">Frontend Developer</h3>
                <div class="entry-subtitle">MAKA</div>
                <div class="entry-date">June 2022 - February 2023</div>
                <ul>
                    <li>Built and maintained responsive web applications using Vue.js and SCSS</li>
                    <li>Implemented client-side form validation and API integration using Axios</li>
                    <li>Reduced page load times by 30% through image optimization and caching strategies</li>
                    <li>Collaborated with backend developers to integrate RESTful APIs and WebSocket connections</li>
                </ul>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-item">HTML5 & CSS3</div>
                <div class="skill-item">JavaScript (ES6+)</div>
                <div class="skill-item">React.js</div>
                <div class="skill-item">Vue.js</div>
                <div class="skill-item">TypeScript</div>
                <div class="skill-item">Tailwind CSS</div>
                <div class="skill-item">SCSS/SASS</div>
                <div class="skill-item">Redux/Vuex</div>
                <div class="skill-item">Jest & React Testing Library</div>
                <div class="skill-item">Webpack</div>
                <div class="skill-item">Git & GitHub</div>
                <div class="skill-item">Responsive Design</div>
                <div class="skill-item">Web Performance</div>
                <div class="skill-item">Figma</div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Projects</h2>
            <div class="entry">
                <h3 class="entry-title">Modern E-commerce Frontend</h3>
                <div class="entry-subtitle">Personal Project</div>
                <ul>
                    <li>Developed a modern e-commerce frontend using React.js, TypeScript, and Tailwind CSS</li>
                    <li>Implemented advanced features like infinite scroll, cart management, and wishlist functionality</li>
                    <li>Achieved 95+ Lighthouse score for performance and accessibility</li>
                </ul>
            </div>
            <div class="entry">
                <h3 class="entry-title">Weather Dashboard</h3>
                <div class="entry-subtitle">Collaborative Project</div>
                <ul>
                    <li>Built a weather dashboard using Vue.js and OpenWeatherMap API</li>
                    <li>Implemented geolocation features and interactive weather maps</li>
                    <li>Created reusable components for weather data visualization</li>
                </ul>
            </div>
            <div class="entry">
                <h3 class="entry-title">Portfolio Website</h3>
                <div class="entry-subtitle">Personal Project</div>
                <ul>
                    <li>Designed and developed a personal portfolio using React.js and Framer Motion</li>
                    <li>Implemented smooth animations and transitions for enhanced user experience</li>
                    <li>Optimized for cross-browser compatibility and mobile responsiveness</li>
                </ul>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Certifications</h2>
            <div class="entry">
                <h3 class="entry-title">Meta Frontend Developer Professional Certificate</h3>
                <div class="entry-date">2023</div>
            </div>
            <div class="entry">
                <h3 class="entry-title">JavaScript Algorithms and Data Structures - freeCodeCamp</h3>
                <div class="entry-date">2022</div>
            </div>
        </section>
    </div>
</body>
</html>
