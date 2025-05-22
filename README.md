<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DarkWeb_Edition</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #121212;
      color: #f0f0f0;
      text-align: center;
      padding: 40px 20px;
    }
    h1 {
      color: #ffffff;
      font-size: 2.5em;
    }
    p {
      font-size: 1.2em;
      color: #cccccc;
      margin: 10px auto 20px;
      max-width: 600px;
    }
    .btn {
      background-color: #1f1f1f;
      color: #fff;
      padding: 12px 24px;
      margin: 15px;
      border: 2px solid #444;
      border-radius: 8px;
      text-decoration: none;
      transition: 0.3s ease;
      display: inline-block;
    }
    .btn:hover {
      background-color: #333;
      border-color: #888;
    }
    .container {
      max-width: 900px;
      margin: auto;
    }
    form {
      margin-top: 30px;
    }
    input, textarea {
      width: 80%;
      max-width: 500px;
      padding: 10px;
      border: none;
      border-radius: 6px;
      margin-bottom: 15px;
      font-size: 1em;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>DarkWeb_Edition</h1>
    <p>Transformando suas ideias em edições únicas, com estilo, identidade e um toque sombrio.</p>
    <p>Capas, fotos personalizadas e artes que marcam presença.</p>
    <a class="btn" href="https://www.instagram.com/darkweb.edition?igsh=YzYzMmZqdnVrNmtv" target="_blank">Me siga no Instagram</a>
    <a class="btn" href="#contato">Solicitar uma edição</a>

    <section id="contato">
      <h2>Solicitar uma Edição</h2>
      <form action="https://formsubmit.co/darkweb.edition@gmail.com" method="POST">
        <input type="text" name="nome" placeholder="Seu nome" required><br>
        <input type="email" name="email" placeholder="Seu email" required><br>
        <textarea name="mensagem" placeholder="Descreva sua ideia..." rows="5" required></textarea><br>
        <button type="submit" class="btn">Enviar pedido</button>
      </form>
    </section>
  </div>
</body>
</html>
