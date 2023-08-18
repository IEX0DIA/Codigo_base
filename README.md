# Codigo_base
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Página do Cientista</title>
</head>
<body>
  <header>
    <h1>Nome do Cientista</h1>
    <img src="foto.jpg" alt="Foto do Cientista">
  </header>
  <section class="bio">
    <h2>Biografia</h2>
    <p><strong>Data e Local de Nascimento:</strong> XX de Mês de Ano - Cidade, País</p>
    <p><strong>Data e Local de Falecimento:</strong> XX de Mês de Ano - Cidade, País</p>
    <p><strong>Fatos Biográficos Relevantes:</strong> Descrição dos fatos importantes da vida do cientista.</p>
  </section>
  <section class="area">
    <h2>Área de Atuação/Pesquisa</h2>
    <p>Descrição da área de atuação ou pesquisa do cientista.</p>
  </section>
  <section class="trabalhos">
    <h2>Trabalhos Científicos</h2>
    <article class="trabalho">
      <h3>Título do Trabalho 1</h3>
      <img src="imagem1.jpg" alt="Imagem do Trabalho 1">
      <p>Breve descrição do Trabalho 1.</p>
      <p>Prêmios: Prêmios associados ao Trabalho 1, se houver.</p>
    </article>
    <article class="trabalho">
      <h3>Título do Trabalho 2</h3>
      <img src="imagem2.jpg" alt="Imagem do Trabalho 2">
      <p>Breve descrição do Trabalho 2.</p>
      <p>Prêmios: Prêmios associados ao Trabalho 2, se houver.</p>
    </article>
    <!-- Adicione mais trabalhos conforme necessário -->
  </section>
</body>
</html>

styles.css
/* Estilos gerais */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

/* Estilos do cabeçalho */
header {
  background-color: #007BFF;
  color: #fff;
  text-align: center;
  padding: 20px;
}

header img {
  max-width: 150px;
  border-radius: 50%;
}

/* Estilos das seções */
section {
  margin: 20px;
  padding: 20px;
  border: 1px solid #ddd;
}

/* Estilos dos trabalhos científicos */
.trabalho {
  margin-bottom: 20px;
}

.trabalho h3 {
  margin: 10px 0;
}

.trabalho img {
  max-width: 300px;
}

/* Estilos dos links */
a {
  color: #007BFF;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

