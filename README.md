


<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta name="description" content="">
      <meta name="theme-color" content="#ffffff">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="robots" content="">
      
      <title>Professional AI & Data Science  | Machine Learning Expert</title>
      <!-- SEO Description -->
      <meta name="description" content="Explore the portfolio of an Applied AI and Data Science professional showcasing innovative projects in machine learning, deep learning, and data engineering with interactive visualizations and case studies.">

      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap" rel="stylesheet">

       <link href="{{fontLink}}" rel="stylesheet">
       <link href="{{secondaryFontLink}}" rel="stylesheet">
      
      <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&display=swap" rel="stylesheet">

      <!-- Performance optimization: Preload critical resources -->
      <link rel="preload" href="https://cdn.tailwindcss.com" as="script">
      
      <!-- Header Scripts -->
      <script id="header-scripts">
        // This script tag will be replaced with actual scripts.head content
        if (window.scripts && window.scripts.head) {
          document.getElementById('header-scripts').outerHTML = window.scripts.head;
        }
      </script>

      <!-- Preconnect -->
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

      <!-- Font stylesheet -->

      <script type="application/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/handlebars.js/4.7.8/handlebars.min.js"></script>

      <!-- Core CSS -->
      <script src="https://cdn.tailwindcss.com"></script>
      <script>
      document.addEventListener('DOMContentLoaded', function() {
        tailwind.config = {
          theme: {
            extend: {
              colors: {
                primary: {
                  DEFAULT: '{{settings.colors.primary}}',
                  50: '#f8f8f8',
                  100: '#e8e8e8', 
                  200: '#d3d3d3',
                  300: '#a3a3a3',
                  400: '#737373',
                  500: '#525252',
                  600: '#404040',
                  700: '#262626',
                  800: '#171717',
                  900: '#0a0a0a',
                  950: '#030303',
                },
                secondary: {
                  DEFAULT: '{{settings.colors.secondary}}',
                  50: '#f8f8f8',
                  100: '#e8e8e8',
                  200: '#d3d3d3', 
                  300: '#a3a3a3',
                  400: '#737373',
                  500: '#525252',
                  600: '#404040',
                  700: '#262626',
                  800: '#171717',
                  900: '#0a0a0a',
                  950: '#030303',
                },
                accent: {
                  DEFAULT: '{{settings.colors.accent}}',
                  50: '#f8f8f8',
                  100: '#e8e8e8',
                  200: '#d3d3d3',
                  300: '#a3a3a3', 
                  400: '#737373',
                  500: '#525252',
                  600: '#404040',
                  700: '#262626',
                  800: '#171717',
                  900: '#0a0a0a',
                  950: '#030303',
                },
              },
              fontFamily: {
                sans: ['Space Grotesk, sans-serif', 'Roboto', 'system-ui', '-apple-system', 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica Neue', 'Arial', 'sans-serif'],
                heading: ['Roboto Mono, monospace', 'system-ui', 'sans-serif'],
                body: ['Roboto Mono, monospace', 'system-ui', 'sans-serif'],
              },
              spacing: {
                '18': '4.5rem',
                '22': '5.5rem',
                '30': '7.5rem',
              },
              maxWidth: {
                '8xl': '88rem',
                '9xl': '96rem',
              },
              animation: {
                'fade-in': 'fadeIn 0.5s ease-in',
                'fade-out': 'fadeOut 0.5s ease-out',
                'slide-up': 'slideUp 0.5s ease-out',
                'slide-down': 'slideDown 0.5s ease-out',
                'slide-left': 'slideLeft 0.5s ease-out',
                'slide-right': 'slideRight 0.5s ease-out',
                'scale-in': 'scaleIn 0.5s ease-out',
                'scale-out': 'scaleOut 0.5s ease-out',
                'spin-slow': 'spin 3s linear infinite',
                'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                'bounce-slow': 'bounce 3s infinite',
                'float': 'float 3s ease-in-out infinite',
              },
              keyframes: {
                fadeIn: {
                  '0%': { opacity: '0' },
                  '100%': { opacity: '1' },
                },
                fadeOut: {
                  '0%': { opacity: '1' },
                  '100%': { opacity: '0' },
                },
                slideUp: {
                  '0%': { transform: 'translateY(20px)', opacity: '0' },
                  '100%': { transform: 'translateY(0)', opacity: '1' },
                },
                slideDown: {
                  '0%': { transform: 'translateY(-20px)', opacity: '0' },
                  '100%': { transform: 'translateY(0)', opacity: '1' },
                },
                slideLeft: {
                  '0%': { transform: 'translateX(20px)', opacity: '0' },
                  '100%': { transform: 'translateX(0)', opacity: '1' },
                },
                slideRight: {
                  '0%': { transform: 'translateX(-20px)', opacity: '0' },
                  '100%': { transform: 'translateX(0)', opacity: '1' },
                },
                scaleIn: {
                  '0%': { transform: 'scale(0.9)', opacity: '0' },
                  '100%': { transform: 'scale(1)', opacity: '1' },
                },
                scaleOut: {
                  '0%': { transform: 'scale(1.1)', opacity: '0' },
                  '100%': { transform: 'scale(1)', opacity: '1' },
                },
                float: {
                  '0%, 100%': { transform: 'translateY(0)' },
                  '50%': { transform: 'translateY(-10px)' },
                },
              },
              aspectRatio: {
                'portrait': '3/4',
                'landscape': '4/3',
                'ultrawide': '21/9',
              },
            },
          },
          variants: {
            extend: {
              opacity: ['disabled'],
              cursor: ['disabled'],
              backgroundColor: ['active', 'disabled'],
              textColor: ['active', 'disabled'],
            },
          },
        }
      });
      </script>

      <!-- Utilities and Components -->
      <script defer src="https://cdnjs.cloudflare.com/ajax/libs/alpinejs/3.13.3/cdn.min.js"></script>
      <script defer src="https://cdnjs.cloudflare.com/ajax/libs/apexcharts/3.45.1/apexcharts.min.js"></script>
      
      <!-- Optimized Font Loading -->
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      
      <!-- Icons -->
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" 
            integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
            crossorigin="anonymous" referrerpolicy="no-referrer" />

      <!-- Dynamic Meta Tags -->
      <meta name="description" content="">
      <meta name="keywords" content="">
      <meta name="robots" content="">
      <meta name="google-site-verification" content="">
      <meta name="baidu-verification" content="">
      <meta name="yandex-verification" content="">
      <meta name="bing-verification" content="">
      <meta property="og:title" content="">
      <meta property="og:description" content="">
      <meta property="og:image" content="">
      <meta property="og:type" content="website">
      <meta property="og:locale" content="en_US">
      <meta property="og:site_name" content="AI Data Science Portfolio">
      <meta name="twitter:card" content="summary_large_image">
      <meta name="twitter:title" content="">
      <meta name="twitter:description" content="">
      <meta name="twitter:image" content="">

      
      <link rel="icon" type="image/x-icon" href="{{settings.favicon}}">
      
      <style>
        h1, h2, h3, h4, h5, h6 {
          font-family: Space Grotesk, sans-serif, system-ui, sans-serif;
        }
        body {
          font-family: Roboto Mono, monospace, system-ui, sans-serif;
        }
      </style>
   </head>
   <body class="antialiased text-gray-800 min-h-screen flex flex-col">
      <!-- Skip to main content link for accessibility -->
      <a href="#main-content" 
         class="sr-only focus:not-sr-only focus:absolute focus:top-0 focus:left-0 focus:z-50 focus:p-4 focus:bg-white focus:text-black">
         Skip to main content
      </a>

      <!-- Header -->
      <header class="relative z-50 bg-white dark:bg-gray-900">
        <!-- Header content goes here -->
      </header>

      <!-- Main content area -->
      <main id="main-content" class="flex-1 relative h-full">
        <!-- Content will be injected here -->
      </main>

      

   </body>
</html>
<div id="root">
  <header id="header" class="fixed w-full z-50 bg-neutral-900/90 backdrop-blur-sm">
    <nav class="container mx-auto px-6 py-4">
      <div class="flex items-center justify-between">
        <a href="index.html" class="text-[#64FFDA] font-space-grotesk text-2xl font-bold">
          Shravan Kumar
        </a>

        <!-- Mobile Menu Button -->
        <button id="menu-btn" class="lg:hidden text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
          </svg>
        </button>

        <!-- Desktop Navigation -->
        <ul class="hidden lg:flex space-x-8">
          <li>
            <a href="index.html" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 font-roboto-mono">
              Home
            </a>
          </li>
          <li>
            <a href="/about" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 font-roboto-mono">
              About
            </a>
          </li>
          <li>
            <a href="/experience" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 font-roboto-mono">
              Experience
            </a>
          </li>
          <li>
            <a href="/projects" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 font-roboto-mono">
              Projects
            </a>
          </li>
          <li>
            <a href="/skills" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 font-roboto-mono">
              Skills
            </a>
          </li>
          <li>
            <a href="/blog" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 font-roboto-mono">
              Blog
            </a>
          </li>
          <li>
            <a href="/contact" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 font-roboto-mono">
              Contact
            </a>
          </li>
        </ul>

        <!-- Mobile Navigation -->
        <div id="mobile-menu" class="fixed inset-0 bg-neutral-900/95 backdrop-blur-lg transform translate-x-full transition-transform duration-300 lg:hidden">
          <div class="flex justify-end p-6">
            <button id="close-menu" class="text-white">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
              </svg>
            </button>
          </div>
          <ul class="flex flex-col items-center space-y-6 p-6">
            <li>
              <a href="/" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 text-xl font-roboto-mono">
                Home
              </a>
            </li>
            <li>
              <a href="/about" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 text-xl font-roboto-mono">
                About
              </a>
            </li>
            <li>
              <a href="/experience" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 text-xl font-roboto-mono">
                Experience
              </a>
            </li>
            <li>
              <a href="/projects" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 text-xl font-roboto-mono">
                Projects
              </a>
            </li>
            <li>
              <a href="/skills" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 text-xl font-roboto-mono">
                Skills
              </a>
            </li>
            <li>
              <a href="/blog" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 text-xl font-roboto-mono">
                Blog
              </a>
            </li>
            <li>
              <a href="/contact" class="text-gray-300 hover:text-[#64FFDA] transition-colors duration-300 text-xl font-roboto-mono">
                Contact
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <div class="h-screen pt-20 bg-neutral-900">
    <div class="container mx-auto px-6 h-full flex items-center">
      <!-- Left Section (Text) -->
      <div class="w-full md:w-1/2">
        <h1 class="text-[#64FFDA] font-space-grotesk text-lg mb-4 animate__animated animate__fadeIn">
          Hi, I'm
        </h1>
        <h2 class="text-white text-5xl lg:text-7xl font-bold mb-6 animate__animated animate__fadeInUp">
          Shravan
        </h2>
        <p class="text-gray-400 text-xl lg:text-2xl max-w-2xl mb-8 animate__animated animate__fadeInUp animate__delay-1s">
          From IIT Jodhpur Learning Applied AI & Data Science I am deeply interested in harnessing the power of machine learning, deep learning, and data-driven insights to solve real-world problems.

          With a strong foundation in mathematics, programming, and AI algorithms, I am continuously expanding my knowledge in areas like computer vision, NLP, data analytics, and AI-driven decision-making. 
        </p>
        <button class="bg-transparent border-2 border-[#64FFDA] text-[#64FFDA] px-8 py-3 rounded hover:bg-[#64FFDA]/10 transition-colors duration-300 animate__animated animate__fadeInUp animate__delay-2s">
          Explore Projects
        </button>
      </div>
  
      <!-- Right Section (PNG Image with No Styling) -->
      <div class="w-full md:w-1/2 flex justify-center">
        <img src="image/me.jpg" alt="Shravan's Image" class="animate__animated animate__fadeInRight">
      </div>
    </div>
  </div>
  
  
      

  <script>
    document.getElementById('menu-btn').addEventListener('click', () => {
      document.getElementById('mobile-menu').classList.remove('translate-x-full');
    });

    document.getElementById('close-menu').addEventListener('click', () => {
      document.getElementById('mobile-menu').classList.add('translate-x-full');
    });

    // Close mobile menu when clicking outside
    document.addEventListener('click', (e) => {
      const mobileMenu = document.getElementById('mobile-menu');
      const menuBtn = document.getElementById('menu-btn');
      
      if (!mobileMenu.contains(e.target) && e.target !== menuBtn) {
        mobileMenu.classList.add('translate-x-full');
      }
    });
  </script>
</div>

<div id="root">
  <section id="hero" class="min-h-screen bg-neutral-900 relative overflow-hidden">
    <!-- Particle Background -->
    <div id="particles-js" class="absolute inset-0 opacity-50"></div>
    
    <div class="container mx-auto px-6 relative z-10 pt-32">
      <div class="flex flex-col items-start justify-center h-[calc(100vh-8rem)]">
        <div class="animate__animated animate__fadeIn">
          <span class="inline-block text-[#64FFDA] font-space-grotesk text-lg mb-4">
            Hello, I'm shravan
          </span>
        </div>
        
        <div class="animate__animated animate__fadeInUp animate__delay-1s">
          <h1 class="text-white text-5xl md:text-7xl font-bold mb-6 font-space-grotesk">
            AI & Data Science
            <span class="block">Professional</span>
          </h1>
        </div>
        
        <div class="animate__animated animate__fadeInUp animate__delay-2s">
          <p class="text-gray-400 text-xl max-w-2xl mb-8 font-roboto-mono">
            Transforming complex data into actionable insights through advanced AI solutions and machine learning algorithms.
          </p>
        </div>
        
        <div class="flex gap-6 animate__animated animate__fadeInUp animate__delay-3s">
          <button class="px-8 py-3 bg-[#64FFDA] text-neutral-900 rounded-md hover:bg-[#64FFDA]/90 transition-all duration-300 font-space-grotesk">
            View Projects
          </button>
          <button class="px-8 py-3 border-2 border-[#64FFDA] text-[#64FFDA] rounded-md hover:bg-[#64FFDA]/10 transition-all duration-300 font-space-grotesk">
            Contact Me
          </button>
        </div>
        
        <div class="absolute bottom-12 left-1/2 transform -translate-x-1/2 animate__animated animate__bounce animate__infinite">
          <div class="w-8 h-12 rounded-full border-2 border-[#64FFDA] flex justify-center items-start p-2">
            <div class="w-1 h-3 bg-[#64FFDA] rounded-full animate-scroll"></div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <script>
    particlesJS('particles-js', {
      particles: {
        number: { value: 80, density: { enable: true, value_area: 800 } },
        color: { value: '#64FFDA' },
        shape: { type: 'circle' },
        opacity: { value: 0.5, random: false },
        size: { value: 3, random: true },
        line_linked: {
          enable: true,
          distance: 150,
          color: '#64FFDA',
          opacity: 0.2,
          width: 1
        },
        move: {
          enable: true,
          speed: 2,
          direction: 'none',
          random: false,
          straight: false,
          out_mode: 'out',
          bounce: false,
        }
      },
      interactivity: {
        detect_on: 'canvas',
        events: {
          onhover: { enable: true, mode: 'repulse' },
          onclick: { enable: true, mode: 'push' },
          resize: true
        }
      },
      retina_detect: true
    });

    // Smooth scroll animation
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
  </script>

  <style>
    @keyframes scroll {
      0% { transform: translateY(0); }
      50% { transform: translateY(8px); }
      100% { transform: translateY(0); }
    }
    .animate-scroll {
      animation: scroll 2s ease-in-out infinite;
    }
  </style>
</div>

<div id="root">
  <section id="about" class="py-20 bg-neutral-800">
    <div class="container mx-auto px-6">
      <div class="mb-16 animate__animated animate__fadeIn">
        <h2 class="text-4xl font-bold text-white mb-4 font-space-grotesk">About Me</h2>
        <div class="w-20 h-1 bg-[#64FFDA]"></div>
      </div>

      <div class="grid md:grid-cols-2 gap-12 items-center">
        <div class="animate__animated animate__fadeInLeft">
          <p class="text-gray-300 text-lg mb-6 font-roboto-mono">
            Hi, I'm Shravan, a passionate learner exploring the vast world of Applied AI & Data Science at IIT Jodhpur. My journey in tech started back in 8th grade, when I was first introduced to programming. That moment was a turning point—I realized how powerful coding could be, and it sparked my curiosity to dive deeper into the world of technology.

At that time, I didn’t have a specific domain in tech, but I knew one thing: I wanted to build my future in technology. As I progressed, I kept exploring different fields, and then in 11th grade, I discovered AI—and it completely changed my perspective. AI wasn’t just another subject; it was a field that fascinated me beyond anything else. Unlike in 8th grade, where I had no clear direction, by 11th grade, I found my passion in AI, and it became the domain I wanted to master.

Now, as I continue my learning journey at IIT Jodhpur, I am focused on machine learning, deep learning, and data-driven solutions. I am excited about leveraging AI to solve real-world challenges and make an impact in the field of Applied AI & Data Science.

🚀 Let's connect and build the future with AI!          </p>
        </div>

        <div class="space-y-6 animate__animated animate__fadeInRight">
          <div class="relative timeline-container">
            <!-- Timeline items -->
            <div class="border-l-2 border-[#64FFDA] ml-3">
              <div class="transform transition-all hover:scale-105 duration-300">
                <div class="flex items-center mb-8 relative">
                  <div class="absolute -left-[7px] w-3 h-3 bg-[#64FFDA] rounded-full"></div>
                  <div class="ml-6">
                    <div class="bg-neutral-700 p-6 rounded-lg">
                      <h3 class="text-[#64FFDA] font-bold mb-2">Algorithmic Thinking and its Applications</h3>
                      <p class="text-white">Learning</p>
                      <p class="text-gray-400 mt-2">By IIT Jodhpur Associate Professor Dr. <a href="https://sites.google.com/site/dipsankarban/">Dip Sankar Banarjee</a></p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="transform transition-all hover:scale-105 duration-300">
                <div class="flex items-center mb-8 relative">
                  <div class="absolute -left-[7px] w-3 h-3 bg-[#64FFDA] rounded-full"></div>
                  <div class="ml-6">
                    <div class="bg-neutral-700 p-6 rounded-lg">
                      <h3 class="text-[#64FFDA] font-bold mb-2">Basics Of Data Analytics</h3>
                      <p class="text-white">Learning</p>
                      <p class="text-gray-400 mt-2">By IIT Jodhpur Associate Professor Dweepobotee
                        Brahma</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="transform transition-all hover:scale-105 duration-300">
                <div class="flex items-center mb-8 relative">
                  <div class="absolute -left-[7px] w-3 h-3 bg-[#64FFDA] rounded-full"></div>
                  <div class="ml-6">
                    <div class="bg-neutral-700 p-6 rounded-lg">
                      <h3 class="text-[#64FFDA] font-bold mb-2">Linear Algebra &
                        Numerical Analysis</h3>
                      <p class="text-white">Learning</p>
                      <p class="text-gray-400 mt-2">By IIT Jodhpur Associate Professor Dr. Dipanjan Roy</p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="transform transition-all hover:scale-105 duration-300">
                <div class="flex items-center relative">
                  <div class="absolute -left-[7px] w-3 h-3 bg-[#64FFDA] rounded-full"></div>
                  <div class="ml-6">
                    <div class="bg-neutral-700 p-6 rounded-lg">
                      <h3 class="text-[#64FFDA] font-bold mb-2">Foundation of Statistics
                        and Probablity</h3>
                      <p class="text-white">Learning</p>
                      <p class="text-gray-400 mt-2">By IIT Jodhpur Associate Professor Dr. Railaxmi Chouhan</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="mt-20 grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-neutral-700 p-8 rounded-lg transform transition-all hover:scale-105 duration-300 animate__animated animate__fadeInUp">
          <div class="text-[#64FFDA] text-4xl mb-4">
            <i class="fa-brands fa-python"></i>
          </div>
          <h3 class="text-white text-xl font-bold mb-4">Python</h3>
          <p class="text-gray-300">We have a strong foundation in Python, utilizing it for various applications in Artificial Intelligence and Data Science</p>
        </div>

        <div class="bg-neutral-700 p-8 rounded-lg transform transition-all hover:scale-105 duration-300 animate__animated animate__fadeInUp animate__delay-1s">
          <div class="text-[#64FFDA] text-4xl mb-4">
            <i class="fas fa-database"></i>
          </div>
          <h3 class="text-white text-xl font-bold mb-4">SQL</h3>
          <p class="text-gray-300"> We understand databases, queries, and optimization techniques.</p>
        </div>

        <div class="bg-neutral-700 p-8 rounded-lg transform transition-all hover:scale-105 duration-300 animate__animated animate__fadeInUp animate__delay-2s">
          <div class="text-[#64FFDA] text-4xl mb-4">
            <i class="fa-solid fa-globe"></i>
          </div>
          <h3 class="text-white text-xl font-bold mb-4">WEB Development</h3>
          <p class="text-gray-300">We build websites using HTML, CSS, JavaScript, and backend frameworks like Flask and Django.</p>
        </div>
      </div>
    </div>
  </section>
</div>

<div id="root">
  <section id="experience" class="py-20 bg-neutral-900">
    <div class="container mx-auto px-6">
      <div class="mb-16 animate__animated animate__fadeIn">
        <h2 class="text-4xl font-bold text-white mb-4 font-space-grotesk">Experience</h2>
        <div class="w-20 h-1 bg-[#64FFDA]"></div>
      </div>

      <div class="grid md:grid-cols-2 gap-12">
        <!-- Experience Tabs -->
        <div class="animate__animated animate__fadeInLeft">
          <div class="flex flex-col md:flex-row">
            <div class="border-l-2 border-[#64FFDA] mb-8 md:mb-0">
              <button class="px-6 py-3 text-left w-full hover:bg-neutral-800 transition-colors duration-300 focus:outline-none text-[#64FFDA] bg-neutral-800" data-tab="1">
                Senior Data Scientist
              </button>
              <button class="px-6 py-3 text-left w-full hover:bg-neutral-800 transition-colors duration-300 focus:outline-none text-gray-400" data-tab="2">
                ML Engineer
              </button>
              <button class="px-6 py-3 text-left w-full hover:bg-neutral-800 transition-colors duration-300 focus:outline-none text-gray-400" data-tab="3">
                Data Analyst
              </button>
            </div>
          </div>
        </div>

        <!-- Experience Content -->
        <div class="animate__animated animate__fadeInRight">
          <div class="tab-content" id="tab1">
            <h3 class="text-2xl font-bold text-white mb-2">Senior Data Scientist @ Tech Corp</h3>
            <p class="text-[#64FFDA] mb-4">2020 - Present</p>
            <ul class="space-y-4">
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Led a team of 5 data scientists in developing advanced ML models for prediction</span>
              </li>
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Implemented state-of-the-art NLP solutions resulting in 40% efficiency improvement</span>
              </li>
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Architected end-to-end ML pipelines using AWS and Azure cloud services</span>
              </li>
            </ul>
          </div>

          <div class="tab-content hidden" id="tab2">
            <h3 class="text-2xl font-bold text-white mb-2">ML Engineer @ AI Solutions Inc</h3>
            <p class="text-[#64FFDA] mb-4">2018 - 2020</p>
            <ul class="space-y-4">
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Developed computer vision models for autonomous systems</span>
              </li>
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Optimized model performance resulting in 60% faster inference time</span>
              </li>
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Created automated testing frameworks for ML models</span>
              </li>
            </ul>
          </div>

          <div class="tab-content hidden" id="tab3">
            <h3 class="text-2xl font-bold text-white mb-2">Data Analyst @ Data Corp</h3>
            <p class="text-[#64FFDA] mb-4">2016 - 2018</p>
            <ul class="space-y-4">
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Conducted statistical analysis on large-scale datasets</span>
              </li>
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Created interactive dashboards using Power BI and Tableau</span>
              </li>
              <li class="flex items-start">
                <span class="text-[#64FFDA] mr-2">▹</span>
                <span class="text-gray-300">Improved data collection processes by implementing automated systems</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <script>
    // Tab functionality
    const tabs = document.querySelectorAll('[data-tab]');
    const contents = document.querySelectorAll('.tab-content');

    tabs.forEach(tab => {
      tab.addEventListener('click', () => {
        // Reset all tabs
        tabs.forEach(t => {
          t.classList.remove('bg-neutral-800', 'text-[#64FFDA]');
          t.classList.add('text-gray-400');
        });

        // Hide all content
        contents.forEach(c => c.classList.add('hidden'));

        // Show selected content
        const contentId = `tab${tab.dataset.tab}`;
        document.getElementById(contentId).classList.remove('hidden');

        // Highlight selected tab
        tab.classList.add('bg-neutral-800', 'text-[#64FFDA]');
        tab.classList.remove('text-gray-400');
      });
    });
  </script>
</div>
<div id="root">
  <section id="projects" class="py-20 bg-neutral-800">
    <div class="container mx-auto px-6">
      <div class="mb-16 animate__animated animate__fadeIn">
        <h2 class="text-4xl font-bold text-white mb-4 font-space-grotesk">Projects</h2>
        <div class="w-20 h-1 bg-[#64FFDA]"></div>
      </div>

      <!-- Filter Buttons -->
      <div class="flex flex-wrap gap-4 mb-12 animate__animated animate__fadeInUp">
        <button class="filter-btn active px-6 py-2 rounded-full bg-[#64FFDA] text-neutral-900 font-medium transition-all duration-300" data-filter="all">
          All
        </button>
        <button class="filter-btn px-6 py-2 rounded-full bg-neutral-700 text-gray-300 hover:bg-[#64FFDA] hover:text-neutral-900 transition-all duration-300" data-filter="ml">
          Machine Learning
        </button>
        <button class="filter-btn px-6 py-2 rounded-full bg-neutral-700 text-gray-300 hover:bg-[#64FFDA] hover:text-neutral-900 transition-all duration-300" data-filter="dl">
          Deep Learning
        </button>
        <button class="filter-btn px-6 py-2 rounded-full bg-neutral-700 text-gray-300 hover:bg-[#64FFDA] hover:text-neutral-900 transition-all duration-300" data-filter="nlp">
          NLP
        </button>
      </div>

      <!-- Projects Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Project 1 -->
        <div class="project-card animate__animated animate__fadeInUp" data-category="ml">
          <div class="bg-neutral-700 rounded-lg overflow-hidden transform hover:scale-105 transition-all duration-300">
            <div class="p-6">
              <div class="text-[#64FFDA] mb-4">
                <i class="fas fa-brain text-3xl"></i>
              </div>
              <h3 class="text-xl font-bold text-white mb-3">Predictive Analytics Engine</h3>
              <p class="text-gray-300 mb-4">Advanced ML model for predictive maintenance using sensor data.</p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">Python</span>
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">TensorFlow</span>
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">AWS</span>
              </div>
              <button class="view-project text-white hover:text-[#64FFDA] transition-colors duration-300">
                Learn More →
              </button>
            </div>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="project-card animate__animated animate__fadeInUp animate__delay-1s" data-category="dl">
          <div class="bg-neutral-700 rounded-lg overflow-hidden transform hover:scale-105 transition-all duration-300">
            <div class="p-6">
              <div class="text-[#64FFDA] mb-4">
                <i class="fas fa-robot text-3xl"></i>
              </div>
              <h3 class="text-xl font-bold text-white mb-3">Computer Vision System</h3>
              <p class="text-gray-300 mb-4">Real-time object detection system using deep learning.</p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">PyTorch</span>
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">OpenCV</span>
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">CUDA</span>
              </div>
              <button class="view-project text-white hover:text-[#64FFDA] transition-colors duration-300">
                Learn More →
              </button>
            </div>
          </div>
        </div>

        <!-- Project 3 -->
        <div class="project-card animate__animated animate__fadeInUp animate__delay-2s" data-category="nlp">
          <div class="bg-neutral-700 rounded-lg overflow-hidden transform hover:scale-105 transition-all duration-300">
            <div class="p-6">
              <div class="text-[#64FFDA] mb-4">
                <i class="fas fa-language text-3xl"></i>
              </div>
              <h3 class="text-xl font-bold text-white mb-3">NLP Chatbot</h3>
              <p class="text-gray-300 mb-4">Advanced conversational AI using transformer architecture.</p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">BERT</span>
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">FastAPI</span>
                <span class="px-3 py-1 bg-neutral-600 text-[#64FFDA] rounded-full text-sm">Docker</span>
              </div>
              <button class="view-project text-white hover:text-[#64FFDA] transition-colors duration-300">
                Learn More →
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Project Modal -->
    <div id="projectModal" class="fixed inset-0 bg-black bg-opacity-80 z-50 hidden flex items-center justify-center">
      <div class="bg-neutral-800 rounded-lg max-w-2xl w-full mx-4 animate__animated animate__fadeInUp">
        <div class="p-6">
          <div class="flex justify-between items-center mb-4">
            <h3 class="text-2xl font-bold text-white" id="modalTitle"></h3>
            <button class="close-modal text-gray-400 hover:text-white">
              <i class="fas fa-times text-xl"></i>
            </button>
          </div>
          <div id="modalContent"></div>
        </div>
      </div>
    </div>
  </section>

  <script>
    // Filter functionality
    const filterBtns = document.querySelectorAll('.filter-btn');
    const projectCards = document.querySelectorAll('.project-card');

    filterBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        // Remove active class from all buttons
        filterBtns.forEach(b => b.classList.remove('active', 'bg-[#64FFDA]', 'text-neutral-900'));
        // Add active class to clicked button
        btn.classList.add('active', 'bg-[#64FFDA]', 'text-neutral-900');

        const filter = btn.dataset.filter;
        projectCards.forEach(card => {
          if (filter === 'all' || card.dataset.category === filter) {
            card.style.display = 'block';
          } else {
            card.style.display = 'none';
          }
        });
      });
    });

    // Modal functionality
    const modal = document.getElementById('projectModal');
    const modalTitle = document.getElementById('modalTitle');
    const modalContent = document.getElementById('modalContent');
    const viewButtons = document.querySelectorAll('.view-project');
    const closeModal = document.querySelector('.close-modal');

    viewButtons.forEach(btn => {
      btn.addEventListener('click', (e) => {
        const project = e.target.closest('.project-card');
        const title = project.querySelector('h3').textContent;
        const description = project.querySelector('p').textContent;
        
        modalTitle.textContent = title;
        modalContent.innerHTML = `
          <p class="text-gray-300 mb-4">${description}</p>
          <div class="space-y-4">
            <h4 class="text-[#64FFDA] font-bold">Key Features:</h4>
            <ul class="list-disc list-inside text-gray-300">
              <li>Feature 1</li>
              <li>Feature 2</li>
              <li>Feature 3</li>
            </ul>
          </div>
        `;
        
        modal.classList.remove('hidden');
      });
    });

    closeModal.addEventListener('click', () => {
      modal.classList.add('hidden');
    });

    window.addEventListener('click', (e) => {
      if (e.target === modal) {
        modal.classList.add('hidden');
      }
    });
  </script>
