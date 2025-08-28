# TGESMUN.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>School MUN 2025</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  <header class="navbar">
    <img class="logo" src="assets/logo.png" alt="School Logo" />
    <nav>
      <a href="#home">Home</a>
      <a href="#resources">Resources</a>
      <a href="#secretariat">Secretariat</a>
      <a href="#register">Registrations</a>
      <a href="#committees">Committees</a>
      <a href="#matrix">Allocation Matrix</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Welcome to [Your School] MUN 2025</h1>
    <h2>Engage. Debate. Achieve.</h2>
    <a class="btn-register" href="#register">Register Now</a>
  </section>

  <section id="venue" class="venue">
    <h3>Venue Details</h3>
    <p>
      [Venue Address Line 1]<br />
      [City, State] – [PIN]
    </p>
  </section>

  <footer class="footer">
    <p>© 2025 [Your Institution] MUN | All Rights Reserved</p>
  </footer>

  <!-- Optional countdown script -->
  <script src="js/script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

.navbar {
  background: #004080;
  display: flex;
  align-items: center;
  padding: 1rem 2rem;
}

.navbar .logo {
  height: 50px;
  margin-right: 1.5rem;
}

.navbar nav a {
  color: #fff;
  margin-right: 1rem;
  text-decoration: none;
}

.navbar nav a:hover {
  text-decoration: underline;
}

.hero {
  background: url('../assets/hero-bg.jpg') center/cover no-repeat;
  color: #fff;
  text-align: center;
  padding: 6rem 2rem;
}

.hero h1 {
  font-size: 2.8rem;
  margin-bottom: 1rem;
}

.hero h2 {
  font-size: 1.5rem;
  margin-bottom: 2rem;
}

.btn-register {
  display: inline-block;
  background: #ff8800;
  color: #fff;
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  border-radius: 4px;
  font-size: 1rem;
}

.btn-register:hover {
  background: #ffad33;
}

.venue {
  padding: 3rem 2rem;
  background: #f9f9f9;
  text-align: center;
}

.venue h3 {
  margin-bottom: 1rem;
}

.footer {
  background: #222;
  color: #ccc;
  text-align: center;
  padding: 1.5rem;
}
