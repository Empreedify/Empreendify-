# Empreendify-<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Empreendify</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #bbb, #e0e0e0);
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #222;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      margin: 0 10px;
      color: #333;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      padding: 60px 20px;
      text-align: center;
      background-color: #fff;
    }
    .hero h2 {
      color: #444;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2em;
      max-width: 700px;
      margin: 0 auto;
    }
    .benefits {
      background: #eee;
      padding: 40px 20px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .benefit {
      background: #fff;
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 20px;
      max-width: 250px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    .cta {
      text-align: center;
      padding: 40px 20px;
    }
    .cta button {
      background: #444;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1em;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #ccc;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Empreendify</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#beneficios">Benefícios</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero" id="sobre">
    <h2>Organize sua empresa com Eficiência</h2>
    <p>A Empreendify oferece soluções inteligentes para organizar processos, melhorar a produtividade e transformar sua gestão empresarial em algo realmente eficiente.</p>
  </section>

  <section class="benefits" id="beneficios">
    <div class="benefit">
      <h3>Consultoria Personalizada</h3>
      <p>Diagnósticos feitos sob medida para a necessidade de cada empresa.</p>
    </div>
    <div class="benefit">
      <h3>Automatização de Processos</h3>
      <p>Implementação de ferramentas digitais para ganho de tempo e redução de erros.</p>
    </div>
    <div class="benefit">
      <h3>Treinamentos Empresariais</h3>
      <p>Capacitação para equipes com foco em produtividade e organização.</p>
    </div>
  </section>

  <section class="cta" id="contato">
    <h2>Quer transformar sua empresa?</h2>
    <button onclick="alert('Vamos conversar em breve!')">Fale conosco</button>
  </section>

  <footer>
    &copy; 2025 Empreendify. Todos os direitos reservados.
  </footer>
</body>
</html>
