<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🦎 Gecko-Car 🚗</title>
  <link rel="icon" href="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" />
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #1c1c1e;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      text-align: center;
    }

    h1 {
      margin-top: 30px;
      font-size: 2.5rem;
    }

    p {
      font-size: 1.2rem;
    }

    .gif {
      margin: 20px auto;
    }

    .games {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 40px;
      gap: 20px;
    }

    .game-card {
      background-color: #2a2a2d;
      padding: 20px;
      border-radius: 12px;
      width: 200px;
      transition: 0.3s;
    }

    .game-card:hover {
      transform: scale(1.05);
      background-color: #343437;
    }

    .game-card a {
      color: #4ade80;
      text-decoration: none;
      font-weight: bold;
    }

    .footer {
      margin-top: 50px;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>

  <h1>🦎 Gecko-Car 🚗</h1>

  <div class="gif">
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="120"/>
  </div>

  <p><b>Juegos educativos y de entretenimiento para momentos libres.</b></p>

  <div class="games">
    <div class="game-card">
      <p>📘 Run 3</p>
      <a href="https://example.com/run3" target="_blank">Jugar</a>
    </div>
    <div class="game-card">
      <p>🏀 Basket Random</p>
      <a href="https://example.com/basket" target="_blank">Jugar</a>
    </div>
    <div class="game-card">
      <p>🧱 2048</p>
      <a href="https://example.com/2048" target="_blank">Jugar</a>
    </div>
    <!-- You can copy this block to add more games -->
  </div>

  <div class="footer">
    hecho con 💚 por Gecko
  </div>

</body>
</html>
