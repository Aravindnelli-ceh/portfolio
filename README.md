<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Nelli Aravind – Portfolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fira+Sans:wght@400;500;600&family=Fira+Sans+Condensed:wght@600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#eef3f6;--surface:#fff;--ink:#12242e;--muted:#4c6270;--line:#c5d3da;--signal:#0b7a75;--warn:#b86a12;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0f1c24;--surface:#16262f;--ink:#e6eef2;--muted:#9db3bf;--line:#2c4350;--signal:#3cc4bb;--warn:#e8a04c}}
:root[data-theme="dark"]{--bg:#0f1c24;--surface:#16262f;--ink:#e6eef2;--muted:#9db3bf;--line:#2c4350;--signal:#3cc4bb;--warn:#e8a04c}
*,*::before,*::after{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--ink);font:400 17px/1.6 "Fira Sans",system-ui,-apple-system,"Segoe UI",Arial,sans-serif}
.wrap{max-width:820px;margin:0 auto;padding:0 22px}
h1,h2,h3{font-family:"Fira Sans Condensed","Arial Narrow",Arial,sans-serif;line-height:1.1;margin:0}
h1{font-size:clamp(2.6rem,9vw,4.4rem);letter-spacing:-.01em}
h2{font-size:1.7rem;margin-bottom:18px}
h3{font-size:1.2rem;font-weight:600}
a{color:var(--signal)}
a:focus-visible,button:focus-visible{outline:3px solid var(--signal);outline-offset:3px}
header{padding:56px 0 40px}
.role{font-size:1.2rem;color:var(--muted);margin:14px 0 0;max-width:34ch}
.chain-label{margin:40px 0 12px;font-weight:500}
.chain{list-style:none;margin:0;padding:0;display:flex;flex-wrap:wrap;gap:8px 0}
.chain li{position:relative;padding:8px 14px;border:2px solid var(--line);background:var(--surface);font-weight:500;font-size:.95rem;margin-right:22px;animation:hit .5s ease forwards;animation-delay:calc(var(--i)*.35s + .3s)}
.chain li::after{content:"";position:absolute;left:100%;top:50%;width:22px;border-top:2px solid var(--line)}
.chain li:last-child{margin-right:0;border-color:var(--warn);color:var(--warn)}
.chain li:last-child::after{display:none}
@keyframes hit{to{border-color:var(--signal);color:var(--signal)}}
.chain li:last-child{animation-name:hitlast}
@keyframes hitlast{to{background:var(--warn);color:var(--surface)}}
@media (prefers-reduced-motion:reduce){.chain li{animation:none}}
.chain-note{color:var(--muted);font-size:.95rem;margin:12px 0 0}
section{padding:36px 0;border-top:2px solid var(--line)}
p{margin:0 0 14px;max-width:66ch}
.work{border-left:4px solid var(--signal);padding:2px 0 2px 18px;margin-bottom:26px}
.work p{margin:6px 0 0}
.tag{color:var(--muted);font-size:.95rem}
dl{display:grid;grid-template-columns:minmax(0,11rem) 1fr;gap:12px 20px;margin:0}
dt{font-weight:600}dd{margin:0}
@media (max-width:560px){dl{grid-template-columns:1fr;gap:2px}dd{margin-bottom:14px}}
.timeline{list-style:none;margin:0;padding:0}
.timeline li{display:grid;grid-template-columns:minmax(0,9rem) 1fr;gap:6px 20px;padding-bottom:20px}
.timeline .when{color:var(--muted);font-size:.95rem}
@media (max-width:560px){.timeline li{grid-template-columns:1fr}}
.contact a{display:inline-block;margin:0 18px 8px 0;font-weight:500}
footer{padding:28px 0 48px;color:var(--muted);font-size:.9rem;border-top:2px solid var(--line)}
</style>
</head>
<body>
<div class="wrap">
<header>
  <h1>Nelli Aravind</h1>
  <p class="role">Network support engineer for fixed broadband, IPTV and OTT services. Hyderabad, India.</p>
  <p class="chain-label">How I work a fiber or IPTV ticket</p>
  <ol class="chain" aria-label="First-level checks before escalation">
    <li style="--i:0">Ticket logged</li>
    <li style="--i:1">IP address</li>
    <li style="--i:2">DHCP</li>
    <li style="--i:3">DNS</li>
    <li style="--i:4">PPPoE</li>
    <li style="--i:5">RADIUS</li>
    <li style="--i:6">Fix or escalate</li>
  </ol>
  <p class="chain-note">I run these first-level checks before handing a ticket to the specialist network teams, and I keep the ticket updated within SLA.</p>
</header>

