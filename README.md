<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>نور الإيمان الدولية</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="frame">
    <h1 id="main-name">Prof.Dr.HassanHusseinAli</h1>
  </div>

  <audio id="welcome-voice" src="voice.mp3"></audio>
  <audio id="background-music" src="monamour.mp3" loop></audio>

  <script src="script.js"></script>
</body>
</html>

body {
  background: url('egyptian-pattern.jpg') no-repeat center center fixed;
  background-size: cover;
  font-family: 'Cairo', sans-serif;
  text-align: center;
  padding-top: 20vh;
}

.frame {
  border: 10px double gold;
  padding: 40px;
  width: 70%;
  margin: auto;
  background-color: rgba(255, 255, 255, 0.85);
  border-radius: 25px;
}

#main-name {
  font-size: 3em;
  font-weight: bold;
  animation: colorChange 3s infinite;
}

@keyframes colorChange {
  0% { color: red; }
  33% { color: green; }
  66% { color: orange; }
  100% { color: red; }
}

