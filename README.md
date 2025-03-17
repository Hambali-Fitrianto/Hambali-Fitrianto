<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hambali Fitrianto - Web Programmer</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700" rel="stylesheet">
    <style>
        /* Global Styles */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: #fff;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2, h3 {
            margin: 0;
        }

        h1 {
            font-size: 2.5rem;
            font-weight: 700;
        }

        h2 {
            font-size: 2rem;
            font-weight: 500;
            margin-bottom: 20px;
        }

        h3 {
            font-size: 1.5rem;
            font-weight: 400;
            color: #6c757d;
        }

        p {
            font-size: 1.1rem;
            margin: 10px 0;
        }

        .section {
            padding: 40px 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            margin: 20px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .section:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
        }

        .badge-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }

        .badge {
            display: inline-block;
            padding: 10px 20px;
            border-radius: 25px;
            background: rgba(255, 255, 255, 0.2);
            transition: background 0.3s ease, transform 0.3s ease;
        }

        .badge:hover {
            background: rgba(255, 255, 255, 0.4);
            transform: scale(1.1);
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .contact-links .badge {
            padding: 10px 20px;
        }

        .github-stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .github-stats img {
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .footer {
            text-align: center;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            margin-top: 40px;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }

            h2 {
                font-size: 1.5rem;
            }

            h3 {
                font-size: 1.2rem;
            }

            .badge {
                padding: 8px 16px;
                font-size: 0.9rem;
            }

            .contact-links {
                flex-direction: column;
                align-items: center;
            }

            .github-stats {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <!-- Header Section -->
        <div class="section" align="center">
            <h1>Halo, I am <strong>Hambali Fitrianto</strong> 👋</h1>
            <h3>🌟 Web Programmer | Developer 🌟</h3>
            <p>
                🚀 <em>I am passionate about creating responsive, modern and dynamic web applications.</em><br>
                💼 <em>My specialty is backend and frontend integration.</em><br>
                🎓 <em>Graduate of Informatics Engineering, Trunojoyo University Madura.</em>
            </p>
        </div>

        <!-- Skills Section -->
        <div class="section">
            <h2 align="center">🛠️ Technology & Tools Mastered</h2>
            <div class="badge-container">
                <span class="badge">PHP</span>
                <span class="badge">Laravel</span>
                <span class="badge">HTML</span>
                <span class="badge">CSS</span>
                <span class="badge">JavaScript</span>
                <span class="badge">JQuery</span>
                <span class="badge">MySQL</span>
                <span class="badge">PostgreSQL</span>
                <span class="badge">Git</span>
                <span class="badge">GitHub</span>
            </div>
        </div>

        <!-- Contact Section -->
        <div class="section">
            <h2 align="center">📬 Contact Me</h2>
            <div class="contact-links">
                <a href="mailto:hambali.fitrianto01@gmail.com" class="badge">Email</a>
                <a href="https://www.linkedin.com/in/hambali-fitrianto" class="badge">LinkedIn</a>
                <a href="https://github.com/Hambali-Fitrianto" class="badge">GitHub</a>
                <a href="https://www.instagram.com/capt_msf/" class="badge">Instagram</a>
                <a href="https://porto.hambalifitrianto.web.id/" class="badge">Portfolio</a>
            </div>
        </div>

        <!-- Portfolio Section -->
        <div class="section">
            <h2 align="center">🌐 Portfolio</h2>
            <p align="center">✨ Explore my projects and know more about my work!</p>
            <div align="center">
                <a href="https://porto.hambalifitrianto.web.id/" class="badge">Visit My Portfolio Website</a>
            </div>
        </div>

        <!-- GitHub Stats Section -->
        <div class="section">
            <h2 align="center">📊 GitHub Statistics</h2>
            <div class="github-stats">
                <img src="https://github-readme-stats.vercel.app/api?username=Hambali-Fitrianto&show_icons=true&theme=radical" alt="GitHub Stats">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hambali-Fitrianto&layout=compact&theme=radical" alt="Top Languages">
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p>© 2025 <strong>Hambali Fitrianto</strong>. All rights are protected.</p>
        </div>
    </div>
</body>

</html>
