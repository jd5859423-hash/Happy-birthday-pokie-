<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy World Alice Day</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }.card {
  background: white;
  width: 350px;
  padding: 20px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 10px 25px rgba(0,0,0,0.2);
  position: relative;
  overflow: hidden;
}

h1 {
  color: #ff4081;
  font-size: 22px;
  margin-bottom: 20px;
}

.balloon {
  width: 40px;
  height: 55px;
  background: red;
  border-radius: 50%;
  position: absolute;
  animation: float 4s infinite ease-in-out;
}

.balloon::after {
  content: '';
  width: 2px;
  height: 30px;
  background: #555;
  position: absolute;
  bottom: -30px;
  left: 50%;
}

.balloon:nth-child(1) { left: 20px; top: 250px; background: #ff4d4d; animation-delay: 0s; }
.balloon:nth-child(2) { right: 20px; top: 250px; background: #4da6ff; animation-delay: 1s; }
.balloon:nth-child(3) { left: 150px; top: 260px; background: #66ff66; animation-delay: 2s; }

@keyframes float {
  0% { transform: translateY(0); }
  50% { transform: translateY(-30px); }
  100% { transform: translateY(0); }
}

.flowers {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  display: flex;
  justify-content: space-around;
}

.flower {
  font-size: 24px;
}

.message {
  font-size: 16px;
  color: #555;
  margin-top: 10px;
}

  </style>
</head>
<body>  <div class="card">
    <h1>🎉 Happy World Alice Day 🎂</h1>
    <div class="message">Wishing you joy, love, and happiness!</div><!-- Balloons -->
<div class="balloon"></div>
<div class="balloon"></div>
<div class="balloon"></div>

<!-- Flowers -->
<div class="flowers">
  <div class="flower">🌸</div>
  <div class="flower">🌼</div>
  <div class="flower">🌺</div>
  <div class="flower">🌻</div>
</div>

  </div></body>
</html>
