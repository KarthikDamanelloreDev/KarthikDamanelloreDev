<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KarthikDamanelloreDev — README</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@3.11.0/dist/tabler-icons.min.css">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --bg:#ffffff;
  --surface:#f6f8fa;
  --surface2:#eaeef2;
  --border:#d0d7de;
  --border-light:#eaeef2;
  --text:#1f2328;
  --text2:#656d76;
  --text3:#9198a1;
  --blue:#0969da;
  --blue-bg:#ddf4ff;
  --blue-border:#54aeff66;
  --green:#1a7f37;
  --green-bg:#dafbe1;
  --purple:#8250df;
  --purple-bg:#fbefff;
  --orange:#bc4c00;
  --orange-bg:#fff1e5;
  --sans:'Inter',system-ui,sans-serif;
  --mono:'JetBrains Mono',monospace;
}
body{background:#f6f8fa;font-family:var(--sans);color:var(--text);font-size:14px;line-height:1.6}

.gh-nav{background:var(--bg);border-bottom:1px solid var(--border);padding:0 24px;height:48px;display:flex;align-items:center;gap:16px;position:sticky;top:0;z-index:50}
.gh-nav-logo{display:flex;align-items:center}
.gh-nav-logo svg{width:24px;height:24px;fill:var(--text)}
.gh-nav-crumb{font-size:13px;display:flex;align-items:center;gap:6px;color:var(--text2)}
.gh-nav-crumb a{color:var(--blue);text-decoration:none;font-weight:500}
.gh-nav-crumb a:hover{text-decoration:underline}
.gh-nav-crumb .sep{color:var(--text3);font-weight:300}
.special-badge{background:var(--blue-bg);color:#0550ae;border:1px solid var(--blue-border);border-radius:2em;padding:1px 8px;font-size:11px;font-weight:500;margin-left:4px}

.page{max-width:980px;margin:0 auto;padding:24px 16px 80px;display:grid;grid-template-columns:296px 1fr;gap:24px;align-items:start}

.sidebar{display:flex;flex-direction:column;gap:0}
.avatar-wrap{margin-bottom:16px}
.avatar{width:260px;height:260px;border-radius:50%;border:1px solid var(--border);background:#e8f0fe;display:flex;align-items:center;justify-content:center;font-family:var(--sans);font-size:72px;font-weight:600;color:#1967d2;letter-spacing:-2px;overflow:hidden}
.name{font-size:20px;font-weight:600;color:var(--text);line-height:1.25;margin-bottom:4px}
.handle{font-size:18px;font-weight:300;color:var(--text2);margin-bottom:12px}
.bio{font-size:13.5px;color:var(--text);line-height:1.55;margin-bottom:16px}
.follow-btn{width:100%;padding:5px 12px;background:var(--surface);border:1px solid var(--border);border-radius:6px;font-size:13px;font-weight:500;color:var(--text);cursor:pointer;font-family:var(--sans);transition:background .12s}
.follow-btn:hover{background:var(--surface2)}
.sidebar-divider{border:none;border-top:1px solid var(--border-light);margin:16px 0}
.sidebar-meta{display:flex;flex-direction:column;gap:8px}
.meta-row{display:flex;align-items:center;gap:8px;font-size:13px;color:var(--text2)}
.meta-row i{font-size:16px;color:var(--text3);flex-shrink:0;width:16px;text-align:center}
.meta-row a{color:var(--blue);text-decoration:none}
.meta-row a:hover{text-decoration:underline}
.meta-row .meta-strong{color:var(--text);font-weight:500}

.main{min-width:0}

.file-header{background:var(--surface);border:1px solid var(--border);border-radius:6px 6px 0 0;padding:10px 16px;display:flex;align-items:center;justify-content:space-between}
.file-name-row{display:flex;align-items:center;gap:8px;font-size:13px;color:var(--text2)}
.file-name-row i{font-size:15px;color:var(--text3)}
.file-name-row strong{color:var(--text);font-weight:500}
.file-actions{display:flex;gap:6px}
.file-btn{background:var(--bg);border:1px solid var(--border);border-radius:6px;padding:4px 10px;font-size:12px;font-weight:500;color:var(--text2);cursor:pointer;font-family:var(--sans);display:flex;align-items:center;gap:4px;transition:background .12s}
.file-btn:hover{background:var(--surface);color:var(--text)}
.file-btn i{font-size:14px}

.readme-body{background:var(--bg);border:1px solid var(--border);border-top:none;border-radius:0 0 6px 6px;padding:36px 40px}

.hero{display:grid;grid-template-columns:1fr auto;gap:24px;align-items:center;padding-bottom:32px;border-bottom:1px solid var(--border-light);margin-bottom:32px}
.hero-left{}
.status-pill{display:inline-flex;align-items:center;gap:6px;background:var(--green-bg);border:1px solid #aceebb;border-radius:2em;padding:3px 10px;font-size:11.5px;font-weight:500;color:#116329;margin-bottom:14px}
.status-dot{width:7px;height:7px;border-radius:50%;background:#1a7f37}
.hero h1{font-size:26px;font-weight:600;letter-spacing:-0.3px;line-height:1.2;margin-bottom:6px;color:var(--text)}
.hero h1 span{color:var(--blue)}
.hero-role{font-family:var(--mono);font-size:12px;color:var(--text3);letter-spacing:0.04em;margin-bottom:14px}
.hero-desc{font-size:13.5px;color:var(--text2);line-height:1.6;max-width:440px;margin-bottom:20px}
.hero-cta{display:flex;gap:8px;flex-wrap:wrap}
.btn-primary{display:inline-flex;align-items:center;gap:6px;padding:6px 14px;background:var(--blue);color:#fff;border:none;border-radius:6px;font-size:13px;font-weight:500;cursor:pointer;text-decoration:none;font-family:var(--sans);transition:opacity .12s}
.btn-primary:hover{opacity:.88}
.btn-outline{display:inline-flex;align-items:center;gap:6px;padding:5px 13px;background:var(--bg);color:var(--text);border:1px solid var(--border);border-radius:6px;font-size:13px;font-weight:500;cursor:pointer;text-decoration:none;font-family:var(--sans);transition:background .12s}
.btn-outline:hover{background:var(--surface)}
.btn-primary i,.btn-outline i{font-size:15px}
.hero-stats{display:flex;flex-direction:column;gap:8px;align-items:flex-end}
.stat-block{text-align:right}
.stat-num{font-size:22px;font-weight:600;color:var(--text);line-height:1.1;display:block}
.stat-num.accent{color:var(--blue)}
.stat-lbl{font-size:11px;color:var(--text3);text-transform:uppercase;letter-spacing:.05em;font-family:var(--mono)}

.section{margin-bottom:32px}
.section-title{font-size:12px;font-weight:600;text-transform:uppercase;letter-spacing:.06em;color:var(--text3);font-family:var(--mono);margin-bottom:14px;display:flex;align-items:center;gap:8px}
.section-title::after{content:'';flex:1;height:1px;background:var(--border-light)}

.cards-2{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.cards-4{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
.card{background:var(--surface);border:1px solid var(--border-light);border-radius:8px;padding:14px 16px}
.card:hover{border-color:var(--border)}
.card-icon{width:30px;height:30px;border-radius:6px;display:flex;align-items:center;justify-content:center;margin-bottom:10px}
.card-icon i{font-size:17px}
.card-icon.blue{background:var(--blue-bg);color:#0550ae}
.card-icon.green{background:var(--green-bg);color:#116329}
.card-icon.purple{background:var(--purple-bg);color:#6e40c9}
.card-icon.orange{background:var(--orange-bg);color:#953800}
.card-title{font-size:13px;font-weight:600;color:var(--text);margin-bottom:3px}
.card-desc{font-size:12px;color:var(--text2);line-height:1.5}

.stat-card{background:var(--surface);border:1px solid var(--border-light);border-radius:8px;padding:16px;text-align:center}
.stat-card:hover{border-color:var(--border)}
.sc-val{font-size:22px;font-weight:600;display:block;margin-bottom:3px;color:var(--text)}
.sc-val.blue{color:var(--blue)}
.sc-val.green{color:var(--green)}
.sc-val.purple{color:var(--purple)}
.sc-lbl{font-size:11px;color:var(--text3);text-transform:uppercase;letter-spacing:.05em;font-family:var(--mono)}

.stack-group{margin-bottom:16px}
.sg-label{font-size:11px;color:var(--text3);font-family:var(--mono);text-transform:uppercase;letter-spacing:.06em;margin-bottom:8px}
.tags{display:flex;flex-wrap:wrap;gap:6px}
.tag{display:inline-flex;align-items:center;gap:5px;padding:3px 9px;border-radius:2em;font-size:12px;font-family:var(--mono);font-weight:500;border:1px solid}
.tag i{font-size:12px}
.tag.blue{background:var(--blue-bg);border-color:var(--blue-border);color:#0550ae}
.tag.green{background:var(--green-bg);border-color:#aceebb;color:#116329}
.tag.purple{background:var(--purple-bg);border-color:#d8b9ff;color:#6e40c9}
.tag.orange{background:var(--orange-bg);border-color:#ffc799;color:#953800}
.tag.gray{background:var(--surface);border-color:var(--border);color:var(--text2)}
.tag.teal{background:#e6fffa;border-color:#b2f5ea;color:#065666}

.exp-card{border:1px solid var(--border-light);border-radius:8px;padding:18px 20px;position:relative;overflow:hidden;margin-bottom:10px}
.exp-card:hover{border-color:var(--border)}
.exp-accent{position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--blue)}
.exp-head{display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:4px}
.exp-role{font-size:14px;font-weight:600;color:var(--text)}
.exp-current{display:inline-flex;align-items:center;gap:5px;background:var(--green-bg);border:1px solid #aceebb;border-radius:2em;padding:2px 8px;font-size:11px;font-weight:500;color:#116329}
.exp-current i{font-size:11px}
.exp-co{font-size:13px;color:var(--blue);font-weight:500;margin-bottom:3px}
.exp-period{font-family:var(--mono);font-size:11px;color:var(--text3);margin-bottom:14px;display:flex;align-items:center;gap:5px}
.exp-period i{font-size:12px}
.exp-list{list-style:none;display:flex;flex-direction:column;gap:7px}
.exp-list li{font-size:13px;color:var(--text2);padding-left:16px;position:relative;line-height:1.55}
.exp-list li::before{content:'›';position:absolute;left:0;color:var(--blue);font-weight:600}
.exp-list li strong{color:var(--text);font-weight:500}

.prog-wrap{margin-bottom:12px}
.prog-head{display:flex;justify-content:space-between;font-size:12px;margin-bottom:5px}
.prog-head .lang{color:var(--text2);font-weight:500;display:flex;align-items:center;gap:6px}
.prog-head .pct{color:var(--text3);font-family:var(--mono)}
.lang-dot{width:10px;height:10px;border-radius:50%;flex-shrink:0}
.prog-bar{height:5px;background:var(--surface2);border-radius:3px;overflow:hidden}
.prog-fill{height:100%;border-radius:3px}

.graph-wrap{background:var(--surface);border:1px solid var(--border-light);border-radius:8px;padding:16px 20px;overflow-x:auto}

.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.contact-item{display:flex;align-items:center;gap:12px;padding:12px 14px;background:var(--surface);border:1px solid var(--border-light);border-radius:8px;text-decoration:none;transition:border-color .12s}
.contact-item:hover{border-color:var(--border)}
.contact-icon-wrap{width:32px;height:32px;border-radius:6px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.contact-icon-wrap i{font-size:17px}
.ci-blue{background:var(--blue-bg);color:#0550ae}
.ci-red{background:#fff0ee;color:#c4432b}
.ci-green{background:var(--green-bg);color:#116329}
.ci-gray{background:var(--surface2);color:var(--text2)}
.contact-lbl{font-size:11px;color:var(--text3);font-family:var(--mono);text-transform:uppercase;letter-spacing:.05em}
.contact-val{font-size:12.5px;color:var(--text);font-weight:500}

.footer{border-top:1px solid var(--border-light);padding-top:24px;text-align:center}
.footer-quote{font-size:13px;color:var(--text2);font-style:italic;margin-bottom:8px}
.footer-meta{font-family:var(--mono);font-size:11px;color:var(--text3)}
</style>
</head>
<body>

<nav class="gh-nav">
  <div class="gh-nav-logo">
    <svg viewBox="0 0 98 96" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M48.854 0C21.839 0 0 22 0 49.217c0 21.756 13.993 40.172 33.405 46.69 2.427.49 3.316-1.059 3.316-2.362 0-1.141-.08-5.052-.08-9.127-13.59 2.934-16.42-5.867-16.42-5.867-2.184-5.704-5.42-7.17-5.42-7.17-4.448-3.015.324-3.015.324-3.015 4.934.326 7.523 5.052 7.523 5.052 4.367 7.496 11.404 5.378 14.235 4.074.404-3.178 1.699-5.378 3.074-6.6-10.839-1.141-22.243-5.378-22.243-24.283 0-5.378 1.94-9.778 5.014-13.2-.485-1.222-2.184-6.275.486-13.038 0 0 4.125-1.304 13.426 5.052a46.97 46.97 0 0 1 12.214-1.63c4.125 0 8.33.571 12.213 1.63 9.302-6.356 13.427-5.052 13.427-5.052 2.67 6.763.97 11.816.485 13.038 3.155 3.422 5.015 7.822 5.015 13.2 0 18.905-11.404 23.06-22.324 24.283 1.78 1.548 3.316 4.481 3.316 9.126 0 6.6-.08 11.897-.08 13.526 0 1.304.89 2.853 3.316 2.364 19.412-6.52 33.405-24.935 33.405-46.691C97.707 22 75.788 0 48.854 0z"/></svg>
  </div>
  <div class="gh-nav-crumb">
    <a href="#">KarthikDamanelloreDev</a>
    <span class="sep">/</span>
    <a href="#"><strong>KarthikDamanelloreDev</strong></a>
    <span class="special-badge">special</span>
  </div>
</nav>

<div class="page">

  <aside class="sidebar">
    <div class="avatar-wrap">
      <div class="avatar">KD</div>
    </div>
    <div class="name">Karthik Damanellore</div>
    <div class="handle">KarthikDamanelloreDev</div>
    <div class="bio">Engineering AI-powered monitoring, vision systems, and enterprise orchestration for high-impact technical platforms.</div>
    <button class="follow-btn">Follow</button>
    <hr class="sidebar-divider">
    <div class="sidebar-meta">
      <div class="meta-row"><i class="ti ti-building" aria-hidden="true"></i><span>Viljetech Labs Pvt Ltd</span></div>
      <div class="meta-row"><i class="ti ti-map-pin" aria-hidden="true"></i><span>Hyderabad, Telangana, IN</span></div>
      <div class="meta-row"><i class="ti ti-world" aria-hidden="true"></i><a href="https://karthik-dev-portfolio.netlify.app" target="_blank">karthik-dev-portfolio.netlify.app</a></div>
      <div class="meta-row"><i class="ti ti-mail" aria-hidden="true"></i><a href="mailto:damanellorekarthik@gmail.com">damanellorekarthik@gmail.com</a></div>
      <div class="meta-row"><i class="ti ti-phone" aria-hidden="true"></i><span>+91 94415 70523</span></div>
    </div>
  </aside>

  <main class="main">

    <div class="file-header">
      <div class="file-name-row">
        <i class="ti ti-file-text" aria-hidden="true"></i>
        <strong>README.md</strong>
      </div>
      <div class="file-actions">
        <button class="file-btn" onclick="copyMarkdown(this)"><i class="ti ti-copy"></i>Copy Markdown</button>
        <button class="file-btn"><i class="ti ti-pencil"></i>Edit</button>
      </div>
    </div>

    <div class="readme-body">

      <div class="hero">
        <div class="hero-left">
          <div class="status-pill"><span class="status-dot"></span>Open to opportunities</div>
          <h1>Hi, I'm <span>Karthik</span><br>Damanellore</h1>
          <div class="hero-role">FULL-STACK · AI SYSTEMS · CLOUD ARCHITECT</div>
          <div class="hero-desc">Building AI-first products — real-time vision pipelines, LLM-powered apps, and enterprise orchestration across AWS, Azure, and GCP.</div>
          <div class="hero-cta">
            <a class="btn-primary" href="https://karthik-dev-portfolio.netlify.app" target="_blank"><i class="ti ti-briefcase"></i>View Portfolio</a>
            <a class="btn-outline" href="mailto:damanellorekarthik@gmail.com"><i class="ti ti-mail"></i>Get in Touch</a>
          </div>
        </div>
        <div class="hero-stats">
          <div class="stat-block"><span class="stat-num accent">3+</span><div class="stat-lbl">Years</div></div>
          <div class="stat-block"><span class="stat-num">8</span><div class="stat-lbl">Projects</div></div>
          <div class="stat-block"><span class="stat-num" style="color:var(--purple)">AI</span><div class="stat-lbl">Focus</div></div>
          <div class="stat-block"><span class="stat-num">3</span><div class="stat-lbl">Clouds</div></div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Currently building</div>
        <div class="cards-2">
          <div class="card">
            <div class="card-icon blue"><i class="ti ti-eye" aria-hidden="true"></i></div>
            <div class="card-title">AI Vision Systems</div>
            <div class="card-desc">Real-time monitoring pipelines with computer vision and anomaly detection</div>
          </div>
          <div class="card">
            <div class="card-icon purple"><i class="ti ti-brain" aria-hidden="true"></i></div>
            <div class="card-title">LLM-Powered Apps</div>
            <div class="card-desc">LangChain workflows, RAG pipelines, and vector search with pgvector and Pinecone</div>
          </div>
          <div class="card">
            <div class="card-icon green"><i class="ti ti-hierarchy" aria-hidden="true"></i></div>
            <div class="card-title">Enterprise Orchestration</div>
            <div class="card-desc">Microservices, API gateways, and event-driven architectures at scale</div>
          </div>
          <div class="card">
            <div class="card-icon orange"><i class="ti ti-device-mobile" aria-hidden="true"></i></div>
            <div class="card-title">Cross-Platform Mobile</div>
            <div class="card-desc">React Native and Expo apps with offline-first design and native performance</div>
          </div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Tech stack</div>

        <div class="stack-group">
          <div class="sg-label">Frontend & UI</div>
          <div class="tags">
            <span class="tag blue"><i class="ti ti-brand-react"></i>React</span>
            <span class="tag blue"><i class="ti ti-brand-nextjs"></i>Next.js</span>
            <span class="tag blue"><i class="ti ti-brand-typescript"></i>TypeScript</span>
            <span class="tag teal"><i class="ti ti-wind"></i>Tailwind CSS</span>
            <span class="tag purple"><i class="ti ti-stack"></i>Redux</span>
            <span class="tag green"><i class="ti ti-brand-react-native"></i>React Native</span>
            <span class="tag green"><i class="ti ti-device-mobile"></i>Expo</span>
          </div>
        </div>

        <div class="stack-group">
          <div class="sg-label">Backend & APIs</div>
          <div class="tags">
            <span class="tag green"><i class="ti ti-brand-nodejs"></i>Node.js</span>
            <span class="tag orange"><i class="ti ti-bolt"></i>FastAPI</span>
            <span class="tag orange"><i class="ti ti-brand-python"></i>Python</span>
            <span class="tag gray"><i class="ti ti-server"></i>Express.js</span>
          </div>
        </div>

        <div class="stack-group">
          <div class="sg-label">Data & AI</div>
          <div class="tags">
            <span class="tag blue"><i class="ti ti-database"></i>PostgreSQL</span>
            <span class="tag green"><i class="ti ti-leaf"></i>MongoDB</span>
            <span class="tag orange"><i class="ti ti-brand-redis"></i>Redis</span>
            <span class="tag purple"><i class="ti ti-link"></i>LangChain</span>
            <span class="tag teal"><i class="ti ti-vector"></i>Vector DB</span>
            <span class="tag purple"><i class="ti ti-cpu"></i>GenAI</span>
            <span class="tag gray"><i class="ti ti-adjustments"></i>LLM Ops</span>
          </div>
        </div>

        <div class="stack-group">
          <div class="sg-label">Cloud & DevOps</div>
          <div class="tags">
            <span class="tag orange"><i class="ti ti-brand-aws"></i>AWS</span>
            <span class="tag blue"><i class="ti ti-brand-azure"></i>Azure</span>
            <span class="tag blue"><i class="ti ti-cloud"></i>GCP</span>
            <span class="tag teal"><i class="ti ti-brand-docker"></i>Docker</span>
          </div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Experience</div>
        <div class="exp-card">
          <div class="exp-accent"></div>
          <div class="exp-head">
            <div class="exp-role">Front-End Developer — React JS</div>
            <span class="exp-current"><i class="ti ti-circle-filled" style="font-size:8px"></i>Current</span>
          </div>
          <div class="exp-co">Viljetech Labs Pvt Ltd · Hyderabad</div>
          <div class="exp-period"><i class="ti ti-calendar" aria-hidden="true"></i>March 2022 – Present · 3+ years</div>
          <ul class="exp-list">
            <li>Developed scalable web apps with <strong>ReactJS + NodeJS</strong>; responsive UI with HTML5/CSS3/Bootstrap — boosted UX by <strong>20%</strong></li>
            <li>React hooks for state management improved maintainability by <strong>15%</strong>; TypeScript adoption reduced bugs by <strong>25%</strong></li>
            <li>Built reusable component library cutting new feature dev time by <strong>30%</strong>; leveraged <strong>NextJS</strong> and <strong>Redux</strong> for user-facing features</li>
            <li>Mobile-first design with <strong>React Native + Expo</strong>; customized Material-UI for brand consistency across platforms</li>
            <li>NodeJS + ExpressJS + MongoDB for backend; collaborated on Figma designs, lifting user satisfaction by <strong>10%</strong></li>
          </ul>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Language breakdown</div>
        <div id="prog-section"></div>
      </div>

      <div class="section">
        <div class="section-title">Contribution activity</div>
        <div class="graph-wrap" id="graph-wrap"></div>
      </div>

      <div class="section">
        <div class="section-title">Currently exploring</div>
        <div class="tags">
          <span class="tag purple"><i class="ti ti-git-branch"></i>RAG pipelines</span>
          <span class="tag blue"><i class="ti ti-cpu"></i>Real-time AI inference</span>
          <span class="tag orange"><i class="ti ti-cloud-computing"></i>Multi-cloud deployments</span>
          <span class="tag teal"><i class="ti ti-search"></i>Semantic search at scale</span>
          <span class="tag green"><i class="ti ti-layout-grid"></i>Micro-frontend architecture</span>
          <span class="tag gray"><i class="ti ti-topology-star"></i>Edge computing</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Get in touch</div>
        <div class="contact-grid">
          <a class="contact-item" href="mailto:damanellorekarthik@gmail.com">
            <div class="contact-icon-wrap ci-red"><i class="ti ti-mail" aria-hidden="true"></i></div>
            <div><div class="contact-lbl">Email</div><div class="contact-val">damanellorekarthik@gmail.com</div></div>
          </a>
          <a class="contact-item" href="https://karthik-dev-portfolio.netlify.app" target="_blank">
            <div class="contact-icon-wrap ci-blue"><i class="ti ti-world" aria-hidden="true"></i></div>
            <div><div class="contact-lbl">Portfolio</div><div class="contact-val">karthik-dev-portfolio.netlify.app</div></div>
          </a>
          <a class="contact-item" href="tel:+919441570523">
            <div class="contact-icon-wrap ci-green"><i class="ti ti-phone" aria-hidden="true"></i></div>
            <div><div class="contact-lbl">Phone</div><div class="contact-val">+91 94415 70523</div></div>
          </a>
          <a class="contact-item" href="https://linkedin.com" target="_blank">
            <div class="contact-icon-wrap ci-blue"><i class="ti ti-brand-linkedin" aria-hidden="true"></i></div>
            <div><div class="contact-lbl">LinkedIn</div><div class="contact-val">Connect on LinkedIn</div></div>
          </a>
        </div>
      </div>

      <div class="footer">
        <div class="footer-quote">"Build systems that think, scale, and matter."</div>
        <div class="footer-meta">Karthik Damanellore · Hyderabad, India · Full-Stack + AI Systems</div>
      </div>

    </div>
  </main>
</div>

<script>
(function(){
  const langs=[
    {name:'TypeScript / JavaScript',pct:45,color:'#3178c6',dot:'#3178c6'},
    {name:'Python',pct:28,color:'#f7c948',dot:'#f7c948'},
    {name:'CSS / Tailwind',pct:14,color:'#06b6d4',dot:'#06b6d4'},
    {name:'Shell / YAML / Docker',pct:9,color:'#1a7f37',dot:'#1a7f37'},
    {name:'SQL',pct:4,color:'#8250df',dot:'#8250df'},
  ];
  const ps=document.getElementById('prog-section');
  ps.innerHTML=langs.map(l=>`
    <div class="prog-wrap">
      <div class="prog-head">
        <span class="lang"><span class="lang-dot" style="background:${l.dot}"></span>${l.name}</span>
        <span class="pct">${l.pct}%</span>
      </div>
      <div class="prog-bar"><div class="prog-fill" style="width:${l.pct}%;background:${l.color}"></div></div>
    </div>`).join('');
})();

(function(){
  const wrap=document.getElementById('graph-wrap');
  const months=['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'];
  const today=new Date(2026,4,27);
  const start=new Date(2025,4,25);
  let days=[];
  let d=new Date(start);
  while(d<=today){days.push(new Date(d));d.setDate(d.getDate()+1);}
  const pad=days[0].getDay();
  for(let i=0;i<pad;i++)days.unshift(null);
  while(days.length%7!==0)days.push(null);
  const weeks=[];
  for(let i=0;i<days.length;i+=7)weeks.push(days.slice(i,i+7));

  function lvl(d){
    if(!d)return 0;
    const dw=d.getDay();
    if(dw===0||dw===6)return Math.random()<0.28?Math.floor(Math.random()*2)+1:0;
    const r=Math.random();
    if(r<0.08)return 0;if(r<0.32)return 1;if(r<0.62)return 2;if(r<0.86)return 3;return 4;
  }
  const colors=['#ebedf0','#9be9a8','#40c463','#30a14e','#216e39'];

  let monthsHtml='<div style="width:24px;flex-shrink:0"></div>';
  let lastM=-1;
  weeks.forEach(w=>{
    const f=w.find(x=>x!==null);
    if(f&&f.getMonth()!==lastM){
      lastM=f.getMonth();
      monthsHtml+=`<div style="font-family:var(--mono);font-size:10px;color:var(--text3);width:13px;flex-shrink:0;white-space:nowrap">${months[lastM]}</div>`;
    } else {
      monthsHtml+=`<div style="width:13px;flex-shrink:0"></div>`;
    }
  });

  const dayLabels=['','Mon','','Wed','','Fri',''];
  const dayLabelHtml=dayLabels.map(l=>`<div style="font-family:var(--mono);font-size:9px;color:var(--text3);height:13px;line-height:13px;width:24px;text-align:right;padding-right:4px">${l}</div>`).join('');

  const weeksHtml=weeks.map(w=>{
    const cells=w.map(day=>{
      if(!day)return`<div style="width:11px;height:11px;visibility:hidden"></div>`;
      const l=lvl(day);
      return`<div style="width:11px;height:11px;border-radius:2px;background:${colors[l]}" title="${day.toDateString()}"></div>`;
    }).join('');
    return`<div style="display:flex;flex-direction:column;gap:2px">${cells}</div>`;
  }).join('');

  wrap.innerHTML=`
    <div style="display:flex;gap:0;margin-bottom:6px">${monthsHtml}</div>
    <div style="display:flex;gap:4px;align-items:flex-start">
      <div style="display:flex;flex-direction:column;gap:2px;padding-top:2px">${dayLabelHtml}</div>
      <div style="display:flex;gap:2px;flex-wrap:nowrap;overflow-x:auto">${weeksHtml}</div>
    </div>
    <div style="display:flex;align-items:center;gap:4px;margin-top:10px;justify-content:flex-end">
      <span style="font-family:var(--mono);font-size:10px;color:var(--text3)">Less</span>
      ${colors.map(c=>`<div style="width:11px;height:11px;border-radius:2px;background:${c};border:1px solid rgba(27,31,36,.06)"></div>`).join('')}
      <span style="font-family:var(--mono);font-size:10px;color:var(--text3)">More</span>
    </div>`;
})();

function copyMarkdown(btn){
  const md=`# Hi, I'm Karthik Damanellore

**Full-Stack · AI Systems · Cloud Architect** | Hyderabad, India

> Building AI-first products — real-time vision pipelines, LLM-powered apps, and enterprise orchestration across AWS, Azure, and GCP.

---

## Currently Building

- **AI Vision Systems** — Real-time monitoring pipelines with CV & anomaly detection
- **LLM-Powered Apps** — LangChain, RAG pipelines, vector search (pgvector / Pinecone)
- **Enterprise Orchestration** — Microservices, API gateways, event-driven at scale
- **Cross-Platform Mobile** — React Native + Expo with offline-first design

---

## Tech Stack

**Frontend** · \`React\` \`Next.js\` \`TypeScript\` \`Tailwind CSS\` \`Redux\` \`React Native\` \`Expo\`

**Backend** · \`Node.js\` \`FastAPI\` \`Python\` \`Express.js\`

**Data & AI** · \`PostgreSQL\` \`MongoDB\` \`Redis\` \`LangChain\` \`Vector DB\` \`GenAI\` \`LLM Ops\`

**Cloud & DevOps** · \`AWS\` \`Azure\` \`GCP\` \`Docker\`

---

## Experience

### Front-End Developer (React JS) · Viljetech Labs Pvt Ltd, Hyderabad
*March 2022 – Present · 3+ years*

- ReactJS + NodeJS web apps with responsive HTML5/CSS3/Bootstrap — **+20% UX improvement**
- TypeScript reduced bugs by **25%**; React hooks improved maintainability by **15%**
- Reusable component library cut dev time by **30%**; used NextJS + Redux for features
- React Native + Expo for mobile; Figma-to-code implementations — **+10% user satisfaction**

---

## Get in Touch

- Mail: damanellorekarthik@gmail.com
- Phone: +91 94415 70523
- Portfolio: https://karthik-dev-portfolio.netlify.app

---

*"Build systems that think, scale, and matter."*`;
  navigator.clipboard.writeText(md).then(()=>{
    btn.innerHTML='<i class="ti ti-check"></i>Copied!';
    btn.style.color='#1a7f37';
    setTimeout(()=>{btn.innerHTML='<i class="ti ti-copy"></i>Copy Markdown';btn.style.color='';},2200);
  });
}
</script>
</body>
</html>
