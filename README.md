<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CIBERESTRELAS — README</title>
  <style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin: 28px; color:#111; line-height:1.5; background:#f7fafc; }
    .container { max-width:900px; margin:0 auto; background:#fff; padding:28px; border-radius:12px; box-shadow:0 8px 24px rgba(13,38,59,0.08); }
    header h1 { margin:0; font-size:28px; }
    .badges img { height:20px; margin-right:8px; vertical-align:middle; }
    hr { border:0; height:1px; background:#e6eef6; margin:18px 0; }
    h2 { font-size:18px; margin-top:18px; }
    pre { background:#0f1724; color:#e6eef6; padding:12px; border-radius:8px; overflow:auto; }
    code { background:#eef6ff; padding:2px 6px; border-radius:4px; font-family:monospace; }
    table { border-collapse:collapse; width:100%; margin-top:8px; }
    table th, table td { text-align:left; padding:8px; border-bottom:1px solid #f1f7fb; }
    .sidebar { float:right; width:220px; margin-left:18px; text-align:center; }
    .cover { max-width:200px; border-radius:8px; box-shadow:0 6px 18px rgba(13,38,59,0.08); }
    footer { font-size:13px; color:#5b6b7a; margin-top:20px; }
    .btn { display:inline-block; padding:10px 14px; background:#0b70ff; color:#fff; border-radius:8px; text-decoration:none; margin-top:8px; }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div style="display:flex; align-items:center; gap:18px; justify-content:space-between;">
        <div>
          <h1>📘 CIBERESTRELAS: Manual de Defesa no Campo de Batalha Digital</h1>
          <div class="badges" style="margin-top:8px;">
            <img src="https://img.shields.io/badge/status-ativo-brightgreen" alt="Status">
            <img src="https://img.shields.io/badge/categoria-cibersegurança-blue" alt="Categoria">
            <img src="https://img.shields.io/badge/license-MIT-lightgrey" alt="License">
          </div>
        </div>
        <div class="sidebar" aria-hidden="true">
          <!-- Se houver cover.png no repo, ela será exibida aqui -->
          <img src="cover.png" alt="Capa do ebook" class="cover" onerror="this.style.display='none'">
          <div style="margin-top:12px;">
            <a class="btn" href="#conteudo">Ver Conteúdo</a>
          </div>
        </div>
      </div>
    </header>

    <hr>

    <section id="sobre">
      <h2>🚀 Sobre o Projeto</h2>
      <p><strong>CIBERESTRELAS</strong> é um ebook voltado para iniciantes em <strong>Segurança da Informação</strong>. O material é didático, com exemplos em Linux e linguagem acessível. A temática é inspirada em ficção espacial e foi produzido com apoio de inteligência artificial para facilitar a compreensão.</p>
      <p><em>O conhecimento é o melhor escudo da galáxia digital.</em></p>
    </section>

    <section id="conteudo">
      <h2>📚 Conteúdo do Ebook</h2>
      <p>O ebook inclui:</p>
      <table>
        <thead>
          <tr><th>Capítulo</th><th>Tema</th></tr>
        </thead>
        <tbody>
          <tr><td>1</td><td>Phishing</td></tr>
          <tr><td>2</td><td>Engenharia Social</td></tr>
          <tr><td>3</td><td>Força Bruta</td></tr>
          <tr><td>4</td><td>Malware</td></tr>
          <tr><td>5</td><td>Wi-Fi e Dispositivos Conectados</td></tr>
        </tbody>
      </table>

      <p>Extras: exemplos práticos com comandos Linux, checklist de segurança, agradecimentos e aviso legal.</p>
    </section>

    <section id="estrutura">
      <h2>🧩 Estrutura do Repositório</h2>
      <pre><code>ciberestrelas_repo/
├─ README.html        # este arquivo (HTML)
├─ README.md          # versão Markdown opcional
├─ ebook.md           # conteúdo completo do ebook
├─ cover.png          # imagem de capa (opcional)
├─ LICENSE            # Licença MIT
├─ .gitignore         # arquivos ignorados no git
└─ create_repo.sh     # script com instruções para iniciar repo local
</code></pre>
    </section>

    <section id="avisos">
      <h2>🛑 Aviso Importante</h2>
      <p>Este material <strong>não</strong> incentiva atividades maliciosas. Todo conteúdo deve ser utilizado de forma <strong>ética e legal</strong>. O objetivo é conscientização e aprendizado.</p>
    </section>

    <section id="instalar">
      <h2>🛠 Como subir para o GitHub</h2>
      <p>Crie um repositório vazio no GitHub e, no terminal do seu projeto local, rode:</p>
      <pre><code>git init
git add .
git commit -m "Initial commit — CIBERESTRELAS ebook"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
git push -u origin main
</code></pre>
      <p>Substitua <code>SEU_USUARIO/NOME_DO_REPO</code> pelo seu repositório no GitHub.</p>
    </section>

    <section id="contribuir">
      <h2>📫 Contribuindo</h2>
      <p>Contribuições são bem-vindas! Abra uma <strong>Issue</strong> ou envie um <strong>Pull Request</strong>. Siga boas práticas: descreva a mudança, escreva testes se necessário e mantenha o foco educacional do projeto.</p>
    </section>

    <section id="licenca">
      <h2>📄 Licença</h2>
      <p>Distribuído sob a licença <strong>MIT</strong>. Veja o arquivo <code>LICENSE</code> para mais detalhes.</p>
    </section>

    <section id="agradecimento">
      <h2>🙌 Agradecimento</h2>
      <p>Obrigado por embarcar nessa jornada pela segurança da informação! Este conteúdo foi produzido com fins <strong>didáticos</strong> e com apoio de <strong>inteligência artificial</strong>. Que a força das Ciberestrelas esteja com você! 🚀🔐</p>
    </section>

    <footer>
      <hr>
      <p>Se desejar, posso gerar também o PDF final do ebook, criar a landing page para divulgação ou preparar o upload automático para o GitHub. Basta pedir!</p>
    </footer>
  </div>
</body>
</html>
