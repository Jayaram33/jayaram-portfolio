# jayaram-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jayaram | Digital Marketing Specialist – SEO, Google Ads, Meta Ads, AI Video</title>
  <meta name="description" content="Jayaram – Digital Marketing professional with 4+ years of experience in SEO, Google Ads, Meta Ads, AI video content creation, social media management and content writing." />
  <meta name="keywords" content="digital marketing, SEO, Google Ads, Meta Ads, AI video, social media management, content writing, freelance digital marketer" />
  <meta name="author" content="Jayaram" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet" />
  <style>
:root{
  --bg:#0b0b1a;
  --bg2:#12122a;
  --card:#181838;
  --text:#e8e8f5;
  --muted:#a3a3c2;
  --primary:#7c5cff;
  --accent:#00d4ff;
  --radius:18px;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:'Inter',sans-serif;background:var(--bg);color:var(--text);line-height:1.7;overflow-x:hidden}
h1,h2,h3,h4,.logo,.btn{font-family:'Poppins',sans-serif}
a{color:inherit;text-decoration:none}
ul{list-style:none}
img{max-width:100%;display:block}
.container{width:min(1140px,92%);margin:auto}

/* Buttons */
.btn{display:inline-block;padding:13px 28px;border-radius:50px;background:linear-gradient(135deg,var(--primary),var(--accent));color:#fff;font-weight:600;border:none;cursor:pointer;transition:.3s;font-size:15px}
.btn:hover{transform:translateY(-3px);box-shadow:0 10px 30px rgba(124,92,255,.4)}
.btn-outline{background:transparent;border:2px solid var(--primary)}
.btn-sm{padding:8px 20px;font-size:14px}

/* Nav */
.nav{position:fixed;top:0;width:100%;z-index:100;transition:.3s}
.nav.scrolled{background:rgba(11,11,26,.92);backdrop-filter:blur(10px);box-shadow:0 2px 20px rgba(0,0,0,.4)}
.nav-inner{display:flex;justify-content:space-between;align-items:center;height:72px}
.logo{font-size:26px;font-weight:800}
.logo span{color:var(--accent)}
.menu{display:flex;align-items:center;gap:28px}
.menu a{font-size:15px;color:var(--muted);transition:.3s}
.menu a:hover{color:#fff}
.menu a.btn{color:#fff}
.burger{display:none;background:none;border:none;cursor:pointer}
.burger span{display:block;width:26px;height:3px;background:#fff;margin:5px 0;border-radius:3px;transition:.3s}

/* Hero */
.hero{min-height:100vh;display:flex;align-items:center;padding-top:90px;
  background:radial-gradient(circle at 80% 20%,rgba(124,92,255,.25),transparent 45%),radial-gradient(circle at 10% 80%,rgba(0,212,255,.15),transparent 40%)}
.hero-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:50px;align-items:center}
.tag{color:var(--accent);font-weight:600;margin-bottom:6px}
.hero h1{font-size:clamp(38px,6vw,64px);line-height:1.1;font-weight:800}
.grad{background:linear-gradient(135deg,var(--primary),var(--accent));-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent}
.hero h2{font-size:clamp(20px,3vw,28px);margin:10px 0 18px;font-weight:500;color:var(--muted)}
.lead{color:var(--muted);max-width:560px;margin-bottom:28px}
.hero-btns{display:flex;gap:16px;flex-wrap:wrap;margin-bottom:28px}
.chips{display:flex;flex-wrap:wrap;gap:10px}
.chips li{padding:6px 16px;border:1px solid rgba(255,255,255,.15);border-radius:50px;font-size:13px;color:var(--muted)}
.photo-wrap{position:relative;max-width:380px;margin:auto}
.photo-wrap img{border-radius:30px;border:3px solid rgba(124,92,255,.5);box-shadow:0 20px 60px rgba(124,92,255,.35)}
.float{position:absolute;background:var(--card);padding:10px 16px;border-radius:14px;font-size:14px;font-weight:600;box-shadow:0 10px 30px rgba(0,0,0,.4);animation:floaty 4s ease-in-out infinite}
.f1{top:20px;left:-40px}
.f2{bottom:90px;right:-30px;animation-delay:1s}
.f3{bottom:-10px;left:20px;animation-delay:2s}
@keyframes floaty{50%{transform:translateY(-12px)}}

/* Stats */
.stats{background:var(--bg2);padding:50px 0}
.stats-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;text-align:center}
.stat h3{font-size:40px;color:var(--accent)}
.stat p{color:var(--muted);font-size:14px}

/* Sections */
.section{padding:100px 0}
.section.alt{background:var(--bg2)}
.center{text-align:center;margin-bottom:50px}
.eyebrow{color:var(--accent);text-transform:uppercase;letter-spacing:2px;font-size:13px;font-weight:600;margin-bottom:8px}
.title{font-size:clamp(26px,4vw,38px);line-height:1.25;margin-bottom:16px}
.sub{color:var(--muted)}
.about-grid{display:grid;grid-template-columns:1fr 1.1fr;gap:50px;align-items:start}
.about-grid p{color:var(--muted);margin-bottom:16px}
.ticks li{padding-left:28px;position:relative;margin:8px 0}
.ticks li::before{content:"✔";position:absolute;left:0;color:var(--accent)}

/* Cards */
.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:24px}
.card{background:var(--card);padding:32px 28px;border-radius:var(--radius);border:1px solid rgba(255,255,255,.06);transition:.35s}
.card:hover{transform:translateY(-8px);border-color:var(--primary);box-shadow:0 18px 40px rgba(124,92,255,.2)}
.icon{font-size:36px;margin-bottom:14px}
.card h3{margin-bottom:8px;font-size:21px}
.card>p{color:var(--muted);font-size:15px;margin-bottom:14px}
.card ul li{font-size:14px;color:var(--muted);padding-left:20px;position:relative;margin:5px 0}
.card ul li::before{content:"→";position:absolute;left:0;color:var(--accent)}

/* Skills + results */
.results-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px}
.bar{margin-bottom:18px}
.bar span{font-size:14px;font-weight:500}
.bar>div{height:9px;background:var(--card);border-radius:20px;margin-top:6px;overflow:hidden}
.bar i{display:block;height:100%;width:0;background:linear-gradient(90deg,var(--primary),var(--accent));border-radius:20px;transition:width 1.4s ease}
.bar.in i{width:var(--w)}
.result-list{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.result{background:var(--card);padding:22px;border-radius:var(--radius);border:1px solid rgba(255,255,255,.06)}
.result b{display:block;font-size:30px;font-family:'Poppins';color:var(--accent)}
.result span{font-size:13px;color:var(--muted)}
.note{font-size:12px;color:var(--muted);margin-top:14px}

/* Timeline */
.timeline{max-width:720px;margin:auto;border-left:2px solid rgba(124,92,255,.5);padding-left:30px}
.t-item{position:relative;margin-bottom:34px}
.dot{position:absolute;left:-39px;top:6px;width:16px;height:16px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 5px rgba(0,212,255,.2)}
.t-item small{color:var(--accent)}
.t-item p{color:var(--muted);margin-top:4px}

/* Steps */
.steps{display:grid;grid-template-columns:repeat(4,1fr);gap:22px}
.step{background:var(--card);padding:28px;border-radius:var(--radius);text-align:center;border:1px solid rgba(255,255,255,.06)}
.step b{font-size:38px;font-family:'Poppins';color:var(--primary);opacity:.8}
.step h4{margin:6px 0}
.step p{font-size:14px;color:var(--muted)}

/* Clients */
.industries{display:flex;flex-wrap:wrap;gap:14px;justify-content:center;margin-bottom:44px}
.industries span{background:var(--card);padding:10px 22px;border-radius:50px;font-size:14px;border:1px solid rgba(255,255,255,.08)}
.testi{display:grid;grid-template-columns:1fr 1fr;gap:24px}
blockquote{background:var(--card);padding:28px;border-radius:var(--radius);border-left:4px solid var(--accent);font-style:italic;color:var(--muted)}
cite{display:block;margin-top:12px;font-style:normal;font-weight:600;color:var(--text);font-size:14px}

/* Contact */
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:50px}
.contact-grid>div>p{color:var(--muted);margin-bottom:20px}
.contact-list li{margin:10px 0}
.contact-list a:hover{color:var(--accent)}
.socials{display:flex;gap:12px;margin-top:20px;flex-wrap:wrap}
.socials a{padding:8px 18px;border:1px solid var(--primary);border-radius:50px;font-size:14px;transition:.3s}
.socials a:hover{background:var(--primary)}
.form{background:var(--card);padding:32px;border-radius:var(--radius);border:1px solid rgba(255,255,255,.06)}
.form label{display:block;font-size:14px;margin-bottom:16px;font-weight:500}
.form input,.form select,.form textarea{width:100%;margin-top:6px;padding:12px 14px;background:var(--bg);border:1px solid rgba(255,255,255,.12);border-radius:10px;color:var(--text);font:inherit}
.form input:focus,.form select:focus,.form textarea:focus{outline:none;border-color:var(--accent)}
.form-msg{margin-top:12px;font-size:14px;color:var(--accent)}

