# ยินดีต้อนรับสู่โลกเวทมนต์ Creme Tarot 🧙‍♀️✨

สวัสดีค่ะ! 🌸🌟 ยินดีต้อนรับสู่เว็บดูดวงและโลกเวทมนต์ Creme Tarot ✨ ที่นี่คุณจะได้พบกับการทำนายจากไพ่ทาโรต์ในรูปแบบที่น่าตื่นเต้น! 💖💫

<div style="text-align: center; background-color: #FFCCCC; border-radius: 15px; padding: 20px; margin-top: 20px; font-family: 'Sarabun', sans-serif; color: #333; font-size: 20px;">
    🌟 สวัสดีค่ะ! ยินดีต้อนรับสู่โลกเวทมนต์ Creme Tarot 🌟<br><br>
    🎴 คุณพร้อมที่จะเริ่มการทำนายแล้วหรือยัง? <br>
    รอโหลดหน้า 2 วินาทีแล้วคลิกที่ปุ่มเข้าสู่ระบบเพื่อเริ่มต้นการเดินทาง! 🧭<br><br>
    <a href="login.html" style="background-color: #FF3399; color: white; padding: 12px 25px; text-decoration: none; border-radius: 8px; font-size: 18px;">เข้าสู่ระบบ</a>
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
