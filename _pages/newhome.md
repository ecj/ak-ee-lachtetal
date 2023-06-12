---
layout: page
title: Kontakt
---

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Community Solar Project</title>
    <link rel="stylesheet" href="{{ site.baseurl }}/assets/css/style.css">
    <style>
      .header-image {
        position: relative;
        height: 100vh;
        background-image: url('{{ site.baseurl }}/assets/images/header-image.jpg');
        background-position: center;
        background-size: cover;
      }
      
      .header-image .overlay {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-align: center;
        color: #ffffff;
        font-size: 30px;
        font-weight: bold;
      }
      
      .cta-button {
        margin-top: 20px;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="header-image">
        <div class="overlay">
          <h1>Community Solar Project</h1>
          <p>Your Sustainable Energy Solution</p>
          <a href="/signup" class="cta-button">Sign up for the Latest News</a>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/about">About</a></li>
          <li><a href="/projects">Projects</a></li>
          <li><a href="/contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    
    <main>
      <section>
        <h2>Welcome to our Community Solar Project!</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean eget quam quis est eleifend rutrum ac nec lectus.</p>
      </section>
      
      <section>
        <h2>Latest News</h2>
        <!-- Add your latest news content here -->
      </section>
      
      <section>
        <h2>Upcoming Events</h2>
        <!-- Add your upcoming events content here -->
      </section>
    </main>
    
    <footer>
      <p>&copy; 2023 Community Solar Project. All rights reserved.</p>
    </footer>
    
    <script src="{{ site.baseurl }}/assets/js/main.js"></script>
  </body>
</html>
