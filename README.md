
<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Syne:wght@400;700;800&display=swap');
*{margin:0;padding:0;box-sizing:border-box}
body{background:#0d1117;color:#e6edf3;font-family:'Syne',sans-serif}
.wrap{max-width:820px;margin:0 auto;padding:1.5rem 1rem}
.hero{display:flex;gap:1.5rem;align-items:flex-start;margin-bottom:2rem;flex-wrap:wrap}
.avatar-ring{width:90px;height:90px;border-radius:50%;background:linear-gradient(135deg,#00d2ff,#7b2ff7,#ff6b6b);padding:3px;flex-shrink:0}
.avatar-inner{width:100%;height:100%;border-radius:50%;background:#161b22;display:flex;align-items:center;justify-content:center;font-size:28px;font-weight:800;color:#00d2ff;font-family:'JetBrains Mono',monospace}
.hero-text{flex:1;min-width:200px}
.name{font-size:1.7rem;font-weight:800;background:linear-gradient(90deg,#00d2ff,#7b2ff7);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.handle{font-family:'JetBrains Mono',monospace;font-size:0.85rem;color:#7d8590;margin:2px 0 8px}
.bio{font-size:0.88rem;color:#8b949e;line-height:1.6;max-width:460px}
.badges{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
.badge{padding:4px 10px;border-radius:20px;font-size:0.72rem;font-family:'JetBrains Mono',monospace;font-weight:700;letter-spacing:0.04em}
.b1{background:#00d2ff22;color:#00d2ff;border:1px solid #00d2ff44}
.b2{background:#7b2ff722;color:#a78bfa;border:1px solid #7b2ff744}
.b3{background:#ff6b6b22;color:#ff6b6b;border:1px solid #ff6b6b44}
.b4{background:#ffd60022;color:#ffd600;border:1px solid #ffd60044}
.typing-line{font-family:'JetBrains Mono',monospace;font-size:0.9rem;color:#00d2ff;margin:1.2rem 0 1.8rem;display:flex;align-items:center;gap:8px}
.cursor{display:inline-block;width:10px;height:1.1em;background:#00d2ff;animation:blink 1s step-end infinite;vertical-align:middle}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.section-label{font-family:'JetBrains Mono',monospace;font-size:0.75rem;color:#7d8590;letter-spacing:0.1em;text-transform:uppercase;margin-bottom:12px;padding-bottom:6px;border-bottom:1px solid #21262d}
.stats-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px;margin-bottom:2rem}
.stat-card{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:14px 16px;transition:border-color .2s}
.stat-card:hover{border-color:#00d2ff55}
.stat-num{font-size:1.5rem;font-weight:800;font-family:'JetBrains Mono',monospace;color:#e6edf3}
.stat-label{font-size:0.72rem;color:#7d8590;margin-top:2px}
.skills-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:10px;margin-bottom:2rem}
.skill-card{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:14px 16px}
.skill-name{font-size:0.82rem;font-weight:700;margin-bottom:8px;display:flex;justify-content:space-between;align-items:center}
.skill-bar-bg{height:6px;background:#21262d;border-radius:3px;overflow:hidden}
.skill-bar{height:100%;border-radius:3px;transition:width 1.5s ease}
.repos-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:10px;margin-bottom:2rem}
.repo-card{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:14px 16px;transition:all .2s;cursor:pointer}
.repo-card:hover{border-color:#7b2ff7;transform:translateY(-2px)}
.repo-title{font-size:0.88rem;font-weight:700;color:#58a6ff;margin-bottom:6px}
.repo-desc{font-size:0.78rem;color:#7d8590;line-height:1.5;margin-bottom:10px}
.repo-footer{display:flex;gap:12px;font-size:0.72rem;color:#7d8590;font-family:'JetBrains Mono',monospace}
.repo-lang{display:flex;align-items:center;gap:4px}
.lang-dot{width:10px;height:10px;border-radius:50%}
.contact-row{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:1rem}
.contact-btn{display:flex;align-items:center;gap:6px;padding:7px 14px;border-radius:8px;font-size:0.78rem;font-family:'JetBrains Mono',monospace;font-weight:700;border:1px solid;cursor:pointer;text-decoration:none;transition:all .2s}
.c-gh{background:#00d2ff18;color:#00d2ff;border-color:#00d2ff44}
.c-li{background:#0077b518;color:#58a6ff;border-color:#0077b544}
.c-web{background:#ff6b6b18;color:#ff6b6b;border-color:#ff6b6b44}
.c-gh:hover{background:#00d2ff30}.c-li:hover{background:#0077b530}.c-web:hover{background:#ff6b6b30}
.snake-bar{display:flex;gap:3px;margin:8px 0 1.5rem;flex-wrap:wrap}
.dot{width:12px;height:12px;border-radius:2px;display:inline-block}
.d0{background:#161b22}.d1{background:#0e4429}.d2{background:#006d32}.d3{background:#26a641}.d4{background:#39d353}
.footer-quote{font-family:'JetBrains Mono',monospace;font-size:0.78rem;color:#7d8590;text-align:center;padding:1rem 0;border-top:1px solid #21262d;margin-top:.5rem}
</style>
<div class="wrap">
  <div class="hero">
    <div class="avatar-ring"><div class="avatar-inner">SK</div></div>
    <div class="hero-text">
      <div class="name">Siddhant Kumar Patel</div>
      <div class="handle">@SIDDXIAO · Lucknow, IN</div>
      <div class="bio">BCA (DS & AI) Student at BBD University · Building things at the intersection of data, AI, and code · Currently exploring Generative AI</div>
      <div class="badges">
        <span class="badge b1">Python</span>
        <span class="badge b2">Machine Learning</span>
        <span class="badge b3">Data Science</span>
        <span class="badge b4">Gen AI Learner</span>
      </div>
    </div>
  </div>

  <div class="typing-line">
    <span id="typed"></span><span class="cursor"></span>
  </div>

  <div class="section-label">— github stats</div>
  <div class="stats-grid">
    <div class="stat-card"><div class="stat-num">6</div><div class="stat-label">Repositories</div></div>
    <div class="stat-card"><div class="stat-num">4</div><div class="stat-label">Python Projects</div></div>
    <div class="stat-card"><div class="stat-num">∞</div><div class="stat-label">Curiosity Level</div></div>
    <div class="stat-card"><div class="stat-num">2025</div><div class="stat-label">Journey Began</div></div>
  </div>

  <div class="section-label">— skills & tools</div>
  <div class="skills-grid">
    <div class="skill-card">
      <div class="skill-name"><span>Python</span><span style="color:#00d2ff;font-family:'JetBrains Mono',monospace;font-size:0.75rem" id="p1">85%</span></div>
      <div class="skill-bar-bg"><div class="skill-bar" id="b1" style="background:linear-gradient(90deg,#00d2ff,#7b2ff7);width:0"></div></div>
    </div>
    <div class="skill-card">
      <div class="skill-name"><span>Machine Learning</span><span style="color:#a78bfa;font-family:'JetBrains Mono',monospace;font-size:0.75rem">70%</span></div>
      <div class="skill-bar-bg"><div class="skill-bar" id="b2" style="background:linear-gradient(90deg,#7b2ff7,#ff6b6b);width:0"></div></div>
    </div>
    <div class="skill-card">
      <div class="skill-name"><span>Data Analysis</span><span style="color:#ff6b6b;font-family:'JetBrains Mono',monospace;font-size:0.75rem">75%</span></div>
      <div class="skill-bar-bg"><div class="skill-bar" id="b3" style="background:linear-gradient(90deg,#ff6b6b,#ffd600);width:0"></div></div>
    </div>
    <div class="skill-card">
      <div class="skill-name"><span>Generative AI</span><span style="color:#ffd600;font-family:'JetBrains Mono',monospace;font-size:0.75rem">40%</span></div>
      <div class="skill-bar-bg"><div class="skill-bar" id="b4" style="background:linear-gradient(90deg,#ffd600,#00d2ff);width:0"></div></div>
    </div>
  </div>

  <div class="section-label">— pinned repos</div>
  <div class="repos-grid">
    <div class="repo-card">
      <div class="repo-title">Anime-Recommendation-System</div>
      <div class="repo-desc">ML-based anime recommender using collaborative filtering & content analysis</div>
      <div class="repo-footer"><span class="repo-lang"><span class="lang-dot" style="background:#3572A5"></span>Python</span><span>★ 0</span></div>
    </div>
    <div class="repo-card">
      <div class="repo-title">Text-to-Voice</div>
      <div class="repo-desc">Convert any text to natural speech with Python's TTS engine</div>
      <div class="repo-footer"><span class="repo-lang"><span class="lang-dot" style="background:#3572A5"></span>Python</span><span>★ 0</span></div>
    </div>
    <div class="repo-card">
      <div class="repo-title">Language Translator</div>
      <div class="repo-desc">Multi-language translation tool powered by Google Translate API</div>
      <div class="repo-footer"><span class="repo-lang"><span class="lang-dot" style="background:#3572A5"></span>Python</span><span>★ 0</span></div>
    </div>
    <div class="repo-card">
      <div class="repo-title">Predictive Analytics</div>
      <div class="repo-desc">Data-driven predictive models for real-world business problems</div>
      <div class="repo-footer"><span class="repo-lang"><span class="lang-dot" style="background:#3572A5"></span>Python</span><span>★ 0</span></div>
    </div>
  </div>

  <div class="section-label">— contribution activity</div>
  <div class="snake-bar" id="contrib"></div>

  <div class="section-label">— connect with me</div>
  <div class="contact-row">
    <a class="contact-btn c-gh" href="#">GitHub @SIDDXIAO</a>
    <a class="contact-btn c-li" href="#">LinkedIn</a>
    <a class="contact-btn c-web" href="#">siddhantpatel.tech</a>
  </div>

  <div class="footer-quote">"Code is poetry written for machines, read by humans." · Keep building, Siddhant 🚀</div>
</div>
<script>
const phrases=["Building AI-powered solutions...","Exploring Data Science 🔬","BCA @ BBD University, Lucknow","Currently learning Generative AI...","Python enthusiast & problem solver"];
let pi=0,ci=0,del=false;
function typeIt(){const ph=phrases[pi];if(!del){if(ci<ph.length){document.getElementById('typed').textContent=ph.slice(0,++ci);setTimeout(typeIt,60);}else{del=true;setTimeout(typeIt,1800);}}else{if(ci>0){document.getElementById('typed').textContent=ph.slice(0,--ci);setTimeout(typeIt,30);}else{del=false;pi=(pi+1)%phrases.length;setTimeout(typeIt,400);}}}
typeIt();
setTimeout(()=>{document.getElementById('b1').style.width='85%';document.getElementById('b2').style.width='70%';document.getElementById('b3').style.width='75%';document.getElementById('b4').style.width='40%';},300);
const c=document.getElementById('contrib');const levels=[0,0,0,1,0,0,1,2,1,0,0,0,1,1,2,3,2,1,0,0,0,1,2,3,4,3,2,1,0,0,1,2,3,4,3,2,1,0,1,2,3,4,4,3,2,1,0,1,2,3];
levels.forEach(l=>{const d=document.createElement('div');d.className=`dot d${l}`;c.appendChild(d);});
</script>
