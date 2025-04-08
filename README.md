<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>ยินดีต้อนรับสู่โลกเวทมนต์ Creme Tarot</title>
  <link href="https://fonts.googleapis.com/css2?family=Sarabun&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Sarabun', sans-serif;
      background-color: #FFCCCC;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    .container {
      padding: 20px;
      border-radius: 15px;
      background-color: #ffffff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      margin-top: 50px;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }
    h1 {
      color: #FF3399;
    }
    p {
      font-size: 20px;
      color: #333;
    }
    a {
      background-color: #FF3399;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 8px;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>ยินดีต้อนรับสู่โลกเวทมนต์ Creme Tarot</h1>
    <p>สวัสดีค่ะ! 🌸🌟 ยินดีต้อนรับสู่เว็บดูดวงและโลกเวทมนต์ Creme Tarot ✨ ที่นี่คุณจะได้พบกับการทำนายจากไพ่ทาโรต์ในรูปแบบที่น่าตื่นเต้น! 💖💫</p>
    <a href="login.html">เข้าสู่ระบบ</a>
  </div>

  <script>
    // ตรวจสอบสถานะการเข้าสู่ระบบ
    if (localStorage.getItem("loggedIn") || sessionStorage.getItem("loggedIn")) {
        // ถ้าเข้าสู่ระบบแล้ว ให้ไปที่หน้า home/index.html
        setTimeout(function() {
            window.location.href = 'home/index.html';
        }, 2000); // รอ 2 วินาที
    } else {
        // ถ้ายังไม่ได้เข้าสู่ระบบ ให้ไปที่หน้า home/login.html
        setTimeout(function() {
            window.location.href = 'home/login.html';
        }, 2000); // รอ 2 วินาที
    }
  </script>
</body>
</html>
