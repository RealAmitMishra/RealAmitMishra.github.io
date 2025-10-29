<!DOCTYPE html>
<html lang="en" class="">
<head>
  <script>
    // Global error logger
    window.onerror = (m,s,l,c,e) => {
      console.error("GLOBAL ERROR:", m, s, l, c, e);
    };
  </script>
  <meta charset="UTF-8" />
  <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Amit Mishra | Healthcare Business Development & Utilization Review Expert</title>
  <meta name="description" content="Amit Mishra - A forward-thinking expert in healthcare business development, revenue optimization, and strategic growth.">
  <meta name="keywords" content="Amit Mishra, Healthcare Innovation, Business Development, Utilization Review, Behavioral Health, Revenue Optimization, Healthcare Consulting, Keystone Ledger">
  <meta name="author" content="Amit Mishra">
  <link rel="canonical" href="index.html" />

  <!-- Open Graph -->
  <meta property="og:title" content="Amit Mishra | Healthcare Business Development & Utilization Review Expert">
  <meta property="og:image" content="https://lh3.googleusercontent.com/pw/AP1GczM7M_f5tFRo0mUcKNqzN_smlLmBq5lRzk0Lewvu_7u7suTGeZdhJRqeMTb_4KIc6loDheIW64p5cXX_YbWZzpjlh4sVsfLA9ZcxsNCmXAGfGRDN6grw=w1920-h1080">
  <meta property="og:description" content="Amit Mishra - Healthcare business development expert.">

  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Amit Mishra | Healthcare Business Development & Utilization Review Expert">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/pw/AP1GczM7M_f5tFRo0mUcKNqzN_smlLmBq5lRzk0Lewvu_7u7suTGeZdhJRqeMTb_4KIc6loDheIW64p5cXX_YbWZzpjlh4sVsfLA9ZcxsNCmXAGfGRDN6grw=w1920-h1080">
  <meta name="twitter:description" content="Amit Mishra - Healthcare business development expert.">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = { darkMode: 'class' }
  </script>

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  
  <!-- Chart.js (Optional, script will handle if it's missing) -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

  <!-- Critical theme bootstrap (prevents flash) -->
  <script>
    (function () {
      try {
        const isDark = localStorage.getItem('darkMode') === 'true';
        document.documentElement.classList.toggle('dark', isDark);
      } catch {}
    })();
  </script>

  <style>
    html { scroll-behavior: smooth; }
    body { font-family: 'Poppins', sans-serif; }
    section[id] { scroll-margin-top: 80px; }
    .hidden { display: none !important; }

    @keyframes fade-in-up { from { opacity:0; transform: translateY(20px);} to { opacity:1; transform: translateY(0);} }
    .animate-fade-in-up { animation: fade-in-up .5s ease-out forwards; }
    @keyframes fade-in { from { opacity:0; } to { opacity:1; } }
    .animate-fade-in { animation: fade-in .3s ease-out forwards; }

    /* spinner */
    .loader{ width:1.25rem; height:1.25rem; border:2px solid #f3f3f3; border-top:2px solid #3b82f6; border-radius:50%; animation:spin 1s linear infinite; }
    .dark .loader{ border-color:#4b5563; border-top-color:#60a5fa; }
    @keyframes spin { to { transform: rotate(360deg);} }

    /* prose invert helper */
    .dark .prose-invert{ --tw-prose-body:#d1d5db; --tw-prose-headings:#fff; --tw-prose-links:#60a5fa; }
    
    /* Styles for new modals/lightbox from your script */
    #lightbox { background-color: rgba(0,0,0,0.8); backdrop-filter: blur(4px); }
    #lightbox-img { max-height: 90vh; max-width: 90vw; }
    #publication-modal, #email-modal { background-color: rgba(0,0,0,0.6); backdrop-filter: blur(4px); }
    
  </style>
</head>

<body class="bg-white text-gray-900 dark:bg-gray-900 dark:text-gray-300">
  <div id="root">
    <!-- NAV -->
    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 bg-transparent">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between h-20 items-center">
          <a href="#home" class="text-2xl font-bold bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">Amit Mishra</a>
          <div class="hidden md:flex items-center space-x-6 lg:space-x-8">
            <a href="#about" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">About</a>
            <a href="#expertise" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Expertise</a>
            <a href="#insights" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Insights</a>
            <a href="#keystone-ledger" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Keystone Ledger</a>
            <a href="#achievements" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Results</a>
            <a href="#services" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Services</a>
            <a href="#publications" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Features</a>
            <a href="#blog" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Blog</a>
            <a href="#gallery" class="text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 font-medium">Gallery</a>
            <button class="theme-toggle-btn text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400" aria-label="Toggle theme">
              <i class="fas fa-moon text-xl"></i>
            </button>
            <a href="#contact" class="bg-blue-600 text-white px-5 py-2 rounded-md font-semibold hover:bg-blue-700">Contact</a>
          </div>
          <div class="md:hidden flex items-center">
            <button class="theme-toggle-btn text-gray-600 dark:text-gray-300 hover:text-blue-600 dark:hover:text-blue-400 mr-4" aria-label="Toggle theme">
              <i class="fas fa-moon text-xl"></i>
            </button>
            <button id="mobile-menu-toggle" class="text-gray-800 dark:text-gray-200" aria-label="Open menu" aria-expanded="false">
              <i class="fas fa-bars text-2xl"></i>
            </button>
          </div>
        </div>
      </div>
    </nav>

    <!-- MOBILE MENU -->
    <div id="mobile-menu" class="fixed inset-0 z-40 bg-white dark:bg-gray-900 transform translate-x-full transition-transform duration-300 ease-in-out md:hidden">
      <div class="flex flex-col items-center justify-center h-full pt-20">
        <a href="#about" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">About</a>
        <a href="#expertise" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Expertise</a>
        <a href="#insights" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Insights</a>
        <a href="#keystone-ledger" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Keystone Ledger</a>
        <a href="#achievements" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Results</a>
        <a href="#services" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Services</a>
        <a href="#publications" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Features</a>
        <a href="#blog" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Blog</a>
        <a href="#gallery" class="mobile-menu-link py-4 text-2xl text-gray-800 dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-400 font-semibold">Gallery</a>
        <a href="#contact" class="mobile-menu-link mt-6 bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold text-xl hover:bg-blue-700">Contact</a>
      </div>
    </div>

    <main>
      <!-- HERO -->
      <section class="min-h-screen flex items-center bg-gray-50 dark:bg-gray-900 pt-20" id="home">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="grid md:grid-cols-2 gap-12 items-center">
            <div>
              <p class="text-blue-600 dark:text-blue-400 mb-2 text-lg font-semibold">Healthcare Business Development</p>
              <h1 class="text-4xl md:text-6xl font-bold mb-4 text-gray-900 dark:text-white leading-tight">Innovating Healthcare.<br/>Driving Growth.</h1>
              <p class="text-xl mb-8 text-gray-600 dark:text-gray-400 max-w-lg">A seasoned expert in optimizing revenue cycles and fostering strategic partnerships within the behavioral health sector.</p>
              <div class="flex flex-col sm:flex-row gap-4">
                <a href="#contact" class="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold text-center hover:bg-blue-700 hover:scale-105 transition transform">
                  <i class="fas fa-paper-plane mr-2"></i>Let's Connect
                </a>
                <a href="amit-mishra-resume.pdf" download="Amit_Mishra_Resume.pdf" class="border-2 border-blue-600 text-blue-600 px-8 py-3 rounded-lg font-semibold text-center hover:bg-blue-600 hover:text-white dark:border-blue-500 dark:text-blue-500 dark:hover:bg-blue-500 dark:hover:text-white hover:scale-105 transition transform">
                  <i class="fas fa-download mr-2"></i>Download Resume
                </a>
              </div>
            </div>
            <div class="text-center">
              <div class="relative group">
                <img src="https://lh3.googleusercontent.com/pw/AP1GczM7M_f5tFRo0mUcKNqzN_smlLmBq5lRzk0Lewvu_7u7suTGeZdhJRqeMTb_4KIc6loDheIW64p5cXX_YbWZzpjlh4sVsfLA9ZcxsNCmXAGfGRDN6grw=w1920-h1080" alt="Amit Mishra Profile" class="w-full max-w-sm mx-auto h-auto rounded-full object-cover relative z-10 shadow-2xl" onerror="this.src='https://placehold.co/400x400/3B82F6/FFFFFF?text=Amit+Mishra'"/>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- ABOUT -->
      <section id="about" class="py-20 dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
              <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">About Me</span>
            </h2>
            <p class="text-xl text-gray-600 dark:text-gray-400 max-w-3xl mx-auto">A results-driven healthcare executive with a proven track record of transforming behavioral health organizations through strategic business development and operational excellence.</p>
          </div>
          <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-white dark:bg-gray-700 border border-gray-200 dark:border-gray-600 p-8 rounded-xl text-center hover:-translate-y-2 hover:shadow-xl transition">
              <i class="fas fa-brain text-blue-500 text-4xl mb-4"></i>
              <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200 mb-4">Behavioral Health Specialist</h3>
              <p class="text-gray-600 dark:text-gray-400">8+ years of dedicated experience, from direct client care to executive leadership.</p>
            </div>
            <div class="bg-white dark:bg-gray-700 border border-gray-200 dark:border-gray-600 p-8 rounded-xl text-center hover:-translate-y-2 hover:shadow-xl transition">
              <i class="fas fa-gem text-teal-500 text-4xl mb-4"></i>
              <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200 mb-4">High-Net-Worth Expertise</h3>
              <p class="text-gray-600 dark:text-gray-400">Mastery in navigating complex financial arrangements for affluent clients.</p>
            </div>
            <div class="bg-white dark:bg-gray-700 border border-gray-200 dark:border-gray-600 p-8 rounded-xl text-center hover:-translate-y-2 hover:shadow-xl transition">
              <i class="fas fa-chart-line text-blue-500 text-4xl mb-4"></i>
              <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200 mb-4">Revenue Growth Expert</h3>
              <p class="text-gray-600 dark:text-gray-400">Consistently delivered record-breaking financial performance.</p>
            </div>
          </div>
        </div>
      </section>

      <!-- EXPERTISE -->
      <section id="expertise" class="py-20 bg-gray-50 dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
              <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">Core Expertise</span>
            </h2>
            <p class="text-xl text-gray-600 dark:text-gray-400">A comprehensive skill set driving organizational success.</p>
          </div>
          <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
            <div class="text-center"><div class="bg-white dark:bg-gray-800 rounded-lg shadow-md p-6 h-full flex flex-col items-center justify-center"><i class="fas fa-handshake text-5xl mb-4 text-blue-500"></i><h3 class="font-bold text-gray-800 dark:text-gray-200">Business Development</h3></div></div>
            <div class="text-center"><div class="bg-white dark:bg-gray-800 rounded-lg shadow-md p-6 h-full flex flex-col items-center justify-center"><i class="fas fa-file-invoice-dollar text-5xl mb-4 text-teal-500"></i><h3 class="font-bold text-gray-800 dark:text-gray-200">Utilization Review</h3></div></div>
            <div class="text-center"><div class="bg-white dark:bg-gray-800 rounded-lg shadow-md p-6 h-full flex flex-col items-center justify-center"><i class="fas fa-dollar-sign text-5xl mb-4 text-blue-500"></i><h3 class="font-bold text-gray-800 dark:text-gray-200">Financial Negotiations</h3></div></div>
            <div class="text-center"><div class="bg-white dark:bg-gray-800 rounded-lg shadow-md p-6 h-full flex flex-col items-center justify-center"><i class="fas fa-network-wired text-5xl mb-4 text-teal-500"></i><h3 class="font-bold text-gray-800 dark:text-gray-200">Referral Networks</h3></div></div>
          </div>
        </div>
      </section>

      <!-- INSIGHTS -->
      <section id="insights" class="py-20 dark:bg-gray-800">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
            <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">Future of Healthcare</span>
          </h2>
          <p class="text-xl text-gray-600 dark:text-gray-400 mb-8 max-w-3xl mx-auto">Staying ahead of the curve is critical. This section will soon generate up-to-date insights on behavioral healthcare trends.</p>
          <button id="generate-insights-btn" class="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold text-lg inline-flex items-center justify-center gap-2 hover:bg-blue-700 hover:scale-105 transition">
            <span class="btn-icon">✨</span>
            <span class="btn-text">Generate Industry Insights</span>
          </button>
          
          <!-- Container for results (hidden by default) -->
          <div id="insights-result-container" class="mt-8 text-left bg-white dark:bg-gray-900 p-8 rounded-xl shadow-lg border border-gray-200 dark:border-gray-700 min-h-[0] hidden">
            <div id="insights-loading" class="hidden items-center justify-center">
              <div class="loader"></div>
              <p class="ml-4 text-lg text-gray-600 dark:text-gray-400">Generating latest insights...</p>
            </div>
            <div id="insights-content" class="prose dark:prose-invert max-w-none"></div>
            <div id="insights-error" class="text-red-500 text-center"></div>
          </div>
        </div>
      </section>

      <!-- KEYSTONE LEDGER -->
      <section id="keystone-ledger" class="py-20 bg-gray-50 dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
              <span class="bg-gradient-to-r from-teal-500 to-green-600 bg-clip-text text-transparent">Keystone Ledger</span>
            </h2>
            <p class="text-xl text-gray-600 dark:text-gray-400 max-w-3xl mx-auto">Empowering small businesses with clear, concise, and reliable bookkeeping services.</p>
          </div>
          <div class="flex justify-center">
            <div class="w-full max-w-lg bg-white dark:bg-gray-800 p-8 rounded-xl shadow-lg text-center border border-gray-200 dark:border-gray-700">
              <i class="fas fa-calculator text-6xl text-teal-500 mb-4"></i>
              <h3 class="text-2xl font-semibold text-gray-800 dark:text-gray-200 mb-4">Bookkeeping Solutions</h3>
              <p class="text-gray-700 dark:text-gray-300 mb-6">Accurate financial records are the cornerstone of any successful business. Keystone Ledger provides tailored bookkeeping services to keep your finances organized and compliant.</p>
              <p class="text-sm text-gray-500 dark:text-gray-400">(Website and contact information coming soon)</p>
            </div>
          </div>
        </div>
      </section>

      <!-- ACHIEVEMENTS -->
      <section id="achievements" class="py-20 dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
              <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">Proven Results</span>
            </h2>
            <p class="text-xl text-gray-600 dark:text-gray-400">Exceptional performance metrics that drive organizational success.</p>
          </div>
          <div class="grid md:grid-cols-2 gap-12 items-center">
            <div>
              <div class="bg-white dark:bg-gray-700 p-4 rounded-xl shadow-lg">
                <canvas id="revenueChart"></canvas>
              </div>
            </div>
            <div class="space-y-8">
              <div class="bg-white dark:bg-gray-700 p-6 rounded-xl shadow-lg flex items-center"><i class="fas fa-trophy text-yellow-500 text-3xl mr-4"></i><div><h3 class="text-lg font-bold text-gray-800 dark:text-gray-200">Employee of the Year 2023</h3><p class="text-gray-600 dark:text-gray-400">Recognized for outstanding leadership.</p></div></div>
              <div class="bg-white dark:bg-gray-700 p-6 rounded-xl shadow-lg flex items-center"><i class="fas fa-medal text-gray-500 text-3xl mr-4"></i><div><h3 class="text-lg font-bold text-gray-800 dark:text-gray-200">4x Employee of the Month</h3><p class="text-gray-600 dark:text-gray-400">Consistent recognition for contributions.</p></div></div>
            </div>
          </div>
        </div>
      </section>

      <!-- SERVICES -->
      <section id="services" class="py-20 bg-gray-50 dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="grid lg:grid-cols-2 gap-12 items-center">
            <div>
              <span class="text-blue-600 dark:text-blue-400 text-sm font-semibold uppercase tracking-wider">Professional Service</span>
              <h2 class="text-4xl font-bold text-gray-900 dark:text-white my-4">Insurance Billing & Claims Advocacy</h2>
              <p class="text-lg text-gray-600 dark:text-gray-400 mb-6">Navigating the complexities of insurance claims can be daunting. With my expertise, I fight for unpaid and underpaid claims to ensure you receive the reimbursement you're entitled to. I advocate on behalf of both healthcare facilities and individuals, turning denials into approvals and maximizing revenue.</p>
              <h4 class="text-xl font-bold text-gray-800 dark:text-gray-200 mb-4">Why Partner With Me?</h4>
              <ul class="space-y-4 text-gray-600 dark:text-gray-400">
                <li class="flex items-start"><i class="fas fa-check-circle text-green-500 mt-1 mr-3"></i><span><strong>Proven Results:</strong> Track record of success.</span></li>
                <li class="flex items-start"><i class="fas fa-check-circle text-green-500 mt-1 mr-3"></i><span><strong>Industry Expertise:</strong> Deep knowledge of policies.</span></li>
                <li class="flex items-start"><i class="fas fa-check-circle text-green-500 mt-1 mr-3"></i><span><strong>Dedicated Advocacy:</strong> Relentless approach.</span></li>
              </ul>
              <a href="https://www.fiverr.com/s/9v5vVE" target="_blank" rel="noopener noreferrer" class="mt-8 inline-block bg-green-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-green-700 hover:scale-105 transition transform">
                <i class="fas fa-gavel mr-2"></i>View Service on Fiverr
              </a>
            </div>
            <div class="text-center">
              <div class="rounded-xl overflow-hidden shadow-2xl border-4 border-white dark:border-gray-700 transform hover:scale-105 transition">
                <img src="https://lh3.googleusercontent.com/pw/AP1GczPWTMZmzfJclDo_KBBWt9zfEPlHfGYJBGMn_3NNSZ_2bYu0vR4ZyjoUuZxtb_I0cCkoUfFwutxxY_qU3e_BspR2kHyt9Cj-CGIyLhqB7pMTlzygQS0O=w1920-h1080" alt="A professional discussing insurance claims and billing" class="w-full h-auto object-cover" onerror="this.src='https://placehold.co/600x400/3B82F6/FFFFFF?text=Claims+Advocacy'"/>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- PUBLICATIONS -->
      <section id="publications" class="py-20 dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
              <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">As Featured In</span>
            </h2>
            <p class="text-xl text-gray-600 dark:text-gray-400 max-w-3xl mx-auto">Proud to be featured in publications that highlight innovation and personal journeys in healthcare.</p>
          </div>
          <div id="publications-grid" class="grid md:grid-cols-3 gap-8">
            <!-- Skeletons (will be replaced by script) -->
            <div class="publication-skeleton bg-white dark:bg-gray-700 rounded-xl shadow-lg overflow-hidden flex flex-col animate-pulse"><div class="w-full h-48 bg-gray-200 dark:bg-gray-600"></div><div class="p-6"><div class="h-6 bg-gray-200 dark:bg-gray-600 rounded w-3/4 mb-3"></div><div class="h-4 bg-gray-200 dark:bg-gray-600 rounded w-5/6"></div></div></div>
            <div class="publication-skeleton bg-white dark:bg-gray-700 rounded-xl shadow-lg overflow-hidden flex flex-col animate-pulse"><div class="w-full h-48 bg-gray-200 dark:bg-gray-600"></div><div class="p-6"><div class="h-6 bg-gray-200 dark:bg-gray-600 rounded w-3/4 mb-3"></div><div class="h-4 bg-gray-200 dark:bg-gray-600 rounded w-5/6"></div></div></div>
            <div class="publication-skeleton bg-white dark:bg-gray-700 rounded-xl shadow-lg overflow-hidden flex flex-col animate-pulse"><div class="w-full h-48 bg-gray-200 dark:bg-gray-600"></div><div class="p-6"><div class="h-6 bg-gray-200 dark:bg-gray-600 rounded w-3/4 mb-3"></div><div class="h-4 bg-gray-200 dark:bg-gray-600 rounded w-5/6"></div></div></div>
          </div>
        </div>
      </section>

      <!-- BLOG -->
      <section id="blog" class="py-20 bg-gray-50 dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
              <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">Latest Articles</span>
            </h2>
            <p class="text-xl text-gray-600 dark:text-gray-400 max-w-3xl mx-auto">Insights, trends, and thoughts on healthcare innovation and business strategy from my Medium blog.</p>
            <div class="mt-8">
              <a href="https://medium.com/@roomservicebranding" target="_blank" rel="noopener noreferrer" class="bg-black text-white px-6 py-3 rounded-lg font-semibold inline-flex items-center gap-2 hover:bg-gray-800 dark:bg-gray-200 dark:text-gray-900 dark:hover:bg-white hover:scale-105 transition transform">
                <i class="fab fa-medium"></i> Follow on Medium
              </a>
            </div>
          </div>

          <div id="blog-posts-container" class="grid md:grid-cols-3 gap-8">
            <!-- Skeletons (will be replaced by script) -->
            <div class="blog-skeleton bg-white dark:bg-gray-800 rounded-xl shadow-lg overflow-hidden flex flex-col animate-pulse"><div class="w-full h-48 bg-gray-200 dark:bg-gray-700"></div><div class="p-6"><div class="h-4 bg-gray-200 dark:bg-gray-700 rounded w-1/4 mb-4"></div><div class="h-6 bg-gray-200 dark:bg-gray-700 rounded w-3/4 mb-3"></div><div class="h-4 bg-gray-200 dark:bg-gray-700 rounded w-5/6"></div></div></div>
            <div class="blog-skeleton bg-white dark:bg-gray-800 rounded-xl shadow-lg overflow-hidden flex flex-col animate-pulse"><div class="w-full h-48 bg-gray-200 dark:bg-gray-700"></div><div class="p-6"><div class="h-4 bg-gray-200 dark:bg-gray-700 rounded w-1/4 mb-4"></div><div class="h-6 bg-gray-200 dark:bg-gray-700 rounded w-3/4 mb-3"></div><div class="h-4 bg-gray-200 dark:bg-gray-700 rounded w-5/6"></div></div></div>
            <div class="blog-skeleton bg-white dark:bg-gray-800 rounded-xl shadow-lg overflow-hidden flex flex-col animate-pulse"><div class="w-full h-48 bg-gray-200 dark:bg-gray-700"></div><div class="p-6"><div class="h-4 bg-gray-200 dark:bg-gray-700 rounded w-1/4 mb-4"></div><div class="h-6 bg-gray-200 dark:bg-gray-700 rounded w-3/4 mb-3"></div><div class="h-4 bg-gray-200 dark:bg-gray-700 rounded w-5/6"></div></div></div>
          </div>
          <div id="blog-error-container" class="text-red-500 text-center mt-4"></div>
        </div>
      </section>

      <!-- GALLERY -->
      <section id="gallery" class="py-20 dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
              <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">Gallery</span>
            </h2>
            <p class="text-xl text-gray-600 dark:text-gray-400 max-w-3xl mx-auto">A collection of professional photos.</p>
          </div>
          <div id="gallery-grid" class="grid grid-cols-2 md:grid-cols-3 gap-4">
            <!-- Skeletons (will be replaced by script) -->
            <div class="gallery-skeleton w-full h-64 bg-gray-200 dark:bg-gray-700 rounded-lg animate-pulse"></div>
            <div class="gallery-skeleton w-full h-64 bg-gray-200 dark:bg-gray-700 rounded-lg animate-pulse"></div>
            <div class="gallery-skeleton w-full h-64 bg-gray-200 dark:bg-gray-700 rounded-lg animate-pulse"></div>
            <div class="gallery-skeleton w-full h-64 bg-gray-200 dark:bg-gray-700 rounded-lg animate-pulse hidden md:block"></div>
            <div class="gallery-skeleton w-full h-64 bg-gray-200 dark:bg-gray-700 rounded-lg animate-pulse hidden md:block"></div>
            <div class="gallery-skeleton w-full h-64 bg-gray-200 dark:bg-gray-700 rounded-lg animate-pulse hidden md:block"></div>
          </div>
        </div>
      </section>

      <!-- CONTACT -->
      <section id="contact" class="py-20 bg-gray-50 dark:bg-gray-900">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
            <span class="bg-gradient-to-r from-blue-600 to-teal-500 bg-clip-text text-transparent">Let's Build the Future</span>
          </h2>
          <p class="text-xl text-gray-600 dark:text-gray-400 mb-8 max-w-2xl mx-auto">Seeking new opportunities. Let's connect.</p>

          <div class="bg-white dark:bg-gray-800 p-8 rounded-xl shadow-lg border border-gray-200 dark:border-gray-700 w-full max-w-2xl mx-auto text-left">
            <h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-6 text-center">Get in Touch</h3>
            <!-- Form now triggers modal from new script -->
            <form id="contact-form" class="space-y-6">
              <div>
                <label for="name" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">Name</label>
                <input type="text" id="name" name="name" required class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-lg bg-gray-50 dark:bg-gray-700 focus:ring-blue-500 focus:border-blue-500 transition">
              </div>
              <div>
                <label for="email" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">Email</label>
                <input type="email" id="email" name="email" required class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-lg bg-gray-50 dark:bg-gray-700 focus:ring-blue-500 focus:border-blue-500 transition">
              </div>
              <div>
                <label for="message" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">Message</label>
                <textarea id="message" name="message" rows="4" required class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-lg bg-gray-50 dark:bg-gray-700 focus:ring-blue-500 focus:border-blue-500 transition"></textarea>
              </div>
              <div class="text-center">
                <!-- Swapped button type to "submit" for form validation, script handles the rest -->
                <button type="submit" id="draft-email-btn" class="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold text-lg inline-flex items-center justify-center gap-2 hover:bg-blue-700 hover:scale-105 transition transform w-full sm:w-auto">
                  <span id="contact-btn-text">Send Message</span>
                  <div id="contact-loader" class="loader hidden"></div>
                </button>
              </div>
            </form>
            <div id="contact-error" class="mt-4 text-red-500 text-center"></div>
            
            <div class="mt-12 pt-8 border-t border-gray-200 dark:border-gray-700">
              <h4 class="text-lg font-semibold text-gray-800 dark:text-gray-200 mb-4 text-center">Or reach me directly:</h4>
              <div class="flex flex-col sm:flex-row justify-center gap-6 sm:gap-8 text-gray-600 dark:text-gray-400">
                <div class="flex items-center gap-3 justify-center">
                  <i class="fas fa-envelope text-blue-500 text-xl"></i>
                  <a href="mailto:Amitmishra@consultant.com" class="hover:text-blue-500">Amitmishra@consultant.com</a>
                </div>
                <div class="flex items-center gap-3 justify-center">
                  <i class="fas fa-phone text-blue-500 text-xl"></i>
                  <a href="tel:4697771004" class="hover:text-blue-500">(469) 777-1004</a>
                </div>
                <div class="flex items-center gap-3 justify-center">
                  <i class="fas fa-map-marker-alt text-blue-500 text-xl"></i>
                  <span>Dallas-Fort Worth, TX</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <!-- FOOTER -->
    <footer class="bg-gray-800 dark:bg-gray-950 text-gray-400 py-12 border-t border-gray-700">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <div class="flex justify-center gap-6 mb-6">
          <a href="https://www.linkedin.com/in/amitmishraclear" target="_blank" rel="noopener noreferrer" class="text-2xl hover:text-blue-400 transition" aria-label="LinkedIn">
            <i class="fab fa-linkedin"></i>
          </a>
          <a href="https://medium.com/@roomservicebranding" target="_blank" rel="noopener noreferrer" class="text-2xl hover:text-white transition" aria-label="Medium">
            <i class="fab fa-medium"></i>
          </a>
          <a href="https://www.fiverr.com/s/9v5vVE" target="_blank" rel="noopener noreferrer" class="text-2xl hover:text-green-400 transition" aria-label="Fiverr">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-explicit" viewBox="0 0 16 16">
              <path d="M6.828 10.88H6.39v-1.7h.438c.4 0 .732-.092.984-.276s.378-.45.378-.792c0-.343-.127-.604-.38-.78a1.3 1.3 0 0 0-.98-.264H6.39v-1.7h.438c.392 0 .72.09.98.27s.39.44.39.77c0 .34-.127.597-.38.774a1.3 1.3 0 0 0-.98.26V10.88zM5 11.68V4.32h2.06c.63 0 1.15.15 1.57.45.42.3.63.7.63 1.2 0 .5-.21.9-.63 1.2-.42.3-.94.45-1.57.45H6.39v1.7h.438c.64 0 1.17.15 1.58.452.41.3.61.7.61 1.2 0 .5-.2.9-.6 1.2s-.9.45-1.6.45H5z"/>
              <path d="M0 2a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V2zm15 0a1 1 0 0 0-1-1H2a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V2z"/>
            </svg>
          </a>
          <a href="https://www.youtube.com/channel/UCa8MMIwYaVjHkv3jH3C1sg" target="_blank" rel="noopener noreferrer" class="text-2xl hover:text-red-500 transition" aria-label="YouTube">
            <i class="fab fa-youtube"></i>
          </a>
        </div>
        <p>&copy; <span id="footer-year">2025</span> Amit Mishra. All rights reserved.</p>
      </div>
    </footer>
  </div>

  <!-- MODALS (for new script) -->
  
  <!-- Email/AI Modal -->
  <div id="email-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 hidden animate-fade-in">
    <div class="w-full max-w-lg bg-white dark:bg-gray-800 rounded-xl shadow-2xl animate-fade-in-up">
      <div class="flex justify-between items-center p-5 border-b dark:border-gray-700">
        <h3 class="text-xl font-bold text-gray-900 dark:text-white">AI Feature Offline</h3>
        <button id="close-email-modal-btn" class="text-gray-500 dark:text-gray-400 hover:text-red-500 dark:hover:text-red-400" aria-label="Close modal">
          <i class="fas fa-times text-2xl"></i>
        </button>
      </div>
      <div class="p-6">
        <textarea id="email-output" rows="8" class="w-full p-3 border border-gray-300 dark:border-gray-600 rounded-lg bg-gray-50 dark:bg-gray-700 focus:ring-blue-500 focus:border-blue-500" readonly></textarea>
        <button id="copy-email-btn" class="mt-4 w-full bg-blue-600 text-white px-6 py-2 rounded-lg font-semibold inline-flex items-center justify-center gap-2 hover:bg-blue-700">
          <i class="fas fa-copy"></i> Copy to Clipboard
        </button>
        <p id="copy-success-msg" class="text-green-600 dark:text-green-400 text-center text-sm mt-2"></p>
      </div>
    </div>
  </div>

  <!-- Publication Modal -->
  <div id="publication-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 hidden animate-fade-in">
    <div class="w-full max-w-2xl bg-white dark:bg-gray-800 rounded-xl shadow-2xl animate-fade-in-up max-h-[90vh] flex flex-col">
      <div class="flex justify-between items-center p-5 border-b dark:border-gray-700 flex-shrink-0">
        <div id="publication-modal-header" class="flex items-center gap-3">
          <!-- Content injected by script -->
        </div>
        <button id="close-publication-modal-btn" class="text-gray-500 dark:text-gray-400 hover:text-red-500 dark:hover:text-red-400" aria-label="Close modal">
          <i class="fas fa-times text-2xl"></i>
        </button>
      </div>
      <div id="publication-modal-content" class="p-6 overflow-y-auto prose dark:prose-invert max-w-none">
        <!-- Article content injected by script -->
      </div>
    </div>
  </div>

  <!-- Gallery Lightbox -->
  <div id="lightbox" class="fixed inset-0 z-[60] flex items-center justify-center p-4 hidden animate-fade-in">
    <button id="lightbox-close" class="absolute top-4 right-4 text-white text-4xl opacity-80 hover:opacity-100" aria-label="Close gallery">
      <i class="fas fa-times"></i>
    </button>
    <button id="lightbox-prev" class="absolute left-4 text-white text-4xl opacity-80 hover:opacity-100" aria-label="Previous image">
      <i class="fas fa-chevron-left"></i>
    </button>
    <button id="lightbox-next" class="absolute right-4 text-white text-4xl opacity-80 hover:opacity-100" aria-label="Next image">
      <i class="fas fa-chevron-right"></i>
    </button>
    <img id="lightbox-img" src="" alt="Gallery image" class="rounded-lg shadow-2xl">
  </div>


  <!-- SCRIPT 1: THEME & NAV (Patched) -->
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      console.log("SCRIPT 1: Theme & Nav (Patched)");
      
      const themeToggleBtns = document.querySelectorAll('.theme-toggle-btn');
      const htmlEl = document.documentElement;

      // --- Central Sync Function ---
      const syncTheme = () => {
        const isDark = localStorage.getItem('darkMode') === 'true';
        htmlEl.classList.toggle('dark', isDark); 
        const iconClass = isDark ? 'fa-sun' : 'fa-moon';
        themeToggleBtns.forEach(btn => {
          btn.innerHTML = `<i class="fas ${iconClass} text-xl"></i>`;
        });
      };

      // --- Function to handle the theme button click ---
      const handleThemeToggle = () => {
        const isDark = localStorage.getItem('darkMode') === 'true';
        localStorage.setItem('darkMode', !isDark);
        syncTheme();
        if (window.createRevenueChart) {
          window.createRevenueChart();
        }
      };

      // --- Attach Click Listeners ---
      themeToggleBtns.forEach(btn => btn.addEventListener('click', handleThemeToggle));
      
      // --- Initial Sync on DOM Load ---
      syncTheme(); 

      // --- [DELETED] Redundant listeners removed as requested ---
      // window.addEventListener('pageshow', ...);
      // window.addEventListener('hashchange', ...);
      // allAnchorLinks.forEach(...);


      // --- Mobile Menu ---
      const menuToggle = document.getElementById('mobile-menu-toggle');
      const mobileMenu = document.getElementById('mobile-menu');
      const mobileMenuLinks = document.querySelectorAll('.mobile-menu-link');

      const handleMobileMenuToggle = () => {
        const isOpen = mobileMenu.classList.toggle('translate-x-full');
        menuToggle.setAttribute('aria-expanded', !isOpen);
        document.body.style.overflow = isOpen ? 'auto' : 'hidden';
        menuToggle.innerHTML = isOpen ? '<i class="fas fa-bars text-2xl"></i>' : '<i class="fas fa-times text-2xl"></i>';
      };

      menuToggle.addEventListener('click', handleMobileMenuToggle);
      mobileMenuLinks.forEach(link => {
        link.addEventListener('click', handleMobileMenuToggle);
      });

      // --- [REPLACED] Navbar Scroll Effect (Patched) ---
      const navbar = document.getElementById('navbar');
      window.addEventListener('scroll', () => {
        const isDark = document.documentElement.classList.contains('dark');

        // ---- DARK MODE: always dark glass navbar ----
        if (isDark) {
          navbar.classList.add('dark:bg-gray-900/90','backdrop-blur-md','shadow-lg');
          navbar.classList.remove('bg-transparent','bg-white');
          return;
        }

        // ---- LIGHT MODE: original scroll behavior ----
        if (window.scrollY > 50) {
          navbar.classList.add('bg-white','shadow-lg','backdrop-blur-md');
          navbar.classList.remove('bg-transparent');
        } else {
          navbar.classList.remove('bg-white','shadow-lg','backdrop-blur-md');
          navbar.classList.add('bg-transparent');
        }
      });

      // --- Footer Year ---
      document.getElementById('footer-year').textContent = new Date().getFullYear();
    });
  </script>
  
  <!-- SCRIPT 2: DYNAMIC CONTENT (Unchanged) -->
  <script>
    document.addEventListener('DOMContentLoaded', async () => {
      console.log("SCRIPT 2 (no-AI): started");

      // --- Utility: fatal error banner (kept just in case)
      const displayFatalError = (message) => {
        const errorDisplay = document.getElementById("blog-error-container") || document.getElementById("insights-error") || document.body;
        const errorP = document.createElement('p');
        errorP.textContent = message;
        errorP.className = "text-red-600 dark:text-red-400 text-center text-lg p-4 font-semibold fatal-error";
        if (errorDisplay && !errorDisplay.querySelector('.fatal-error')) {
          errorDisplay.appendChild(errorP);
        } else if (!document.querySelector('.fatal-error')) {
          document.body.insertAdjacentElement('afterbegin', errorP);
        }
      };

      // --- DOM refs
      const generateInsightsBtn = document.getElementById("generate-insights-btn");
      const insightsResultContainer = document.getElementById("insights-result-container");
      const insightsLoading = document.getElementById("insights-loading");
      const insightsContent = document.getElementById("insights-content");
      const insightsError = document.getElementById("insights-error");

      const draftEmailBtn = document.getElementById("draft-email-btn");
      const contactForm = document.getElementById("contact-form");
      const contactError = document.getElementById("contact-error");

      const emailModal = document.getElementById("email-modal");
      const closeEmailModalBtn = document.getElementById("close-email-modal-btn");
      const emailOutput = document.getElementById("email-output");
      const copyEmailBtn = document.getElementById("copy-email-btn");
      const copySuccessMsg = document.getElementById("copy-success-msg");

      const publicationModal = document.getElementById("publication-modal");
      const closePublicationModalBtn = document.getElementById("close-publication-modal-btn");
      const publicationModalHeader = document.getElementById("publication-modal-header");
      const publicationModalContent = document.getElementById("publication-modal-content");
      const publicationsGrid = document.getElementById("publications-grid");

      const lightbox = document.getElementById("lightbox");
      const lightboxImg = document.getElementById("lightbox-img");
      const lightboxClose = document.getElementById("lightbox-close");
      const lightboxPrev = document.getElementById("lightbox-prev");
      const lightboxNext = document.getElementById("lightbox-next");
      const galleryGrid = document.getElementById("gallery-grid");

      const blogPostsContainer = document.getElementById("blog-posts-container");
      const blogErrorContainer = document.getElementById("blog-error-container");

      // --- Modal helpers
      const openModal = (el) => el && el.classList.remove('hidden');
      const closeModal = (el) => el && el.classList.add('hidden');

      if (closeEmailModalBtn) closeEmailModalBtn.addEventListener("click", () => closeModal(emailModal));
      if (emailModal) emailModal.addEventListener("click", (e) => { if (e.target === emailModal) closeModal(emailModal); });

      if (closePublicationModalBtn) closePublicationModalBtn.addEventListener("click", () => closeModal(publicationModal));
      if (publicationModal) publicationModal.addEventListener("click", (e) => { if (e.target === publicationModal) closeModal(publicationModal); });

      // --- Safe text
      const safeText = (text) => {
        const el = document.createElement('div');
        el.textContent = text ?? "";
        return el.textContent;
      };

      // --- Publications data (from your script)
      const publicationsData = [
        {
          id: 'brc-feature',
          title: '#FeatureFriday: Amit Mishra',
          source: 'BRC Healthcare',
          logo: 'https://i.postimg.cc/4xSWKYSF/IMG-4111.jpg',
          imageUrl: 'https://lh3.googleusercontent.com/pw/AP1GczOt4vMotA4jJpp5s3kFeF2E8ZQu0AtFwUAyM0AHiJSw0n7hYSkmVUnz_WfRdyzyY-tVKcAaGA4xDg47j2ujKn3Gvf8NYab8hh_uZdnwjynC0YqvIOFO=w1920-h1080',
          snippet: 'Meet Amit Mishra, Segue Recovery Coach, PRSS. A spotlight on his journey and work at BRC Healthcare.',
          article: `<article><h3>#FeatureFriday: Amit Mishra</h3><p>Everyone meet Amit Mishra, Segue Recovery Coach, PRSS...</p><blockquote>"My family was unsure..."</blockquote><p>In 2016, Amit was intervened on...</p><blockquote>"There, I met mentors... I love my job..."</blockquote></article>`
        },
        {
          id: 'nova-recovery',
          title: 'Stories Of Addiction Recovery: Amit Mishra’s Story',
          source: 'Nova Recovery Center',
          logo: 'https://i.postimg.cc/mg5mcP5d/IMG-4113.jpg',
          imageUrl: 'https://lh3.googleusercontent.com/pw/AP1GczMwGRjA3RLe7tpfdx9sZCrVcIFUS8jSuN_vD-tdeG1C9McXMx3JbGR63fxDNAnyTYD2Qmda_VJHfdkTqnL1-UtTd-GmTNmHR3euok-Op9ps4cNgWFSX=w1920-h1080',
          snippet: 'Sharing the journey from addiction to recovery, highlighting the turning points and finding freedom.',
          article: `<article><h3>Stories Of Addiction Recovery: Amit Mishra’s Story</h3><p>Amit grew up in a home...</p><blockquote>"I had several friends..."</blockquote><p>That chase led Amit straight...</p><blockquote>"I will never forget the feeling..."</blockquote><p>Drugs and alcohol had completely consumed...</p><blockquote>"In that moment, I really felt like I met God..."</blockquote><p>Somehow Amit survived...</p><blockquote>"Nova was different..."</blockquote><p>After completing his rehab at Nova...</p><blockquote>"There is absolutely a way out..."</blockquote></article>`
        },
        {
          id: 'heart-water',
          title: 'Amit Mishra\'s Story (#PourYourHeartOut)',
          source: 'Heart Water',
          logo: 'https://i.postimg.cc/T34tyK47/IMG-4114.jpg',
          imageUrl: 'https://lh3.googleusercontent.com/pw/AP1GczMwGRjA3RLe7tpfdx9sZCrVcIFUS8jSuN_vD-tdeG1C9McXMx3JbGR63fxDNAnyTYD2Qmda_VJHfdkTqnL1-UtTd-GmTNmHR3euok-Op9ps4cNgWFSX?w=1920-h=1080',
          snippet: 'Sharing a personal testimony about childhood, struggles with addiction, finding sobriety, and helping others.',
          link: '#',
          article: `<article><h3>Amit Mishra's Story (#PourYourHeartOut)</h3><blockquote>"Originally from Ann Arbor, MI..."</blockquote><p>I spent my childhood playing sports...</p><p>Gradually, my drug and alcohol use...</p><p>All of this was a result...</p><blockquote>"I've been sober everyday since..."</blockquote></article>`
        },
        {
          id: 'voyage-la',
          title: 'Check Out Amit Mishra’s Story',
          source: 'VoyageLA',
          logo: 'https://voyagela.com/wp-content/uploads/2021/02/cropped-VOYAGE-LA-MAGAZINE-LOGO-5.png',
          imageUrl: 'https://lh3.googleusercontent.com/pw/AP1GczPERO1eniWQPw1Bmim0kRcE1P8JQ11HYae437im9jPfY-FGCiu-oZst_0lRRjp2_8e6Q_j1kV7dVOCql20d4UC8jT5h4QlltuOb4ydgrCIgkIwi2x7u=w1920-h1080',
          snippet: 'An in-depth interview discussing my journey in the healthcare industry and vision for behavioral health.',
          link: 'https://voyagela.com/interview/check-out-amit-mishras-story/',
          article: `<article><h3>Check Out Amit Mishra’s Story</h3><p><strong>Amit, let’s start with your story...</strong><br/>My journey...</p><p>My career...</p><p><strong>Overall, has it been relatively smooth?...</strong><br/>The road...</p></article>`
        }
      ];

      // --- Publications UI
      const loadPublications = () => {
        console.log("loadPublications");
        const grid = publicationsGrid;
        if (!grid) return;
        grid.innerHTML = "";
        publicationsData.forEach((item) => {
          const card = document.createElement('div');
          card.className = "bg-white dark:bg-gray-700 rounded-xl shadow-lg overflow-hidden flex flex-col cursor-pointer transition-all duration-300 hover:shadow-2xl hover:-translate-y-1 group";
          card.innerHTML = `
            <div class="h-48 w-full overflow-hidden relative">
              <img src="${item.imageUrl}" alt="${safeText(item.title)}" class="w-full h-full object-cover transition-transform duration-300 group-hover:scale-105" onerror="this.onerror=null; this.src='https://placehold.co/600x400/7F1D1D/FFFFFF?text=Load+Error';">
            </div>
            <div class="p-6 flex flex-col flex-grow">
              <div class="flex items-center gap-3 mb-3">
                <div class="flex-shrink-0 bg-white h-8 w-8 rounded-full flex items-center justify-center p-1 shadow-sm border dark:border-gray-600">
                  <img class="max-h-full max-w-full object-contain" src="${item.logo}" alt="${safeText(item.source)} Logo" onerror="this.parentElement.style.display='none'">
                </div>
                <h4 class="text-sm font-semibold text-gray-600 dark:text-gray-400">${safeText(item.source)}</h4>
              </div>
              <h3 class="text-lg font-bold text-gray-800 dark:text-gray-200 mb-2 leading-tight">${safeText(item.title)}</h3>
              <p class="text-gray-600 dark:text-gray-400 text-sm mb-4 flex-grow">${safeText(item.snippet)}</p>
              <span class="text-blue-600 dark:text-blue-400 font-semibold inline-flex items-center text-sm group-hover:underline mt-auto">
                Read Feature <i class="fas fa-arrow-right ml-1 text-xs"></i>
              </span>
            </div>
          `;
          card.addEventListener("click", () => {
            if (publicationModalHeader) {
              publicationModalHeader.innerHTML =
                `<img src="${item.logo}" alt="${safeText(item.source)} Logo" class="h-8 max-h-8 max-w-[150px] object-contain flex-shrink-0" onerror="this.style.display='none'">
                 <h2 id="publication-modal-title" class="text-xl font-bold text-gray-800 dark:text-gray-200">${safeText(item.source)}</h2>`;
            }
            if (publicationModalContent) {
              publicationModalContent.innerHTML = item.article;
            }
            openModal(publicationModal);
          });
          grid.appendChild(card);
        });
      };

      // --- Blog
      const loadBlogPosts = async () => {
        if (!blogPostsContainer) return;
        const mediumRssFeed = "https://medium.com/feed/@roomservicebranding";
        const proxyUrl = "https://api.rss2json.com/v1/api.json?rss_url=";
        try {
          const res = await fetch(proxyUrl + encodeURIComponent(mediumRssFeed));
          if (!res.ok) throw new Error(`HTTP ${res.status}`);
          const data = await res.json();
          if (data.status !== 'ok') throw new Error('RSS status not ok');
          const posts = data.items.slice(0, 3);
          if (!posts.length) throw new Error('No posts found');
          blogPostsContainer.innerHTML = "";
          posts.forEach(post => {
            const postDate = new Date(post.pubDate).toLocaleDateString('en-US', { year: 'numeric', month: 'short', day: 'numeric' });
            const snippet = new DOMParser().parseFromString(post.description, 'text/html').body.textContent.slice(0, 100) + '...';
            const card = document.createElement('a');
            card.href = post.link;
            card.target = "_blank";
            card.rel = "noopener noreferrer";
            card.className = "blog-card bg-white dark:bg-gray-800 rounded-xl shadow-lg overflow-hidden flex flex-col group transition-all duration-300 hover:shadow-2xl hover:-translate-y-1";
            card.innerHTML = `
              <div class="h-48 w-full overflow-hidden">
                <img src="${post.thumbnail}" alt="${safeText(post.title)}" class="w-full h-full object-cover transition-transform duration-300 group-hover:scale-105"
                     onerror="this.src='https://placehold.co/600x400/10B981/FFFFFF?text=Blog+Post'; this.onerror=null;"/>
              </div>
              <div class="p-6 flex flex-col flex-grow">
                <p class="text-sm text-gray-500 dark:text-gray-400 mb-2">${safeText(postDate)}</p>
                <h3 class="text-lg font-bold text-gray-800 dark:text-gray-200 mb-3 leading-tight">${safeText(post.title)}</h3>
                <p class="text-sm text-gray-600 dark:text-gray-400 mb-4 flex-grow">${safeText(snippet)}</p>
                <span class="text-blue-600 dark:text-blue-400 font-semibold inline-flex items-center text-sm group-hover:underline mt-auto">
                  Read More <i class="fas fa-arrow-right ml-1 text-xs"></i>
                </span>
              </div>
            `;
            blogPostsContainer.appendChild(card);
          });
          console.log("Blog posts loaded.");
        } catch (e) {
          console.warn("Blog feed failed:", e);
          blogPostsContainer.innerHTML = '';
          if (blogErrorContainer) {
            blogErrorContainer.innerHTML = `<p>Could not load blog posts. Please <a href="https://medium.com/@roomservicebranding" target="_blank" class="underline hover:text-blue-500">visit my Medium profile</a> directly.</p>`;
          }
        }
      };

      // --- Gallery & Lightbox
      const fiverrLink = 'https://www.fiverr.com/s/qDLADq9';
      const fiverrImageSrc = 'https://lh3.googleusercontent.com/pw/AP1GczPWTMZmzfJclDo_KBBWt9zfEPlHfGYJBGMn_3NNSZ_2bYu0vR4ZyjoUuZxtb_I0cCkoUfFwutxxY_qU3e_BspR2kHyt9Cj-CGIyLhqB7pMTlzygQS0O=w1920-h1080';

      const galleryImages = [
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczOkap3k52m5ojG6FGwOHX55aIMxSJ2rP-Kgs5CUHz7tdRO_YaPgCjUw1Q3aH0VB9B-UWJylaDWG8oRZC-TN77lJ0tKVj3I1wivZHQiLL1n3EgkxO1LA=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczPERO1eniWQPw1Bmim0kRcE1P8JQ11HYae437im9jPfY-FGCiu-oZst_0lRRjp2_8e6Q_j1kV7dVOCql20d4UC8jT5h4QlltuOb4ydgrCIgkIwi2x7u=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczMwGRjA3RLe7tpfdx9sZCrVcIFUS8jSuN_vD-tdeG1C9McXMx3JbGR63fxDNAnyTYD2Qmda_VJHfdkTqnL1-UtTd-GmTNmHR3euok-Op9ps4cNgWFSX=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczOt4vMotA4jJpp5s3kFeF2E8ZQu0AtFwUAyM0AHiJSw0n7hYSkmVUnz_WfRdyzyY-tVKcAaGA4xDg47j2ujKn3Gvf8NYab8hh_uZdnwjynC0YqvIOFO=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczNGaHPsFiJCLJzQ5BrPpPTYqL6THYV6CKRcGIm1nU_OH958xKY0YSJtt5RUKOpHrmXbX3RbsdecQZsO30HiTMOFqvL5TDFpNESQPph5UN4ZzPIqHYaL=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczMu3e3iaz8PTuoYQg5kMktD3y0cCKwoUxLDUbjVSTQ2qZ7lY0GtumDhtDLK55LW8_ok5k06PvQa97lU9l_P-mmzzY1Akd-NapF5RZsxu55hun0Ppmij=w1920-h1080' },
        { src: fiverrImageSrc, link: fiverrLink },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczNvTV8ofgBpuRhh4cakJIxpEP2nIKR3Qx6HwB_YvUXyTSvfSEa3vAYoPtmCqnWsVD7nrf1uXqVn2nk37ntxmfbHN3ujq5NRQHAiOPrjL5upO8naJrhc=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczPaL3qF74teIOBUZTqoiBtXjOmfj0ygoZW1eJWkyQT4e-iPidEeogX_HCTxplsH2wDE5yzWIsu18CZTPjPurpxUvB8p8bLoeVn-AmBndoi5BGZT7_sj=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczNHZjIJ6qB4EivJNXb0z7rJx_WvF4gfnB2C0LDiwDF-qRPkHIRgyhwV9se5vGwej1pcEHY_NIG88Fzqf4P2cKzt8tVLBTQfLGbQmvkxroQlRriZD-pi=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczNcycEMQL0wPcnh-xJSbvh6tQSNUeUC70ULB2IFgePOVMrTaGBHRwRSyFsjWE31z1fhbmGfAWPag08__2uOe4oq_AP9OlNVZEY1MNZa31JEubHF71Tm=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczNCMzdbc4mP51UPKwLkl--FPB3EfTWSY-qbNtneftoYBwt64zEDmumBuirXAT3_nzQPoOyrIpgWn7Xo9-RB1hbZcdrGWko7MfeA4BLHgFXMm7iy16XO=w1920-h1080' },
        { src: 'https://lh3.googleusercontent.com/pw/AP1GczM7fyR8bs7KKnM3-nNAfeljulwsri5Cn9Psp7K-8yxPoq_BPflRAj_alVoU5W1JgfIdvLWZMqSln2-tQ_AEwbJACIPk3iQWVtyqwXI--JL-cMUB3MmO=w1920-h1080' }
      ];

      let currentLightboxIndex = 0;
      const lightboxImages = galleryImages.filter(item => !item.link);

      const loadGallery = () => {
        if (!galleryGrid) return;
        galleryGrid.innerHTML = "";
        let lbIndex = 0;
        galleryImages.forEach((item, idx) => {
          const container = document.createElement("div");
          const img = document.createElement("img");
          img.src = item.src;
          img.alt = item.link ? "Fiverr Profile Link" : `Gallery image ${idx + 1}`;
          img.className = "w-full h-64 object-cover rounded-lg transition-all duration-300 hover:scale-105 hover:shadow-lg";
          img.loading = "lazy";
          img.onerror = function(){ this.src='https://placehold.co/600x400/7F1D1D/FFFFFF?text=Load+Error'; this.onerror=null; };
          if (item.link) {
            const link = document.createElement("a");
            link.href = item.link; link.target = "_blank"; link.rel = "noopener noreferrer"; link.title = "Visit my Fiverr Profile";
            img.classList.add("cursor-pointer");
            link.appendChild(img);
            container.appendChild(link);
          } else {
            img.classList.add("cursor-pointer");
            const thisIndex = lbIndex;
            img.addEventListener("click", () => openLightbox(thisIndex));
            container.appendChild(img);
            lbIndex++;
          }
          galleryGrid.appendChild(container);
        });
      };

      const showImage = (index) => {
        if (index < 0 || index >= lightboxImages.length) return;
        currentLightboxIndex = index;
        if (lightboxImg) lightboxImg.src = lightboxImages[index].src;
      };
      const openLightbox = (index) => { showImage(index); openModal(lightbox); };
      const closeLightbox = () => closeModal(lightbox);
      const prevImage = () => showImage((currentLightboxIndex - 1 + lightboxImages.length) % lightboxImages.length);
      const nextImage = () => showImage((currentLightboxIndex + 1) % lightboxImages.length);
      if (lightboxClose) lightboxClose.addEventListener("click", (e) => { e.stopPropagation(); closeLightbox(); });
      if (lightboxPrev) lightboxPrev.addEventListener("click", (e) => { e.stopPropagation(); prevImage(); });
      if (lightboxNext) lightboxNext.addEventListener("click", (e) => { e.stopPropagation(); nextImage(); });
      if (lightbox) lightbox.addEventListener("click", (e) => { if (e.target === lightbox) closeLightbox(); });
      document.addEventListener('keydown', (e) => { if (!lightbox || lightbox.classList.contains('hidden')) return; if (e.key === 'Escape') closeLightbox(); if (e.key === 'ArrowLeft') prevImage(); if (e.key === 'ArrowRight') nextImage(); });

      // --- Chart.js (graceful)
      let revenueChartInstance = null;
      window.createRevenueChart = () => {
        const ctx = document.getElementById('revenueChart');
        if (!ctx) return;

        if (typeof window.Chart === 'undefined') {
          // No Chart available — show a friendly placeholder
          const holder = ctx.parentElement;
          if (holder && !holder.querySelector('.chart-placeholder')) {
            holder.innerHTML = `
              <div class="p-6 text-center text-gray-600 dark:text-gray-400 chart-placeholder">
                <p class="font-semibold">Revenue Growth (2023-2024)</p>
                <p class="mt-2 text-sm opacity-80">Chart preview unavailable in this environment.</p>
              </div>
            `;
          }
          return;
        }

        const isDarkMode = document.documentElement.classList.contains('dark');
        const gridColor = isDarkMode ? 'rgba(255, 255, 255, 0.1)' : 'rgba(0, 0, 0, 0.1)';
        const labelColor = isDarkMode ? '#cbd5e1' : '#4b5563';

        const chartData = {
          labels: ['Q1 2023', 'Q2 2023', 'Q3 2023', 'Q4 2023', 'Q1 2024', 'Q2 2024'],
          datasets: [{
            label: 'Revenue (Millions)',
            data: [1.2, 1.9, 2.3, 2.1, 2.7, 3.4],
            borderColor: '#3b82f6',
            backgroundColor: 'rgba(59, 130, 246, 0.2)',
            fill: true,
            tension: 0.4,
          }]
        };

        if (revenueChartInstance) revenueChartInstance.destroy();
        revenueChartInstance = new window.Chart(ctx, {
          type: 'line',
          data: chartData,
          options: {
            responsive: true,
            maintainAspectRatio: true,
            plugins: {
              legend: { labels: { color: labelColor } },
              title: { display: true, text: 'Revenue Growth (2023-2024)', color: labelColor, font: { size: 16 } }
            },
            scales: {
              y: { beginAtZero: true, grid: { color: gridColor }, ticks: { color: labelColor, callback: (v) => `$${v}M` } },
              x: { grid: { color: 'transparent' }, ticks: { color: labelColor } }
            }
          }
        });
        console.log("Chart created/updated.");
      };
      // Initial chart render
      window.createRevenueChart();

      // --- AI button behavior (modal “coming soon”)
      const AI_OFFLINE_TITLE = "AI feature temporarily offline";
      const AI_OFFLINE_MESSAGE = "This AI-powered feature is temporarily offline while we transition to a new backend. Please check back soon.";

      const showAiOfflineModal = () => {
        if (!emailModal) return;
        // Update modal title text
        const titleEl = emailModal.querySelector('h3');
        if (titleEl) titleEl.textContent = AI_OFFLINE_TITLE;
        // Put message in the textarea and make it selectable (so “Copy” still works if you want)
        if (emailOutput) {
          emailOutput.value = AI_OFFLINE_MESSAGE;
          emailOutput.readOnly = true;
        }
        // Keep copy button active (or disable if you prefer)
        if (copySuccessMsg) copySuccessMsg.textContent = "";
        openModal(emailModal);
      };

      if (generateInsightsBtn) {
        generateInsightsBtn.addEventListener("click", (e) => {
          // Show the container so user sees where insights would appear
          if (insightsResultContainer) insightsResultContainer.classList.remove('hidden');
          if (insightsLoading) insightsLoading.classList.add('hidden');
          if (insightsContent) insightsContent.innerHTML = "";
          if (insightsError) insightsError.innerHTML = "";
          // Pop the modal
          showAiOfflineModal();
        });
      }

      if (contactForm) {
        contactForm.addEventListener("submit", (e) => {
          e.preventDefault();
          if (contactError) contactError.textContent = '';
          showAiOfflineModal();
        });
      }

      // --- Copy Button Logic (for the AI offline modal) ---
      if (copyEmailBtn) {
        copyEmailBtn.addEventListener('click', () => {
          if (emailOutput) {
            emailOutput.select();
            try {
              // Use execCommand as a fallback for iframe environments
              document.execCommand('copy');
              if(copySuccessMsg) copySuccessMsg.textContent = "Copied!";
              setTimeout(() => {
                if(copySuccessMsg) copySuccessMsg.textContent = "";
              }, 2000);
            } catch (err) {
              console.error('Failed to copy text: ', err);
              if(copySuccessMsg) copySuccessMsg.textContent = "Copy failed";
            }
          }
        });
      }

      // --- Initial loads
      loadPublications();
      loadGallery();
      await loadBlogPosts();

      console.log("SCRIPT 2 (no-AI): finished");
    });
  </script>
</body>
</html>
