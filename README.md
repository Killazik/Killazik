<!-- Анимированный баннер в стиле терминала -->
<p align="center">
  <svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Стиль и анимации -->
      <style>
        .bg { fill: #000000; }
        
        /* Текст фона (строки терминала) */
        .term-text {
          font-family: 'Fira Code', 'Courier New', monospace;
          font-size: 13px;
          fill: #333333;
        }
        
        /* Движение текста вверх */
        .scroll-bg {
          animation: scrollTerminal 8s linear infinite;
        }
        
        @keyframes scrollTerminal {
          0% { transform: translateY(0px); }
          100% { transform: translateY(-100px); }
        }

        /* Главный прозрачный заголовок с обводкой */
        .main-title {
          font-family: 'Arial Black', Impact, sans-serif;
          font-size: 72px;
          font-weight: 900;
          fill: none;
          stroke: #ffffff;
          stroke-width: 2.5px;
          letter-spacing: 12px;
          animation: pulseGlow 3s ease-in-out infinite alternate;
        }

        .sub-title {
          font-family: 'Fira Code', 'Courier New', monospace;
          font-size: 16px;
          fill: #ffffff;
          letter-spacing: 6px;
        }

        @keyframes pulseGlow {
          0% { stroke: #888888; filter: drop-shadow(0 0 2px rgba(255,255,255,0.2)); }
          100% { stroke: #ffffff; filter: drop-shadow(0 0 8px rgba(255,255,255,0.9)); }
        }
      </style>
    </defs>

    <!-- Чёрный фон -->
    <rect width="100%" height="100%" class="bg" rx="8"/>

    <!-- Бегущий текст терминала на заднем плане -->
    <g class="scroll-bg">
      <text x="20" y="30" class="term-text">> init_system_kernel --verbose</text>
      <text x="20" y="50" class="term-text">> loading modules: [python3, postgresql, git, vscode]... OK</text>
      <text x="20" y="70" class="term-text">> connecting to remote host 127.0.0.1:8000... status 200 OK</text>
      <text x="20" y="90" class="term-text">> exec /bin/bash -c 'echo ACCESS_GRANTED'</text>
      <text x="20" y="110" class="term-text">> compiling backend_service.py... done in 0.04s</text>
      <text x="20" y="130" class="term-text">> SELECT * FROM users WHERE status = 'developer';</text>
      <text x="20" y="150" class="term-text">> git commit -m "feat: core functionality integrated"</text>
      <text x="20" y="170" class="term-text">> system initialized successfully. listening on port 443...</text>
      <text x="20" y="190" class="term-text">> init_system_kernel --verbose</text>
      <text x="20" y="210" class="term-text">> loading modules: [python3, postgresql, git, vscode]... OK</text>
      <text x="20" y="230" class="term-text">> connecting to remote host 127.0.0.1:8000... status 200 OK</text>
      <text x="20" y="250" class="term-text">> exec /bin/bash -c 'echo ACCESS_GRANTED'</text>
      <text x="20" y="270" class="term-text">> compiling backend_service.py... done in 0.04s</text>
      <text x="20" y="290" class="term-text">> SELECT * FROM users WHERE status = 'developer';</text>
    </g>

    <!-- Поверх поверх фона: Большой заголовок KILLAZIK -->
    <text x="50%" y="125" text-anchor="middle" class="main-title">KILLAZIK</text>
    <text x="50%" y="170" text-anchor="middle" class="sub-title">> BACKEND DEVELOPER</text>
  </svg>
</p>

<br>

<!-- Анимированный печатающийся стек -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2500&pause=1000&color=FFFFFF&center=true&vCenter=true&width=500&lines=%3E_Python;%3E_VS+Code;%3E_Git;%3E_PostgreSQL;%3E_Backend+Dev" alt="Typing SVG" />
</p>

<br>

<!-- Иконки технологий -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/VS%20Code-000000?style=for-the-badge&logo=visual-studio-code&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=ffffff" />
</p>

<br>

<!-- Счетчик просмотров -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Killazik&label=VIEWS&color=000000&style=for-the-badge" alt="Views" />
</p>
