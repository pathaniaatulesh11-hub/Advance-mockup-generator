<!DOCTYPE html>
<html>
<head>
  <title>Advanced Mockup Generator</title>
  <link rel="stylesheet" href="style.css">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/fabric.js/5.3.0/fabric.min.js"></script>
</head>
<body>

<h2>Advanced Mockup Tool</h2>

<input type="file" id="upload" />

<select id="templateSelect">
  <option value="street_front.png">Street Front</option>
  <option value="street_back.png">Street Back</option>
  <option value="studio_front.png">Studio Front</option>
</select>

<select id="shirtColor">
  <option value="#000000">Black</option>
  <option value="#ffffff">White</option>
  <option value="#2f2f2f">Dark Grey</option>
</select>

<br><br>

<canvas id="canvas" width="600" height="700"></canvas>

<br><br>

<button onclick="downloadImage()">Download HD</button>

<script src="script.js"></script>
</body>
</html>
