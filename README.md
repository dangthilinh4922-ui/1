#<!DOCTYPE html>
<html>
<head>
  <title>Security Alert</title>
  <meta charset="UTF-8">
</head>

<body style="background:black;color:red;text-align:center;font-family:Arial;">

  <h1>⚠️ Tài khoản của bạn đã bị mã hóa!</h1>
  <p>Nhấn OK để xử lý ngay lập tức</p>

  <button onclick="handleClick()" style="padding:15px 30px;font-size:20px;">
    OK
  </button>

  <script>
    function handleClick() {
      alert("💀 Tài khoản của bạn đã bị xóa!");
    }

    // Nếu không bấm thì 5 giây sau troll
    setTimeout(function(){
      alert("😂 Bạn đã bị troll rồi!");
    }, 5000);
  </script>

</body>
</html>
