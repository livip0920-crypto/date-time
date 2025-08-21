# date-time
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Show Date and Time</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 40px;
      text-align: center;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
    #datetime {
      margin-top: 20px;
      font-size: 18px;
      color: #333;
    }
  </style>
</head>
<body>

  <h1>Date and Time Display</h1>
  <button onclick="showDateTime()">Show Date and Time</button>
  <div id="datetime"></div>

  <script>
    function showDateTime() {
      const now = new Date();
      const dateTimeString = now.toLocaleString();
      document.getElementById('datetime').textContent = dateTimeString;
    }
  </script>

</body>
</html>
