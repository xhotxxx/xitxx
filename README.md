<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>18+ Warning Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #000;
      color: #fff;
      text-align: center;
    }

    /* Popup background */
    #ageWarning {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.9);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      z-index: 9999;
    }

    #ageWarning h1 {
      font-size: 2rem;
      margin-bottom: 10px;
      color: #ff5050;
    }

    #ageWarning p {
      font-size: 1.1rem;
      color: #ccc;
      margin-bottom: 20px;
    }

    #enterBtn {
      background: #ff0000;
      color: #fff;
      border: none;
      padding: 12px 30px;
      font-size: 1.1rem;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    #enterBtn:hover {
      background: #cc0000;
    }

    #mainContent {
      display: none;
      padding: 20px;
    }
  </style>
</head>
<body>

  <!-- 18+ Warning Popup -->
  <div id="ageWarning">
    <h1>18+ Age Restriction</h1>
    <p>This website contains adult content. You must be 18 years or older to enter.</p>
    <button id="enterBtn">I’m 18+ Continue</button>
  </div>

  <!-- Main Page Content -->
  <div id="mainContent">
    <h2>Welcome to the 18+ Content Page</h2>
    <p>All content visible now after age verification.</p>
    <img src="https://i.ibb.co/DDmxpvVD/image.jpg" alt="18+ Image" style="width:100%;max-width:600px;border-radius:10px;">
  </div>

  <script>
    document.getElementById("enterBtn").addEventListener("click", function() {
      // Open your Adsterra link in a new tab
      window.open("https://www.effectivegatecpm.com/r2u4b7w27?key=8f496fa6ff37b5a7148b45c225e7b110", "_blank");
      
      // Hide the warning and show main content
      document.getElementById("ageWarning").style.display = "none";
      document.getElementById("mainContent").style.display = "block";
    });
  </script>

</body>
</html>
