<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Esteban González Osso | Portfolio</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.5; }
    .wrap { max-width: 900px; margin: 0 auto; padding: 28px 18px; }
    h1 { margin: 0 0 6px; font-size: 28px; }
    h2 { margin: 18px 0 8px; font-size: 18px; }
    .tag { font-weight: 600; margin: 0 0 14px; }
    .grid { display: grid; grid-template-columns: 1fr; gap: 6px; }
    .item a { color: #0b5fff; text-decoration: none; }
    .item a:hover { text-decoration: underline; }
    .card { border: 1px solid #e5e5e5; border-radius: 10px; padding: 16px; }
    footer { margin-top: 18px; font-size: 12px; color: #666; }
    @media (min-width: 720px) {
      .grid { grid-template-columns: 1fr 1fr; gap: 10px; }
    }
  </style>
</head>
<body>
  <main class="wrap">
    <section class="card">
      <h1>ESTEBAN GONZÁLEZ OSSO</h1>
      <p class="tag">Business Intelligence Analyst | Data Analysis</p>

      <div class="grid">
        <div class="item">📞 <a href="tel:+573222350974">+57 322 235 0974</a></div>
        <div class="item">📧 <a href="mailto:esteban0sso@outlook.com">esteban0sso@outlook.com</a></div>
        <div class="item">💼 <a href="https://www.linkedin.com/in/esteban0sso/" target="_blank" rel="noopener">LinkedIn: esteban0sso</a></div>
        <div class="item">🌐 <a href="#" target="_blank" rel="noopener">Portfolio and Website</a></div>
      </div>

      <h2>About</h2>
      <p>
        Analyst with over 3 years of experience in finance, projects, and process optimization.
        I specialize in transforming data into strategic decisions that help companies reduce costs,
        optimize time, profile customers, and improve profitability.
      </p>
      <p>
        My differentiator is that I do not limit myself to technical analysis; I understand the business behind the data.
        I identify strengths and areas for improvement, using data to enhance what already works and correct what limits your company’s growth.
      </p>
    </section>

    <footer>
      © <span id="y"></span> Esteban González Osso
    </footer>
  </main>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>
