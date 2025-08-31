# Wild-Flower-4
<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>WILD FLOWER - Pollen Alert</title>

  <style>

    /* Reset */

    * {

      margin: 0;

      padding: 0;

      box-sizing: border-box;

      font-family: "Segoe UI", sans-serif;

      scroll-behavior: smooth;

    }

    /* Navbar */

    header {

      position: sticky;

      top: 0;

      background: linear-gradient(90deg, #6ab04c, #badc58);

      display: flex;

      justify-content: center;

      padding: 1rem 0;

      box-shadow: 0 3px 8px rgba(0,0,0,0.1);

      z-index: 1000;

    }

    nav ul {

      list-style: none;

      display: flex;

      gap: 2rem;

    }

    nav ul li a {

      text-decoration: none;

      color: white;

      font-weight: 600;

      font-size: 18px;

      padding: 6px 12px;

      border-radius: 6px;

      transition: 0.3s;

    }

    nav ul li a:hover {

      background: #f6e58d;

      color: #2f3e2f;

    }

    /* Sections */

    section {

      min-height: 100vh;

      padding: 4rem 2rem;

      text-align: center;

    }

    #home { background: #fdfdfd; color: #2f3e2f; }

    #about { background: #f6f6e9; color: #333; }

    #nasa { background: #dff9fb; color: #2c3e50; }

    #allergy { background: #fef5e7; color: #2f3e2f; }

    #contact { background: #407537; color: white; }

    /* Forms */

    form {

      margin-top: 2rem;

      background: white;

      color: #2f3e2f;

      padding: 2rem;

      border-radius: 10px;

      max-width: 400px;

      margin-left: auto;

      margin-right: auto;

      box-shadow: 0 3px 10px rgba(0,0,0,0.1);

    }

    form input, form button {

      width: 100%;

      padding: 10px;

      margin: 10px 0;

      border-radius: 6px;

      border: 1px solid #ccc;

    }

    form button {

      background: #6ab04c;

      color: white;

      border: none;

      cursor: pointer;

      font-weight: 600;

    }

    form button:hover {

      background: #407537;

    }

    footer {

      background: #2f3e2f;

      color: white;

      text-align: center;

      padding: 1rem;

    }

  </style>

</head>

<body>

  <!-- Navigation -->

  <header>

    <nav>

      <ul>

        <li><a href="#home">Home</a></li>

        <li><a href="#about">About</a></li>

        <li><a href="#nasa">NASA & Pollen</a></li>

        <li><a href="#allergy">Pollen Allergy</a></li>

        <li><a href="#contact">Contact</a></li>

      </ul>

    </nav>

  </header>

  <!-- Sections -->

  <section id="home">

    <h1>WILD FLOWER</h1>

    <h2>Welcome to our project (Pollen Alert)</h2>

    <p><strong>Your smart companion to stay safe from pollen allergies using NASA’s data.</strong></p>

  </section>

  <section id="about">

    <h2>About</h2>

    <p>

      At Wild Flower, we care about your health. Our Pollen Alert system tracks pollen levels in your area 

      in real-time, helping allergy and asthma sufferers prepare and protect themselves before pollen 

      seasons begin. Using advanced satellite data from NASA, we provide accurate forecasts, 

      interactive maps, and timely alerts.

    </p>

    <ul>

      <li>Real-time interactive pollen maps</li>

      <li>Personalized alerts via email or SMS</li>

      <li>Seasonal pollen trend analysis</li>

      <li>Health tips and preventive advice</li>

    </ul>

  </section>

  <section id="nasa">

    <h2>NASA & Pollen</h2>

    <p>

      NASA provides important environmental data that helps us understand when pollen 

      seasons are likely to start. By monitoring Earth’s climate, vegetation, and air quality, 

      NASA offers valuable insights into how plants release pollen and how it spreads.

    </p>

    <p>

      This information can help people with pollen allergy to prepare better, reduce 

      exposure, and stay safe during the flowering season. Using NASA’s data, we can 

      predict when the pollen levels will rise and take action before the symptoms appear.

    </p>

    <p>

      For more information visit 

      <a href="https://www.nasa.gov/centers-and-facilities/marshall/pollen-you-can-run-but-you-cant-hide-vcpci/" target="_blank">NASA Space Article</a>

    </p>

  </section>

  <section id="allergy">

    <h2>Pollen Allergy</h2>

    <h3>Pollen</h3>

    <p>Fine, powdery grains released by trees, grasses, and weeds to fertilize other plants.</p>

    <h3>Allergic Reaction</h3>

    <p>An overactive immune system identifies pollen as harmful and produces antibodies, leading to symptoms.</p>

    <h3>Seasonality</h3>

    <p>Symptoms are often seasonal, depending on the type of pollen and when the plant pollinates (trees in spring, grasses in summer, weeds in fall).</p>

    <img src="https://cdn.shopify.com/s/files/1/0267/9370/5585/files/Symtpoms_of_Pollen_Allergy_Diagram.png?v=1601979758"

         alt="Pollen allergy symptoms" width="600">

  </section>

  <section id="contact">

    <h2>Stay Updated</h2>

    <p>Enter your details below and subscribe to get more information about pollen and NASA’s research.</p>

    <form action="https://formspree.io/f/xblayobq" method="post">

      <input type="text" id="name" name="name" placeholder="Your name" required>

      <input type="email" id="email" name="email" placeholder="Your email" required>

      <input type="text" id="country" name="country" placeholder="Your country">

      <input type="text" id="region" name="region" placeholder="Your city or region">

      <button type="submit">Submit</button>

    </form>

  </section>

  <footer>

    <p>© 2025 Wild Flower - Pollen Alert Project</p>

  </footer>

</body>

</html>
