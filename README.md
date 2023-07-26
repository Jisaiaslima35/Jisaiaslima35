<!DOCTYPE html>
<html lang="pt-br">
<head>
  <!-- meta tags, title e estilos -->
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


