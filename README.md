<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rayan Correa | GitHub Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet">
  <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Fira Code', monospace;
      background-color: #0d1117;
      color: #c9d1d9;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .container {
      max-width: 900px;
      padding: 2rem;
      text-align: center;
    }
    h1 span {
      color: #58a6ff;
    }
    .typewriter h1 {
      overflow: hidden;
      border-right: .15em solid #58a6ff;
      white-space: nowrap;
      letter-spacing: .15em;
      animation: typing 3s steps(30, end), blink-caret .75s step-end infinite;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink-caret {
      from, to { border-color: transparent }
      50% { border-color: #58a6ff; }
    }
    .techs {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
    }
    .techs img {
      width: 50px;
      transition: transform 0.3s ease, filter 0.3s ease;
    }
    .techs img:hover {
      transform: scale(1.2);
      filter: drop-shadow(0 0 10px #58a6ff);
    }
    .glow {
      text-shadow: 0 0 5px #58a6ff, 0 0 10px #58a6ff;
    }
    .socials a {
      margin: 0 10px;
      color: #58a6ff;
      text-decoration: none;
      font-size: 20px;
    }
    .stats img {
      margin: 10px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(88, 166, 255, 0.3);
    }
  </style>
</head>
<body>
  <div class="container">

    <lottie-player src="https://assets5.lottiefiles.com/packages/lf20_jtbfg2nb.json" background="transparent" speed="1" style="width: 200px; height: 200px;" loop autoplay></lottie-player>

    <div class="typewriter">
      <h1>Olá! Eu sou <span class="glow">Rayan Correa</span></h1>
    </div>

    <p>Desenvolvedor Full Stack | Estudante de Análise e Desenvolvimento de Sistemas</p>

    <div class="socials">
      <a href="https://github.com/RayCorrea" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/rayan-correa-4930931b3" target="_blank">LinkedIn</a>
    </div>

    <h2>🚀 Tecnologias</h2>
    <div class="techs">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JS">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TS">
    </div>

    <h2>✨ Sobre mim</h2>
    <p>Sou apaixonado por tecnologia, backend, dados e resolver problemas com código. Sempre buscando novos desafios e aprendizado contínuo!</p>

    <h2>📊 GitHub Stats</h2>
    <div class="stats">
      <img src="https://github-readme-stats.vercel.app/api?username=RayCorrea&show_icons=true&theme=github_dark" height="150" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RayCorrea&layout=compact&theme=github_dark" height="150" />
    </div>
  </div>
</body>
</html>
