<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Samuel Silva · README</title>
  <style>
    /* Reset simples e estilo minimalista */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: #0d1117;
      color: #c9d1d9;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
      line-height: 1.6;
      padding: 2rem 1.5rem;
      max-width: 880px;
      margin: 0 auto;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .note {
      background: #1f2937;
      border-left: 4px solid #58a6ff;
      padding: 1rem 1.2rem;
      border-radius: 6px;
      margin-bottom: 1.8rem;
    }
    .note strong {
      color: #58a6ff;
    }
    .note blockquote {
      margin: 0.4rem 0 0 0;
      padding-left: 0.8rem;
      border-left: 2px solid #30363d;
      color: #e6edf3;
      font-style: italic;
    }
    .note blockquote cite {
      display: block;
      margin-top: 0.3rem;
      font-size: 0.9rem;
      color: #8b949e;
      font-style: normal;
    }
    .terminal {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 8px;
      padding: 1.2rem 1.5rem;
      font-family: 'JetBrains Mono', 'Fira Code', monospace;
      font-size: 0.9rem;
      margin: 1.5rem 0;
      overflow-x: auto;
    }
    .terminal .prompt {
      color: #58a6ff;
    }
    .terminal .output {
      color: #f0e6d0;
      white-space: pre-wrap;
      word-break: break-word;
    }
    .terminal .output .line {
      display: block;
    }
    .terminal .output .key {
      color: #f0883e;
    }
    .terminal .output .value {
      color: #79c0ff;
    }
    .code-block {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 8px;
      padding: 1.2rem 1.5rem;
      margin: 1.5rem 0;
      font-family: 'JetBrains Mono', 'Fira Code', monospace;
      font-size: 0.9rem;
      overflow-x: auto;
    }
    .code-block .comment {
      color: #8b949e;
    }
    .code-block .keyword {
      color: #ff7b72;
    }
    .code-block .string {
      color: #a5d6ff;
    }
    .code-block .bracket {
      color: #ffa657;
    }
    .color-palette {
      display: flex;
      justify-content: center;
      gap: 0.6rem;
      margin: 1.8rem 0 1.2rem;
      flex-wrap: wrap;
    }
    .color-palette span {
      display: inline-block;
      width: 28px;
      height: 28px;
      border-radius: 50%;
      border: 1px solid #30363d;
    }
    .footer-phrase {
      text-align: center;
      color: #8b949e;
      font-style: italic;
      font-size: 1rem;
      margin-top: 1rem;
      padding-top: 1rem;
      border-top: 1px solid #21262d;
    }
    hr {
      border: 0;
      height: 1px;
      background: #21262d;
      margin: 1.8rem 0;
    }
    a {
      color: #58a6ff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    /* Responsivo */
    @media (max-width: 600px) {
      body { padding: 1rem; }
      .terminal, .code-block { font-size: 0.75rem; padding: 0.8rem; }
    }
  </style>
</head>
<body>

  <!-- Citação com alerta -->
  <div class="note">
    <strong>NOTE</strong>
    <blockquote>
      "O computador faz o que você manda, não o que você quer."
      <cite>― Samuel Silva</cite>
    </blockquote>
  </div>

  <hr>

  <!-- Bloco neofetch estilizado -->
  <div class="terminal">
    <div><span class="prompt">></span> neofetch</div>
    <div class="output">
      <span class="line"><span class="key">samuelsilva@github</span></span>
      <span class="line">-------------------</span>
      <span class="line"><span class="key">OS</span>:           <span class="value">Linux (Ubuntu/Mint)</span></span>
      <span class="line"><span class="key">Shell</span>:        <span class="value">bash 5.0</span></span>
      <span class="line"><span class="key">Focus</span>:        <span class="value">Mobile (React Native)</span></span>
      <span class="line"><span class="key">Stack</span>:        <span class="value">Java, Spring Boot, Node.js, Angular</span></span>
      <span class="line"><span class="key">Databases</span>:    <span class="value">MySQL, NoSQL</span></span>
      <span class="line"><span class="key">Tools</span>:        <span class="value">Git, GitHub, Linux</span></span>
      <span class="line"><span class="key">Philosophy</span>:   <span class="value">menos ruído, mais código</span></span>
    </div>
  </div>

  <hr>

  <!-- Bloco JavaScript (const samuel) -->
  <div class="code-block">
    <span class="keyword">const</span> <span style="color:#ffa657;">samuel</span> <span class="bracket">=</span> <span class="bracket">{</span><br>
    &nbsp;&nbsp;<span style="color:#ffa657;">code</span>: <span class="bracket">[</span><span class="string">"Java"</span>, <span class="string">"JavaScript"</span>, <span class="string">"TypeScript"</span><span class="bracket">]</span>,<br>
    &nbsp;&nbsp;<span style="color:#ffa657;">frameworks</span>: <span class="bracket">[</span><span class="string">"Spring Boot"</span>, <span class="string">"Angular"</span>, <span class="string">"React Native"</span><span class="bracket">]</span>,<br>
    &nbsp;&nbsp;<span style="color:#ffa657;">databases</span>: <span class="bracket">[</span><span class="string">"MySQL"</span>, <span class="string">"NoSQL"</span><span class="bracket">]</span>,<br>
    &nbsp;&nbsp;<span style="color:#ffa657;">tools</span>: <span class="bracket">[</span><span class="string">"Git"</span>, <span class="string">"Linux"</span><span class="bracket">]</span>,<br>
    &nbsp;&nbsp;<span style="color:#ffa657;">learning</span>: <span class="string">"mobile com React Native"</span><br>
    <span class="bracket">}</span><span style="color:#ffa657;">;</span>
  </div>

  <!-- Paleta de cores minimalista -->
  <div class="color-palette">
    <span style="background:#fbedf6;"></span>
    <span style="background:#c9594d;"></span>
    <span style="background:#f8b9b2;"></span>
    <span style="background:#ae9c9d;"></span>
    <span style="background:#474342;"></span>
  </div>

  <!-- Filosofia -->
  <div class="footer-phrase">
    <em>Ninniku Seishin</em> – paciência, resiliência, foco no que controlo.
  </div>

</body>
</html>
