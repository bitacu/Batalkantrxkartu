<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Bloker Kartu Kredit/Debit</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }
    .card-blocker {
      max-width: 350px;
      margin: 100px auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 24px rgba(0,0,0,0.10);
      padding: 30px;
    }
    .card-blocker h2 {
      margin-bottom: 20px;
      text-align: center;
    }
    .input-group {
      margin-bottom: 18px;
    }
    .input-group label {
      display: block;
      font-size: 14px;
      margin-bottom: 5px;
    }
    .input-group input {
      width: 100%;
      padding: 8px 10px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .submit-btn {
      width: 100%;
      padding: 10px 0;
      background: #007bff;
      color: #fff;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
      margin-top: 10px;
    }
    .submit-btn:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="card-blocker">
    <h2>Input Kartu Kredit/Debit</h2>
    <form>
      <div class="input-group">
        <label for="card-number">Nomor Kartu</label>
        <input type="text" id="card-number" maxlength="19" placeholder="1234 5678 9012 3456" required>
      </div>
      <div class="input-group">
        <label for="expiry">Kadaluarsa</label>
        <input type="text" id="expiry" maxlength="5" placeholder="MM/YY" required>
      </div>
      <div class="input-group">
        <label for="cvv">CVV</label>
        <input type="password" id="cvv" maxlength="4" placeholder="123" required>
      </div>
      <button type="submit" class="submit-btn">Kirim</button>
    </form>
  </div>
</body>
</html>
