<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zakaria El Hallaoui </title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Playfair+Display:ital,wght@1,700&display=swap'); 

        .code-container { 
            font-family: 'Inter', sans-serif;
            white-space: pre-wrap;
            min-height: 120px;
            overflow: hidden;
            background-color: #1e1e1e;
            border: 1px solid #333;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
            line-height: 1.5;
            padding: 1.5rem;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        
        body {
            background-color: #121212;
            color: #e0e0e0;
            font-family: 'Inter', sans-serif;
        }
        .section-separator {
            border-top: 1px solid #333;
            margin: 2rem 0;
        }

        .quote-container {
            font-family: 'Playfair Display', serif; 
            background-color: #1e1e1e;
            border: 1px solid #333;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
            padding: 2rem;
            text-align: center;
            position: relative;
            overflow: hidden; 
        }

        .quote-text {
            font-size: 1.75rem; 
            font-style: italic;
            color: #e0e0e0;
            margin-bottom: 1rem;
            opacity: 0; 
            animation: fade-in 1.5s forwards;
            animation-delay: 0.5s;
        }

        .quote-author {
            font-size: 1.25rem;
            font-weight: 600;
            color: #888;
            opacity: 0; 
            animation: fade-in 1.5s forwards;
            animation-delay: 1.5s;
        }

        .quote-author strong {
            color: #38bdf8; 
            position: relative;
            display: inline-block;
        }
        
        .quote-author strong::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background-color: #38bdf8;
            animation: expand-underline 1.5s forwards;
            animation-delay: 2s; 
        }

        @keyframes fade-in {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes expand-underline {
            from { width: 0; }
            to { width: 100%; }
        }

    </style>
</head>
<body class="p-4 md:p-8">
    <div class="max-w-4xl mx-auto">

        <div class="flex flex-col items-center text-center mb-6">
            <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Hi.gif" width="35" class="rounded-full" alt="Hi GIF" onerror="this.onerror=null;this.src='https://placehold.co/35x35/00b894/FFFFFF?text=%F0%9F%91%8B';" />
            <h1 class="text-4xl font-bold mt-2 text-white">Zakaria El Hallaoui</h1>
            <p class="text-xl text-blue-400">Full-Stack Web & AI Automation Engineer</p>

            <div class="flex space-x-6 mt-4 p-4 rounded-xl bg-gray-800 shadow-lg">
                <a href="https://www.linkedin.com/in/zakaria-el-hallaoui-50427b284/" target="_blank" class="hover:scale-110 transition-transform">
                    <img width="30px" alt="LinkedIn" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"/>
                </a>
                <a href="https://github.com/zack-elh" target="_blank" class="hover:scale-110 transition-transform">
                    <img width="30px" alt="GitHub" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/>
                </a>
                <a href="mailto:zakariaelhallaoui2002@gmail.com" target="_blank" class="hover:scale-110 transition-transform">
                    <img width="30px" alt="Email" src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png"/>
                </a>
            </div>
        </div>

        <div class="section-separator"></div>

        <div class="mb-8">
            <h2 class="text-3xl font-semibold mb-4 text-white">👋 About Me</h2>
            <p class="mb-4 text-gray-300">
                Hey there! I’m <strong class="text-orange-500">Zakaria El Hallaoui</strong>, a passionate <strong class="text-orange-500">Full-Stack Web & AI Automation Engineer</strong>.
                I love combining <strong class="text-cyan-400">AI</strong>, <strong class="text-cyan-400">web technologies</strong>, and <strong class="text-cyan-400">automation</strong> to build scalable systems that make life easier from intelligent backends to responsive frontends.
            </p>
            <h3 class="text-xl font-medium mt-6 mb-2 text-white">🚀 What I’m focused on:</h3>
            <ul class="list-disc list-inside space-y-1 text-gray-300 ml-4">
                <li>🤖 AI-driven web automation & assistants</li>
                <li>🌐 Full-stack development (C#, Python, Java, JavaScript)</li>
                <li>💾 Data pipelines with <strong class="text-blue-400">MySQL</strong></li>
                <li>🎨 Clean, animated UI/UX using HTML, CSS & JS</li>
                <li>🧠 Experimenting with machine learning integrations</li>
            </ul>
        </div>

        <div class="section-separator"></div>

        <div class="mb-8">
            <h2 class="text-3xl font-semibold mb-4 text-white">✨ Inspirational Code Insight</h2>
            <div class="quote-container rounded-lg">
                <p class="quote-text">
                    "Software is a great combination of artistry and engineering."
                </p>
                <p class="quote-author">
                    – <strong>Bill Gates</strong>
                </p>
            </div>
        </div>
        
        <div class="section-separator"></div>

        <div class="mb-8">
            <h2 class="text-3xl font-semibold mb-4 text-white">🧠 Tech Stack</h2>

            <h3 class="text-xl font-medium mt-6 mb-2 text-white">💻 Languages</h3>
            <div class="flex flex-wrap gap-2 items-center">
                <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white" class="rounded-md"/>
                <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" class="rounded-md"/>
                <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white" class="rounded-md"/>
                <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" class="rounded-md"/>
                <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" class="rounded-md"/>
                <img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white" class="rounded-md"/>
            </div>

            <h3 class="text-xl font-medium mt-6 mb-2 text-white">⚙️ Frameworks & Libraries</h3>
            <div class="flex flex-wrap gap-2">
                <img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white" class="rounded-md"/>
                <img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white" class="rounded-md"/>
                <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" class="rounded-md"/>
                <img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white" class="rounded-md"/>
            </div>
        </div>
    </div>
</body>
</html>
