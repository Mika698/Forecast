<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pluto Dashboard</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f4f6f9;
    }
    .sidebar {
      width: 250px;
      background: #1e2a38;
      height: 100vh;
      color: white;
      position: fixed;
      padding-top: 20px;
    }
    .sidebar h2, .sidebar ul {
      margin: 0;
      padding: 0 20px;
    }
    .sidebar ul {
      list-style-type: none;
    }
    .sidebar ul li {
      padding: 15px 0;
      cursor: pointer;
    }
    .sidebar ul li:hover {
      background: #2a3b4c;
    }
    .topbar {
      margin-left: 250px;
      background: #192533;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 20px;
      color: white;
    }
    .main-content {
      margin-left: 250px;
      padding: 20px;
    }
    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .card {
      flex: 1 1 200px;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .social {
      display: flex;
      gap: 10px;
      margin-top: 20px;
    }
    .social .card {
      flex: 1;
      color: white;
    }
    .facebook { background: #3b5998; }
    .twitter { background: #1da1f2; }
    .linkedin { background: #0077b5; }
    .google { background: #db4437; }
  </style>
</head>
<body>
  <div class="sidebar">
    <div style="text-align:center; padding-bottom: 20px;">
      <img src="https://via.placeholder.com/80" alt="John David" style="border-radius:50%;">
      <h3>John David</h3>
      <p style="color: #4cd137;">● Online</p>
    </div>
    <ul>
      <li>Dashboard</li>
      <li>Widgets</li>
      <li>Elements</li>
      <li>Tables</li>
      <li>Apps</li>
      <li>Pricing Tables</li>
      <li>Contact</li>
      <li>Additional Pages</li>
      <li>Map</li>
      <li>Charts</li>
      <li>Settings</li>
    </ul>
  </div>
  <div class="topbar">
    <h2>Pluto</h2>
    <div>
      <i class="fas fa-bell"></i>
      <i class="fas fa-envelope" style="margin: 0 10px;"></i>
      <span>John David</span>
    </div>
  </div>
  <div class="main-content">
    <h2>Dashboard</h2>
    <div class="cards">
      <div class="card">
        <h3>2500</h3>
        <p>Welcome</p>
      </div>
      <div class="card">
        <h3>123.50</h3>
        <p>Average Time</p>
      </div>
      <div class="card">
        <h3>1,805</h3>
        <p>Collections</p>
      </div>
      <div class="card">
        <h3>54</h3>
        <p>Comments</p>
      </div>
    </div>
    <div class="social">
      <div class="card facebook">
        <h3>35k</h3>
        <p>Friends</p>
        <p>128 Feeds</p>
      </div>
      <div class="card twitter">
        <h3>584k</h3>
        <p>Followers</p>
        <p>978 Tweets</p>
      </div>
      <div class="card linkedin">
        <h3>758+</h3>
        <p>Contacts</p>
        <p>365 Feeds</p>
      </div>
      <div class="card google">
        <h3>450</h3>
        <p>Followers</p>
        <p>57 Circles</p>
      </div>
    </div>
  </div>
</body>
</html>