</div><div id="root">
  <section id="skills" class="py-20 bg-neutral-900">
    <div class="container mx-auto px-6">
      <div class="mb-16 animate__animated animate__fadeIn">
        <h2 class="text-4xl font-bold text-white mb-4 font-space-grotesk">Skills & Technologies</h2>
        <div class="w-20 h-1 bg-[#64FFDA]"></div>
      </div>

      <div class="grid md:grid-cols-2 gap-12 items-center">
        <!-- 3D Tech Cloud -->
        <div class="relative h-[400px] animate__animated animate__fadeInLeft" id="tagcloud">
          <!-- TagCloud.js will inject content here -->
        </div>

        <!-- Skills Progress -->
        <div class="space-y-6 animate__animated animate__fadeInRight">
          <div>
            <div class="flex justify-between mb-2">
              <span class="text-white">Machine Learning</span>
              <span class="text-[#64FFDA]">95%</span>
            </div>
            <div class="h-2 bg-neutral-700 rounded-full">
              <div class="h-full bg-[#64FFDA] rounded-full progress-bar" data-width="95"></div>
            </div>
          </div>

          <div>
            <div class="flex justify-between mb-2">
              <span class="text-white">Deep Learning</span>
              <span class="text-[#64FFDA]">90%</span>
            </div>
            <div class="h-2 bg-neutral-700 rounded-full">
              <div class="h-full bg-[#64FFDA] rounded-full progress-bar" data-width="90"></div>
            </div>
          </div>

          <div>
            <div class="flex justify-between mb-2">
              <span class="text-white">Data Engineering</span>
              <span class="text-[#64FFDA]">85%</span>
            </div>
            <div class="h-2 bg-neutral-700 rounded-full">
              <div class="h-full bg-[#64FFDA] rounded-full progress-bar" data-width="85"></div>
            </div>
          </div>

          <div>
            <div class="flex justify-between mb-2">
              <span class="text-white">Cloud Computing</span>
              <span class="text-[#64FFDA]">88%</span>
            </div>
            <div class="h-2 bg-neutral-700 rounded-full">
              <div class="h-full bg-[#64FFDA] rounded-full progress-bar" data-width="88"></div>
            </div>
          </div>
        </div>
      </div>

      <!-- Technology Cards -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-20">
        <div class="bg-neutral-800 p-6 rounded-lg transform hover:scale-105 transition-all duration-300 animate__animated animate__fadeInUp">
          <h3 class="text-[#64FFDA] text-xl font-bold mb-4">Programming</h3>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">Python</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">R</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">SQL</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">Julia</span>
          </div>
        </div>

        <div class="bg-neutral-800 p-6 rounded-lg transform hover:scale-105 transition-all duration-300 animate__animated animate__fadeInUp animate__delay-1s">
          <h3 class="text-[#64FFDA] text-xl font-bold mb-4">Frameworks</h3>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">TensorFlow</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">PyTorch</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">Scikit-learn</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">Keras</span>
          </div>
        </div>

        <div class="bg-neutral-800 p-6 rounded-lg transform hover:scale-105 transition-all duration-300 animate__animated animate__fadeInUp animate__delay-2s">
          <h3 class="text-[#64FFDA] text-xl font-bold mb-4">Tools</h3>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">Docker</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">Git</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">AWS</span>
            <span class="px-3 py-1 bg-neutral-700 text-gray-300 rounded-full">Kubernetes</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <script src="https://cdn.jsdelivr.net/npm/TagCloud@2.2.0/dist/TagCloud.min.js"></script>
  <script>
    // TagCloud
    const container = '#tagcloud';
    const texts = [
      'Python', 'TensorFlow', 'PyTorch', 'Scikit-learn',
      'SQL', 'AWS', 'Docker', 'Kubernetes',
      'Machine Learning', 'Deep Learning', 'NLP',
      'Computer Vision', 'Data Engineering', 'MLOps'
    ];

    const options = {
      radius: 230,
      maxSpeed: 'normal',
      initSpeed: 'normal',
      keep: true,
      useContainerInlineStyles: true,
      useItemInlineStyles: true,
      containerClass: 'tagcloud',
      itemClass: 'tagcloud--item'
    };

    window.TagCloud(container, texts, options);

    // Animate progress bars on scroll
    const progressBars = document.querySelectorAll('.progress-bar');

    const animateProgress = () => {
      progressBars.forEach(bar => {
        const width = bar.dataset.width;
        bar.style.width = '0%';
        setTimeout(() => {
          bar.style.width = `${width}%`;
          bar.style.transition = 'width 1.5s ease-in-out';
        }, 300);
      });
    };

    // Intersection Observer for progress bars
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          animateProgress();
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.5 });

    document.querySelector('.space-y-6').querySelectorAll('.progress-bar').forEach(bar => {
      observer.observe(bar);
    });
  </script>

  <style>
    .tagcloud {
      color: #64FFDA;
      font-family: 'Space Grotesk', sans-serif;
      font-weight: bold;
      font-size: 1rem;
    }
    .tagcloud--item {
      padding: 2px 4px;
      background-color: transparent;
      border-radius: 3px;
      border: 1px solid transparent;
      transition: all 0.3s ease;
    }
    .tagcloud--item:hover {
      background-color: rgba(100, 255, 218, 0.1);
      border-color: #64FFDA;
    }
    .progress-bar {
      width: 0%;
      transition: width 1.5s ease-in-out;
    }
  </style>
