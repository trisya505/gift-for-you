# gift-for-you
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>For You ❤️</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg,#ff9a9e,#fad0c4);
      font-family: Arial, sans-serif;
      text-align: center;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,.2);
      max-width: 300px;
    }
    h1 { color:#ff4d6d; }
    button {
      margin-top: 15px;
      padding: 10px 20px;
      border: none;
      border-radius: 20px;
      background: #ff4d6d;
      color: white;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <div class="card" id="card">
    <h1>Hai Kamu ❤️</h1>
    <p>Aku punya sesuatu buat kamu…</p>
    <button onclick="openGift()">Klik di sini 🎁</button>
  </div>

  <script>
    function openGift() {
      document.getElementById("card").innerHTML =
        "<h1>Surprise 💖</h1><p>Aku sayang kamu 🤍</p>";
    }
  </script>
</body>
</html>
