<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Hỏi màu yêu thích</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      height: 100vh;
      align-items: center;
      justify-content: center;
    }
    .box {
      background: white;
      padding: 20px 30px;
      border-radius: 10px;
      text-align: center;
    }
    button {
      margin-top: 15px;
      padding: 8px 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="box">
    <h2>Màu bạn thích là gì?</h2>
    <input type="color" id="color">
    <br>
    <button onclick="showColor()">Gửi</button>
    <p id="result"></p>
  </div>

  <script>
    function showColor() {
      const color = document.getElementById("color").value;
      document.getElementById("result").innerText =
        "Màu bạn chọn là: " + color;
      document.body.style.background = color;
    }
  </script>
</body>
</html>
