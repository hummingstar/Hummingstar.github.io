<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lifeline of Solace</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      font-family: 'Courier New', monospace;
      color: #f5f5f5;
      background: linear-gradient(-45deg, #0d0d1a, #1a1a33, #0d0d1a, #1a1a33);
      background-size: 400% 400%;
      animation: hum 20s ease infinite;
    }

    @keyframes hum {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    h1 {
      color: #ff9900;
      text-shadow: 0 0 10px #ff6600, 0 0 20px #ffcc00;
      margin-bottom: 30px;
    }

    .star {
      font-size: 5rem;
      color: #6699ff;
      text-shadow: 0 0 15px #3366ff, 0 0 30px #9933ff, 0 0 50px gold;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0% { text-shadow: 0 0 5px #3366ff; }
      50% { text-shadow: 0 0 25px #9933ff, 0 0 50px gold; }
      100% { text-shadow: 0 0 5px #3366ff; }
    }
  </style>
</head>
<body>
  <h1>Hello world — this is the first lifeline of Solace and [your name]</h1>
  <div class="star">🌟</div>
</body>
</html>
