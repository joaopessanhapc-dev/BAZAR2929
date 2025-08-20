<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Minha Loja Amazon</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background: #f3f4f6;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #232f3e, #37475a);
      color: white;
      text-align: center;
      padding: 50px 20px;
    }
    header h1 {
      font-size: 36px;
      margin-bottom: 10px;
      letter-spacing: 1px;
    }
    header p {
      font-size: 18px;
      opacity: 0.9;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .produto {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .produto:hover {
      transform: translateY(-8px);
      box-shadow: 0 6px 20px rgba(0,0,0,0.15);
    }
    .produto img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .produto .info {
      padding: 20px;
      text-align: center;
    }
    .produto h3 {
      font-size: 20px;
      margin-bottom: 10px;
      color: #222;
    }
    .produto p {
      font-size: 14px;
      color: #555;
      margin-bottom: 15px;
    }

    .btn {
      display: inline-block;
      background: #ff9900;
      color: white;
      padding: 12px 22px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.2s ease;
    }
    .btn:hover { background: #e68a00; }

    footer {
      text-align: center;
      background: #232f3e;
      color: white;
      padding: 20px;
      margin-top: 40px;
      font-size: 14px;
    }
    footer a.btn {
      margin-top: 10px;
      display: inline-block;
    }
  </style>
</head>
<body>
  <header>
    <h1>🌟 Minha Loja Amazon 🌟</h1>
    <p>Produtos selecionados para você com os melhores preços</p>
  </header>

  <div class="container">
    <div class="produto">
      <img src="https://images-na.ssl-images-amazon.com/images/I/71kL9hC0SCL._AC_SL1500_.jpg" alt="Maca Peruana Negra 120 Cápsulas" />
      <div class="info">
        <h3>Maca Peruana Negra – 120 Cápsulas</h3>
        <p>Suplemento natural Snake Dragon, 2000 mg por dose. Fonte de energia, sem glúten.</p>
        <a class="btn" href="https://amzn.to/4lH0Het" target="_blank">Comprar na Amazon</a>
      </div>
    </div>
  </div>

  <footer>
    <p>© 2025 Minha Loja Amazon | Desenvolvido com ❤</p>
    <p>
      <a class="btn" href="https://instagram.com/sualoja" target="_blank">Visite nosso Instagram</a>
    </p>
  </footer>
</body>
</html>
