<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>snowt - GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            position: relative;
        }

        .snowflake {
            position: absolute;
            top: -10px;
            color: #fff;
            font-size: 1em;
            opacity: 0.8;
            pointer-events: none;
            animation: fall linear infinite;
        }

        @keyframes fall {
            to {
                transform: translateY(100vh) rotate(360deg);
            }
        }

        .container {
            position: relative;
            z-index: 10;
            max-width: 600px;
            width: 90%;
        }

        .profile-card {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
        }

        .profile-header {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 30px;
        }

        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #30363d;
            margin-bottom: 20px;
            background: #0d1117;
        }

        .username {
            font-size: 32px;
            font-weight: 300;
            margin-bottom: 8px;
            color: #f0f6fc;
        }

        .bio-title {
            font-size: 14px;
            color: #8b949e;
            font-style: italic;
        }

        .section {
            margin-top: 30px;
        }

        .section-title {
            font-size: 16px;
            font-weight: 600;
            margin-bottom: 15px;
            color: #f0f6fc;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .about-text {
            font-size: 14px;
            line-height: 1.6;
            color: #8b949e;
        }

        .languages {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        .language-tag {
            background: #21262d;
            border: 1px solid #30363d;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 14px;
            color: #c9d1d9;
        }

        .projects {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .project-item {
            background: #0d1117;
            border: 1px solid #30363d;
            padding: 16px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            gap: 12px;
            transition: border-color 0.2s;
        }

        .project-item:hover {
            border-color: #58a6ff;
        }

        .github-icon {
            width: 20px;
            height: 20px;
            fill: #8b949e;
        }

        .project-name {
            font-size: 14px;
            color: #c9d1d9;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-card">
            <div class="profile-header">
                <div class="avatar"></div>
                <h1 class="username">snowt</h1>
                <p class="bio-title">Кодер/Идиот</p>
            </div>

            <div class="section">
                <div class="section-title">
                    <span>👤</span>
                    Обо мне:
                </div>
                <p class="about-text">
                    Ленивый кодер тг ботов и скриптов на боблох, имею тг канал с почти 10k
                </p>
            </div>

            <div class="section">
                <div class="section-title">
                    <span>&lt;/&gt;</span>
                    Языки
                </div>
                <div class="languages">
                    <span class="language-tag">Python</span>
                    <span class="language-tag">HTML</span>
                    <span class="language-tag">JavaScript</span>
                    <span class="language-tag">Lua</span>
                </div>
            </div>

            <div class="section">
                <div class="section-title">
                    <span>🎯</span>
                    Проекты
                </div>
                <div class="projects">
                    <div class="project-item">
                        <svg class="github-icon" viewBox="0 0 16 16">
                            <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path>
                        </svg>
                        <span class="project-name">Луа соурсы</span>
                    </div>
                    <div class="project-item">
                        <svg class="github-icon" viewBox="0 0 16 16">
                            <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path>
                        </svg>
                        <span class="project-name">Мой хаб (шифрован)</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function createSnowflake() {
            const snowflake = document.createElement('div');
            snowflake.classList.add('snowflake');
            snowflake.innerHTML = '❄';
            snowflake.style.left = Math.random() * 100 + 'vw';
            snowflake.style.animationDuration = Math.random() * 3 + 2 + 's';
            snowflake.style.opacity = Math.random() * 0.6 + 0.4;
            snowflake.style.fontSize = Math.random() * 10 + 10 + 'px';
            
            document.body.appendChild(snowflake);
            
            setTimeout(() => {
                snowflake.remove();
            }, 5000);
        }

        setInterval(createSnowflake, 200);
        
        for (let i = 0; i < 20; i++) {
            setTimeout(createSnowflake, i * 100);
        }
    </script>
</body>
</html>
