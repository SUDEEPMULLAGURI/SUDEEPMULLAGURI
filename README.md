<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:var(--font-sans)}
.wrap{max-width:680px;padding:2rem 0}
.hero{padding:2rem 1.5rem;border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);background:var(--color-background-primary);margin-bottom:1rem}
.avatar-row{display:flex;align-items:center;gap:1rem;margin-bottom:1.25rem}
.avatar{width:56px;height:56px;border-radius:50%;background:#1D9E75;display:flex;align-items:center;justify-content:center;font-size:20px;font-weight:500;color:#E1F5EE;flex-shrink:0}
.name{font-size:22px;font-weight:500;color:var(--color-text-primary);line-height:1.2}
.handle{font-size:13px;color:var(--color-text-secondary);margin-top:2px}
.tagline{font-size:15px;color:var(--color-text-secondary);line-height:1.6;border-left:2px solid #1D9E75;padding-left:12px;margin-bottom:1.25rem}
.pill-row{display:flex;flex-wrap:wrap;gap:6px}
.pill{font-size:12px;padding:4px 10px;border-radius:20px;background:#E1F5EE;color:#0F6E56;border:0.5px solid #9FE1CB}
.pill.blue{background:#E6F1FB;color:#185FA5;border-color:#B5D4F4}
.pill.amber{background:#FAEEDA;color:#854F0B;border-color:#FAC775}
.grid-2{display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-bottom:1rem}
.card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1.25rem}
.card-label{font-size:11px;font-weight:500;letter-spacing:0.06em;text-transform:uppercase;color:var(--color-text-tertiary);margin-bottom:0.75rem}
.card h3{font-size:15px;font-weight:500;color:var(--color-text-primary);margin-bottom:0.5rem}
.item-row{display:flex;align-items:flex-start;gap:8px;margin-bottom:6px}
.dot{width:6px;height:6px;border-radius:50%;background:#1D9E75;margin-top:6px;flex-shrink:0}
.dot.blue{background:#378ADD}
.item-text{font-size:13px;color:var(--color-text-secondary);line-height:1.5}
.item-text strong{font-weight:500;color:var(--color-text-primary)}
.full-card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1.25rem;margin-bottom:1rem}
.stack-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(72px,1fr));gap:8px;margin-top:0.75rem}
.stack-item{background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:8px 6px;text-align:center;font-size:12px;color:var(--color-text-secondary)}
.stack-item span{display:block;font-size:18px;margin-bottom:3px}
.philo-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:0.75rem}
.philo-item{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:10px 12px;font-size:13px;color:var(--color-text-secondary);line-height:1.4}
.philo-item strong{display:block;font-weight:500;color:var(--color-text-primary);margin-bottom:2px}
.connect-row{display:flex;gap:8px;margin-top:0.75rem;flex-wrap:wrap}
.connect-btn{font-size:13px;padding:7px 16px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);background:transparent;color:var(--color-text-primary);cursor:pointer;display:flex;align-items:center;gap:6px}
.connect-btn:hover{background:var(--color-background-secondary)}
.stat-row{display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px;margin-top:0.75rem}
.stat-box{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:10px;text-align:center}
.stat-num{font-size:20px;font-weight:500;color:var(--color-text-primary)}
.stat-lbl{font-size:11px;color:var(--color-text-tertiary);margin-top:2px}
.divider{height:0.5px;background:var(--color-border-tertiary);margin:1rem 0}
.section-tag{display:inline-block;font-size:11px;font-weight:500;letter-spacing:0.06em;text-transform:uppercase;color:#0F6E56;background:#E1F5EE;border:0.5px solid #9FE1CB;padding:3px 8px;border-radius:4px;margin-bottom:0.75rem}
</style>

<div class="wrap">

<div class="hero">
  <div class="avatar-row">
    <div class="avatar">SM</div>
    <div>
      <div class="name">Sudeep Mullaguri</div>
      <div class="handle">@SUDEEPMULLAGURI</div>
    </div>
  </div>
  <p class="tagline">Building technology that solves real-world problems in agriculture and automation — farmers don't need more data, they need decisions.</p>
  <div class="pill-row">
    <span class="pill">Founder</span>
    <span class="pill">Embedded Engineer</span>
    <span class="pill blue">ESP32 / C / C++</span>
    <span class="pill blue">Drone Firmware</span>
    <span class="pill amber">Smart Irrigation</span>
  </div>
</div>

<div class="grid-2">
  <div class="card">
    <div class="card-label">Startup</div>
    <h3>Smart Irrigation System</h3>
    <div class="item-row"><div class="dot"></div><div class="item-text"><strong>Problem</strong> — irrigation is still manual and inefficient</div></div>
    <div class="item-row"><div class="dot"></div><div class="item-text"><strong>Solution</strong> — firmware-level decision logic with real-time sensing</div></div>
    <div class="item-row"><div class="dot"></div><div class="item-text"><strong>Future</strong> — AI-based recommendations, simple UI for real farmers</div></div>
  </div>

  <div class="card">
    <div class="card-label">Engineering projects</div>
    <div class="item-row"><div class="dot blue"></div><div class="item-text"><strong>Drone Firmware Builder</strong> — Blockly + ESP32</div></div>
    <div class="item-row"><div class="dot blue"></div><div class="item-text"><strong>WiFi RC Receiver</strong> — custom radio system</div></div>
    <div class="item-row"><div class="dot blue"></div><div class="item-text"><strong>EEG Signal Processing</strong> — alpha to theta detection</div></div>
    <div class="item-row"><div class="dot blue"></div><div class="item-text"><strong>Custom Automation</strong> — embedded systems</div></div>
  </div>
</div>

<div class="full-card">
  <div class="card-label">Tech stack</div>
  <div class="stack-grid">
    <div class="stack-item"><span>⚙</span>C / C++</div>
    <div class="stack-item"><span>🐍</span>Python</div>
    <div class="stack-item"><span>📟</span>Arduino</div>
    <div class="stack-item"><span>🔌</span>ESP32</div>
    <div class="stack-item"><span>🐧</span>Linux</div>
    <div class="stack-item"><span>🔀</span>Git</div>
  </div>
</div>

<div class="full-card">
  <div class="card-label">Philosophy</div>
  <div class="philo-grid">
    <div class="philo-item"><strong>Build solutions</strong>not just projects</div>
    <div class="philo-item"><strong>Real users first</strong>not just tech</div>
    <div class="philo-item"><strong>Simplicity wins</strong>over complexity</div>
    <div class="philo-item"><strong>Execution</strong>over ideas</div>
  </div>
</div>

<div class="full-card">
  <div class="card-label">GitHub stats</div>
  <div class="stat-row">
    <div class="stat-box"><div class="stat-num">ESP32</div><div class="stat-lbl">primary MCU</div></div>
    <div class="stat-box"><div class="stat-num">4+</div><div class="stat-lbl">active projects</div></div>
    <div class="stat-box"><div class="stat-num">Agri</div><div class="stat-lbl">focus domain</div></div>
  </div>
  <div class="divider"></div>
  <div style="display:flex;gap:8px;flex-wrap:wrap">
    <a href="https://github.com/SUDEEPMULLAGURI" target="_blank" style="text-decoration:none">
      <button class="connect-btn">GitHub profile ↗</button>
    </a>
    <a href="https://linkedin.com/in/YOUR_LINKEDIN" target="_blank" style="text-decoration:none">
      <button class="connect-btn">LinkedIn ↗</button>
    </a>
  </div>
</div>

</div>
