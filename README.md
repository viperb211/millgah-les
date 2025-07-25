<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Diagnosis Button</title>
  <style>
    body, html {
      height: 100%;
      margin: 0;
      padding: 0;
    }
    .center-container {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .diagnosis-btn {
      background: none;
      border: none;
      color: #333;
      font-size: 2rem;
      cursor: pointer;
      padding: 0.5em 1em;
      font-weight: bold;
    }
    .diagnosis-btn:focus {
      outline: 2px solid #007BFF;
    }
  </style>
</head>
<body>
  <div class="center-container">
    <button class="diagnosis-btn" onclick="diagnoseErrors()">diagnosis no fake</button>
  </div>
  <script>
    function diagnoseErrors() {
      // Your diagnosis logic here
      alert('Diagnosing errors...');
    }
  </script>
</body>
</html>
