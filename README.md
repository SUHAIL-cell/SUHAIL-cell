- 👋 Hi, I’m @SUHAIL-cell

<!---
SUHAIL-cell/SUHAIL-cell is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pookie Pet Game</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="game-container">
    <h1>Meet Pookie!</h1>
    <div class="pet">
      <img id="pookie" src="https://i.imgur.com/3Ucz4D5.png" alt="Pookie the pet"/>
    </div>
    <div class="stats">
      <p>Happiness: <span id="happiness">50</span></p>
      <p>Energy: <span id="energy">50</span></p>
      <p>Hunger: <span id="hunger">50</span></p>
    </div>
    <div class="buttons">
      <button onclick="feed()">Feed</button>
      <button onclick="play()">Play</button>
      <button onclick="sleep()">Sleep</button>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
