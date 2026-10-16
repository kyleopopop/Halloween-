<!DOCTYPE html>
<html>
<head>
<style>
body {
  background: #000;
  overflow: hidden;
}
.blood-moon {
  width: 150px; height: 150px;
  background: radial-gradient(circle, red 0%, #300 100%);
  border-radius: 50%;
  position: absolute;
  top: 50px; right: 100px;
  box-shadow: 0 0 50px red;
}
.spider {
  width: 30px; height: 30px;
  background: black;
  border-radius: 50%;
  position: absolute;
  top: -50px; left: 50%;
  animation: drop 4s infinite;
}
@keyframes drop {
 0% { top: -50px; }
 50% { top: 300px; }
 100% { top: -50px; }
}
.tombstone {
  position: absolute;
  bottom: 50px; left: 50%;
  transform: translateX(-50%);
  color: gray;
  font-size: 20px;
  font-family: 'Courier New';
}
</style>
</head>
<body>
  <div class="blood-moon"></div>
  <div class="spider">🕷️</div>
  <div class="tombstone">RIP [Lich]</div>
</body>
</html># Halloween-
a prank link for a friend 
