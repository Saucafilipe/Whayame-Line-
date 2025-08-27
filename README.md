
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Whayame Line</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0f172a;
      color: white;
      overflow-x: hidden;
    }

    header {
      background: #1e293b;
      padding: 20px;
      text-align: center;
      position:fixed;
      top: -50px;
      left: 0;
      width: 100%;
      z-index: 1;
      right: 100%;
    }

    header h1 {
      color: #38bdf8;
      /* Animação mais intensa para o nome */
      animation: moveTitle 2s infinite alternate;
      display: inline-block;
      white-space: nowrap; /* Evita que o texto quebre a linha */
      overflow: hidden; /* Garante que o texto não saia da tela */
    }

    @keyframes moveTitle {
      0% {
        transform: translateY(0);
      }
      100% {
        transform: translateY(-5px); /* Movimento mais amplo */
      }
    }

    nav {
      background: #334155;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: #94a3b8;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .container {
      padding: 120px 20px 40px;
      max-width: 1000px;
      margin: auto;
    }

    section {
      margin-bottom: 40px;
    }

    section h2 {
      color: #38bdf8;
      margin-bottom: 10px;
    }

    img {
      max-width: 100%;
      border-radius: 8px;
    }
  
  
  
  
  #fuder {
      background: #1e293b;
      padding: 10px; /* Rodapé mais curto */
      text-align: center;
      font-size: 14px;
      color: #94a3b8;
    }
  
  
  
  
  
  

    footer {
      background: #000;
      padding: 10px; /* Rodapé mais curto */
      text-align: center;
      font-size: 14px;
      color: #94a3b8;
    }

    button {
      background: #38bdf8;
      border: none;
      color: white;
      padding: 10px 20px;
      margin-top: 10px;
      border-radius: 4px;
      cursor: pointer;
    }

    button:hover {
      background: #0ea5e9;
    }

    /* Menu Colateral */
    .menu-btn {
      position: fixed;
      top: 9px;
      right: 20px;
      z-index: 1001;
      background-color: #ff5722;
      color: #fff;
      padding: 12px 18px;
      border: none;
      cursor: pointer;
      border-radius: 50px;
      font-size: 18px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }

    .side-menu {
      height: 100%;
      width: 0;
      position: fixed;
      top: 0;
      right: 0;
      background: linear-gradient(to bottom, #ffffff, #e3f2fd);
      overflow-x: hidden;
      transition: 0.4s;
      padding-top: 60px;
      z-index: 1000;
      box-shadow: -2px 0 5px rgba(0,0,0,0.4);
    }

    .side-menu a {
      display: block;
      padding: 16px 30px;
      text-decoration: none;
      color: #1976d2;
      font-weight: bold;
      font-size: 18px;
    }

    .side-menu a:hover {
      background-color: #bbdefb;
      color: #0d47a1;
    }

    .close-btn {
      position: absolute;
      top: 15px;
      right: 25px;
      font-size: 32px;
      cursor: pointer;
      color: #f44336;
    }

    /* Animações de texto */
    .animated-text {
      display: inline-block;
      overflow: hidden; /* Garante que o texto não saia da tela */
      white-space: nowrap; /* Evita que o texto quebre a linha */
    }

    .letter {
      animation: moveLetters 2s infinite alternate;
      display: inline-block;
    }

    @keyframes moveLetters {
      0% {
        transform: translateY(0);
      }
      100% {
        transform: translateY(-10px);
      }
    }

    /* Estilos dos botões */
    .action-buttons {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }

    .action-button {
      background: #38bdf8;
      border: none;
      color: white;
      padding: 10px 20px;
      margin: 0 10px;
      border-radius: 4px;
      cursor: pointer;
     display: flex;
      align-items: center;
    }

    .action-button:hover {
      background: #0ea5e9;
    }

    .action-button img {
      width: 20px;
      margin-right: 5px;
    }
  </style>
  
  
  
  
  
  
  
  
</head>
<body>

  
  
     
  
  <header>
    
  <img src="/storage/emulated/0/Pictures/facebook/1750943846759.jpg" width="50" height="50" > <h1>Sauca zeca filipe</h1>
    
    
    <nav>
      
     
      <a href="#sobre">Sobre</a>
      <a href="#projetos">Projetos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <button class="menu-btn" onclick="openNav()">☰</button>

  <div id="mySideMenu" class="side-menu">
    <a href="javascript:void(0)" class="close-btn" onclick="closeNav()">--->--</a>
    <a href="#">Home</a>
    <a href="#">Sobre Mim</a>
    <a href="#">Habilidades</a>
    <a href="#">Serviços</a>
    <a href="#">Projetos</a>
    <a href="#">Contato</a>
  </div>

  <br>
  <br>
  <div class="container">
    <section id="sobre">
      <h2>********Sobre Mim*********</h2>
      
      
      
      ___________<img src="/storage/emulated/0/Download/1741185807328.jpg" alt="Imagem sobre tecnologia" width="50%" height="50%" >__________
      
      
      
      <p>
        <br>
        <span class="animated-text">
          <span class="letter">C</span>
          <span class="letter">r</span>
          <span class="letter">i</span>
          <span class="letter">a</span>
          <span class="letter">d</span>
          <span class="letter">o</span>
          <span class="letter">r</span>
        </span>
        de conteúdos digitais, sites modernos e interativos.
      </p>
      <p>Trabalhamos para que a tua empresa tenha outras formas de visualização.</p>
      
      
      
      <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250827-015508.jpg" alt="Imagem sobre tecnologia">
      
      
          <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250827-015525.jpg" alt="Imagem sobre tecnologia">
      
      
      
          <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250827-015541.jpg" alt="Imagem sobre tecnologia">
      
      
      
          <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250827-015554.jpg" alt="Imagem sobre tecnologia">
      
      
          <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250827-015608.jpg" alt="Imagem sobre tecnologia">
      
    
      
          <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250827-015628.jpg" alt="Imagem sobre tecnologia">
      
      
      
    </section>

    <section id="estatisticas">
      <h2>Estatísticas</h2>
      <ul>
        <li>+ de 2 Anos</li>
        <li>+ de 3 Projetos</li>
        <li>100%</li>
      </ul>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <p>Email: sauca@example.com</p>
      <button onclick="alert('Obrigado por visitar!')">Dizer Olá</button>
    </section>
  </div>

  
  
  
  
  <div class="carousel-container">
    <div class="carousel-track" id="track">
      <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250709-075445.png" alt="Imagem sobre tecnologia">
      <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250709-075706.png" alt="">
      <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250709-075341.png" alt="">
      <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20250709-075419.png" alt="">
    </div>
  </div>
  
  
<footer>
  <div class="section">
    <p>Praticamos também auditoria do teu sistema ou da empresa que estará usando um software.</p>
  </div>

  <div class="section">
    <h3>Links do Usuário</h3>
    <h1 class="info-item"><i>ℹ️</i> Sobre</h1>
    <h1 class="info-item"><i>💬</i> Mais informações</h1>
    <h1 class="info-item"><i>📞</i> +244-932-601-138</h1>
    <h1 class="info-item"><i>❓</i> Ajuda</h1>
  </div>

  <div class="section">
    <h3>Localização</h3>
    <p class="info-item"><i>📍</i> Angola-Malanje, Área territorial de 2.422 km², AO</p>
  </div>
</footer>

  
  
  <p id="fuder">
    &copy; 2025 Sauca Zeca Filipe. Todos os direitos reservados.
  </p>

  <script>
    function openNav() {
      document.getElementById("mySideMenu").style.width = "250px";
    }

    function closeNav() {
      document.getElementById("mySideMenu").style.width = "0";
    }
  </script>

</body>
</html>
