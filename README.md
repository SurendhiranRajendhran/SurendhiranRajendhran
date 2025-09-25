<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Surendhiran</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  <script src="https://cdn.jsdelivr.net/npm/scrollreveal"></script>
</head>
<body class="bg-gradient-to-br from-gray-900 via-black to-gray-800 text-white font-sans">
  
  <!-- Hero Section -->
  <section class="h-screen flex flex-col justify-center items-center text-center px-6">
    <h1 class="text-5xl md:text-6xl font-extrabold bg-gradient-to-r from-green-400 to-blue-500 bg-clip-text text-transparent mb-4">
      Hi, I'm Surendhiran
    </h1>
    <h2 class="text-2xl md:text-3xl font-semibold">
      <span id="typed-text"></span>
    </h2>
    <p class="mt-6 text-gray-300 max-w-xl">
      Turning ideas into impactful digital solutions with data, design, and development.
    </p>
  </section>

  <!-- About Section -->
  <section class="py-20 px-8 bg-gradient-to-b from-black to-gray-900">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-4xl font-bold mb-6 text-green-400">About Me</h2>
      <p class="text-gray-300 leading-relaxed text-lg">
        Passionate about data, AI, and web development. I love solving problems and building efficient, user-friendly solutions. 
        With hands-on experience in data analysis, machine learning, and WordPress development, 
        I aim to bridge the gap between technology and creativity.
      </p>
    </div>
  </section>

  <!-- Let's Connect -->
  <section class="py-20 px-8 bg-gradient-to-b from-gray-900 to-black text-center">
    <h2 class="text-4xl font-bold text-blue-400 mb-8">Let's Connect</h2>
    <div class="flex justify-center space-x-6">
      <a href="https://www.linkedin.com" target="_blank" class="transform hover:scale-125 transition duration-300">
        <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn" class="w-12 h-12">
      </a>
      <a href="https://github.com" target="_blank" class="transform hover:scale-125 transition duration-300">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733609.png" alt="GitHub" class="w-12 h-12">
      </a>
      <a href="mailto:youremail@example.com" class="transform hover:scale-125 transition duration-300">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email" class="w-12 h-12">
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center bg-black text-gray-500 text-sm">
    © 2025 Surendhiran | All Rights Reserved
  </footer>

  <!-- Typed.js Effect -->
  <script>
    var typed = new Typed("#typed-text", {
      strings: [
        "Data Analyst & AI/ML",
        "WordPress Developer",
        "Tech Enthusiast & Problem Solver"
      ],
      typeSpeed: 60,
      backSpeed: 40,
      backDelay: 1200,
      loop: true
    });
  </script>

  <!-- ScrollReveal Animations -->
  <script>
    ScrollReveal().reveal('h1, h2, p, .flex, footer', { 
      delay: 200, 
      distance: '40px', 
      origin: 'bottom', 
      duration: 1000, 
      easing: 'ease-out',
      reset: true
    });
  </script>
</body>
</html>
