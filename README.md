# New-project-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Shashikant | Website Developer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=DM+Sans:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --paper:#E9EEF5; --ink:#16213A; --muted:#55627D; --cobalt:#2F5BFF; --sun:#FFC857; --white:#fff;
  --head:"Bricolage Grotesque","Segoe UI",Arial,sans-serif;
  --body:"DM Sans","Segoe UI",Arial,sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--paper);color:var(--ink);font-family:var(--body);font-size:1.0625rem;line-height:1.6}
a{color:inherit}
:focus-visible{outline:3px solid var(--cobalt);outline-offset:3px}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
nav{display:flex;justify-content:space-between;align-items:center;padding:20px 0}
nav strong{font-family:var(--head);font-size:1.2rem}
nav a{text-decoration:none;margin-left:20px;font-weight:500}
nav a:hover{color:var(--cobalt)}

/* Hero: a browser window, because this person builds websites */
.browser{background:var(--white);border:2px solid var(--ink);border-radius:14px;overflow:hidden;box-shadow:8px 8px 0 var(--ink);margin:24px 0 72px}
.bar{display:flex;align-items:center;gap:8px;padding:10px 14px;border-bottom:2px solid var(--ink);background:var(--sun)}
.dot{width:12px;height:12px;border-radius:50%;border:2px solid var(--ink);background:var(--white)}
.url{margin-left:10px;flex:1;background:var(--white);border:2px solid var(--ink);border-radius:20px;padding:2px 14px;font-size:.85rem;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}
.hero{padding:48px 32px 56px}
h1{font-family:var(--head);font-weight:800;font-size:clamp(2.8rem,10vw,5.5rem);line-height:1;letter-spacing:-.03em}
.role{font-family:var(--head);font-weight:500;font-size:clamp(1.2rem,3.5vw,1.7rem);color:var(--cobalt);margin:14px 0 18px}
.hero p{max-width:34em;color:var(--muted)}
.btns{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.btn{display:inline-block;padding:12px 22px;border-radius:10px;border:2px solid var(--ink);font-weight:500;text-decoration:none}
.btn.main{background:var(--cobalt);color:var(--white)}
.btn.alt{background:var(--white)}
.btn:hover{transform:translate(-2px,-2px);box-shadow:3px 3px 0 var(--ink)}

section{padding:0 0 72px}
h2{font-family:var(--head);font-size:clamp(1.7rem,5vw,2.3rem);letter-spacing:-.02em;margin-bottom:8px}
.lead{color:var(--muted);max-width:36em;margin-bottom:28px}
.grid{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(250px,1fr))}
.box{background:var(--white);border:2px solid var(--ink);border-radius:12px;padding:22px}
.box h3{font-family:var(--head);font-size:1.25rem;margin-bottom:6px}
.box p{color:var(--muted);font-size:1rem}
.skills{display:flex;flex-wrap:wrap;gap:10px;list-style:none}
.skills li{background:var(--white);border:2px solid var(--ink);border-radius:30px;padding:6px 16px;font-weight:500}
.proj{border-style:dashed}
.proj .tag{display:inline-block;background:var(--sun);border:2px solid var(--ink);border-radius:6px;padding:0 8px;font-size:.85rem;font-weight:500;margin-bottom:10px}

.contact{background:var(--ink);color:var(--white);border-radius:14px;padding:40px 28px}
.contact p{color:#C7D0E4;margin-bottom:20px;max-width:32em}
.contact .btn{background:var(--sun);color:var(--ink);border-color:var(--sun)}
.links{margin-top:22px;display:flex;flex-wrap:wrap;gap:18px}
.links a{color:#C7D0E4}
footer{text-align:center;color:var(--muted);font-size:.9rem;padding:32px 0}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}.btn:hover{transform:none}}
@media (max-width:520px){.hero{padding:32px 20px 40px}nav a{margin-left:14px}}
</style>
</head>
<body>
<div class="wrap">
  <nav>
    <strong>Shashikant</strong>
    <div><a href="#work">Work</a><a href="#skills">Skills</a><a href="#contact">Contact</a></div>
  </nav>

  <header class="browser">
    <div class="bar">
      <span class="dot"></span><span class="dot"></span><span class="dot"></span>
      <span class="url">shashikant.dev</span>
    </div>
    <div class="hero">
      <h1>Shashikant</h1>
      <p class="role">Website Developer</p>
      <p>I build fast, clear websites that work well on phones and laptops, from personal portfolios to full business sites.</p>
      <div class="btns">
        <a class="btn main" href="#contact">Hire me</a>
        <a class="btn alt" href="#work">See my work</a>
      </div>
    </div>
  </header>

  <section id="skills">
    <h2>What I build</h2>
    <p class="lead">Websites designed around what your visitors need to do.</p>
    <div class="grid">
      <div class="box"><h3>Business websites</h3><p>Clear pages that tell customers who you are and how to reach you.</p></div>
      <div class="box"><h3>Portfolios</h3><p>A personal site that shows your work and gets you noticed.</p></div>
      <div class="box"><h3>Online stores</h3><p>Product pages and checkout that are simple to use on mobile.</p></div>
    </div>
  </section>

  <section>
    <h2>Tools I use</h2>
    <p class="lead">Edit this list to match your own skills.</p>
    <ul class="skills">
      <li>HTML</li><li>CSS</li><li>JavaScript</li><li>Responsive design</li><li>Git</li>
    </ul>
  </section>

  <section id="work">
    <h2>Projects</h2>
    <p class="lead">Replace these placeholders with your real projects.</p>
    <div class="grid">
      <div class="box proj"><span class="tag">Add project</span><h3>Project name</h3><p>One line on what you built and who it was for.</p></div>
      <div class="box proj"><span class="tag">Add project</span><h3>Project name</h3><p>One line on what you built and who it was for.</p></div>
      <div class="box proj"><span class="tag">Add project</span><h3>Project name</h3><p>One line on what you built and who it was for.</p></div>
    </div>
  </section>

  <section id="contact">
    <div class="contact">
      <h2>Need a website?</h2>
      <p>Tell me what you want to build and I will reply with a plan and a price.</p>
      <a class="btn" href="mailto:sky.555swr@gmail.com">Email Shashikant</a>
      <div class="links">
        <a href="mailto:sky.555swr@gmail.com">sky.555swr@gmail.com</a>
        <a href="#">LinkedIn</a>
      </div>
    </div>
  </section>

  <footer>&copy; 2026 Shashikant</footer>
</div>
</body>
</html>

