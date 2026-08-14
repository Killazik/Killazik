<!-- Анимированный баннер с эффектом прорисовки обводки KILLAZIK -->
<p align="center">
  <svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <style>
        .bg { fill: #000000; }
        
        /* Волна на фоне */
        .wave {
          fill: #0a0a0a;
          animation: waveMove 4s ease-in-out infinite alternate;
        }
        
        /* Анимированный текст с эффектом рисующейся обводки */
        .stroke-title {
          font-family: 'Arial Black', Impact, sans-serif;
          font-size: 75px;
          font-weight: 900;
          fill: transparent;
          stroke: #ffffff;
          stroke-width: 2.5px;
          letter-spacing: 10px;
          stroke-dasharray: 400;
          stroke-dashoffset: 400;
          animation: drawStroke 4s ease-in-out infinite alternate;
        }

        .sub-title {
          font-family: 'Fira Code', 'Courier New', monospace;
          font-size: 16px;
          fill: #ffffff;
          letter-spacing: 6px;
          opacity: 0.8;
        }

        @keyframes drawStroke {
          0% {
            stroke-dashoffset: 400;
            fill: transparent;
            filter: drop-shadow(0 0 2px rgba(255, 255, 255, 0.2));
          }
          70% {
            stroke-dashoffset: 0;
            fill: transparent;
            filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.9));
          }
          100% {
            stroke-dashoffset: 0;
            fill: rgba(255, 255, 255, 0.1);
            filter: drop-shadow(0 0 15px rgba(255, 255, 255, 1));
          }
        }
      </style>
    </defs>

    <!-- Тёмный фон -->
    <rect width="100%" height="100%" class="bg" rx="10"/>

    <!-- Волна на заднем плане -->
    <path class="wave" d="M 0 140 Q 200 180 400 140 T 800 140 L 800 220 L 0 220 Z" />

    <!-- Заголовок KILLAZIK с рисующимся контуром -->
    <text x="50%" y="115" text-anchor="middle" class="stroke-title">KILLAZIK</text>
    <text x="50%" y="165" text-anchor="middle" class="sub-title">> BACKEND DEVELOPER</text>
  </svg>
</p>

<br>

<!-- Печатающийся стек -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2500&pause=1000&color=FFFFFF&center=true&vCenter=true&width=500&lines=%3E_init_system_kernel...;%3E_Python;%3E_VS+Code;%3E_Git;%3E_PostgreSQL" alt="Typing SVG" />
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
