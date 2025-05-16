<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VN7 - Alta Performance</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0a0f1c;
      color: #f1f1f1;
    }
    header {
      background-color: #121a2f;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      color: #e21b1b;
      font-size: 2.5rem;
      margin: 0;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .btn {
      background-color: #e21b1b;
      color: white;
      padding: 1rem 2rem;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      display: inline-block;
      text-decoration: none;
      margin-top: 1rem;
    }
    .plans {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      gap: 1rem;
      margin-top: 2rem;
    }
    .plan {
      background-color: #1c2233;
      padding: 1rem;
      border-radius: 10px;
      border: 1px solid #333;
      position: relative;
    }
    .plan h3 {
      color: #e21b1b;
      font-size: 1.3rem;
    }
    .price-original {
      text-decoration: line-through;
      color: #888;
      font-size: 0.9rem;
    }
    .price-discount {
      color: #0f0;
      font-size: 1.2rem;
      font-weight: bold;
    }
    .badge {
      background: #e21b1b;
      color: white;
      font-size: 0.8rem;
      padding: 0.2rem 0.5rem;
      border-radius: 5px;
      position: absolute;
      top: 10px;
      right: 10px;
    }
    footer {
      background-color: #121a2f;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #aaa;
    }
    a { color: #e21b1b; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>VN7 Performance</h1>
    <p>Alta Performance. Resultado Real.</p>
  </header>

  <section>
    <h2>Transforme seu corpo com acompanhamento individualizado</h2>
    <p>
      A VN7 nasceu com o propósito de levar pessoas comuns a alcançarem resultados extraordinários. Treinos personalizados, avaliação física com tecnologia e suporte completo.
    </p>

    <h2>Avaliações físicas</h2>
    <ul>
      <li><strong>Bioimpedância:</strong> Composição corporal em detalhes</li>
      <li><strong>Teste de PR:</strong> Força máxima nos principais exercícios</li>
    </ul>

    <h2>Planos <span style="color:#0f0">(promoção por tempo limitado!)</span></h2>
    <div class="plans">
      <div class="plan">
        <div class="badge">-20%</div>
        <h3>Mensal</h3>
        <p class="price-original">De R$249,99</p>
        <p class="price-discount">Por R$199,99</p>
        <ul>
          <li>4 treinos personalizados</li>
          <li>1 avaliação física</li>
        </ul>
      </div>
      <div class="plan">
        <div class="badge">-30%</div>
        <h3>Trimestral</h3>
        <p class="price-original">De R$799,99</p>
        <p class="price-discount">Por R$549,99</p>
        <ul>
          <li>12 treinos + 2 avaliações</li>
          <li>Suporte completo</li>
        </ul>
      </div>
      <div class="plan">
        <div class="badge">-40%</div>
        <h3>Semestral</h3>
        <p class="price-original">De R$1.699,99</p>
        <p class="price-discount">Por R$999,99</p>
        <ul>
          <li>24 treinos + 4 avaliações</li>
          <li>Camiseta exclusiva VN7</li>
        </ul>
      </div>
    </div>

    <a href="#" class="btn">Quero Começar Agora</a>
  </section>

  <section>
    <h2>Contato</h2>
    <p>📞 WhatsApp: <a href="https://wa.me/5511959924799" target="_blank">+55 11 95992-4799</a></p>
    <p>📸 Instagram: <a href="https://instagram.com/Vini_hayashi" target="_blank">@Vini_hayashi</a></p>
  </section>

  <footer>
    © 2025 VN7 Performance. Todos os direitos reservados.
  </footer>
</body>
</html>
