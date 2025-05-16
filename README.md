<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Đăng Ký Tư Vấn</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f4f7;
    }
    .form-container {
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      max-width: 500px;
      width: 100%;
    }
    .form-header {
      text-align: center;
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 20px;
    }
    .form-input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .form-btn {
      width: 100%;
      padding: 12px;
      background-color: #ff7b00;
      border: none;
      color: white;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
    }
    .form-btn:hover {
      background-color: #e67300;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <div class="form-header">Đăng Ký Tư Vấn</div>
    <form>
      <input class="form-input" type="text" placeholder="Tên của bạn" required>
      <input class="form-input" type="email" placeholder="Email" required>
      <input class="form-input" type="text" placeholder="Số điện thoại" required>
      <select class="form-input">
        <option value="">Chọn khóa học quan tâm</option>
        <option value="digital-marketing">Digital Marketing</option>
        <option value="web-design">Thiết kế Web</option>
        <option value="seo">SEO</option>
      </select>
      <input class="form-input" type="text" placeholder="Trình độ học vấn" required>
      <input class="form-input" type="text" placeholder="Check Spam: Thủ đô của nước ta là?" required>
      <button class="form-btn" type="submit">Đăng ký tư vấn</button>
    </form>
  </div>
</body>
</html>