/* Footer + WhatsApp */
.footer{background:var(--bg2);text-align:center;padding:26px 0;color:var(--muted);font-size:14px}
.wa{position:fixed;right:20px;bottom:20px;width:56px;height:56px;border-radius:50%;background:#25d366;display:flex;align-items:center;justify-content:center;font-size:26px;box-shadow:0 8px 24px rgba(0,0,0,.4);z-index:90;transition:.3s}
.wa:hover{transform:scale(1.1)}

/* Reveal animation */
.reveal{opacity:0;transform:translateY(40px);transition:1s ease}
.reveal.show{opacity:1;transform:none}

/* Responsive */
@media(max-width:960px){
  .hero-grid,.about-grid,.results-grid,.contact-grid,.testi{grid-template-columns:1fr}
  .cards{grid-template-columns:1fr 1fr}
  .steps,.stats-grid{grid-template-columns:1fr 1fr}
  .hero-visual{order:-1}
  .photo-wrap{max-width:280px}
  .f1{left:-10px}.f2{right:-10px}
}
@media(max-width:700px){
  .burger{display:block}
  .menu{position:absolute;top:72px;right:0;left:0;background:var(--bg2);flex-direction:column;padding:24px 0;gap:18px;display:none}
  .menu.open{display:flex}
  .cards{grid-template-columns:1fr}
  .section{padding:70px 0}
  .result-list{grid-template-columns:1fr}
}
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <header class="nav" id="nav">
    <div class="container nav-inner">
      <a href="#home" class="logo">Jayaram<span>.</span></a>
      <nav class="menu" id="menu">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#results">Results</a>
        <a href="#experience">Experience</a>
        <a href="#clients">Clients</a>
        <a href="#contact" class="btn btn-sm">Hire Me</a>
      </nav>
      <button class="burger" id="burger" aria-label="Toggle menu"><span></span><span></span><span></span></button>
    </div>
  </header>

  <!-- HERO -->
  <section class="hero" id="home">
    <div class="container hero-grid">
      <div class="hero-text reveal">
        <p class="tag">👋 Hi, I'm</p>
        <h1>Jayaram <span class="grad">[Your Surname]</span></h1>
        <h2>Digital Marketing Specialist</h2>
        <p class="lead">
          4+ years of helping brands get found on Google, convert on ads and grow on social media —
          with SEO, Google Ads, Meta Ads, AI video content and high-quality content writing.
        </p>
        <div class="hero-btns">
          <a href="#contact" class="btn">Let's Work Together</a>
          <a href="#services" class="btn btn-outline">View Services</a>
        </div>
        <ul class="chips">
          <li>SEO</li><li>Google Ads</li><li>Meta Ads</li><li>AI Video</li><li>Social Media</li><li>Content Writing</li>
        </ul>
      </div>
      <div class="hero-visual reveal">
        <div class="photo-wrap">
          <!-- Replace with your photo: put it in the same folder and change src -->
          <img src="https://placehold.co/420x480/1e1b4b/ffffff?text=Jayaram" alt="Jayaram – Digital Marketer" />
          <div class="float f1">📈 +180% Traffic</div>
          <div class="float f2">🎯 4.8x ROAS</div>
          <div class="float f3">🎬 AI Video</div>
        </div>
      </div>
    </div>
  </section>

  <!-- STATS -->
  <section class="stats">
    <div class="container stats-grid">
      <div class="stat"><h3><span class="count" data-to="4">0</span>+</h3><p>Years Experience</p></div>
      <div class="stat"><h3><span class="count" data-to="50">0</span>+</h3><p>Projects Delivered</p></div>
      <div class="stat"><h3><span class="count" data-to="25">0</span>+</h3><p>Happy Clients</p></div>
      <div class="stat"><h3><span class="count" data-to="100">0</span>+</h3><p>Campaigns Managed</p></div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="section" id="about">
    <div class="container about-grid">
      <div class="reveal">
        <p class="eyebrow">About Me</p>
        <h2 class="title">Marketing that is creative, data-driven and focused on results</h2>
      </div>
      <div class="reveal">
        <p>
          I'm Jayaram, a digital marketer with over four years of hands-on experience helping
          businesses grow online. I combine strategy, creativity and analytics to build a complete
          marketing system — from ranking on Google to running profitable ad campaigns and creating
          scroll-stopping content.
        </p>
        <p>
          I'm also actively using AI tools to produce video content faster and at lower cost, so my
          clients can stay consistent on social media without a big production budget.
        </p>
        <ul class="ticks">
          <li>Strategy backed by data and analytics</li>
          <li>Transparent monthly reporting</li>
          <li>Fast turnaround and clear communication</li>
          <li>One person for SEO, ads, content and social</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- SERVICES -->
  <section class="section alt" id="services">
    <div class="container">
      <div class="center reveal">
        <p class="eyebrow">What I Do</p>
        <h2 class="title">Services to grow your business online</h2>
      </div>
      <div class="cards">
        <article class="card reveal">
          <div class="icon">🔍</div>
          <h3>SEO</h3>
          <p>Rank higher and get organic leads that keep coming.</p>
          <ul><li>Keyword research</li><li>On-page &amp; technical SEO</li><li>Link building</li><li>Local SEO &amp; Google Business Profile</li></ul>
        </article>
        <article class="card reveal">
          <div class="icon">💰</div>
          <h3>Google Ads</h3>
          <p>High-intent traffic from people ready to buy.</p>
          <ul><li>Search &amp; Display campaigns</li><li>Shopping &amp; YouTube Ads</li><li>Conversion tracking (GA4/GTM)</li><li>Budget &amp; bid optimisation</li></ul>
        </article>
        <article class="card reveal">
          <div class="icon">📱</div>
          <h3>Meta Ads</h3>
          <p>Facebook &amp; Instagram ads that generate leads and sales.</p>
          <ul><li>Lead generation campaigns</li><li>Retargeting &amp; lookalike audiences</li><li>Creative testing (A/B)</li><li>Pixel &amp; Conversion API setup</li></ul>
        </article>
        <article class="card reveal">
          <div class="icon">🎬</div>
          <h3>AI Video Content Creation</h3>
          <p>Reels, ads and explainers made faster with AI tools.</p>
          <ul><li>AI-generated reels &amp; shorts</li><li>Product &amp; promo videos</li><li>Voice-over, captions &amp; editing</li><li>Script to final video</li></ul>
        </article>
        <article class="card reveal">
          <div class="icon">🤝</div>
          <h3>Social Media Management</h3>
          <p>I handle your accounts so your brand stays active and engaging.</p>
          <ul><li>Instagram, Facebook, LinkedIn, YouTube</li><li>Content calendar &amp; posting</li><li>Community engagement</li><li>Monthly growth reports</li></ul>
        </article>
        <article class="card reveal">
          <div class="icon">✍️</div>
          <h3>Content Writing</h3>
          <p>Words that rank, engage and convert.</p>
          <ul><li>Blogs &amp; SEO articles</li><li>Website &amp; landing page copy</li><li>Ad copy &amp; captions</li><li>Email &amp; newsletter content</li></ul>
        </article>
      </div>
    </div>
  </section>

  <!-- RESULTS / SKILLS -->
  <section class="section" id="results">
    <div class="container results-grid">
      <div class="reveal">
        <p class="eyebrow">Skills</p>
        <h2 class="title">Tools &amp; expertise</h2>
        <div class="bars">
          <div class="bar"><span>SEO</span><div><i style="--w:92%"></i></div></div>
          <div class="bar"><span>Google Ads</span><div><i style="--w:90%"></i></div></div>
          <div class="bar"><span>Meta Ads</span><div><i style="--w:90%"></i></div></div>
          <div class="bar"><span>AI Video Creation</span><div><i style="--w:85%"></i></div></div>
          <div class="bar"><span>Social Media</span><div><i style="--w:92%"></i></div></div>
          <div class="bar"><span>Content Writing</span><div><i style="--w:88%"></i></div></div>
        </div>
      </div>
      <div class="reveal">
        <p class="eyebrow">Sample Results</p>
        <h2 class="title">What clients can expect</h2>
        <!-- Replace these with your real numbers -->
        <div class="result-list">
          <div class="result"><b>+180%</b><span>Organic traffic growth in 6 months</span></div>
          <div class="result"><b>4.8x</b><span>Return on ad spend (Meta Ads)</span></div>
          <div class="result"><b>-40%</b><span>Cost per lead (Google Ads)</span></div>
          <div class="result"><b>10K+</b><span>Followers grown organically</span></div>
        </div>
        <p class="note">*Update these numbers with your real client results.</p>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section class="section alt" id="experience">
    <div class="container">
      <div class="center reveal">
        <p class="eyebrow">Journey</p>
        <h2 class="title">My experience</h2>
      </div>
      <div class="timeline">
        <div class="t-item reveal">
          <span class="dot"></span>
          <h4>Digital Marketing Specialist</h4>
          <small>Company Name · 20XX – Present</small>
          <p>Managing SEO, paid campaigns and social media for multiple clients.</p>
        </div>
        <div class="t-item reveal">
          <span class="dot"></span>
          <h4>Digital Marketing Executive</h4>
          <small>Company Name · 20XX – 20XX</small>
          <p>Ran Google Ads and Meta Ads, wrote content and handled brand social accounts.</p>
        </div>
        <div class="t-item reveal">
          <span class="dot"></span>
          <h4>Digital Marketing Trainee / Intern</h4>
          <small>Company Name · 20XX – 20XX</small>
          <p>Learned SEO fundamentals, content creation and campaign reporting.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- PROCESS -->
  <section class="section">
    <div class="container">
      <div class="center reveal">
        <p class="eyebrow">How I Work</p>
        <h2 class="title">A simple 4-step process</h2>
      </div>
      <div class="steps">
        <div class="step reveal"><b>01</b><h4>Discover</h4><p>Understand your business, audience and goals.</p></div>
        <div class="step reveal"><b>02</b><h4>Strategy</h4><p>Create a custom plan across SEO, ads and content.</p></div>
        <div class="step reveal"><b>03</b><h4>Execute</h4><p>Launch campaigns, publish content and manage accounts.</p></div>
        <div class="step reveal"><b>04</b><h4>Optimise</h4><p>Track results, report monthly and keep improving.</p></div>
      </div>
    </div>
  </section>

  <!-- CLIENTS / TESTIMONIALS -->
  <section class="section alt" id="clients">
    <div class="container">
      <div class="center reveal">
        <p class="eyebrow">Clients</p>
        <h2 class="title">Who I've worked with</h2>
        <p class="sub">Add your client logos or industries here.</p>
      </div>
      <div class="industries reveal">
        <span>🛍️ E-commerce</span><span>🏥 Healthcare</span><span>🎓 Education</span>
        <span>🏠 Real Estate</span><span>🍽️ Restaurants</span><span>💻 IT / SaaS</span>
      </div>
      <div class="testi">
        <blockquote class="reveal">
          “Jayaram brought us consistent leads from Google and Instagram. Very professional and always on time.”
          <cite>— Client Name, Company</cite>
        </blockquote>
        <blockquote class="reveal">
          “Our social media finally looks active and our traffic has grown steadily.”
          <cite>— Client Name, Company</cite>
        </blockquote>
      </div>
    </div>
  </section>

  <!-- CTA + CONTACT -->
  <section class="section" id="contact">
    <div class="container contact-grid">
      <div class="reveal">
        <p class="eyebrow">Contact</p>
        <h2 class="title">Let's grow your business together</h2>
        <p>Tell me about your project and I'll get back to you within 24 hours.</p>
        <ul class="contact-list">
          <li>📧 <a href="mailto:youremail@example.com">youremail@example.com</a></li>
          <li>📞 <a href="tel:+919498425830">+91 94984 25830</a></li>
          <li>💬 <a href="https://wa.me/919498425830" target="_blank" rel="noopener">Chat on WhatsApp</a></li>
          <li>📍 India</li>
        </ul>
        <div class="socials">
          <a href="#" aria-label="LinkedIn">LinkedIn</a>
          <a href="#" aria-label="Instagram">Instagram</a>
          <a href="#" aria-label="YouTube">YouTube</a>
        </div>
      </div>

      <form class="form reveal" id="contactForm">
        <label>Your Name<input type="text" id="name" required placeholder="Enter your name" /></label>
        <label>Email<input type="email" id="email" required placeholder="you@example.com" /></label>
        <label>Service Needed
          <select id="service">
            <option>SEO</option>
            <option>Google Ads</option>
            <option>Meta Ads</option>
            <option>AI Video Content</option>
            <option>Social Media Management</option>
            <option>Content Writing</option>
            <option>Full Digital Marketing</option>
          </select>
        </label>
        <label>Message<textarea id="message" rows="4" required placeholder="Tell me about your project"></textarea></label>
        <button type="submit" class="btn">Send Message</button>
        <p class="form-msg" id="formMsg"></p>
      </form>
    </div>
  </section>

  <footer class="footer">
    <div class="container">
      <p>© <span id="year"></span> Jayaram. All rights reserved. · Digital Marketing Specialist</p>
    </div>
  </footer>

  <a href="https://wa.me/919498425830" class="wa" target="_blank" rel="noopener" aria-label="WhatsApp">💬</a>

  <script>
// Sticky navbar style
const nav = document.getElementById('nav');
window.addEventListener('scroll', () => {
  nav.classList.toggle('scrolled', window.scrollY > 40);
});

// Mobile menu
const burger = document.getElementById('burger');
const menu = document.getElementById('menu');
burger.addEventListener('click', () => menu.classList.toggle('open'));
menu.querySelectorAll('a').forEach(a => a.addEventListener('click', () => menu.classList.remove('open')));

// Scroll reveal + skill bars
const io = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.classList.add('show');
      e.target.querySelectorAll('.bar').forEach(b => b.classList.add('in'));
    }
  });
}, { threshold: 0.15 });
document.querySelectorAll('.reveal').forEach(el => io.observe(el));

