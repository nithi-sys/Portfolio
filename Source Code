<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Nithish M - Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  

  <style>
    body {
      background-color: #000;
      color: rgb(235, 147, 147);
      position: relative;
      overflow-x: hidden;
    }

    .background-animated {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: radial-gradient(circle, rgba(178, 11, 147, 0.15) 0%, rgba(0,0,0,1) 70%);
      z-index: -1;
      animation: moveBackground 20s infinite linear;
    }

    @keyframes moveBackground {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .icon-button {
      width: 56px;
      height: 56px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 9999px;
      background-color: #5712be;
      transition: background-color 0.3s;
    }

    .icon-button:hover {
      background-color: #1a0033;
    }

    .icon-button i {
      color: #00d9ff;
      font-size: 24px;
    }

    /* Slide In/Out Animation */
    .slide-section {
      opacity: 0;
      transform: translateY(80px);
      transition: opacity 0.8s cubic-bezier(.4,0,.2,1), transform 0.8s cubic-bezier(.4,0,.2,1);
      will-change: opacity, transform;
    }
    .slide-section.slide-in-up {
      opacity: 1;
      transform: translateY(0);
      transition: opacity 0.8s cubic-bezier(.4,0,.2,1), transform 0.8s cubic-bezier(.4,0,.2,1);
    }
    .slide-section.slide-out-down {
      opacity: 0;
      transform: translateY(80px);
      transition: opacity 0.8s cubic-bezier(.4,0,.2,1), transform 0.8s cubic-bezier(.4,0,.2,1);
    }
    .slide-section.slide-in-down {
      opacity: 1;
      transform: translateY(0);
      transition: opacity 0.8s cubic-bezier(.4,0,.2,1), transform 0.8s cubic-bezier(.4,0,.2,1);
    }
    .slide-section.slide-out-up {
      opacity: 0;
      transform: translateY(-80px);
      transition: opacity 0.8s cubic-bezier(.4,0,.2,1), transform 0.8s cubic-bezier(.4,0,.2,1);
    }
  </style>
</head>
<body class="scroll-smooth">
  

  <div class="background-animated"></div>

  <!-- Navbar -->
  <header class="bg-black/90 backdrop-blur shadow sticky top-0 z-50 slide-section">
    <div class="container mx-auto flex justify-between items-center px-6 py-4">
      <h1 class="text-xl font-bold text-blue-400">📜 Portfolio</h1>
      <nav class="space-x-6 font-semibold text-white">
        <a href="#home" class="hover:text-blue-400">Home</a>
        <a href="#about" class="hover:text-blue-400">About</a>
        <a href="#skills" class="hover:text-blue-400">Skills</a>
        <a href="#projects" class="hover:text-blue-400">Projects</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="flex flex-col md:flex-row items-center justify-center min-h-screen px-6 slide-section">
    <div class="max-w-xl text-center md:text-left space-y-6">
      <h2 class="text-4x1 md:text-5xl font-extrabold text-white">Hi There,<br>I'm <span class="text-orange-500">Nithish M</span></h2>
      <p class="text-xl">I Am Into <span id="typing-text" class="text-red-400 font-semibold"></span><span class="text-red-400">|</span></p>
      <a href="#about" class="inline-block px-6 py-3 bg-orange-700 text-white square-full shadow hover:bg-white-800 transition">About Me ↓</a>
    </div>
    <img src="image.webp" alt="Profile" class="w-160 h-80 square-full border-8 border-green-40 mt-10 md:mt-0 md:ml-10 shadow-lg"/>
  </section>

  <!-- About -->
  <section id="about" class="py-20 px-6 slide-section">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold mb-10 text-center text-white">About Me</h2>
      <div class="grid md:grid-cols-2 gap-10 text-white">
        <div class="space-y-4">
          <p><strong class="text-blue-400">Name:</strong> Nithish M</p>
          <p><strong class="text-blue-400">Age:</strong> 17</p>
          <p><strong class="text-blue-400">Phone:</strong> +91 8015173905</p>
          <p><strong class="text-blue-400">Email:</strong> nithishmarimuthu103@gmail.com</p>
          <p><strong class="text-blue-400">Location:</strong> Chennai, India</p>
        </div>
        <div>
          <p class="leading-relaxed">
           I’m a passionate sophomore engineering student at Vellore Institute of Technology, pursuing a B.Tech in Computer Science with a specialization in Data Science.
           I have a strong interest in data science, Java, and research, and I enjoy building projects that combine design with practical functionality. 
           I'm always eager to explore and learn new technologies.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Redirecting with Icons -->
  <section class="py-12 text-center slide-section">
    <h2 class="text-2xl font-bold mb-6 text-white">Profile</h2>
    <div class="flex justify-center space-x-6">
      <!-- LinkedIn -->
      <a href="https://www.linkedin.com/in/nithish-marimuthu-56470731b/" target="_blank" class="icon-button" title="LinkedIn">
        <i class="fab fa-linkedin-in"></i>
      </a>
      <!-- GitHub -->
      <a href="https://github.com/dashboard" target="_blank" class="icon-button" title="GitHub">
        <i class="fab fa-github"></i>
      </a>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-20 px-6 slide-section bg-gradient-to-br from-gray-900 to-black text-white">
  <div class="max-w-5xl mx-auto text-center">
    <h2 class="text-4xl font-extrabold mb-12">Skills</h2>
    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6">
      <!-- Skill Card -->
      <div class="backdrop-blur-md bg-white/10 border border-white/20 p-6 rounded-xl shadow-lg transform transition duration-300 hover:scale-105 hover:bg-white/20">
        <i class="fab fa-java text-4xl mb-3 text-yellow-300"></i>
        <p class="text-lg font-semibold">Java</p>
      </div>
      <div class="backdrop-blur-md bg-white/10 border border-white/20 p-6 rounded-xl shadow-lg transform transition duration-300 hover:scale-105 hover:bg-white/20">
        <i class="fab fa-python text-4xl mb-3 text-blue-400"></i>
        <p class="text-lg font-semibold">Python</p>
      </div>
      <div class="backdrop-blur-md bg-white/10 border border-white/20 p-6 rounded-xl shadow-lg transform transition duration-300 hover:scale-105 hover:bg-white/20">
        <i class="fab fa-html5 text-4xl mb-3 text-orange-500"></i>
        <p class="text-lg font-semibold">HTML/CSS</p>
      </div>
      <div class="backdrop-blur-md bg-white/10 border border-white/20 p-6 rounded-xl shadow-lg transform transition duration-300 hover:scale-105 hover:bg-white/20">
        <i class="fas fa-code text-4xl mb-3 text-green-300"></i>
        <p class="text-lg font-semibold">C & C++</p>
      </div>
      <div class="backdrop-blur-md bg-white/10 border border-white/20 p-6 rounded-xl shadow-lg transform transition duration-300 hover:scale-105 hover:bg-white/20 col-span-2 sm:col-span-1 md:col-span-1">
        <i class="fab fa-github text-4xl mb-3 text-white"></i>
        <p class="text-lg font-semibold">Git & GitHub</p>
      </div>
    </div>
  </div>
</section>


  <!-- Projects -->
  <section id="projects" class="py-20 px-6 slide-section">
    <div class="max-w-5xl mx-auto text-center">
      <h2 class="text-3xl font-bold text-white mb-10">Projects Done</h2>
      <div class="space-y-6 text-white">
        <!-- Example Project -->
        <div class="bg-white/10 border border-white/20 p-6 rounded-lg text-left">
          <h3 class="text-xl font-bold text-blue-400">Example Project Title</h3>
          <p class="mt-2">Description of your project goes here. You can list what technologies were used and what the outcome was.</p>
        </div>
        <!-- Add more projects here -->
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-6 bg-black border-t border-white/20 slide-section">
    <p class="text-gray-400">&copy; 2025 Nithish M. All rights reserved.</p>
  </footer>

  <!-- Typing Script -->
  <script>
    const features = ["Data Science", "Java", "Android Development", "Web Development"];
    let part = 0, offset = 0, forwards = true, skip_count = 0;
    const skip_delay = 15, speed = 100;
    const textElement = document.getElementById("typing-text");

    function typeEffect() {
      setInterval(() => {
        if (forwards) {
          if (offset >= features[part].length) {
            if (++skip_count === skip_delay) {
              forwards = false;
              skip_count = 0;
            }
          }
        } else if (--offset === 0) {
          forwards = true;
          part = (part + 1) % features.length;
        }

        textElement.textContent = features[part].substring(0, offset);
        if (!skip_count) offset += forwards ? 1 : 0;
      }, speed);
    }
    typeEffect();

    // Slide Animation on Scroll Up and Down
    document.addEventListener("DOMContentLoaded", function () {
      const slideSections = document.querySelectorAll('.slide-section');
      let lastScrollY = window.scrollY;

      // Initial state: animate sections already in view
      function setInitialSlides() {
        slideSections.forEach(section => {
          const rect = section.getBoundingClientRect();
          if (rect.top < window.innerHeight && rect.bottom > 0) {
            section.classList.add('slide-in-up');
            section.classList.remove('slide-out-down', 'slide-in-down', 'slide-out-up');
          }
        });
      }
      setInitialSlides();

      window.addEventListener('scroll', function () {
        const currentScrollY = window.scrollY;
        const scrollingDown = currentScrollY > lastScrollY;
        slideSections.forEach(section => {
          const rect = section.getBoundingClientRect();
          // If the section is entering the viewport from the bottom or top
          if (rect.top < window.innerHeight && rect.bottom > 0) {
            // Section is visible
            if (scrollingDown) {
              section.classList.add('slide-in-up');
              section.classList.remove('slide-out-down', 'slide-in-down', 'slide-out-up');
            } else {
              section.classList.add('slide-in-down');
              section.classList.remove('slide-out-up', 'slide-in-up', 'slide-out-down');
            }
          } else {
            // Section is not visible, animate out
            if (scrollingDown && rect.top > window.innerHeight) {
              // Scrolled past downward
              section.classList.remove('slide-in-up', 'slide-in-down');
              section.classList.add('slide-out-down');
              section.classList.remove('slide-out-up');
            } else if (!scrollingDown && rect.bottom < 0) {
              // Scrolled past upward
              section.classList.remove('slide-in-up', 'slide-in-down');
              section.classList.remove('slide-out-down');
              section.classList.add('slide-out-up');
            } else {
              // To avoid flicker, if not visible at all, remove all
              section.classList.remove('slide-in-up', 'slide-in-down', 'slide-out-down', 'slide-out-up');
            }
          }
        });
        lastScrollY = currentScrollY;
      });
    });
  </script>
</body>
</html>
