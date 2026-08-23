<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Samuel Silva dos Reis | Currículo</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=JetBrains+Mono:wght@400;600&display=swap');

    :root {
      --bg: #eef2f5;
      --card-bg: #ffffff;
      --border: #d1d5db;
      --text: #1e293b;
      --text-light: #475569;
      --accent: #0f172a;
      --accent2: #2563eb;
      --mono: 'JetBrains Mono', 'Fira Code', monospace;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      background: var(--bg);
      color: var(--text);
      padding: 2rem;
      line-height: 1.5;
    }

    .resume {
      max-width: 1100px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 1fr 360px;
      gap: 1.5rem;
    }

    .card {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 0;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
      padding: 1.5rem;
      margin-bottom: 1.5rem;
    }

    .card:last-child {
      margin-bottom: 0;
    }

    h1 {
      font-size: 2rem;
      letter-spacing: 0.05em;
      color: var(--accent);
      text-transform: uppercase;
    }

    .title {
      font-size: 1rem;
      color: var(--accent2);
      font-weight: 600;
      margin: 0.25rem 0 0.5rem;
    }

    .contact {
      font-size: 0.9rem;
      color: var(--text-light);
    }

    h2 {
      font-size: 1.1rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--accent);
      border-bottom: 2px solid var(--accent2);
      padding-bottom: 0.5rem;
      margin-bottom: 0.75rem;
    }

    ul {
      list-style: none;
    }

    li {
      margin-bottom: 0.4rem;
    }

    .exp h3 {
      font-size: 0.95rem;
      color: var(--accent);
    }

    .period {
      font-size: 0.85rem;
      color: var(--text-light);
      margin-bottom: 0.4rem;
    }

    .terminal {
      background: #0f172a;
      color: #e2e8f0;
      border: 1px solid #1e293b;
      font-family: var(--mono);
      font-size: 0.8rem;
      padding: 0;
    }

    .terminal-header {
      background: #1e293b;
      padding: 0.5rem 1rem;
      border-bottom: 1px solid #334155;
      color: #94a3b8;
      font-family: 'Inter', sans-serif;
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.1em;
    }

    .terminal pre {
      padding: 1rem;
      white-space: pre-wrap;
      word-break: break-word;
      color: #a5f3fc;
      margin: 0;
    }

    .extensions h2 {
      margin-bottom: 0.75rem;
    }

    .chips {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .chips span {
      background: #f1f5f9;
      border: 1px solid #cbd5e1;
      padding: 0.25rem 0.6rem;
      font-family: var(--mono);
      font-size: 0.75rem;
      color: #0f172a;
    }

    .quote blockquote {
      font-style: italic;
      color: var(--text-light);
      border-left: 3px solid var(--accent2);
      padding-left: 1rem;
    }

    .quote footer {
      margin-top: 0.5rem;
      font-style: normal;
      font-weight: 600;
      color: var(--accent);
    }

    a {
      color: var(--accent2);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    @media (max-width: 800px) {
      body {
        padding: 1rem;
      }

      .resume {
        grid-template-columns: 1fr;
      }

      .side {
        order: 2;
      }
    }

    @media print {
      body {
        background: #fff;
        padding: 0;
      }

      .card {
        box-shadow: none;
        border: 1px solid #ccc;
      }

      .terminal {
        background: #fff;
        color: #000;
        border: 1px solid #000;
      }

      .terminal-header {
        background: #eee;
        color: #000;
      }

      .terminal pre {
        color: #000;
      }

      .chips span {
        background: #eee;
      }
    }
  </style>
</head>
<body>
  <div class="resume">
    <!-- Coluna principal: dados -->
    <div class="main">
      <header class="card header">
        <h1>SAMUEL SILVA DOS REIS</h1>
        <p class="title">Desenvolvedor Fullstack em formação</p>
        <p class="contact">São Paulo, SP • samuelsilva.reis2625@gmail.com • (11) 95759-5256</p>
      </header>

      <section class="card">
        <h2>Objetivo</h2>
        <p>Estudante de Análise e Desenvolvimento de Sistemas – 4º semestre. Busco estágio em tecnologia com foco em desenvolvimento fullstack. Experiência administrativa e conhecimento em Java, Spring Boot, JavaScript, Node.js, React, React Native e banco de dados.</p>
      </section>

      <section class="card">
        <h2>Educação</h2>
        <ul>
          <li><strong>Análise e Desenvolvimento de Sistemas</strong> – SENAC Santo Amaro (2025 – 2027)</li>
          <li><strong>Técnico em Administração</strong> – ETEC C. C. Sampaio | Concluído em 2023</li>
        </ul>
      </section>

      <section class="card">
        <h2>Experiência</h2>
        <div class="exp">
          <h3>Auxiliar Administrativo – Livraria Saraiva</h3>
          <p class="period">Abr 2023 – Out 2023</p>
          <ul>
            <li>Controle de estoque, rotinas administrativas e atendimento interno</li>
            <li>Elaboração de planilhas, organização documental e suporte logístico</li>
          </ul>
        </div>
        <div class="exp" style="margin-top: 1rem;">
          <h3>Jardineiro Autônomo</h3>
          <p class="period">Fev 2024 – Atual</p>
          <ul>
            <li>Atendimento a clientes, orçamento de serviços e controle financeiro</li>
            <li>Gestão do negócio, compra de materiais, logística e relacionamento com clientes</li>
          </ul>
        </div>
      </section>

      <section class="card">
        <h2>Habilidades Técnicas</h2>
        <ul>
          <li><strong>Sistemas:</strong> Windows, Linux</li>
          <li><strong>Banco de Dados:</strong> SQL, NoSQL (MySQL, PostgreSQL)</li>
          <li><strong>Linguagens:</strong> Java, JavaScript, TypeScript, Node.js, Spring Boot, AngularJS, HTML/CSS</li>
          <li><strong>Frameworks/Bibliotecas:</strong> React, React Native, Express</li>
          <li><strong>Ferramentas:</strong> Git, GitHub, npm, VS Code, Spring Tool Suite, Figma, Office 365</li>
        </ul>
      </section>

      <section class="card">
        <h2>Idiomas</h2>
        <p>Inglês intermediário | Espanhol básico</p>
      </section>

      <section class="card">
        <h2>Portfólio</h2>
        <p>Projetos disponíveis em <a href="https://github.com/SamuelSilva000" target="_blank">github.com/SamuelSilva000</a></p>
      </section>
    </div>

    <!-- Coluna lateral: terminal, extensões e frase -->
    <aside class="side">
      <div class="card terminal">
        <div class="terminal-header">terminal</div>
        <pre>samuelsilva000@github
-------------------------
OS: Arch Linux x86_64
Shell: zsh 5.8
Pronouns: He/Him
Location: São Paulo, SP
Frameworks: React, React Native, Spring Boot
Languages: JavaScript, TypeScript, HTML, CSS, Java
Learning: Node.js, Express, PostgreSQL, Three.js, C++
Hobbies: Gardening, Cooking, Gaming
Commits: 968
Stars: 14
Discord: RandomPotato#1377</pre>
      </div>

      <div class="card extensions">
        <h2>Stack & Uso</h2>
        <div class="chips">
          <span>.php</span>
          <span>.js</span>
          <span>.html</span>
          <span>.css</span>
          <span>.svg</span>
          <span>.psd</span>
          <span>.ai</span>
        </div>
      </div>

      <div class="card quote">
        <blockquote>
          “Podia parecer que chegamos ao limite do que era possível alcançar com a tecnologia dos computadores, contudo, uma pessoa deveria ser cuidadosa com tais afirmações, pois tendem a soar muito tontas em 5 anos.”
          <footer>— John von Neumann, 1949</footer>
        </blockquote>
      </div>
    </aside>
  </div>
</body>
</html>
