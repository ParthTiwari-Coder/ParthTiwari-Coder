
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500&family=JetBrains+Mono:wght@400;500&family=Lora:ital,wght@0,500;1,400&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#1a1816;--bg2:#201e1b;--bg3:#272320;--bg4:#2e2a26;
  --b0:rgba(255,255,255,0.05);--b1:rgba(255,255,255,0.09);--b2:rgba(255,255,255,0.15);
  --text:#ddd5c8;--sub:#9a9088;--dim:#524c46;--cream:#e4dbd0;
  --gold:#c8a96e;--gold-bg:rgba(200,169,110,0.08);--gold-bd:rgba(200,169,110,0.22);--gold-dim:#7a6535;
  --rose:#c49090;--rose-bg:rgba(196,144,144,0.08);--rose-bd:rgba(196,144,144,0.22);--rose-dim:#7a5050;
  --cyan:#6ab8c8;--cyan-bg:rgba(106,184,200,0.08);--cyan-bd:rgba(106,184,200,0.2);
}
.root{background:var(--bg);color:var(--text);font-family:'Inter',sans-serif;font-size:14px;line-height:1.7;padding-bottom:64px}
.hero{padding:60px 36px 52px;text-align:center}
.hero-name{font-family:'Lora',serif;font-size:36px;font-weight:500;color:var(--cream);letter-spacing:-0.3px;margin-bottom:12px}
.hero-tag{font-size:12.5px;color:var(--sub);font-weight:300;letter-spacing:.5px;margin-bottom:8px}
.hero-desc{font-size:13px;color:var(--dim);margin-bottom:32px;font-style:italic;font-family:'Lora',serif}
.links{display:flex;gap:10px;justify-content:center}
.lbtn{display:inline-flex;align-items:center;gap:8px;padding:9px 20px;border:0.5px solid var(--b1);border-radius:8px;font-size:11px;font-family:'JetBrains Mono',monospace;color:var(--sub);background:var(--bg2);text-decoration:none;transition:.2s}
.lbtn:hover{border-color:var(--b2);color:var(--text);background:var(--bg3)}
.lbtn-dot{width:5px;height:5px;border-radius:50%;flex-shrink:0}
.slbl{font-family:'JetBrains Mono',monospace;font-size:9.5px;letter-spacing:2.5px;text-transform:uppercase;color:var(--dim);padding:0 28px;margin-bottom:12px;display:block}
.about-card{margin:0 28px 48px;background:var(--bg2);border:0.5px solid var(--b0);border-radius:12px;overflow:hidden}
.about-grid{display:grid;grid-template-columns:1.1fr 1fr}
.acol{padding:28px}
.acol-l{border-right:0.5px solid var(--b0)}
.clbl{font-family:'JetBrains Mono',monospace;font-size:9px;letter-spacing:2px;text-transform:uppercase;margin-bottom:14px}
.clbl-gold{color:var(--gold-dim)}.clbl-rose{color:var(--rose-dim)}
.about-txt{font-size:13px;color:var(--sub);line-height:1.85}
.about-txt strong{color:var(--text);font-weight:500}
.about-foot{margin-top:18px;font-size:10px;font-family:'JetBrains Mono',monospace;color:var(--dim)}
.pills{display:flex;flex-wrap:wrap;gap:5px}
.pl{font-family:'JetBrains Mono',monospace;font-size:10px;border-radius:4px;padding:3px 8px;border:0.5px solid;transition:.18s;cursor:default}
.pl-g{color:var(--gold-dim);background:var(--gold-bg);border-color:var(--gold-bd)}.pl-g:hover{color:var(--gold)}
.pl-r{color:var(--rose-dim);background:var(--rose-bg);border-color:var(--rose-bd)}.pl-r:hover{color:var(--rose)}
.pl-c{color:#4a8898;background:var(--cyan-bg);border-color:var(--cyan-bd)}.pl-c:hover{color:var(--cyan)}
.pl-n{color:var(--dim);background:var(--bg3);border-color:var(--b0)}.pl-n:hover{color:var(--sub)}
.projects{margin:0 28px 48px;display:flex;flex-direction:column;gap:8px}
.proj{border-radius:10px;overflow:hidden;border:0.5px solid;transition:.2s}
.proj-gold{background:var(--gold-bg);border-color:var(--gold-bd)}.proj-gold:hover{border-color:rgba(200,169,110,.4)}
.proj-rose{background:var(--rose-bg);border-color:var(--rose-bd)}.proj-rose:hover{border-color:rgba(196,144,144,.4)}
.proj-inner{display:flex}
.proj-bar{width:3px;flex-shrink:0}
.bar-gold{background:var(--gold-bd)}.bar-rose{background:var(--rose-bd)}.bar-n{background:var(--b1)}
.proj-body{padding:18px 20px;flex:1}
.proj-top{display:flex;align-items:baseline;justify-content:space-between;gap:12px;margin-bottom:7px}
.pname{font-size:14.5px;font-weight:500;color:var(--cream);text-decoration:none;transition:.18s}
a.pname-gold:hover{color:var(--gold)}
a.pname-rose:hover{color:var(--rose)}
.pawrd{font-family:'JetBrains Mono',monospace;font-size:9.5px;border-radius:20px;padding:3px 10px;white-space:nowrap;flex-shrink:0;border:0.5px solid}
.pawrd-gold{color:var(--gold);background:rgba(200,169,110,0.07);border-color:var(--gold-bd)}
.pawrd-rose{color:var(--rose);background:rgba(196,144,144,0.07);border-color:var(--rose-bd)}
.pdesc{font-size:12.5px;color:var(--sub);line-height:1.72;margin-bottom:10px}
.ptags{display:flex;gap:5px;flex-wrap:wrap}
.ptag{font-family:'JetBrains Mono',monospace;font-size:9.5px;color:var(--dim);background:rgba(0,0,0,.15);border:0.5px solid rgba(255,255,255,0.06);border-radius:3px;padding:2px 7px}
.ach{margin:0 28px 56px;display:flex;flex-direction:column;gap:8px}
.arow{display:flex;align-items:stretch;border-radius:10px;overflow:hidden;border:0.5px solid}
.arow-gold{background:var(--gold-bg);border-color:var(--gold-bd)}
.arow-rose{background:var(--rose-bg);border-color:var(--rose-bd)}
.arow-n{background:var(--bg2);border-color:var(--b0)}
.aico{width:46px;display:flex;align-items:center;justify-content:center;font-size:14px;flex-shrink:0}
.aico-gold{background:rgba(200,169,110,0.1)}.aico-rose{background:rgba(196,144,144,0.1)}.aico-n{background:var(--bg3)}
.ainfo{flex:1;padding:14px 16px;display:flex;align-items:center;gap:0}
.arank{font-size:13px;font-weight:500;min-width:118px}
.arank-gold{color:var(--gold)}.arank-rose{color:var(--rose)}.arank-n{color:var(--sub)}
.aevent{font-size:12px;color:var(--sub);flex:1}
.acat{font-family:'JetBrains Mono',monospace;font-size:9.5px;color:var(--dim);text-align:right;white-space:nowrap}
.footer{text-align:center;padding-top:8px}
.footer-txt{font-family:'JetBrains Mono',monospace;font-size:10px;letter-spacing:4px;color:var(--dim)}
@media(max-width:480px){
  .about-grid{grid-template-columns:1fr}.acol-l{border-right:none;border-bottom:0.5px solid var(--b0)}
  .hero-name{font-size:28px}.proj-top{flex-direction:column;gap:5px}
  .ainfo{flex-direction:column;align-items:flex-start;gap:4px}.acat{text-align:left}
}
</style>

<div class="root">
  <div class="hero">
    <div class="hero-name">Parth Tiwari</div>
    <div class="hero-tag">AI &nbsp;·&nbsp; Data Science &nbsp;·&nbsp; Full-Stack Builder</div>
    <div class="hero-desc">Building intelligent systems that solve real problems.</div>
    <div class="links">
      <a class="lbtn" href="https://www.linkedin.com/in/parth-tiwari-164474331/" target="_blank">
        <span class="lbtn-dot" style="background:var(--cyan)"></span>LinkedIn
      </a>
      <a class="lbtn" href="mailto:parthtiwari1516@gmail.com">
        <span class="lbtn-dot" style="background:var(--rose)"></span>parthtiwari1516@gmail.com
      </a>
    </div>
  </div>

  <span class="slbl">About</span>
  <div class="about-card">
    <div class="about-grid">
      <div class="acol acol-l">
        <div class="clbl clbl-gold">Focus</div>
        <div class="about-txt">AI &amp; Data Science student building <strong>practical AI-driven systems</strong> and full-stack applications with real-world impact.<br><br>Working at the intersection of language models, retrieval systems, and applied ML — where the output actually matters.</div>
        <div class="about-foot">B.Tech &nbsp;·&nbsp; hackathon finalist &nbsp;·&nbsp; open-source contributor</div>
      </div>
      <div class="acol">
        <div class="clbl clbl-rose">Stack</div>
        <div class="pills">
          <span class="pl pl-g">Python</span><span class="pl pl-n">C++</span><span class="pl pl-g">JavaScript</span><span class="pl pl-n">Java</span><span class="pl pl-c">React</span><span class="pl pl-r">FastAPI</span><span class="pl pl-g">TensorFlow</span><span class="pl pl-n">scikit-learn</span><span class="pl pl-n">OpenCV</span><span class="pl pl-r">OpenAI API</span><span class="pl pl-c">Gemini API</span><span class="pl pl-r">RAG Systems</span><span class="pl pl-r">Prompt Eng.</span><span class="pl pl-n">Git</span>
        </div>
      </div>
    </div>
  </div>

  <span class="slbl">Projects</span>
  <div class="projects">

    <div class="proj proj-gold">
      <div class="proj-inner">
        <div class="proj-bar bar-gold"></div>
        <div class="proj-body">
          <div class="proj-top">
            <a class="pname pname-gold" href="https://github.com/ParthTiwari-Coder/trustmetric" target="_blank">TrustMetric ↗</a>
            <span class="pawrd pawrd-gold">🏆 Top 7 · National Hackathon</span>
          </div>
          <div class="pdesc">AI-powered financial trust scoring for users outside the traditional credit system — behavioral analysis, risk evaluation, and goal simulation.</div>
          <div class="ptags"><span class="ptag">Python</span><span class="ptag">FastAPI</span><span class="ptag">LLM</span><span class="ptag">FinTech</span></div>
        </div>
      </div>
    </div>

    <div class="proj proj-rose">
      <div class="proj-inner">
        <div class="proj-bar bar-rose"></div>
        <div class="proj-body">
          <div class="proj-top">
            <a class="pname pname-rose" href="https://github.com/ParthTiwari-Coder/credify" target="_blank">Credify ↗</a>
            <span class="pawrd pawrd-rose">🎖️ Top 10 · TechSprint 2026</span>
          </div>
          <div class="pdesc">Misinformation detection using semantic analysis, multimodal verification, and a Chrome extension for real-time content flagging.</div>
          <div class="ptags"><span class="ptag">RAG</span><span class="ptag">OpenAI</span><span class="ptag">Chrome Extension</span></div>
        </div>
      </div>
    </div>

    <div class="proj proj-rose">
      <div class="proj-inner">
        <div class="proj-bar bar-rose"></div>
        <div class="proj-body">
          <div class="proj-top">
            <a class="pname pname-rose" href="https://github.com/ParthTiwari-Coder/safe-ai" target="_blank">SAFE AI ↗</a>
            <span class="pawrd pawrd-rose">🎖️ Top 75 · 418 Teams</span>
          </div>
          <div class="pdesc">Medical AI safety layer filtering unsafe clinical outputs through evidence verification and multi-source risk scoring.</div>
          <div class="ptags"><span class="ptag">LLM Safety</span><span class="ptag">FastAPI</span><span class="ptag">Python</span></div>
        </div>
      </div>
    </div>

    <!-- CLEARVAULT: gold, runner-up badge -->
    <div class="proj proj-gold">
      <div class="proj-inner">
        <div class="proj-bar bar-gold"></div>
        <div class="proj-body">
          <div class="proj-top">
            <span class="pname">ClearVault</span>
            <span class="pawrd pawrd-gold">🥈 Runner-Up · Cognition 2025</span>
          </div>
          <div class="pdesc">Secure data sanitization system following NIST SP 800-88 and DoD 5220.22-M standards with SHA-256 verification.</div>
          <div class="ptags"><span class="ptag">Security</span><span class="ptag">Python</span><span class="ptag">NIST</span></div>
        </div>
      </div>
    </div>

  </div>

  <span class="slbl">Achievements</span>
  <div class="ach">
    <div class="arow arow-gold">
      <div class="aico aico-gold">🏆</div>
      <div class="ainfo"><div class="arank arank-gold">Top 7</div><div class="aevent">National-Level Hackathon</div><div class="acat">FinTech AI</div></div>
    </div>
    <div class="arow arow-rose">
      <div class="aico aico-rose">🎖️</div>
      <div class="ainfo"><div class="arank arank-rose">Top 10 Finalist</div><div class="aevent">TechSprint 2026</div><div class="acat">Misinformation</div></div>
    </div>
    <div class="arow arow-rose">
      <div class="aico aico-rose">🎖️</div>
      <div class="ainfo"><div class="arank arank-rose">Top 75 Finalist</div><div class="aevent">SAFE AI · 418 teams</div><div class="acat">Medical AI</div></div>
    </div>
    <div class="arow arow-gold">
      <div class="aico aico-gold">🥈</div>
      <div class="ainfo"><div class="arank arank-gold">Runner-Up</div><div class="aevent">Cognition 2025</div><div class="acat">Cybersecurity</div></div>
    </div>
    <div class="arow arow-n">
      <div class="aico aico-n">📊</div>
      <div class="ainfo"><div class="arank arank-n">Top 9.58%</div><div class="aevent">Naukri Code360 · Arrays</div><div class="acat">DSA</div></div>
    </div>
  </div>

  <div class="footer">
    <div class="footer-txt">HACK &nbsp;·&nbsp; BUILD &nbsp;·&nbsp; IMPACT &nbsp;·&nbsp; REPEAT</div>
  </div>
</div>
