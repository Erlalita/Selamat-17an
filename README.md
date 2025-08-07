!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Selamat Ulang Tahun!</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body {
      height: 100%;
      width: 100%;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #ff9a9e, #fad0c4);
      color: #fff;
      overflow: hidden;
    }
    .container {
      height: 100%;
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }
    h1 {
      font-size: 3em;
      animation: fadeIn 2s ease-in;
    }
    p {
      font-size: 1.5em;
      margin-top: 20px;
      animation: fadeIn 3s ease-in;
    }
    .heart {
      font-size: 3em;
      margin-top: 10px;
      animation: pulse 1s infinite;
    }
    img {
      max-width: 90%;
      max-height: 50%;
      margin-top: 30px;
      border-radius: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      animation: fadeIn 4s ease-in;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🎉 Selamat Ulang Tahun, Cintaku! 🎉</h1>
    <div class="heart">❤️</div>
    <p>Hari ini spesial karena kamu hadir di dunia. Terima kasih sudah jadi bagian dari hidupku.</p>
    <p>Semoga selalu bahagia dan terus bersinar ✨</p>
    <img src="FOTO_KAMU_DIA.jpg" alt="Foto Kita">
  </div>
</body>
</html>
