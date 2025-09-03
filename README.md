<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MakeMaster - Palpites Esportivos</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
    }
    header {
      background: #000;
      color: #FFD700;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    header p {
      margin: 5px 0 0;
      font-size: 16px;
    }
    nav {
      margin-top: 10px;
    }
    nav button {
      margin: 5px;
      padding: 8px 15px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
    }
    .pt { background: #FFD700; color: #000; }
    .en { background: #DC143C; color: #fff; }

    .container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: #1c1c1c;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 0 8px rgba(255, 0, 0, 0.5);
    }
    .card h2 {
      margin-top: 0;
      color: #FFD700;
    }
    .palpite {
      background: #333;
      padding: 10px;
      border-radius: 8px;
      margin-bottom: 10px;
    }
    .palpite input {
      width: 100%;
      padding: 8px;
      border: none;
      border-radius: 5px;
      margin-top: 5px;
    }
    .historico {
      text-align: center;
      margin-top: 10px;
    }
    .historico a {
      color: #DC143C;
      font-weight: bold;
      text-decoration: none;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
      font-size: 14px;
      color: #FFD700;
    }
  </style>
</head>
<body>
  <header>
    <h1>🎯 MakeMaster</h1>
    <p>Os melhores palpites de Futebol, Basquetebol e Tênis!</p>
    <nav>
      <button class="pt">Português 🇧🇷</button>
      <button class="en">English 🇺🇸</button>
    </nav>
  </header>

  <div class="container">
    <!-- Futebol -->
    <div class="card">
      <h2>⚽ Futebol</h2>
      <div class="palpite">
        <label>Data:</label>
        <input type="text" placeholder="dd/mm/aaaa">
        <label>Palpite 1:</label>
        <input type="text" placeholder="Time A x Time B - Hora">
        <label>Palpite 2:</label>
        <input type="text" placeholder="Time A x Time B - Hora">
        <label>Palpite 3:</label>
        <input type="text" placeholder="Time A x Time B - Hora">
      </div>
      <div class="historico">
        <a href="#">📜 Ver histórico</a>
      </div>
    </div>

    <!-- Basquetebol -->
    <div class="card">
      <h2>🏀 Basquetebol</h2>
      <div class="palpite">
        <label>Data:</label>
        <input type="text" placeholder="dd/mm/aaaa">
        <label>Palpite 1:</label>
        <input type="text" placeholder="Time A x Time B - Hora">
        <label>Palpite 2:</label>
        <input type="text" placeholder="Time A x Time B - Hora">
      </div>
      <div class="historico">
        <a href="#">📜 Ver histórico</a>
      </div>
    </div>

    <!-- Tênis -->
    <div class="card">
      <h2>🎾 Tênis</h2>
      <div class="palpite">
        <label>Data:</label>
        <input type="text" placeholder="dd/mm/aaaa">
        <label>Palpite 1:</label>
        <input type="text" placeholder="Jogador A x Jogador B - Hora">
        <label>Palpite 2:</label>
        <input type="text" placeholder="Jogador A x Jogador B - Hora">
      </div>
      <div class="historico">
        <a href="#">📜 Ver histórico</a>
      </div>
    </div>
  </div>

  <footer>
    © 2025 MakeMaster - Todos os direitos reservados
  </footer>
</body>
</html>
