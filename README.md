* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background: #f4f4f4;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 40px 20px;
  text-align: center;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  background: #555;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  padding: 14px 20px;
  display: block;
}

.hero {
  padding: 50px 20px;
  background: #eaeaea;
  text-align: center;
}

.hero h2 {
  margin-bottom: 20px;
}

.hero button {
  padding: 10px 20px;
  background: #333;
  color: white;
  border: none;
  cursor: pointer;
}

.features {
  display: flex;
  justify-content: space-around;
  padding: 40px 20px;
  background: #fff;
}

.feature-box {
  background: #f9f9f9;
  padding: 20px;
  width: 30%;
  text-align: center;
  border: 1px solid #ccc;
  border-radius: 10px;
}

footer {
  text-align: center;
  padding: 20px;<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Landing Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">MyLanding</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">Features</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <h2>Welcome to My Landing Page</h2>
    <p>Your one-stop solution for all things amazing.</p>
    <a href="#" class="btn">Get Started</a>
  </section>

  <section class="features">
    <div class="feature-box">
      <h3>Fast</h3>
      <p>Quick performance to keep you moving forward.</p>
    </div>
    <div class="feature-box">
      <h3>Reliable</h3>
      <p>Built with quality and trust in mind.</p>
    </div>
    <div class="feature-box">
      <h3>Creative</h3>
      <p>Designed to impress and inspire.</p>
    </div>
  </section>

  <footer>
    <p>© 2025 MyLanding. All rights reserved.</p>
  </footer>
</body>
</html>
  background: #333;
  color: white;
}
