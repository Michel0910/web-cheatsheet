  # 📘 Web Cheat Sheet
  **Autor:** Michel S. Alves
  
  📌 Objetivo: Desenvolver uma cheat sheet essencial de tecnologias Web (HTML, CSS, JS) para consulta e reforço de aprendizado.
  
  ---
  
  ## 🌐 HTML, 🎨 CSS, ⚡ JavaScript e 📱 Outros Tópicos
  
  
  ### Estrutura básica 🌐 HTML
  HTML (HyperText Markup Language) é a linguagem usada para estruturar páginas web. Ele define **o conteúdo e a hierarquia dos elementos** que serão exibidos no navegador.
  ```html
  <!DOCTYPE html>
  <html lang="pt-BR">
  <head>
    <meta charset="UTF-8"> <!-- Define a codificação de caracteres -->
    <title>Minha Página</title> <!-- Título exibido na aba do navegador -->
  </head>
  <body>
    <h1>Olá Mundo!</h1> <!-- Título principal -->
    <p>Este é um parágrafo.</p> <!-- Texto simples -->
  </body>
  </html>
  
  <!-- Referência: https://developer.mozilla.org/pt-BR/docs/Web/HTML -->
  
  ###Tags mais usadas
  <div> <!-- Container genérico -->
    <p>Parágrafo de texto</p>
    <h1>Título nível 1</h1>
    <a href="https://example.com">Link para outra página</a>
    <img src="foto.jpg" alt="Descrição da imagem"> <!-- 'alt' garante acessibilidade -->
    <form>
      <input type="text" placeholder="Digite aqui"> <!-- Campo de entrada -->
      <button type="submit">Enviar</button>
    </form>
  </div>
  
  <!-- Referência: https://www.w3schools.com/html/ -->
  
    ---  ---

  # Estrutura básica 🎨 CSS
  CSS (Cascading Style Sheets) é usado para estilizar e dar aparência ao conteúdo HTML. Ele controla cores, fontes, espaçamento e layout.
  
  /* Seleciona todos os parágrafos */
  p {
    color: #333; /* Define a cor do texto */
    font-size: 16px; /* Tamanho da fonte */
    margin: 10px; /* Espaçamento externo */
    padding: 5px; /* Espaçamento interno */
  }
  
  /* Classe para layout flexível */
  .container {
    display: flex; /* Ativa o Flexbox */
    justify-content: space-between; /* Distribui espaço entre elementos */
  }
  
  /* Layout em Grid */
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr; /* Cria duas colunas iguais */
  }
  
  /* Responsividade com media query */
  @media (max-width: 600px) {
    body {
      font-size: 14px; /* Ajusta fonte em telas pequenas */
    }
  }
  
  /* Referência: https://developer.mozilla.org/pt-BR/docs/Web/CSS */
  
  ### Estrutura básica ⚡ JavaScript
  JavaScript é a linguagem que dá interatividade e dinamismo às páginas web. Ele permite manipular elementos, responder a eventos e criar lógica de programação.
  
  ### Variáveis e funções
  let nome = "Michel"; // variável mutável
  const idade = 25; // constante
  
  function soma(a, b) {
    return a + b; // retorna a soma de dois números
  }
  
  // Referência: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide
  
  ### Eventos e manipulação do DOM
  // Captura clique em botão
  document.getElementById("meuBotao").addEventListener("click", function() {
    alert("Você clicou!");
  });
  
  // Manipula conteúdo da página
  document.querySelector("h1").textContent = "Título alterado!";
  
  // Referência: https://www.w3schools.com/js/js_htmldom.asp
  
  
  ### Estrutura básica 📱 Outros Tópicos
  
  
  ### PWA (Progressive Web Apps)
  - Aplicativos web que funcionam offline.
  - Usam Service Workers para cache e notificações.
  - Podem ser instalados no dispositivo como apps nativos.
  
  Referência: https://web.dev/what-are-pwas/
  
  
  ### Bancos em Cache
  - Guardam recursos (HTML, CSS, JS, imagens) para acelerar carregamento.
  - Podem ser controlados via cabeçalhos HTTP ou Service Workers.
  - Melhoram a experiência do usuário em conexões lentas.
  
  Referência: https://developer.mozilla.org/en-US/docs/Web/API/Cache
  
  
  ### Conceitos gerais da Internet 
  - HTTP/HTTPS: protocolos que definem como os dados são transmitidos.
  - DNS: sistema que traduz nomes de domínio em endereços IP.
  - API REST: forma de comunicação entre sistemas usando endpoints e JSON.
  
  Referências:
  HTTP → https://developer.mozilla.org/pt-BR/docs/Web/HTTP
  DNS → https://developer.mozilla.org/en-US/docs/Glossary/DNS
  REST → https://developer.mozilla.org/en-US/docs/Glossary/REST
  
  
  ### 👨‍💻 Autor
  Michel S. Alves
