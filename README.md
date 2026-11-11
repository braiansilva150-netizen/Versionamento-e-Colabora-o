
[index.html](https://github.com/user-attachments/files/34701672/index.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>senai teste bla bla</title>

  <style>
    /* CORES DO SITE: experimente trocar os valores abaixo. */
    :root {
      --fundo: #94bdff;
      --cartao: #ffffff;
      --texto: #000000;
      --detalhe: #f8f8f8;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: var(--fundo);
      color: var(--texto);
      line-height: 1.5;
    }

    .container {
      max-width: 760px;
      margin: 40px auto;
      padding: 0 20px;
    }

    header {
      text-align: center;
      margin-bottom: 28px;
    }

    .avatar {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 90px;
      height: 90px;
      border-radius: 50%;
      background-color: var(--detalhe);
      color: white;
      font-size: 42px;
    }

    h1 { margin-bottom: 6px; }
    h2 { margin-top: 0; }
    .subtitulo { margin-top: 0; color: #1d5eb9; }

    section {
      background-color: var(--cartao);
      padding: 24px;
      margin-bottom: 18px;
      border-radius: 12px;
      box-shadow: 0 3px 12px rgba(0, 0, 0, 0.05);
    }

    .habilidades span {
      display: inline-block;
      background-color: #dbeafe;
      color: #1e40af;
      padding: 6px 10px;
      margin: 4px;
      border-radius: 6px;
    }

    button {
      background-color: var(--detalhe);
      color: rgb(0, 0, 0);
      border: none;
      padding: 10px 16px;
      border-radius: 6px;
      cursor: pointer;
    }

    button:hover { opacity: 0.85; }
    a { color: var(--detalhe); }
    footer { text-align: center; color: #64748b; font-size: 14px; }
  </style>
</head>
<body>
  <main class="container">
    <header>
      <div class="avatar">👨‍💻</div>
      <!-- ALTERE SEU NOME AQUI -->braian lindao
      <h1>fala tu feio. braian aqui</h1>
      <p class="subtitulo">Estudante de Técnico em Informática para Internet</p>
    </header>

    <section>
      <h2>Sobre mim</h2>
      <!-- ESCREVA UMA BREVE APRESENTAÇÃO -->meu nome é braian tenho 17 anos estou fazendo o senai. gosto muito de luta(quase todos os tipos). andar de bike,skate,fazer trilhas e acampar.
      <p>Gosto de tecnologia e estou aprendendo a criar sites e sistemas para a internet. difiicil aprender só</p>
    </section>

    <section>
      <h2>Minhas habilidades</h2>
      <!-- TROQUE OU ADICIONE HABILIDADES --> sei usar o gerenciador de arquivos
      <div class="habilidades">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </section>

    <section>
      <h2>Meu primeiro projeto</h2>
      <!-- DESCREVA UM PROJETO OU ATIVIDADE ESCOLAR -->
      <h3>Meu site pessoal</h3>
      <p>Um site simples para me apresentar e praticar o que aprendi</p>
    </section>

    <section>
      <h2>Contato</h2>
      <!-- SUBSTITUA # PELO LINK DO SEU GITHUB -->
      <p>Meu GitHub: <a href="https://github.com/braiansilva150-netizen/Versionamento-e-Colabora-oS">Acessar perfil</a></p>
      <button onclick="mostrarMensagem()">Clique para conhecer meu site</button>
      <p id="mensagem"></p> 
    </section>

    <footer>
      <!-- ALTERE SEU NOME AQUI TAMBÉM -->braian lindo
      <p>Feito por braian da silva lindao • 2026</p>
    </footer>
  </main>

  <script>
    // JAVASCRIPT: altere a mensagem que aparece ao clicar no botão.
    function mostrarMensagem() {
      document.getElementById("mensagem").textContent =
        "Obrigado por ver meu projeto em teste";
    }
  </script>
</body>
</html>
