<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Scores & Fixtures</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f9fa;
      margin: 0;
      padding: 0;
    }
    .header {
      font-size: 28px;
      font-weight: bold;
      padding: 20px;
      text-align: center;
    }
    .date-nav {
      display: flex;
      justify-content: center;
      background: #fff;
      padding: 10px;
      border-radius: 10px;
      margin: 0 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .date-nav button {
      border: none;
      background: none;
      padding: 8px 15px;
      margin: 0 5px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 14px;
    }
    .date-nav button.active {
      background: #0056d6;
      color: #fff;
    }
    .fixtures {
      margin: 20px;
    }
    .fixtures h2 {
      font-size: 20px;
      margin-bottom: 10px;
    }
    .match {
      background: #fff;
      border-radius: 10px;
      padding: 15px;
      margin-bottom: 10px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .team {
      font-weight: bold;
    }
    body { margin: 0; font-family: Arial; }
    }
   .navbar {
      display: flex;
      background-color: #f2f2f2;
      overflow-x: auto;
      white-space: nowrap;
    }
     .navbar a {
      display: inline-block;
      color: GoLD;
      padding: 14px 20px;
      text-decoration: none;
    }
    .navbar a:hover {
      background-color: black;
  </style>
</head>
<body>   
  </header><div class="navbar">
    <div class="main navbar"></div> <!-- Hambuger menu -->
    <a href="https://golden-lab-bit.github.io/Labaran-wasanni/">Labaran Wasanni</a>
    <a href="https://golden-lab-bit.github.io/labaran-wasanni-live/">Kai Tsaye(live)</a>
    <a href="https://golden-lab-bit.github.io/labaran-wasanni-fixtures/">Fixtures</a>
  </div>

  <div class="header">Scores & Fixtures</div>
  <div class="date-nav">
    <button>Mon 25</button>
    <button>Yesterday</button>
    <button class="active">Today</button>
    <button>Tomorrow</button>
    <button>Fri 29</button>
  </div>
   <p> 
    <div class="match">
      <div class="team">Everton</div>
      <div class="time">7:45pm</div>
      <div class="team">Mansfield Town</div>
    </div>
    
    <div class="match">
      <div class="team">Oxford United</div>
      <div class="time">7:45pm</div>
      <div class="team">Cambridge United</div>
    </div>

    <div class="match">
      <div class="team">Manchester United</div>
      <div class="time">8:00pm</div>
      <div class="team">Grimsby Town</div>
      
    </div>
  </div>
   </p>
</body>
</html>