</div><div id="root">
  <section id="blog" class="py-20 bg-neutral-800">
    <div class="container mx-auto px-6">
      <div class="mb-16 animate__animated animate__fadeIn">
        <h2 class="text-4xl font-bold text-white mb-4 font-space-grotesk">Blog & Insights</h2>
        <div class="w-20 h-1 bg-[#64FFDA]"></div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Blog Post 1 -->
        <article class="bg-neutral-700 rounded-lg overflow-hidden transform hover:scale-105 transition-all duration-300 animate__animated animate__fadeInUp">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <span class="text-[#64FFDA] text-sm">Machine Learning</span>
              <span class="mx-2 text-gray-400">•</span>
              <span class="text-gray-400 text-sm">5 min read</span>
            </div>
            <h3 class="text-xl font-bold text-white mb-3 hover:text-[#64FFDA] transition-colors duration-300">
              The Future of Neural Networks in 2024
            </h3>
            <p class="text-gray-300 mb-4">
              Exploring the latest advancements in neural network architectures and their practical applications.
            </p>
            <div class="flex items-center justify-between">
              <span class="text-gray-400 text-sm">March 15, 2024</span>
              <button class="text-[#64FFDA] hover:underline">Read More →</button>
            </div>
          </div>
        </article>

        <!-- Blog Post 2 -->
        <article class="bg-neutral-700 rounded-lg overflow-hidden transform hover:scale-105 transition-all duration-300 animate__animated animate__fadeInUp animate__delay-1s">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <span class="text-[#64FFDA] text-sm">Deep Learning</span>
              <span class="mx-2 text-gray-400">•</span>
              <span class="text-gray-400 text-sm">8 min read</span>
            </div>
            <h3 class="text-xl font-bold text-white mb-3 hover:text-[#64FFDA] transition-colors duration-300">
              Optimizing Transformer Models
            </h3>
            <p class="text-gray-300 mb-4">
              A deep dive into performance optimization techniques for large language models.
            </p>
            <div class="flex items-center justify-between">
              <span class="text-gray-400 text-sm">March 10, 2024</span>
              <button class="text-[#64FFDA] hover:underline">Read More →</button>
            </div>
          </div>
        </article>

        <!-- Blog Post 3 -->
        <article class="bg-neutral-700 rounded-lg overflow-hidden transform hover:scale-105 transition-all duration-300 animate__animated animate__fadeInUp animate__delay-2s">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <span class="text-[#64FFDA] text-sm">AI Ethics</span>
              <span class="mx-2 text-gray-400">•</span>
              <span class="text-gray-400 text-sm">6 min read</span>
            </div>
            <h3 class="text-xl font-bold text-white mb-3 hover:text-[#64FFDA] transition-colors duration-300">
              Responsible AI Development
            </h3>
            <p class="text-gray-300 mb-4">
              Understanding the importance of ethical considerations in AI system development.
            </p>
            <div class="flex items-center justify-between">
              <span class="text-gray-400 text-sm">March 5, 2024</span>
              <button class="text-[#64FFDA] hover:underline">Read More →</button>
            </div>
          </div>
        </article>
      </div>

      <!-- Newsletter Subscription -->
      <div class="mt-16 bg-neutral-900 rounded-lg p-8 animate__animated animate__fadeIn">
        <div class="max-w-2xl mx-auto text-center">
          <h3 class="text-2xl font-bold text-white mb-4">Stay Updated</h3>
          <p class="text-gray-300 mb-6">Subscribe to my newsletter for the latest insights in AI and Data Science</p>
          
          <form class="flex flex-col sm:flex-row gap-4 justify-center">
            <input 
              type="email" 
              placeholder="Enter your email" 
              class="px-4 py-2 bg-neutral-800 border border-neutral-700 rounded-md focus:outline-none focus:border-[#64FFDA] text-white w-full sm:w-auto"
              required
            >
            <button 
              type="submit" 
              class="px-6 py-2 bg-[#64FFDA] text-neutral-900 rounded-md hover:bg-[#64FFDA]/90 transition-colors duration-300 font-medium w-full sm:w-auto"
            >
              Subscribe
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <script>
    // Newsletter Form Animation
    const form = document.querySelector('form');
    form.addEventListener('submit', (e) => {
      e.preventDefault();
      const email = e.target.querySelector('input[type="email"]');
      if (email.value) {
        email.value = '';
        alert('Thanks for subscribing!');
      }
    });

    // Blog Post Hover Animation
    const articles = document.querySelectorAll('article');
    articles.forEach(article => {
      article.addEventListener('mouseenter', () => {
        article.querySelector('h3').classList.add('text-[#64FFDA]');
      });
      article.addEventListener('mouseleave', () => {
        article.querySelector('h3').classList.remove('text-[#64FFDA]');
      });
    });
  </script>
