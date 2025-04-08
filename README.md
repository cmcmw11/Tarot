<!-- login.html -->
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>เข้าสู่ระบบ</title>
  <link href="https://fonts.googleapis.com/css2?family=Sarabun&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Sarabun', sans-serif;
      background-color: #fff0f5;
      text-align: center;
      padding: 2rem;
    }
    .login-box {
      background: #fff;
      padding: 2rem;
      border-radius: 16px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      width: 300px;
      margin: auto;
    }
    h2 {
      margin-bottom: 1.5rem;
    }
    input[type="text"], input[type="password"] {
      width: 100%;
      padding: 0.5rem;
      border-radius: 8px;
      border: 1px solid #ccc;
      margin-bottom: 1rem;
    }
    button {
      padding: 0.5rem 1.5rem;
      background-color: #66cc66;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <div class="login-box">
    <h2>เข้าสู่ระบบ</h2>
    <input type="text" id="username" placeholder="ชื่อผู้ใช้">
    <input type="password" id="password" placeholder="รหัสผ่าน">
    <button onclick="login()">เข้าสู่ระบบ</button>
  </div>

  <script>
    function login() {
      // คุณสามารถใส่การตรวจสอบการเข้าสู่ระบบที่นี่
      alert("เข้าสู่ระบบสำเร็จ!");
      window.location.href = "index.html"; // ไปหน้า index.html เมื่อเข้าสู่ระบบสำเร็จ
    }
  </script>

</body>
</html>
