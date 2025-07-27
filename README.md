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
