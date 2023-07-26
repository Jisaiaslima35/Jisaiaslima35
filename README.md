<!DOCTYPE html>
<html lang="pt-br">
<head>
  <!-- meta tags, title e estilos -->
   <style>
    /* Estilos CSS para o layout */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #444;
      padding: 1rem;
    }
    section {
      padding: 2rem;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
    }
    img {
      max-width: 100%;
    }
    .project {
      margin-bottom: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Minha Landing Page</h1>
  </header>
  
  <nav>
    <a href="#about">Quem sou eu</a>
    <a href="#projects">Meus Projetos</a>
  </nav>

  <section id="about">
    <div class="container">
      <!-- Conteúdo da seção "Quem sou eu" -->
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2>Meus Projetos</h2>
      <!-- Carrossel de projetos -->
      <div class="swiper-container">
        <div class="swiper-wrapper">
          <!-- Projetos -->
          <div class="swiper-slide">
            <a href="link_para_projeto1">
              <img src="caminho/para/imagem1.jpg" alt="Projeto 1">
            </a>
            <p>Descrição do Projeto 1.</p>
          </div>
          <div class="swiper-slide">
            <a href="link_para_projeto2">
              <img src="caminho/para/imagem2.jpg" alt="Projeto 2">
            </a>
            <p>Descrição do Projeto 2.</p>
          </div>
          <!-- Adicione mais projetos conforme necessário -->
        </div>
        <!-- Navegação do carrossel -->
        <div class="swiper-pagination"></div>
      </div>
    </div>
  </section>

  <!-- Adicione o link para o arquivo do Swiper.js -->
  <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

  <!-- Seu código JavaScript para inicializar o Swiper -->
  <script>
    const swiper = new Swiper('.swiper-container', {
      slidesPerView: 'auto',
      spaceBetween: 20,
      pagination: {
        el: '.swiper-pagination',
      },
    });
  </script>
</body>
</html>