<section>
  <h2>About</h2>
  <p>I have 2+ years of L1/L2 support experience across fiber broadband (FTTH), IPTV and OTT platforms. I currently lead technical support as the SPOC on a large ISP/FTTH project, T-Fiber Grid, where I resolve tickets within SLA, work with internal teams and partners, and report on customer status every day, week and month.</p>
  <p>I am CEH certified, comfortable on calls, chat and email with customers, and open to rotational and night shifts. I can join immediately.</p>
</section>

<section>
  <h2>Selected work</h2>
  <div class="work">
    <h3>Support SPOC for T-Fiber Grid</h3>
    <div class="tag">Lytus Sri Sai Networks, Jan 2025 to present</div>
    <p>Single point of contact for IPTV and fiber broadband/DSL tickets. I do the first-level checks, escalate to specialist teams when needed, log every update in the CRM, and track each ticket to closure within SLA.</p>
  </div>
  <div class="work">
    <h3>IPTV and OTT partner operations</h3>
    <div class="tag">Lytus Sri Sai Networks</div>
    <p>Channel and logo additions, partner creation and mapping, and API/JSON verification for partner platforms including OTTplay, Watcho Partner and Playbox, covering DRM, DRM middleware and bundler platforms.</p>
  </div>
  <div class="work">
    <h3>Servers, IP management and CDN</h3>
    <div class="tag">Lytus Sri Sai Networks</div>
    <p>Installing servers, assigning IP addresses, creating IP pools and configuring CDN. I work over PuTTY, Telnet and Winbox, scan with Nmap, and deploy from GitHub repositories on Linux, Ubuntu and Kali Linux.</p>
  </div>
  <div class="work">
    <h3>Reporting and client meetings</h3>
    <div class="tag">Lytus Sri Sai Networks</div>
    <p>Daily, weekly and monthly reports on active and inactive customers, plus dashboards for monitoring. I join client meetings and product demonstrations, capture requirements as the business analyst and explain solutions in plain language.</p>
  </div>
  <div class="work">
    <h3>Application and production support</h3>
    <div class="tag">Bissi Yaazi Technology (Payzo), Dec 2023 to May 2024</div>
    <p>Diagnosed playback failures, login/OTP failures and session issues over chat, email and calls, using DNS, Ping, NSLookup, Traceroute and API/JSON analysis.</p>
  </div>
</section>

<section>
  <h2>Skills</h2>
  <dl>
    <dt>Service assurance</dt><dd>L1 support, L1/L2 troubleshooting, trouble ticket management, SLA tracking, escalation handling, remote support</dd>
    <dt>Networking</dt><dd>DHCP, DNS, PPPoE, RADIUS, VLANs, GPON/EPON, FTTH, assigning IP addresses, creating IP pools, Winbox, PuTTY and Telnet, Nmap, Ping, NSLookup, Traceroute</dd>
    <dt>Servers and systems</dt><dd>Server installation, Linux, Ubuntu, Kali Linux, Windows, macOS, GitHub for repository deployment</dd>
    <dt>IPTV and OTT</dt><dd>Bundler platforms (OTTplay, Playbox, Watcho Partner), DRM Corpus, DRM middleware Corpus, CDN configuration, API integration support, JSON verification</dd>
    <dt>CRM tools</dt><dd>OneRadius, Corpus, Total View CRM, Sugar CRM, MQ CRM, H8 CRM</dd>
    <dt>Dashboards</dt><dd>Working with operational dashboards for monitoring and reporting</dd>
  </dl>
</section>

<section>
  <h2>Experience</h2>
  <ol class="timeline">
    <li><span class="when">Jan 2025 to present</span><span><strong>Engineer, Networking</strong><br>Lytus Sri Sai Networks Pvt Ltd</span></li>
    <li><span class="when">Dec 2023 to May 2024</span><span><strong>Application Support Engineer I</strong><br>Bissi Yaazi Technology (Payzo)</span></li>
    <li><span class="when">About 21 months</span><span><strong>Intern</strong><br>Lytus Technologies</span></li>
  </ol>
</section>

<section>
  <h2>Education and certification</h2>
  <p><strong>B.Tech, Mechanical Engineering</strong>, JNTU College of Engineering, Kakinada, 2023<br>
  <strong>EC-Council Certified Ethical Hacker (CEH)</strong></p>
</section>

<section class="contact">
  <h2>Contact</h2>
  <a href="mailto:naiduaravind169@gmail.com">naiduaravind169@gmail.com</a>
  <a href="tel:+916309579202">+91 6309579202</a>
  <a href="https://github.com/aravindnelli-ceh" rel="noopener">GitHub: aravindnelli-ceh</a>
</section>

<footer>Nelli Aravind, Hyderabad, India</footer>
</div>
</body>
</html>
