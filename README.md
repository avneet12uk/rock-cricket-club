# rock-cricket-club
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rock Cricket Club - Salem</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #1a73e8;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }
    header h1 { margin: 0; font-size: 2.5rem; }
    header p { margin: 5px 0 0; font-size: 1.1rem; }

    nav {
      background-color: #333;
      overflow: hidden;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover { background-color: #575757; }

    .container {
      max-width: 1000px;
      margin: 20px auto;
      padding: 0 20px;
    }

    section {
      background-color: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    }

    h2 { color: #1a73e8; margin-bottom: 15px; }

    /* Gallery */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 10px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .gallery img:hover { transform: scale(1.05); }

    /* Schedule Table */
    table {
      width: 100%;
      border-collapse: collapse;
    }
    th, td {
      padding: 12px;
      text-align: left;
      border-bottom: 1px solid #ddd;
      transition: background-color 0.3s;
    }
    th { background-color: #1a73e8; color: white; }
    tr:hover { background-color: #f1f1f1; }

    /* Form */
    form { display: flex; flex-direction: column; }
    input, textarea, button {
      padding: 10px;
      margin: 8px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 1rem;
    }
    button {
      background-color: #1a73e8;
      color: white;
      border: none;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover { background-color: #155bb5; }

    /* Footer */
    footer {
      text-align: center;
      padding: 15px;
      background-color: #1a73e8;
      color: white;
    }

    /* Social Icons */
    .social a {
      margin: 0 10px;
      color: #1a73e8;
      font-size: 1.5rem;
      transition: color 0.3s;
    }
    .social a:hover { color: #155bb5; }

    /* Responsive */
    @media(max-width: 600px) {
      nav a { float: none; width: 100%; text-align: left; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Rock Cricket Club</h1>
    <p>Salem, Tamil Nadu</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#schedule">Match Schedule</a>
    <a href="#signup">Sign Up</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">

    <!-- About Section -->
    <section id="about">
      <h2>About Us</h2>
      <p>Rock Cricket Club is a passionate cricket team in Salem, Tamil Nadu. We organize matches, train talent, and foster a love for cricket in the community. Join us and become part of our cricket family!</p>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
      <h2>Team Gallery</h2>
      <div class="gallery">
        <img src="https://via.placeholder.com/200x150" alt="Team Photo 1">
        <img src="https://via.placeholder.com/200x150" alt="Team Photo 2">
        <img src="https://via.placeholder.com/200x150" alt="Team Photo 3">
        <img src="https://via.placeholder.com/200x150" alt="Team Photo 4">
      </div>
    </section>

    <!-- Match Schedule -->
    <section id="schedule">
      <h2>Upcoming Matches</h2>
      <table>
        <tr>
          <th>Date</th>
          <th>Opponent</th>
          <th>Venue</th>
        </tr>
        <tr>
          <td>05-Oct-2025</td>
          <td>Salem Tigers</td>
          <td>Salem Cricket Ground</td>
        </tr>
        <tr>
          <td>12-Oct-2025</td>
          <td>Chennai Strikers</td>
          <td>Chennai Stadium</td>
        </tr>
        <tr>
          <td>19-Oct-2025</td>
          <td>Coimbatore Kings</td>
          <td>Coimbatore Ground</td>
        </tr>
      </table>
    </section>

    <!-- Signup Form -->
    <section id="signup">
      <h2>Join Our Club</h2>
      <form action="https://formsubmit.co/rockcricketclubsalem@gmail.com" method="POST">
        <input type="text" name="name" placeholder="Full Name" required>
        <input type="email" name="email" placeholder="Email Address" required>
        <textarea name="message" placeholder="Message / Skill Level" rows="4"></textarea>
        <button type="submit">Sign Up</button>
      </form>
      <p>We’ll get back to you via email!</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: <a href="mailto:rockcricketclubsalem@gmail.com">rockcricketclubsalem@gmail.com</a></p>
      <p>Location: Salem, Tamil Nadu, India</p>
      <div class="social">
        <p>Follow us:</p>
        <a href="#"><i class="fab fa-facebook-square"></i></a>
        <a href="#"><i class="fab fa-instagram-square"></i></a>
        <a href="#"><i class="fab fa-twitter-square"></i></a>
      </div>
    </section>

  </div>

  <footer>
    &copy; 2025 Rock Cricket Club - All Rights Reserved
  </footer>

</body>
</html>
