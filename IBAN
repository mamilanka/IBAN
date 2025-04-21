
Zafder Caddesi No : 56 GÜRSU BURSA Tel : 05363951767
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Banka Bilgileri</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      padding: 40px;
      text-align: center;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 20px;
      margin: 20px auto;
      max-width: 500px;
      text-align: left;
    }
    .info {
      margin-bottom: 15px;
    }
    .copy-btn {
      background: #007bff;
      color: white;
      border: none;
      padding: 8px 12px;
      border-radius: 6px;
      cursor: pointer;
      margin-left: 10px;
    }
    .copy-btn:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>

  <h1>Banka Bilgileri</h1>

  <div class="card">
    <div class="info">
      <strong>Ahmet Sılacı</strong><br>
      Ziraat Bankası<br>
      <span id="ziraatIban">TR44 0001 0005 0613 5293 5850 01</span>
      <button class="copy-btn" onclick="copyToClipboard('ziraatIban')">Kopyala</button>
    </div>
    <div class="info">
      <strong>Ahmet Sılacı</strong><br>
      Halk Bankası<br>
      <span id="halkIban">TR700001200123100009102148</span>
      <button class="copy-btn" onclick="copyToClipboard('halkIban')">Kopyala</button>
    </div>
  </div>

  <script>
    function copyToClipboard(elementId) {
      const text = document.getElementById(elementId).textContent;
      navigator.clipboard.writeText(text).then(() => {
        alert("IBAN başarıyla kopyalandı!");
      });
    }
  </script>

</body>
</html>
