<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>𝙒𝘼𝙌𝘼𝙎 𝙒𝙀𝘽 𝙎𝙀𝙍𝙑𝙄𝘾𝙀𝙎</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
</head>
<body class="bg-gradient-to-b from-gray-900 via-black to-gray-900 text-white antialiased">

  <!-- HEADER -->
  <header class="max-w-6xl mx-auto px-6 py-6 flex items-center justify-between">
    <h1 class="text-xl font-bold tracking-wide animate__animated animate__fadeIn">
      𝙒𝘼𝙌𝘼𝙎 𝙒𝙀𝘽 𝙎𝙀𝙍𝙑𝙄𝘾𝙀𝙎
    </h1>
    <nav class="hidden md:flex gap-6 text-sm">
      <a href="#services" class="hover:underline">Services</a>
      <a href="#consulting" class="hover:underline">Consulting</a>
      <a href="#contact" class="hover:underline">Contact</a>
    </nav>
  </header>

  <!-- HERO -->
  <section class="max-w-6xl mx-auto px-6 py-12 grid md:grid-cols-2 gap-8 items-center">
    <div>
      <h2 class="text-4xl font-extrabold leading-tight animate__animated animate__fadeInLeft">
        Next-Gen <span class="text-indigo-400">Web & AI Solutions</span> for Business Growth 🚀
      </h2>
      <p class="mt-4 text-gray-300">
        We deliver AI automations, SaaS platforms, custom sites (React, Node.js, PHP), 
        Android/iOS apps, and data-driven marketing campaigns.
      </p>
      <div class="mt-6 flex gap-3 flex-wrap">
        <a href="https://gumroad.com/your-ai-offer" 
           class="px-5 py-3 rounded-full bg-gradient-to-r from-indigo-600 to-pink-500 font-semibold shadow-lg">
           Hire for AI Automation
        </a>
        <a href="https://gumroad.com/your-saas-offer" 
           class="px-5 py-3 rounded-full border border-white/20 text-sm">
           SaaS / Website Build
        </a>
      </div>
    </div>
    <div class="animate__animated animate__zoomIn">
      <div class="w-full h-64 bg-gradient-to-tr from-indigo-500 to-pink-500 rounded-2xl shadow-xl"></div>
    </div>
  </section>

  <!-- SERVICES -->
  <section id="services" class="max-w-6xl mx-auto px-6 py-12">
    <h3 class="text-2xl font-bold mb-6">Our Services</h3>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="p-6 bg-white/5 rounded-xl">
        <h4 class="font-semibold">AI Automations</h4>
        <p class="text-sm text-gray-300 mt-2">Custom GPT bots, workflow automations, CRMs.</p>
      </div>
      <div class="p-6 bg-white/5 rounded-xl">
        <h4 class="font-semibold">SaaS & Websites</h4>
        <p class="text-sm text-gray-300 mt-2">Full-stack apps in React, Node, PHP & Next.js.</p>
      </div>
      <div class="p-6 bg-white/5 rounded-xl">
        <h4 class="font-semibold">E-Commerce</h4>
        <p class="text-sm text-gray-300 mt-2">Evergreen Shopify, WooCommerce & funnels.</p>
      </div>
      <div class="p-6 bg-white/5 rounded-xl">
        <h4 class="font-semibold">Mobile Apps</h4>
        <p class="text-sm text-gray-300 mt-2">Next-Gen Android/iOS solutions.</p>
      </div>
      <div class="p-6 bg-white/5 rounded-xl">
        <h4 class="font-semibold">Marketing & Lead Gen</h4>
        <p class="text-sm text-gray-300 mt-2">Digital campaigns with ROI tracking.</p>
      </div>
      <div class="p-6 bg-white/5 rounded-xl">
        <h4 class="font-semibold">Consulting & Ideas</h4>
        <p class="text-sm text-gray-300 mt-2">Free business ideas + execution plans.</p>
      </div>
    </div>
  </section>

  <!-- CONSULTING -->
  <section id="consulting" class="max-w-6xl mx-auto px-6 py-12 text-center bg-gradient-to-tr from-indigo-900/30 to-pink-900/20 rounded-2xl">
    <h3 class="text-xl font-bold">Get Your Free Idea 💡</h3>
    <p class="text-gray-300 mt-2">We provide every new client with a free, actionable business idea within 7 days.</p>
    <a href="#contact" class="mt-4 inline-block px-6 py-3 rounded-full bg-gradient-to-r from-indigo-600 to-pink-500 font-semibold shadow-lg">
      Book a Free Discovery Call
    </a>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="max-w-6xl mx-auto px-6 py-12">
    <h3 class="text-2xl font-bold mb-4">Contact Us</h3>
    <p class="text-gray-300">Email us at <b>hello@yourdomain.com</b> or use the form below:</p>
    <form action="https://formspree.io/f/your_form_id" method="POST" class="mt-6 grid gap-4 md:w-1/2">
      <input type="text" name="name" placeholder="Your Name" required class="px-4 py-3 rounded-lg bg-white/5"/>
      <input type="email" name="email" placeholder="Your Email" required class="px-4 py-3 rounded-lg bg-white/5"/>
      <textarea name="message" rows="5" placeholder="Tell us about your project" class="px-4 py-3 rounded-lg bg-white/5"></textarea>
      <button type="submit" class="px-6 py-3 rounded-full bg-gradient-to-r from-indigo-600 to-pink-500 font-semibold shadow-lg">
        Send Message
      </button>
    </form>
  </section>

  <!-- FOOTER -->
  <footer class="py-6 text-center text-gray-500 text-sm">
    © <script>document.write(new Date().getFullYear())</script> 𝙒𝘼𝙌𝘼𝙎 𝙒𝙀𝘽 𝙎𝙀𝙍𝙑𝙄𝘾𝙀𝙎. Built with ❤️, Hosted on GitHub Pages.
  </footer>
</body>
</html>
