<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>City Health Office</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }

    /* Header */
    .header {
      background-color: #ffd700;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 30px;
    }

    .header img {
      height: 70px;
    }

    .header h1 {
      color: #0046ad;
      margin: 0;
      font-size: 28px;
      font-weight: bold;
    }

    .nav {
      display: flex;
      gap: 20px;
    }

    .nav a {
      text-decoration: none;
      font-weight: bold;
      color: black;
    }

    /* Main layout */
    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 40px;
    }

    .left img {
      width: 100%;
      max-width: 600px;
      border-radius: 10px;
    }

    .right {
      text-align: center;
      flex: 1;
      margin-left: 50px;
    }

    .right h2 {
      color: gray;
      margin-bottom: 30px;
    }

    .role-btn {
      display: block;
      width: 200px;
      margin: 15px auto;
      padding: 12px;
      border: 2px solid #0073e6;
      border-radius: 30px;
      font-size: 16px;
      font-weight: bold;
      color: #0046ad;
      background-color: white;
      cursor: pointer;
      transition: 0.3s;
    }

    .role-btn:hover {
      background-color: #0073e6;
      color: white;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <div class="header">
    <div style="display:flex;align-items:center;gap:15px;">
      <img src="logo.png" alt="Logo">
      <h1>CITY HEALTH OFFICE</h1>
    </div>
    <div class="nav">
      <a href="#">HOME</a>
      <a href="#">ABOUT</a>
      <a href="#">SERVICES</a>
      <a href="#">CONTACT</a>
    </div>
  </div>

  <!-- Content -->
  <div class="container">
    <div class="left">
      <img src="map.png" alt="Map">
    </div>
    <div class="right">
      <h2>Select Your Role</h2>
      <button class="role-btn" onclick="navigate('client.html')">CLIENT</button>
      <button class="role-btn" onclick="navigate('admin.html')">ADMIN</button>
    </div>
  </div>

  <script>
    function navigate(page) {
      window.location.href = page;
    }
  </script>

</body>
</html>