// Counter animation
const counters = document.querySelectorAll('.count');
const cio = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (!e.isIntersecting) return;
    const el = e.target;
    const to = +el.dataset.to;
    let n = 0;
    const step = Math.max(1, Math.ceil(to / 60));
    const t = setInterval(() => {
      n += step;
      if (n >= to) { n = to; clearInterval(t); }
      el.textContent = n;
    }, 25);
    cio.unobserve(el);
  });
}, { threshold: 0.6 });
counters.forEach(c => cio.observe(c));

// Contact form -> opens WhatsApp with the message (change number below)
const WHATSAPP_NUMBER = '919498425830'; // country code + number, no + or spaces
document.getElementById('contactForm').addEventListener('submit', (e) => {
  e.preventDefault();
  const name = document.getElementById('name').value.trim();
  const email = document.getElementById('email').value.trim();
  const service = document.getElementById('service').value;
  const message = document.getElementById('message').value.trim();
  const text = `Hi Jayaram, I'm ${name} (${email}).%0AService: ${service}%0A${encodeURIComponent(message)}`;
  window.open(`https://wa.me/${WHATSAPP_NUMBER}?text=${text}`, '_blank');
  document.getElementById('formMsg').textContent = 'Thanks! Opening WhatsApp...';
  e.target.reset();
});

// Footer year
document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
