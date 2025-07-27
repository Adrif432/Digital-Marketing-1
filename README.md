<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Preloader -->
<div id="preloader">
  <div class="loader-text">Welcome To My Portfolio</div>
</div>

<!-- Main Content -->
<div class="container" style="display:none;" id="main-content">
  <header>
    <h1>I’m Arafat</h1>
    <p>Web Designer & Developer</p>
  </header>

  <section class="projects">
    <h2>My Projects</h2>
    <ul>
      <li>🌐 Responsive Website Design</li>
      <li>📱 Mobile App UI</li>
      <li>💡 JavaScript Mini Games</li>
    </ul>
  </section>

  <footer>
    <a href="mailto:your@email.com" class="contact-btn">Contact Me</a>
  </footer>
</div>

<script>
  // Preloader Timeout
  window.onload = function () {
    setTimeout(function () {
      document.getElementById('preloader').style.display = 'none';
      document.getElementById('main-content').style.display = 'block';
    }, 3000); // 3s
  }
</script>

</body>
</html>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Preloader */
#preloader {
  background: #111;
  color: #fff;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Arial', sans-serif;
}

.loader-text {
  font-size: 28px;
  animation: drop 0.7s ease-out infinite;
}

@keyframes drop {
  0% { transform: translateY(-20px); opacity: 0; }
  50% { transform: translateY(0px); opacity: 1; }
  100% { transform: translateY(20px); opacity: 0; }
}

/* Main Content */
body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
  background: #f9f9f9;
  padding: 20px;
  color: #333;
}

.container {
  max-width: 600px;
  margin: auto;
}

header h1 {
  font-size: 32px;
  color: #2c3e50;
  margin-bottom: 10px;
}

header p {
  font-size: 18px;
  color: #777;
}

.projects h2 {
  margin: 20px 0 10px;
  font-size: 24px;
  color: #2c3e50;
}

.projects ul {
  list-style-type: none;
  padding-left: 0;
}

.projects li {
  margin-bottom: 10px;
  background: #fff;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

footer {
  margin-top: 30px;
  text-align: center;
}

.contact-btn {
  background: #2c3e50;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 20px;
  font-weight: bold;
  transition: 0.3s;
}

.contact-btn:hover {
  background: #1abc9c;
}
Write to Musa Nur

