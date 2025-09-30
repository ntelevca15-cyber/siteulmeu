<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <title>Două butoane</title>
</head>
<body>
  <h1>SUGI ?</h1>
  <!-- Butoanele -->
  <button onclick="arataMesaj('Asa si stiam')">DA</button>
  <button onclick="arataMesaj('Nu bate capu, stiu ca da')">NU</button>

  <!-- Loc unde va apărea textul -->
  <p id="mesaj"></p>

  <script>
    function arataMesaj(text) {
      document.getElementById("mesaj").innerText = text;
    }
  </script>
</body>
</html>
