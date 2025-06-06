<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="yashpalsinh jadeja's Portfolio - Tech Enthusiast | Motivator | Hustler. Explore my projects, skills, and experience.">
  <meta name="author" content="yashpalsinh jadeja">
  <meta property="og:title" content="yashpalsinh jadeja | Portfolio">
  <meta property="og:description" content="Explore yashpalsinh jadeja's portfolio showcasing his skills, projects, and accomplishments in tech and motivation.">
  <meta property="og:image" content="yashpalsinh.jpg">
  <meta property="og:url" content="https://yashpalsinhjadeja.com">
  <title>yashpalsinh jadeja | Portfolio</title>

  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/scrollreveal"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />

  <style>
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes scaleIn {
      from { opacity: 0; transform: scale(0.5); }
      to { opacity: 1; transform: scale(1); }
    }

    .reveal, .scale-reveal { visibility: hidden; }
    .reveal.visible { visibility: visible; animation: fadeInUp 1s ease-out forwards; }
    .scale-reveal.visible { visibility: visible; animation: scaleIn 1s ease-out forwards; }

    .social-icon:hover { transform: scale(1.2); transition: transform 0.3s ease; }

    .progress-bar {
      width: 100%;
      height: 20px;
      border-radius: 10px;
      background-color: #333;
      overflow: hidden;
    }

    .progress-bar span {
      display: block;
      height: 100%;
      text-align: center;
      color: white;
      line-height: 20px;
      font-weight: bold;
    }

    body { background-color: #1a202c; color: #cbd5e0; }
    .nav-bar { background-color: #2d3748; }
    .nav-link:hover { color: #4fd1c5; }
    .button { background-color: #4fd1c5; color: #1a202c; }
    .button:hover { background-color: #38b2ac; }
    .footer { background-color: #2d3748; }

    .card, .notes-card {
      background-color: #2d3748;
      border-radius: 12px;
      padding: 16px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s;
    }

    .card:hover, .notes-card:hover { transform: translateY(-5px); }
    .notes-card a { color: #4fd1c5; text-decoration: none; }
    .notes-card a:hover { text-decoration: underline; }
  </style>
</head>

<body>
  
  <nav class="nav-bar fixed top-0 w-full shadow-lg z-50">
    <div class="max-w-7xl mx-auto flex items-center justify-between p-6">
      <h1 class="text-3xl font-bold text-teal-400">YASHPALSINH JADEJA</h1>
      <button id="menu-toggle" class="text-teal-400 md:hidden text-3xl focus:outline-none">
        <i class="fas fa-bars"></i>
      </button>
      <ul id="nav-links" class="hidden md:flex space-x-8 text-gray-300 text-lg">
        <li><a href="#about" class="nav-link transition-all">About</a></li>
        <li><a href="#skills" class="nav-link transition-all">Skills</a></li>
        <li><a href="#projects" class="nav-link transition-all">Projects</a></li>
        <li><a href="#announcements" class="nav-link transition-all">Announcements</a></li>
        <li><a href="#contact" class="nav-link transition-all">Contact</a></li>
      </ul>
    </div>

    <div id="mobile-menu" class="md:hidden hidden px-6 pb-4">
      <ul class="flex flex-col space-y-4 text-gray-300 text-lg">
        <li><a href="#about" class="nav-link">About</a></li>
        <li><a href="#skills" class="nav-link">Skills</a></li>
        <li><a href="#projects" class="nav-link">Projects</a></li>
        <li><a href="#announcements" class="nav-link">Announcements</a></li>
        <li><a href="#contact" class="nav-link">Contact</a></li>
      </ul>
    </div>
  </nav>

  <header class="text-center py-32 bg-gradient-to-r from-teal-600 to-teal-800">
    <h1 class="text-5xl font-extrabold text-white">YASHPALSINH JADEJA</h1>
    <p class="text-xl text-gray-200 mt-4">Tech Enthusiast | Motivator | Hustler</p>
  </header>

  <section class="flex flex-col items-center justify-center py-16">
    <img src="yashubha.jpg" alt="Yashpalsinh" class="rounded-full w-64 h-64 object-cover border-8 border-teal-400 shadow-lg scale-reveal">
    <h2 class="mt-6 text-3xl font-semibold text-white reveal">Welcome to my space!</h2>
  </section>

  <section id="about" class="max-w-4xl mx-auto py-16 px-6">
    <h2 class="text-4xl font-bold text-teal-400 mb-6 text-center reveal">About Me</h2>
    <p class="text-lg text-gray-300 text-center reveal">
      I'm a passionate Computer Engineer currently studying and working on exciting tech projects. My goal is to guide and inspire youth through motivation, technology, and hustle culture.
    </p>
  </section>

  <section id="skills" class="bg-gray-800 py-16 px-6">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold text-teal-400 mb-6 text-center reveal">Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">HTML</h3>
          <div class="progress-bar mt-4"><span style="width: 99.99%; background-color: #4caf50;">99.99%</span></div>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">CSS</h3>
          <div class="progress-bar mt-4"><span style="width: 99.99%; background-color: #2196f3;">99.99%</span></div>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">JavaScript</h3>
          <div class="progress-bar mt-4"><span style="width: 55%; background-color: #ff9800;">70%</span></div>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">React</h3>
          <div class="progress-bar mt-4"><span style="width: 75%; background-color: #4caf50;">75%</span></div>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">C</h3>
          <div class="progress-bar mt-4"><span style="width: 80%; background-color: #2196f3;">85%</span></div>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">Communication & Leadership</h3>
          <div class="progress-bar mt-4"><span style="width: 90%; background-color: #4caf50;">90%</span></div>
        </div>
      </div>
    </div>
  </section>

  <section id="projects" class="bg-gray-800 py-16 px-6">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold text-teal-400 mb-6 text-center reveal">My Projects</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">Lost and Found Portal</h3>
          <p class="text-gray-300 mt-2">A platform for users to report and find lost items, with a user-friendly interface and a photo-upload feature.</p>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">AI-based Air Pollution Monitoring</h3>
          <p class="text-gray-300 mt-2">A project that uses AI to monitor and predict air pollution levels in real-time for better health management.</p>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">Reaction Time Tester</h3>
          <p class="text-gray-300 mt-2">A micro-project using Arduino to measure human reaction time with a simple LED and button setup.</p>
        </div>
        <div class="card text-center reveal">
          <h3 class="text-xl font-semibold">Shop Website with Admin Login</h3>
          <p class="text-gray-300 mt-2">An e-commerce website that allows admins to manage products and images, with a sleek and user-friendly design.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="announcements" class="bg-gray-800 py-16 px-6">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-4xl font-bold text-teal-400 mb-6 text-center reveal">Latest Announcements</h2>
      <div class="bg-gray-700 p-6 rounded-lg shadow-lg">
        <h3 class="text-2xl font-semibold text-teal-400">Big Updates Coming Soon!</h3>
        <p class="text-lg text-gray-300 mt-4">We have some exciting new projects and collaborations in the works. Stay tuned for major announcements!</p>
        <div class="mt-6">
          <p class="text-lg text-gray-300">Expected launch date: <span class="text-teal-400">May 2025</span></p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="bg-gray-800 py-16 px-6">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-4xl font-bold text-teal-400 mb-6 text-center reveal">Connect with Me</h2>
      <form action="https://formspree.io/f/xblolvdy" method="POST" class="space-y-4">
        <label class="block text-lg text-gray-300">
          Your email:
          <input type="email" name="email" class="w-full p-3 rounded-md text-black" required>
        </label>
        <label class="block text-lg text-gray-300">
          Your message:
          <textarea name="message" class="w-full p-3 rounded-md text-black" required></textarea>
        </label>
        <button type="submit" class="button w-full py-3 text-lg rounded-md">Send Message</button>
      </form>
    </div>
  </section>

  <footer class="footer py-8">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <p class="text-lg text-gray-300">© 2025 Yashpalsinh Jadeja</p>
      <div class="space-x-4">
        <a href="www.linkedin.com/in/yashpalsinh-jadeja-023a4b302/" class="social-icon text-2xl text-teal-400"><i class="fab fa-linkedin"></i></a>
        <a href="https://www.github.com" class="social-icon text-2xl text-teal-400"><i class="fab fa-github"></i></a>
        <a href="https://www.twitter.com" class="social-icon text-2xl text-teal-400"><i class="fab fa-twitter"></i></a>
        <a href="https://www.instagram.com/yashubha_jadeja_0019?igsh=NDEzbWowc3c5aW01" class="social-icon text-2xl text-teal-400"><i class="fab fa-instagram"></i></a>
        <a href="https://www.facebook.com" class="social-icon text-2xl text-teal-400"><i class="fab fa-facebook"></i></a>
        <a href="https://www.youtube.com" class="social-icon text-2xl text-teal-400"><i class="fab fa-youtube"></i></a>
      </div>
    </div>
  </footer>

  <script>
    // Mobile menu toggle
    const menuToggle = document.getElementById('menu-toggle');
    const mobileMenu = document.getElementById('mobile-menu');

    menuToggle.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // ScrollReveal animations
    ScrollReveal().reveal('.reveal', {
      distance: '50px',
      duration: 1000,
      easing: 'ease-out',
      origin: 'bottom',
      interval: 100
    });

    ScrollReveal().reveal('.scale-reveal', {
      scale: 0.5,
      duration: 1000,
      easing: 'ease-out',
      interval: 100
    });
  </script>

</body>
</html>
