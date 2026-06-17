[helmi_madouri_portfolio_fr.html](https://github.com/user-attachments/files/29050227/helmi_madouri_portfolio_fr.html)
<img width="1440" height="3336" alt="image" src="https://github.com/user-attachments/assets/e215a1db-fa76-46bc-ada3-fa596542e561" />
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Inter:wght@300;400;500&display=swap');
  *{margin:0;padding:0;box-sizing:border-box;}
  .pf{font-family:'Space Grotesk',sans-serif;background:#0A0F1E;color:#CCD6F6;min-height:100vh;padding:0;}
  .hero{padding:60px 40px 50px;border-bottom:1px solid rgba(0,212,255,0.1);}
  .hero-label{font-family:'Inter',sans-serif;font-size:12px;letter-spacing:3px;color:#00D4FF;text-transform:uppercase;margin-bottom:16px;}
  .hero-name{font-size:48px;font-weight:700;color:#E8F4FF;line-height:1.1;margin-bottom:8px;}
  .hero-name span{color:#00D4FF;}
  .hero-role{font-family:'Inter',sans-serif;font-size:16px;color:#8892B0;margin-bottom:28px;font-weight:300;}
  .cursor{display:inline-block;width:3px;height:44px;background:#00D4FF;margin-left:4px;vertical-align:middle;animation:blink 1s step-end infinite;}
  @keyframes blink{50%{opacity:0}}
  .hero-bio{font-family:'Inter',sans-serif;font-size:14px;color:#8892B0;max-width:480px;line-height:1.7;}
  .hero-cta{display:flex;gap:12px;margin-top:28px;}
  .btn-primary{background:#00D4FF;color:#0A0F1E;padding:10px 24px;border:none;border-radius:4px;font-family:'Space Grotesk',sans-serif;font-size:14px;font-weight:600;cursor:pointer;}
  .btn-outline{background:transparent;color:#00D4FF;padding:10px 24px;border:1px solid #00D4FF;border-radius:4px;font-family:'Space Grotesk',sans-serif;font-size:14px;cursor:pointer;}
  .section{padding:40px 40px;}
  .section-title{font-size:13px;letter-spacing:3px;color:#00D4FF;text-transform:uppercase;margin-bottom:24px;font-weight:500;}
  .skills-grid{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:24px;}
  .skill-tag{background:rgba(0,212,255,0.07);border:1px solid rgba(0,212,255,0.2);color:#00D4FF;padding:6px 14px;border-radius:3px;font-size:13px;font-family:'Inter',sans-serif;}
  .skill-tag.design{background:rgba(180,100,255,0.07);border-color:rgba(180,100,255,0.25);color:#B46FFF;}
  .skill-tag.tool{background:rgba(255,165,0,0.06);border-color:rgba(255,165,0,0.2);color:#FFB347;}
  .skill-cat{font-size:11px;letter-spacing:2px;color:#8892B0;text-transform:uppercase;margin-bottom:10px;margin-top:18px;}
  .projects-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px;}
  .proj-card{background:#0D1428;border:1px solid rgba(0,212,255,0.1);border-radius:6px;padding:24px;position:relative;overflow:hidden;transition:border-color .25s,transform .2s;cursor:default;}
  .proj-card:hover{border-color:rgba(0,212,255,0.4);transform:translateY(-2px);}
  .proj-card::before{content:'';position:absolute;top:0;left:0;width:3px;height:100%;background:#00D4FF;}
  .proj-card.design::before{background:#B46FFF;}
  .proj-card.amber::before{background:#FFB347;}
  .proj-card.green::before{background:#4ECDC4;}
  .proj-num{font-size:11px;color:#8892B0;font-family:'Inter',sans-serif;margin-bottom:10px;letter-spacing:1px;}
  .proj-title{font-size:17px;font-weight:600;color:#E8F4FF;margin-bottom:8px;}
  .proj-desc{font-size:13px;font-family:'Inter',sans-serif;color:#8892B0;line-height:1.6;}
  .proj-tags{display:flex;gap:6px;margin-top:14px;flex-wrap:wrap;}
  .proj-tag{font-size:11px;background:rgba(255,255,255,0.05);padding:3px 10px;border-radius:2px;color:#8892B0;font-family:'Inter',sans-serif;}
  .about-strip{background:#0D1428;border-top:1px solid rgba(0,212,255,0.08);border-bottom:1px solid rgba(0,212,255,0.08);padding:28px 40px;display:flex;gap:32px;align-items:center;flex-wrap:wrap;}
  .about-item{display:flex;align-items:center;gap:8px;font-size:13px;font-family:'Inter',sans-serif;color:#8892B0;}
  .about-item i{color:#00D4FF;font-size:16px;}
  .contact-section{padding:36px 40px 48px;}
  .contact-row{display:flex;gap:16px;align-items:center;flex-wrap:wrap;}
  .contact-link{display:flex;align-items:center;gap:8px;background:rgba(0,212,255,0.06);border:1px solid rgba(0,212,255,0.15);padding:10px 20px;border-radius:4px;color:#00D4FF;font-size:13px;font-family:'Inter',sans-serif;text-decoration:none;}
  .divider{height:1px;background:rgba(0,212,255,0.06);margin:0 40px;}
  .status-dot{width:8px;height:8px;border-radius:50%;background:#4ECDC4;display:inline-block;margin-right:6px;animation:pulse 2s ease-in-out infinite;}
  @keyframes pulse{0%,100%{opacity:1}50%{opacity:.4}}
</style>

<div class="pf">
  <div class="hero">
    <div class="hero-label">Développeur Front-End &amp; Designer UI/UX</div>
    <div class="hero-name">Helmi <span>Madouri</span><span class="cursor"></span></div>
    <div class="hero-role">Créer des interfaces modernes — un composant à la fois.</div>
    <div class="hero-bio">Passionné par la création d'applications web responsives et conviviales, alliant code propre et design soigné. Basé en Tunisie, toujours en apprentissage.</div>
    <div class="hero-cta">
      <button class="btn-primary" onclick="openLink('mailto:helmimadouri50@gmail.com')">Me contacter</button>
      <button class="btn-outline" onclick="openLink('https://linkedin.com')">LinkedIn</button>
    </div>
  </div>

  <div class="about-strip">
    <div class="about-item"><i class="ti ti-map-pin" aria-hidden="true"></i> Tunisie</div>
    <div class="about-item"><i class="ti ti-code" aria-hidden="true"></i> Développeur Front-End</div>
    <div class="about-item"><i class="ti ti-palette" aria-hidden="true"></i> Designer UI/UX</div>
    <div class="about-item"><span class="status-dot"></span> En cours d'amélioration sur React &amp; Next.js</div>
  </div>

  <div class="section">
    <div class="section-title">Compétences</div>
    <div class="skill-cat">Développement Front-End</div>
    <div class="skills-grid">
      <span class="skill-tag">HTML5</span>
      <span class="skill-tag">CSS3</span>
      <span class="skill-tag">JavaScript ES6+</span>
      <span class="skill-tag">React.js</span>
      <span class="skill-tag">Next.js</span>
      <span class="skill-tag">Tailwind CSS</span>
    </div>
    <div class="skill-cat">Design UI/UX</div>
    <div class="skills-grid">
      <span class="skill-tag design">Maquettage</span>
      <span class="skill-tag design">Design d'interface</span>
      <span class="skill-tag design">Expérience utilisateur</span>
      <span class="skill-tag design">Design responsive</span>
      <span class="skill-tag design">Prototypage</span>
    </div>
    <div class="skill-cat">Outils</div>
    <div class="skills-grid">
      <span class="skill-tag tool">Git &amp; GitHub</span>
      <span class="skill-tag tool">VS Code</span>
      <span class="skill-tag tool">Figma</span>
    </div>
  </div>

  <div class="divider"></div>

  <div class="section">
    <div class="section-title">Projets</div>
    <div class="projects-grid">
      <div class="proj-card">
        <div class="proj-num">01 / Portfolio</div>
        <div class="proj-title">Site Portfolio</div>
        <div class="proj-desc">Portfolio personnel mettant en valeur mes compétences et projets avec un design moderne et épuré.</div>
        <div class="proj-tags">
          <span class="proj-tag">React</span><span class="proj-tag">Next.js</span><span class="proj-tag">Tailwind</span>
        </div>
      </div>
      <div class="proj-card design">
        <div class="proj-num">02 / E-Commerce</div>
        <div class="proj-title">Interface E-Commerce</div>
        <div class="proj-desc">Interface e-commerce moderne avec fiches produits, panier et tunnel de commande — développée avec React &amp; Next.js.</div>
        <div class="proj-tags">
          <span class="proj-tag">React</span><span class="proj-tag">Next.js</span><span class="proj-tag">CSS3</span>
        </div>
      </div>
      <div class="proj-card amber">
        <div class="proj-num">03 / Réservation</div>
        <div class="proj-title">Application de Prise de Rendez-vous</div>
        <div class="proj-desc">Système de réservation avec une interface entièrement responsive, sélecteur de dates et parcours utilisateur fluide.</div>
        <div class="proj-tags">
          <span class="proj-tag">JavaScript</span><span class="proj-tag">Responsive</span><span class="proj-tag">UX</span>
        </div>
      </div>
      <div class="proj-card green">
        <div class="proj-num">04 / Tableau de bord</div>
        <div class="proj-title">Interface Dashboard Admin</div>
        <div class="proj-desc">Panneau d'administration riche en données avec statistiques, graphiques et hiérarchie visuelle claire.</div>
        <div class="proj-tags">
          <span class="proj-tag">React</span><span class="proj-tag">Visualisation</span><span class="proj-tag">UI Design</span>
        </div>
      </div>
    </div>
  </div>

  <div class="divider"></div>

  <div class="contact-section">
    <div class="section-title">Contact</div>
    <div class="contact-row">
      <a class="contact-link" href="mailto:helmimadouri50@gmail.com"><i class="ti ti-mail" aria-hidden="true"></i> helmimadouri50@gmail.com</a>
      <a class="contact-link" href="https://linkedin.com"><i class="ti ti-brand-linkedin" aria-hidden="true"></i> Profil LinkedIn</a>
    </div>
  </div>
</div>