</div><div id="root">
  <section id="contact" class="py-20 bg-neutral-900">
    <div class="container mx-auto px-6">
      <div class="mb-16 animate__animated animate__fadeIn">
        <h2 class="text-4xl font-bold text-white mb-4 font-space-grotesk">Get in Touch</h2>
        <div class="w-20 h-1 bg-[#64FFDA]"></div>
      </div>

      <div class="grid md:grid-cols-2 gap-12">
        <!-- Contact Form -->
        <div class="animate__animated animate__fadeInLeft">
          <form class="space-y-6">
            <div class="relative">
              <input type="text" id="name" required
                class="block w-full px-4 py-3 bg-neutral-800 border border-neutral-700 rounded-lg text-white focus:outline-none focus:border-[#64FFDA] peer"
                placeholder=" "
              />
              <label for="name" 
                class="absolute text-gray-400 duration-300 transform -translate-y-4 scale-75 top-2 z-10 origin-[0] bg-neutral-800 px-2 peer-focus:px-2 peer-placeholder-shown:scale-100 peer-placeholder-shown:-translate-y-1/2 peer-placeholder-shown:top-1/2 peer-focus:top-2 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:text-[#64FFDA] left-1">
                Name
              </label>
            </div>

            <div class="relative">
              <input type="email" id="email" required
                class="block w-full px-4 py-3 bg-neutral-800 border border-neutral-700 rounded-lg text-white focus:outline-none focus:border-[#64FFDA] peer"
                placeholder=" "
              />
              <label for="email"
                class="absolute text-gray-400 duration-300 transform -translate-y-4 scale-75 top-2 z-10 origin-[0] bg-neutral-800 px-2 peer-focus:px-2 peer-placeholder-shown:scale-100 peer-placeholder-shown:-translate-y-1/2 peer-placeholder-shown:top-1/2 peer-focus:top-2 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:text-[#64FFDA] left-1">
                Email
              </label>
            </div>

            <div class="relative">
              <textarea id="message" rows="5" required
                class="block w-full px-4 py-3 bg-neutral-800 border border-neutral-700 rounded-lg text-white focus:outline-none focus:border-[#64FFDA] peer"
                placeholder=" "
              ></textarea>
              <label for="message"
                class="absolute text-gray-400 duration-300 transform -translate-y-4 scale-75 top-2 z-10 origin-[0] bg-neutral-800 px-2 peer-focus:px-2 peer-placeholder-shown:scale-100 peer-placeholder-shown:-translate-y-1/2 peer-placeholder-shown:top-6 peer-focus:top-2 peer-focus:-translate-y-4 peer-focus:scale-75 peer-focus:text-[#64FFDA] left-1">
                Message
              </label>
            </div>

            <button type="submit"
              class="w-full px-6 py-3 bg-[#64FFDA] text-neutral-900 rounded-lg hover:bg-[#64FFDA]/90 transition-colors duration-300 font-medium">
              Send Message
            </button>
          </form>
        </div>

        <!-- Contact Info -->
        <div class="space-y-8 animate__animated animate__fadeInRight">
          <div>
            <h3 class="text-2xl font-bold text-white mb-4">Contact Information</h3>
            <p class="text-gray-300 mb-6">Feel free to reach out for collaborations or just a friendly chat about AI and Data Science.</p>
          </div>

          <div class="space-y-4">
            <div class="flex items-center space-x-4">
              <div class="w-12 h-12 bg-neutral-800 rounded-lg flex items-center justify-center text-[#64FFDA]">
                <i class="fas fa-envelope text-xl"></i>
              </div>
              <div>
                <p class="text-gray-400">Email</p>
                <p class="text-white">contact@example.com</p>
              </div>
            </div>

            <div class="flex items-center space-x-4">
              <div class="w-12 h-12 bg-neutral-800 rounded-lg flex items-center justify-center text-[#64FFDA]">
                <i class="fas fa-map-marker-alt text-xl"></i>
              </div>
              <div>
                <p class="text-gray-400">Location</p>
                <p class="text-white">San Francisco, CA</p>
              </div>
            </div>
          </div>

          <div class="pt-8">
            <h4 class="text-white mb-4">Connect with me</h4>
            <div class="flex space-x-4">
              <a href="#" class="social-icon w-12 h-12 bg-neutral-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-[#64FFDA] hover:bg-neutral-700 transition-all duration-300">
                <i class="fab fa-linkedin-in text-xl"></i>
              </a>
              <a href="#" class="social-icon w-12 h-12 bg-neutral-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-[#64FFDA] hover:bg-neutral-700 transition-all duration-300">
                <i class="fab fa-github text-xl"></i>
              </a>
              <a href="#" class="social-icon w-12 h-12 bg-neutral-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-[#64FFDA] hover:bg-neutral-700 transition-all duration-300">
                <i class="fab fa-twitter text-xl"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <script>
    // Form submission animation
    const form = document.querySelector('form');
    form.addEventListener('submit', (e) => {
      e.preventDefault();
      const button = form.querySelector('button');
      button.innerHTML = 'Sending...';
      setTimeout(() => {
        button.innerHTML = 'Message Sent!';
        button.style.backgroundColor = '#4CAF50';
        setTimeout(() => {
          button.innerHTML = 'Send Message';
          button.style.backgroundColor = '#64FFDA';
          form.reset();
        }, 2000);
      }, 1500);
    });

    // Social icons hover animation
    const socialIcons = document.querySelectorAll('.social-icon');
    socialIcons.forEach(icon => {
      icon.addEventListener('mouseenter', () => {
        icon.classList.add('animate__animated', 'animate__pulse');
      });
      icon.addEventListener('mouseleave', () => {
        icon.classList.remove('animate__animated', 'animate__pulse');
      });
    });
  </script>
