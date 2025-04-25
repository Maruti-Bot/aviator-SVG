<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aviator Predictor</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      text-align: center;
      padding: 50px;
    }
    .aviator-logo {
      width: 200px;
      height: auto;
      margin-bottom: 20px;
    }
    .prediction {
      font-size: 24px;
      margin-top: 20px;
    }
    .predict-button {
      padding: 10px 20px;
      font-size: 18px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <img src="aviator.svg" alt="Aviator Logo" class="aviator-logo" />
  <h1>Aviator Predictor</h1>
  <button class="predict-button" onclick="generatePrediction()">Predict Next Crash Point</button>
  <div class="prediction" id="predictionResult"></div>

  <script>
    function generatePrediction() {
      // Simple random prediction logic
      const min = 1.0;
      const max = 10.0;
      const prediction = (Math.random() * (max - min) + min).toFixed(2);
      document.getElementById('predictionResult').innerText = `Predicted Crash Point: ${prediction}x`;
    }
  </script>
</body>
</html>
