Comentário linha a linha (principais trechos)
<!DOCTYPE html> <!-- Define o tipo de documento como HTML5 -->
<html lang="pt-br"> <!-- Define o idioma da página como português do Brasil -->
<head>
  <meta charset="UTF-8" /> <!-- Codificação de caracteres UTF-8 -->
  <meta name="viewport" content="width=device-width, initial-scale=1" /> <!-- Responsividade em dispositivos móveis -->
  <title>Layout com Bootstrap 5</title> <!-- Título da aba do navegador -->

  <!-- Importa o CSS do Bootstrap via CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Importa os ícones do Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">


🎨 Estilos personalizados
html, body { height: 100%; } /* Garante altura total para layout flexível */
body {
  font-family: Arial, Helvetica, sans-serif;
  background-color: #f8f9fa; /* Cor de fundo clara */
  color: #333;
  margin: 0;
  display: flex;
  flex-direction: column; /* Permite rodapé fixo no final */
  min-height: 100vh;
}
main { flex: 1 0 auto; } /* Cresce para ocupar espaço restante */
footer { flex-shrink: 0; } /* Rodapé não encolhe */


🧭 Cabeçalho
<header>
  <div class="header-container"> <!-- Container centralizado -->
    <div class="brand"> <!-- Logo e título -->
      <i class="bi bi-x-diamond-fill"></i> <!-- Ícone Bootstrap -->
      <div class="header-title">
        <h1>Exemplo de Grade com Bootstrap 5</h1>
        <p>Utilizando classes de espaçamento e colunas responsivas</p>
      </div>
    </div>
    <nav> <!-- Links de navegação -->
      <a href="index.html">Início</a>
      <a href="features.html">Recursos</a>
      <a href="pricing.html">Planos</a>
    </nav>
  </div>
</header>


🖼️ Carrossel (Hero)
<section class="hero">
  <div id="heroCarousel" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <!-- Cada item do carrossel com imagem de fundo -->
      <div class="carousel-item active" style="background-image: url('images/img1.jpg');">
        <div class="carousel-caption">
          <h2>Desenvolvimento Web</h2>
          <p>Aprenda a criar sites incríveis!</p>
        </div>
      </div>
      <!-- Outros slides seguem o mesmo padrão -->
    </div>
    <!-- Botões de navegação -->
    <button class="carousel-control-prev" ...></button>
    <button class="carousel-control-next" ...></button>
  </div>
</section>


📚 Conteúdo principal com cards
<main class="container mt-5 mb-2">
  <section class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
    <!-- Cada artigo representa um card de conteúdo -->
    <article class="col">
      <div class="bg-gray p-3 border rounded">
        <h5>HTML & Estrutura</h5>
        <p>...</p>
      </div>
    </article>
    <!-- Outros artigos seguem o mesmo padrão -->
  </section>


👤 Cards com imagem
<section class="container my-5">
  <div class="row justify-content-center g-4">
    <div class="col-12 col-md-6 col-lg-5">
      <div class="card shadow-sm mx-auto">
        <img src="images/avatar1.png" class="card-img-top" alt="John Doe">
        <div class="card-body">
          <h5 class="card-title">John Doe</h5>
          <p class="card-text">...</p>
          <a href="john.html" class="btn btn-primary btn-sm">Ver Perfil</a>
        </div>
      </div>
    </div>
    <!-- Outro card com imagem no rodapé -->
  </div>
</section>


🔝 Botão "voltar ao topo"
<a href="#top" class="btn btn-primary btn-sm">Ir para o topo</a>


🦶 Rodapé fixo
<footer role="contentinfo" aria-label="Rodapé do site">
  <p>&copy; 2025 - Exemplo de página HTML5 com Bootstrap 5</p>
</footer>


🧩 Scripts do Bootstrap
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"></script>



📘 Sugestão de descrição para o GitHub
# Layout Responsivo com Bootstrap 5

Este projeto demonstra a criação de uma página web moderna e responsiva utilizando **Bootstrap 5**. Inclui:

- Cabeçalho com navegação
- Carrossel de imagens (Hero)
- Cards informativos e de perfil
- Rodapé fixo (Sticky Footer)
- Estilização personalizada com CSS

Ideal para iniciantes que desejam aprender a estruturar páginas com **HTML, CSS e Bootstrap**.

🔗 [Documentação oficial do Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)


Se quiser, posso ajudar a publicar esse projeto no GitHub com README formatado e instruções de uso. Deseja isso?