</div><div id="root">
  <footer id="footer" class="bg-neutral-900 pt-16 pb-8">
    <div class="container mx-auto px-6">
      <div class="grid md:grid-cols-4 gap-8 mb-12">
        <!-- Brand Section -->
        <div class="col-span-1 md:col-span-2">
          <a href="/" class="text-[#64FFDA] font-space-grotesk text-2xl font-bold mb-4 block">
            AI.Portfolio
          </a>
          <p class="text-gray-400 mb-6 max-w-md">
            Building the future with AI and Data Science. Transforming complex data into actionable insights.
          </p>
          <a href="/resume" class="inline-flex items-center px-6 py-3 bg-[#64FFDA] text-neutral-900 rounded-lg hover:bg-[#64FFDA]/90 transition-all duration-300 font-medium animate__animated animate__pulse animate__infinite">
            <i class="fas fa-download mr-2"></i>
            Download Resume
          </a>
        </div>

        <!-- Quick Links -->
        <div>
          <h3 class="text-white font-bold mb-4">Quick Links</h3>
          <ul class="space-y-3">
            <li>
              <a href="/" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Home
              </a>
            </li>
            <li>
              <a href="/about" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                About
              </a>
            </li>
            <li>
              <a href="/experience" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Experience
              </a>
            </li>
            <li>
              <a href="/projects" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Projects
              </a>
            </li>
            <li>
              <a href="/skills" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Skills
              </a>
            </li>
            <li>
              <a href="/blog" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Blog
              </a>
            </li>
            <li>
              <a href="/contact" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Contact
              </a>
            </li>
          </ul>
        </div>

        <!-- Legal Links -->
        <div>
          <h3 class="text-white font-bold mb-4">Legal</h3>
          <ul class="space-y-3">
            <li>
              <a href="/privacy" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Privacy Policy
              </a>
            </li>
            <li>
              <a href="/terms" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Terms of Use
              </a>
            </li>
            <li>
              <a href="/resume" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                Resume
              </a>
            </li>
            <li>
              <a href="#" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                LinkedIn
              </a>
            </li>
            <li>
              <a href="#" class="text-gray-400 hover:text-[#64FFDA] transition-colors duration-300">
                GitHub
              </a>
            </li>
          </ul>
        </div>
      </div>

      <!-- Social Links -->
      <div class="border-t border-neutral-800 pt-8 mt-8">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <div class="text-gray-400 mb-4 md:mb-0">
            © 2024 Shravan Kumar. All rights reserved.
          </div>
          <div class="flex space-x-4">
            <a href="#" class="social-icon w-10 h-10 bg-neutral-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-[#64FFDA] hover:bg-neutral-700 transition-all duration-300">
              <i class="fab fa-linkedin-in"></i>
            </a>
            <a href="#" class="social-icon w-10 h-10 bg-neutral-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-[#64FFDA] hover:bg-neutral-700 transition-all duration-300">
              <i class="fab fa-github"></i>
            </a>
            <a href="#" class="social-icon w-10 h-10 bg-neutral-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-[#64FFDA] hover:bg-neutral-700 transition-all duration-300">
              <i class="fab fa-twitter"></i>
            </a>
          </div>
        </div>
      </div>
    </div>

    <!-- Chatbot Button -->
    <button id="chatbot-toggle" class="fixed bottom-6 right-6 w-14 h-14 bg-[#64FFDA] rounded-full flex items-center justify-center shadow-lg hover:bg-[#64FFDA]/90 transition-all duration-300 animate__animated animate__bounceIn">
      <i class="fas fa-robot text-neutral-900 text-xl"></i>
    </button>
  </footer>

  <script>
    // Social icons hover animation
    const socialIcons = document.querySelectorAll('.social-icon');
    socialIcons.forEach(icon => {
      icon.addEventListener('mouseenter', () => {
        icon.classList.add('animate__animated', 'animate__pulse');
      });
      icon.addEventListener('mouseleave', () => {
        icon.classList.remove('animate__animated', 'animate__pulse');
      });
    });

    // Chatbot toggle
    const chatbotBtn = document.getElementById('chatbot-toggle');
    chatbotBtn.addEventListener('click', () => {
      // Add chatbot implementation here
      alert('Chatbot functionality coming soon!');
    });
  </script>
</div>
