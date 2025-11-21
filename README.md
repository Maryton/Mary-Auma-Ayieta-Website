# Mary-Auma-Ayieta-Website
Personal website
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Mary Auma — Language Expert, Writer & Researcher</title>
  <meta name="description" content="Mary Auma — Language expert, writer, and researcher. Content writing, copywriting, research, AI prompt creation, SEO fundamentals, and remote collaboration.">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Poppins:wght@600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" crossorigin="anonymous">
  <meta name="theme-color" content="#007acc">

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Mary Auma",
    "url": "https://your-site.example.com",
    "sameAs": [
      "https://linkedin.com/in/maryauma"
    ],
    "jobTitle": "Language Expert, Writer, Researcher",
    "email": "mailto:maritesamary@gmail.com",
    "telephone": "+254745190492"
  }
  </script>

  <style>
    :root{
      --brand:#007acc;
      --accent:#ff6f91;
      --bg:#f7f8fb;
      --card:#ffffff;
      --muted:#666;
      --radius:12px;
      --max-width:1000px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:"Open Sans",system-ui,Arial,sans-serif;
      background:var(--bg);
      color:#222;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
      scroll-behavior:smooth;
    }

    a{color:var(--brand); text-decoration:none}
    a:focus{outline:3px solid rgba(0,122,204,0.15); outline-offset:3px}

    .skip-link {
      position: absolute;
      left: -999px;
      top: auto;
      width: 1px;
      height: 1px;
      overflow: hidden;
    }
    .skip-link:focus {
      left: 1rem;
      top: 1rem;
      width: auto;
      height: auto;
      padding: .5rem .75rem;
      background: #000;
      color: #fff;
      z-index: 1000;
      border-radius: 6px;
    }

    header{
      background:linear-gradient(135deg,var(--brand), #005f9e);
      color:#fff;
      padding:2rem 1rem;
    }
    .header-inner{
      max-width:var(--max-width);
      margin:0 auto;
      display:flex;
      gap:1rem;
      align-items:center;
      justify-content:space-between;
      flex-wrap:wrap;
    }
    .brand{
      display:flex;
      align-items:center;
      gap:1rem;
    }
    .avatar{
      width:86px;
      height:86px;
      border-radius:50%;
      border:3px solid rgba(255,255,255,0.15);
      object-fit:cover;
      background:#eee;
      flex-shrink:0;
    }
    .name{
      font-family:"Poppins",sans-serif;
      font-size:1.45rem;
      margin:0;
    }
    .tagline{margin:0; color:rgba(255,255,255,0.92); font-weight:600}
    nav.primary{
      display:flex;
      gap:0.75rem;
      align-items:center;
      flex-wrap:wrap;
    }
    nav.primary a{
      color:#fff;
      padding:.45rem .65rem;
      border-radius:8px;
      font-weight:600;
      transition:background .18s,color .18s,transform .12s;
    }
    nav.primary a:hover, nav.primary a:focus{
      background:rgba(255,255,255,0.08);
      transform:translateY(-1px);
      color:#fff;
    }

    main{
      max-width:var(--max-width);
      margin: -36px auto 2rem;
      padding:0 1rem;
    }
    section.card{
      background:var(--card);
      border-radius:var(--radius);
      padding:1.6rem;
      box-shadow:0 8px 22px rgba(8,30,60,0.06);
      margin-bottom:1.25rem;
    }
    h2{
      font-family:"Poppins",sans-serif;
      color:var(--brand);
      margin:0 0 .75rem 0;
      font-size:1.25rem;
      display:flex;
      align-items:center;
      gap:.5rem;
    }
    p.lead{margin:0 0 1rem 0; color:var(--muted)}
    ul.skills{display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:.6rem; padding:0; list-style:none; margin:0}
    ul.skills li{display:flex; gap:.6rem; align-items:flex-start; color:#333}
    ul.experience, ul.edu{list-style:none; padding:0; margin:0}
    ul.experience li, ul.edu li{margin-bottom:.6rem}
    .meta{color:var(--muted); font-weight:600; font-size:.95rem}

    .contact-grid{
      display:grid;
      grid-template-columns:1fr 320px;
      gap:1rem;
    }
    .contact-info p{margin:.3rem 0}
    form.contact-form{
      background:linear-gradient(180deg, #fff, #fbfdff);
      padding:1rem;
      border-radius:10px;
      border:1px solid rgba(0,0,0,0.04);
    }
    .field{display:flex; flex-direction:column; gap:.35rem; margin-bottom:.65rem}
    label{font-size:.9rem; color:var(--muted)}
    input[type="text"], input[type="email"], textarea{
      padding:.6rem .7rem;
      border:1px solid #e3e7ee;
      border-radius:8px;
      font-size:1rem;
      font-family:inherit;
    }
    textarea{min-height:120px; resize:vertical}
    button.btn{
      background:var(--brand);
      color:#fff;
      padding:.6rem .9rem;
      border-radius:8px;
      border:0;
      font-weight:700;
      cursor:pointer;
    }
    .small{
      font-size:.9rem; color:var(--muted)
    }
    footer.site-foot{
      text-align:center;
      padding:1rem 0;
      color:#fff;
      background:var(--brand);
      margin-top:1rem;
      border-radius:0 0 var(--radius) var(--radius);
    }

    @media (max-width:860px){
      .contact-grid{grid-template-columns:1fr}
      main{margin-top:0}
      .header-inner{gap:.75rem}
      .avatar{width:72px;height:72px}
    }
  </style>
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header role="banner" aria-label="Site header">
    <div class="header-inner">
      <div class="brand">
        <!-- Place your image at assets/avatar.png -->
        <img src="assets/avatar.png" alt="Portrait photo of Mary Auma" class="avatar" width="86" height="86">
        <div>
          <h1 class="name">Mary Auma</h1>
          <p class="tagline">Language Expert • Writer • Researcher • Content Creator</p>
        </div>
      </div>

      <nav class="primary" role="navigation" aria-label="Primary">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main id="main" tabindex="-1">
    <section id="about" class="card" aria-labelledby="about-heading">
      <h2 id="about-heading"><i class="fas fa-user" aria-hidden="true"></i> About Me</h2>
      <p class="lead">I am a passionate language professional with over three years of experience in teaching, content writing, copywriting, and research. I simplify complex ideas for diverse audiences and deliver clear, engaging content tailored to client goals. I thrive in remote work environments and bring a detail-oriented, collaborative approach to projects.</p>
    </section>

    <section id="skills" class="card" aria-labelledby="skills-heading">
      <h2 id="skills-heading"><i class="fas fa-toolbox" aria-hidden="true"></i> Skills & Tools</h2>
      <ul class="skills" aria-label="Skills list">
        <li><i class="fas fa-pencil-alt" aria-hidden="true"></i> Content Writing & Copywriting</li>
        <li><i class="fas fa-book" aria-hidden="true"></i> Grammar, Syntax & Style Control</li>
        <li><i class="fas fa-lightbulb" aria-hidden="true"></i> Creative Writing & Communication</li>
        <li><i class="fas fa-search" aria-hidden="true"></i> Research & Analysis</li>
        <li><i class="fas fa-robot" aria-hidden="true"></i> AI Prompt Creation & Evaluation</li>
        <li><i class="fas fa-tasks" aria-hidden="true"></i> Content Optimization for Clarity & Accuracy</li>
        <li><i class="fas fa-chart-line" aria-hidden="true"></i> SEO Fundamentals</li>
        <li><i class="fas fa-users" aria-hidden="true"></i> Remote Collaboration & Project Management</li>
        <li><i class="fas fa-laptop" aria-hidden="true"></i> Google Workspace, Microsoft Office, Canva</li>
        <li><i class="fab fa-linkedin" aria-hidden="true"></i> Social Media: LinkedIn, X, Instagram, Facebook</li>
      </ul>
    </section>

    <section id="experience" class="card" aria-labelledby="exp-heading">
      <h2 id="exp-heading"><i class="fas fa-briefcase" aria-hidden="true"></i> Experience</h2>
      <ul class="experience">
        <li><strong>Freelance Ads Copywriter</strong> <span class="meta">Jan 2025 — Oct 2025</span>
          <div class="small">Researched client services, created LinkedIn ad copy, managed multiple projects independently, and aligned messaging with client goals.</div>
        </li>
        <li><strong>English & Integrated Science Teacher</strong> <span class="meta">Jan 2024 — Jan 2025</span>
          <div class="small">Delivered lessons, supervised experiments, prepared assessments, and promoted student engagement.</div>
        </li>
        <li><strong>Homeschool Tutor</strong> <span class="meta">Apr 2022 — Dec 2023</span>
          <div class="small">Personalized lessons in English, Science & Mathematics; tracked progress and prepared students for exams.</div>
        </li>
      </ul>
    </section>

    <section id="education" class="card" aria-labelledby="edu-heading">
      <h2 id="edu-heading"><i class="fas fa-graduation-cap" aria-hidden="true"></i> Education & Certifications</h2>
      <ul class="edu">
        <li><strong>Bachelor of Education (English & Literature)</strong> — Kenyatta University, 2nd Class Upper, 2017–2022</li>
        <li>Data Analytics Essentials — Cisco</li>
        <li>LinkedIn Marketing Solutions Fundamentals — LinkedIn</li>
        <li>Google Ads Apps Certification — Skillshop</li>
        <li>Gender-Responsive Teaching — Girl Rising</li>
        <li>Certificate in Computer Fundamentals — Elgonview College</li>
      </ul>
    </section>

    <section id="contact" class="card" aria-labelledby="contact-heading">
      <h2 id="contact-heading"><i class="fas fa-envelope" aria-hidden="true"></i> Contact</h2>

      <div class="contact-grid">
        <div class="contact-info">
          <p><strong>Email:</strong> <a href="mailto:maritesamary@gmail.com">maritesamary@gmail.com</a></p>
          <p><strong>Phone:</strong> <a href="tel:+254745190492">+254 745190492</a></p>
          <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/maryauma" target="_blank" rel="noopener">linkedin.com/in/maryauma</a></p>
          <p><strong>Resume:</strong> <a href="/resume.md" download>Download (placeholder)</a></p>
          <p class="small">Prefer direct messaging? Use the form to send a quick note or request.</p>
        </div>

        <form class="contact-form" id="contactForm" action="#" method="post" onsubmit="return handleContact(event)" aria-label="Contact form">
          <div class="field">
            <label for="name">Name</label>
            <input id="name" name="name" type="text" required placeholder="Your name">
          </div>
          <div class="field">
            <label for="email">Email</label>
            <input id="email" name="email" type="email" required placeholder="you@example.com">
          </div>
          <div class="field">
            <label for="message">Message</label>
            <textarea id="message" name="message" required placeholder="Write your message..."></textarea>
          </div>
          <div style="display:flex; gap:.6rem; align-items:center;">
            <button type="submit" class="btn">Send Message</button>
            <span class="small" id="status" aria-live="polite"></span>
          </div>
          <noscript class="small">JavaScript is disabled. Use the email link above to contact.</noscript>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-foot" role="contentinfo">
    <div class="small">&copy; 2025 Mary Auma</div>
  </footer>

  <script>
    function handleContact(e){
      e.preventDefault();
      var name = document.getElementById('name').value.trim();
      var email = document.getElementById('email').value.trim();
      var message = document.getElementById('message').value.trim();
      var status = document.getElementById('status');

      if(!name || !email || !message){
        status.textContent = 'Please fill all fields.';
        return false;
      }

      var subject = encodeURIComponent('Portfolio contact from ' + name);
      var body = encodeURIComponent('Name: ' + name + '\\nEmail: ' + email + '\\n\\n' + message);
      var mailto = 'mailto:maritesamary@gmail.com?subject=' + subject + '&body=' + body;

      window.location.href = mailto;
      status.textContent = 'Opening mail client...';
      setTimeout(function(){ status.textContent = ''; }, 4000);
      return true;
    }
  </script>
</body>
</html>
````markdown name=README.md
```markdown
# Mary Auma — Personal Website
