<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Landing Page</title>
  <style>
    /* Basic Reset */
    body, h1, h2, p, ul {
      margin: 0;
      padding: 0;
    }
    body {
      background-color: blue;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    /* Hero Section */
    header {
      background: url('images/schoolbanner.jpg') no-repeat center center/cover; /* Replace 'hero-image.jpg' with your actual image file */
      height: 80vh;
      color: blue;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3em;
      margin-bottom: 20px;
    }
    header p {
      font-size: 1.2em;
      margin-bottom: 30px;
    }
    header a {
      background-color: #ff6600;
      color: Blue;
      text-decoration: none;
      padding: 10px 20px;
      border-radius: 5px;
      font-size: 1.2em;
    }

    /* Features Section */
    .features {
      padding: 40px 20px;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .feature {
      flex: 1 1 30%;
      margin: 10px;
      text-align: center;
    }
    .feature img {
      width: 80px;
      height: 80px;
      margin-bottom: 15px;
    }
    .feature h2 {
      margin-bottom: 10px;
    }
    .feature p {
      font-size: 1em;
    }

    /* Footer Section */
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    /* Responsive Adjustments */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2.5em;
      }
      .features {
        flex-direction: column;
        align-items: center;
      }
      .feature {
        flex: none;
        width: 80%;
      }
    }
  </style>
</head>
<body>
  <!-- Hero Section -->
  <header>
    <h1>Introducing Our Digital Education Features</h1>
    <p>Experience the next generation of innovation Education.</p>
    <a href="#signup">Sign Up Now</a>
  </header>

  <!-- Features Section -->
  <section class="features">
    <div class="feature">
      <img src="images/bluehouse.jpg" alt="Innovative approach">
      <h2>Innovative approach</h2>
      <p>children in this house has an innovative approach in AI development.</p>
    </div>
    <div class="feature">
      <img src="images/redhouse.jpg" alt="best ICT">
      <h2>best ICT</h2>
      <p>this house is best know for it bold ICT innovation breaking unlimied bounds.</p>
    </div>
    <div class="feature">
      <img src="images/yellohouse.jpg" alt="Brain system">
      <h2>Brain system</h2>
      <p>this house is the brain box of the whole schooling system you will love this .</p>
    </div>

  </section>

  <!-- Footer Section -->
  <footer>
    <p>Contact us: info@Gospelcommunicationschool.com| Follow us on social media @facebook/Gospelcommunicationschool call us: 08147105228</p>
    <p>&copy; 2025 Gospel Communication School. All rights reserved.</p>
  </footer>
</body>
</html>
