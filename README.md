<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Click Game</title>
  <style>
    body { font-family: Arial; text-align: center; margin-top: 50px; }
    #score { font-size: 24px; margin: 20px; }
    button { font-size: 20px; padding: 15px 30px; }
  </style>
</head>
<body>
  <h1>🔥 Click Game 🔥</h1>
  <p id="score">Score: 0</p>
  <button onclick="addScore()">Click Me!</button>

  <script>
    let score = 0;
    function addScore() {
      score++;
      document.getElementById("score").innerText = "Score: " + score;
    }
  </script>
</body>
</html>
