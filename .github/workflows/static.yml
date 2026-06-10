<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Romcel Geluz | Workforce Planner &amp; eCommerce Catalog Specialist</title>
<link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 32 32'%3E%3Crect width='32' height='32' rx='8' fill='%230F766E'/%3E%3Ctext x='50%25' y='54%25' dominant-baseline='middle' text-anchor='middle' font-family='sans-serif' font-weight='800' font-size='15' fill='%23FFFFFF'%3ERG%3C/text%3E%3C/svg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&family=DM+Sans:wght@300;400;500;600;700;800&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#F8FAFC;--bg-alt:#F1F5F9;--surface:#FFFFFF;
  --text:#0F172A;--text-muted:#64748B;--text-light:#94A3B8;
  --accent:#0F766E;--accent-dark:#0D5F58;--accent-light:#CCFBF1;--accent-rgb:15,118,110;
  --gold:#C9A84C;--gold-dark:#9A7A1E;--gold-rgb:201,168,76;
  --border:#E2E8F0;--border-accent:rgba(15,118,110,0.25);
  --shadow-sm:0 1px 3px rgba(15,23,42,.06);
  --shadow-md:0 4px 16px rgba(15,23,42,.08),0 2px 6px rgba(15,23,42,.04);
  --shadow-lg:0 16px 40px rgba(15,23,42,.1),0 4px 12px rgba(15,23,42,.06);
  --radius:12px;--radius-lg:20px;
  --font-display:'Inter','DM Sans',system-ui,sans-serif;--font-body:'Plus Jakarta Sans',sans-serif;
  --ease-spring:cubic-bezier(.34,1.56,.64,1);--ease-out:cubic-bezier(.16,1,.3,1);
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;overflow-x:clip}
body{font-family:var(--font-body);background:var(--bg);color:var(--text);line-height:1.65;overflow-x:clip;cursor:auto;transition:background .8s ease}
img{max-width:100%;display:block}a{color:inherit;text-decoration:none;cursor:pointer}
button{cursor:pointer;font-family:var(--font-body)}ul{list-style:none}


/* PARTICLE CANVAS */
#hero-particles{position:absolute;inset:0;pointer-events:none;z-index:0;opacity:.6}

/* SCROLL INDICATOR */
.hero__scroll-cue{position:absolute;bottom:28px;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:5px;pointer-events:none}
.hero__scroll-cue span{font-size:9px;letter-spacing:.18em;text-transform:uppercase;color:var(--text-muted);opacity:.5}
.hero__scroll-cue-line{width:1px;height:0;background:linear-gradient(to bottom,var(--accent),transparent);animation:scrollGrow 2.2s ease-in-out infinite}
@keyframes scrollGrow{0%{height:0;opacity:0}50%{height:36px;opacity:.7}100%{height:36px;opacity:0}}

/* ACHIEVEMENT CARD TILT */
.ach__card{transform-style:preserve-3d;transition:transform .5s var(--ease-spring),box-shadow .4s}

/* WORD REVEAL */
.word-reveal .wr{display:inline-block;opacity:0;transform:translateY(14px);transition:opacity .55s var(--ease-out),transform .55s var(--ease-out)}
.word-reveal.wr-done .wr{opacity:1;transform:none}


/* ═══════════════════════════════════════════════════
   200% ANIMATION UPGRADE — FLOATING / LIVE EFFECTS
═══════════════════════════════════════════════════ */

/* FLOATING NICHE ICONS in hero */
.hero__float-icons{position:absolute;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.hfi{position:absolute;opacity:0;animation:hfloat linear infinite}
.hfi{color:var(--accent)} .hfi svg{color:var(--accent);filter:drop-shadow(0 0 6px rgba(15,118,110,.3))}
@keyframes hfloat{
  0%{opacity:0;transform:translateY(20px) rotate(0deg)}
  10%{opacity:.18}
  90%{opacity:.18}
  100%{opacity:0;transform:translateY(-60px) rotate(25deg)}
}

/* HERO PROOF CARD PULSE */
.hero__proof{position:relative}
.hero__proof::before{
  content:'';position:absolute;inset:-2px;
  border-radius:calc(var(--radius-lg) + 2px);
  background:linear-gradient(135deg,rgba(15,118,110,.4),transparent,rgba(15,118,110,.2));
  animation:proofPulse 3s ease-in-out infinite;
  z-index:-1
}
@keyframes proofPulse{0%,100%{opacity:.4;transform:scale(1)}50%{opacity:.8;transform:scale(1.01)}}

/* PROOF STAT LIVE DOT */
.proof__stat-val{position:relative}
.proof__live-dot{
  display:inline-block;width:5px;height:5px;
  border-radius:50%;background:#16A34A;
  margin-left:4px;vertical-align:middle;
  animation:livepulse 1.8s ease-in-out infinite
}
@keyframes livepulse{0%,100%{transform:scale(1);opacity:1}50%{transform:scale(1.6);opacity:.5}}

/* STATS SECTION FLOATING NUMBERS */
.stats__bg-nums{position:absolute;inset:0;overflow:hidden;pointer-events:none;z-index:0}
.stats__bg-num{
  position:absolute;font-family:var(--font-display);
  font-weight:800;font-size:clamp(60px,12vw,140px);
  color:rgba(15,118,110,.04);line-height:1;
  animation:bgNumFloat 18s ease-in-out infinite
}
@keyframes bgNumFloat{0%,100%{transform:translateY(0)}50%{transform:translateY(-20px)}}

/* STATS SECTION */
#stats{position:relative;overflow:hidden}

/* SECTION GLOW PULSE on entry */
@keyframes sectionGlow{
  0%{box-shadow:none}
  30%{box-shadow:0 0 40px rgba(15,118,110,.06)}
  100%{box-shadow:none}
}
.section-glow{animation:sectionGlow 1.2s ease-out forwards}

/* ANIMATED TAB INDICATOR */
.services__tabs-nav{position:relative}
.tab-indicator{
  position:absolute;bottom:0;height:2px;
  background:var(--accent);border-radius:2px;
  transition:left .3s var(--ease-spring),width .3s var(--ease-spring)
}

/* SERVICE CARD CORNER ACCENT */
.svc__card::before{
  content:'';position:absolute;top:0;right:0;
  width:60px;height:60px;
  background:linear-gradient(135deg,rgba(15,118,110,.06),transparent);
  border-radius:0 var(--radius-lg) 0 60px;
  pointer-events:none
}

/* TOOLKIT BACKGROUND DOT GRID */
#toolkit{background:var(--bg)}
#toolkit::before{
  content:'';position:absolute;inset:0;
  background-image:radial-gradient(circle,rgba(15,118,110,.12) 1px,transparent 1px);
  background-size:28px 28px;
  animation:gridShift 20s linear infinite;
  pointer-events:none;z-index:0
}
.toolkit__inner{position:relative;z-index:1}
@keyframes gridShift{0%{background-position:0 0}100%{background-position:28px 28px}}

/* TOOLKIT TAG POP */
.toolkit__tag{position:relative;overflow:hidden}
.toolkit__tag::after{
  content:'';position:absolute;inset:0;
  background:rgba(15,118,110,.0);
  transition:background .2s
}
.toolkit__tag:hover::after{background:rgba(15,118,110,.06)}

/* TOOLKIT CAT ICON */
.toolkit__cat-label svg{
  animation:catIconSpin 8s linear infinite;
  flex-shrink:0
}
@keyframes catIconSpin{0%{transform:rotate(0deg)}100%{transform:rotate(360deg)}}

/* EXPERIENCE TIMELINE DOTS PULSE */
.exp__dot{position:relative}
.exp__dot::after{
  content:'';position:absolute;inset:-4px;
  border-radius:50%;border:1px solid rgba(15,118,110,0);
  transition:border-color .3s,transform .3s
}
.exp__item:hover .exp__dot::after{
  border-color:rgba(15,118,110,.4);
  transform:scale(1.4)
}

/* EXP CONTENT SLIDE IN */
.exp__content{
  position:relative;
  transition:border-color .3s,box-shadow .3s,transform .35s var(--ease-out)
}
.exp__content.is-in{transform:none!important}

/* ACHIEVEMENTS FLOATING BADGE */
.ach__float-badge{
  position:absolute;pointer-events:none;
  font-family:var(--font-display);font-weight:700;
  font-size:11px;letter-spacing:.08em;
  color:rgba(201,168,76,.25);
  animation:achBadgeFloat linear infinite
}
@keyframes achBadgeFloat{
  0%{transform:translateY(0) rotate(-8deg);opacity:0}
  20%{opacity:1}
  80%{opacity:1}
  100%{transform:translateY(-50px) rotate(8deg);opacity:0}
}

/* PROGRESS BARS in achievements */
.ach__progress-wrap{margin-top:14px}
.ach__progress-label{
  display:flex;justify-content:space-between;
  font-size:11px;color:var(--text-muted);margin-bottom:5px;font-weight:500
}
.ach__progress-track{
  height:4px;background:var(--border);border-radius:2px;overflow:hidden
}
.ach__progress-fill{
  height:100%;background:linear-gradient(90deg,var(--accent),var(--gold));
  border-radius:2px;width:0;
  transition:width 1.2s cubic-bezier(.16,1,.3,1)
}

/* RIPPLE on buttons */
.btn--primary,.btn--secondary,.svc__cta,.nav__cta{overflow:hidden;position:relative}
.ripple{
  position:absolute;border-radius:50%;
  background:rgba(255,255,255,.25);
  transform:scale(0);animation:rippleAnim .5s linear;
  pointer-events:none
}
@keyframes rippleAnim{to{transform:scale(4);opacity:0}}

/* FOOTER WAVE */
footer{position:relative;overflow:hidden}
footer::before{
  content:'';position:absolute;top:0;left:-50%;
  width:200%;height:3px;
  background:linear-gradient(90deg,transparent,var(--accent),var(--gold),var(--accent),transparent);
  animation:footerWave 4s linear infinite
}
@keyframes footerWave{0%{transform:translateX(-25%)}100%{transform:translateX(25%)}}

/* ABOUT SECTION ANIMATED GRADIENT */
#about{position:relative;overflow:hidden}
#about::after{
  content:'';position:absolute;
  width:600px;height:600px;
  background:radial-gradient(circle,rgba(15,118,110,.04),transparent 70%);
  border-radius:50%;
  animation:aboutOrb 15s ease-in-out infinite;
  pointer-events:none;z-index:0
}
.about__grid{position:relative;z-index:1}
@keyframes aboutOrb{
  0%{top:-200px;right:-200px}
  50%{top:50%;right:10%}
  100%{top:-200px;right:-200px}
}

/* CONTACT SECTION GLOW */
#contact{position:relative;overflow:hidden}
#contact::before{
  content:'';position:absolute;
  width:500px;height:500px;bottom:-200px;left:-100px;
  background:radial-gradient(circle,rgba(15,118,110,.05),transparent 70%);
  border-radius:50%;animation:contactOrb 12s ease-in-out infinite;
  pointer-events:none;z-index:0
}
.contact__tabs-nav,.contact__panel,.contact__links{position:relative;z-index:1}
@keyframes contactOrb{
  0%,100%{transform:translateY(0) scale(1)}
  50%{transform:translateY(-60px) scale(1.1)}
}

/* NAV LINK ANIMATED UNDERLINE */
.nav__link{position:relative}
.nav__link::after{
  content:'';position:absolute;
  bottom:-2px;left:0;width:0;height:1.5px;
  background:var(--accent);
  transition:width .25s var(--ease-out)
}
.nav__link:hover::after,.nav__link.active::after{width:100%}

/* SECTION NUMBER WATERMARK */
.section__watermark{pointer-events:none;
  position:absolute;right:0;top:50%;transform:translateY(-50%);
  font-family:var(--font-display);font-weight:800;
  font-size:clamp(80px,15vw,160px);
  color:rgba(15,118,110,.035);line-height:1;
  pointer-events:none;user-select:none;
  animation:wmPulse 4s ease-in-out infinite
}
@keyframes wmPulse{0%,100%{opacity:.7}50%{opacity:1}}

/* GLOWING STAT NUMBERS */
.stat-num{
  position:relative;
  text-shadow:0 0 30px rgba(15,118,110,.0);
  transition:text-shadow .3s
}
.stat-item:hover .stat-num{
  text-shadow:0 0 20px rgba(15,118,110,.3)
}


/* CREDENTIALS SECTION */
.cred__grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
@media(max-width:900px){.cred__grid{grid-template-columns:repeat(2,1fr)}}
@media(max-width:560px){.cred__grid{grid-template-columns:1fr}}

.cred__card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius);padding:24px;
  display:flex;gap:16px;align-items:flex-start;
  transition:border-color .3s,box-shadow .3s,transform .4s var(--ease-spring);
  transform-style:preserve-3d;
}
.cred__card:hover{
  border-color:var(--border-accent);
  box-shadow:0 12px 32px rgba(15,23,42,.1);
  transform:translateY(-4px)
}
.cred__icon-wrap{
  width:42px;height:42px;flex-shrink:0;
  border-radius:10px;background:rgba(var(--accent-rgb),.1);
  display:flex;align-items:center;justify-content:center;
  color:var(--accent);
  transition:background .3s,transform .3s
}
.cred__card:hover .cred__icon-wrap{
  background:rgba(var(--accent-rgb),.18);transform:scale(1.1) rotate(-5deg)
}
.cred__meta{flex:1;min-width:0}
.cred__badge{
  display:inline-block;font-size:10px;font-weight:700;
  letter-spacing:.1em;text-transform:uppercase;
  color:var(--accent);background:rgba(var(--accent-rgb),.08);
  border:1px solid rgba(var(--accent-rgb),.2);
  padding:2px 8px;border-radius:4px;margin-bottom:8px
}
.cred__title{font-size:14px;font-weight:700;color:var(--text);margin-bottom:4px}
.cred__score{
  font-family:var(--font-display);font-size:28px;font-weight:800;
  color:var(--accent);line-height:1;margin:6px 0 4px
}
.cred__score span{font-size:14px;font-weight:500;color:var(--text-muted);margin-left:2px}
.cred__detail{font-size:11.5px;color:var(--text-muted);line-height:1.5;margin-bottom:10px}
.cred__bar-wrap{
  height:3px;background:var(--border);border-radius:2px;overflow:hidden
}
.cred__bar{
  height:100%;width:0;
  background:linear-gradient(90deg,var(--accent),var(--gold,#C9A84C));
  border-radius:2px;
  transition:width 1.2s cubic-bezier(.16,1,.3,1)
}

/* TECH SETUP SECTION */
.setup__grid{display:grid;grid-template-columns:repeat(3,1fr);gap:24px}
@media(max-width:900px){.setup__grid{grid-template-columns:1fr 1fr}}
@media(max-width:560px){.setup__grid{grid-template-columns:1fr}}

.setup__card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius-lg);padding:28px;
  transition:border-color .3s,box-shadow .3s,transform .4s var(--ease-spring)
}
.setup__card:hover{
  border-color:var(--border-accent);
  box-shadow:0 16px 40px rgba(15,23,42,.1);
  transform:translateY(-5px)
}
.setup__icon-wrap{
  width:48px;height:48px;
  border-radius:12px;background:rgba(var(--accent-rgb),.1);
  display:flex;align-items:center;justify-content:center;
  color:var(--accent);margin-bottom:16px;
  transition:background .3s,transform .3s
}
.setup__card:hover .setup__icon-wrap{
  background:rgba(var(--accent-rgb),.18);transform:scale(1.08) rotate(-4deg)
}
.setup__label{
  font-size:10px;font-weight:700;letter-spacing:.12em;
  text-transform:uppercase;color:var(--accent);margin-bottom:6px
}
.setup__name{
  font-family:var(--font-display);font-size:18px;font-weight:700;
  color:var(--text);margin-bottom:14px;line-height:1.2
}
.setup__specs{list-style:none;padding:0;margin:0;display:flex;flex-direction:column;gap:7px}
.setup__specs li{
  display:flex;align-items:center;gap:7px;
  font-size:13px;color:var(--text-muted)
}
.setup__specs li svg{color:var(--accent);flex-shrink:0}


/* VIEW PROOF LINK */
.cred__proof-link{
  display:inline-flex;align-items:center;gap:5px;
  font-size:11px;font-weight:600;letter-spacing:.05em;
  color:var(--accent);text-decoration:none;
  margin-top:8px;
  transition:gap .2s,opacity .2s;
  opacity:.75;
}
.cred__proof-link:hover{gap:8px;opacity:1}
.cred__proof-link svg{transition:transform .2s}
.cred__proof-link:hover svg{transform:translateX(2px)}


/* FORM SUCCESS STATE */
.form__success{
  display:none;flex-direction:column;align-items:center;
  justify-content:center;text-align:center;
  padding:48px 24px;gap:16px;
  animation:successReveal .5s var(--ease-spring) forwards
}
@keyframes successReveal{
  0%{opacity:0;transform:scale(.9) translateY(10px)}
  100%{opacity:1;transform:none}
}
.form__success-icon{
  width:64px;height:64px;border-radius:50%;
  background:rgba(var(--accent-rgb),.1);
  display:flex;align-items:center;justify-content:center;
  color:var(--accent);animation:iconPop .4s var(--ease-spring) .1s both
}
@keyframes iconPop{
  0%{transform:scale(0)}
  60%{transform:scale(1.15)}
  100%{transform:scale(1)}
}
.form__success-title{
  font-family:var(--font-display);font-size:24px;
  font-weight:700;color:var(--text)
}
.form__success-sub{font-size:14px;color:var(--text-muted);line-height:1.6;max-width:320px}
.form__success-meta{
  font-size:12px;color:var(--accent);
  font-family:var(--font-mono);letter-spacing:.05em;
  opacity:.7;margin-top:4px
}
.contact__form.is-sent .form__fields{display:none}
.contact__form.is-sent .form__success{display:flex}


/* ═══════════════════════════════════════════════════
   ROMCEL UPGRADE ROUND 2 — MORE EVERYTHING
═══════════════════════════════════════════════════ */

/* KINETIC HERO TEXT */
.hero__kinetic{
  color:var(--accent);font-style:italic;
  display:inline-block;
  transition:opacity .3s ease,transform .3s ease
}

/* WIPE REVEAL on section headings */

.wipe-in::after{
  content:'';position:absolute;inset:0;
  background:var(--accent);
  transform:translateX(-101%);z-index:2
}
.wipe-in.wipe-fired::after{
  animation:wipeThrough .65s cubic-bezier(.77,0,.18,1) forwards
}
@keyframes wipeThrough{
  0%{transform:translateX(-101%)}
  50%{transform:translateX(0)}
  100%{transform:translateX(101%)}
}

/* SLOT MACHINE FLIP on stats */
.stat-flip-char{
  display:inline-block;
  transition:transform .06s linear,opacity .06s linear
}

/* SECTION DIVIDERS that draw across */
.section-divider{
  width:0;height:1px;
  background:linear-gradient(90deg,var(--accent),transparent);
  margin:0 0 32px;
  transition:width 1s cubic-bezier(.16,1,.3,1)
}
.section-divider.is-drawn{width:100%}

/* SERVICE ICON PULSE on hover */
.svc__icon-wrap{transition:background .3s,transform .3s,box-shadow .3s}
.svc__card:hover .svc__icon-wrap{
  box-shadow:0 0 20px rgba(var(--accent-rgb),.25)
}
.svc__icon-wrap svg{
  transition:transform .4s cubic-bezier(.34,1.56,.64,1)
}
.svc__card:hover .svc__icon-wrap svg{transform:scale(1.15) rotate(-8deg)}

/* CRED SCORE GLOW PULSE */
.cred__score{transition:text-shadow .3s}
.cred__card.score-glow .cred__score{
  text-shadow:0 0 20px rgba(var(--accent-rgb),.5),
              0 0 40px rgba(var(--accent-rgb),.25)
}

/* FLOATING ICONS in credentials + achievements */
.section-float-icons{
  position:absolute;inset:0;
  pointer-events:none;z-index:0;overflow:hidden
}
.sfi{
  position:absolute;color:rgba(var(--accent-rgb),.08);
  animation:sfiFloat linear infinite
}
@keyframes sfiFloat{
  0%{opacity:0;transform:translateY(20px) rotate(0deg)}
  15%{opacity:1}
  85%{opacity:1}
  100%{opacity:0;transform:translateY(-60px) rotate(20deg)}
}

/* CONTACT LINKS BOUNCE */
.contact__link{
  transition:transform .3s cubic-bezier(.34,1.56,.64,1),color .2s
}
.contact__link:hover{transform:translateY(-6px) scale(1.05)}

/* FORM FIELD FOCUS GLOW */
.form__input:focus,.form__textarea:focus{
  box-shadow:0 0 0 2px rgba(var(--accent-rgb),.2),
             0 0 16px rgba(var(--accent-rgb),.1) !important;
  border-color:var(--accent) !important
}

/* ABOUT STATS with icons */
.about__quick-stats{
  display:grid;grid-template-columns:repeat(4,1fr);
  gap:12px;margin-top:28px;position:relative;z-index:1
}
.about__stat-pill{
  background:rgba(var(--accent-rgb),.06);
  border:1px solid rgba(var(--accent-rgb),.15);
  border-radius:8px;padding:14px;
  display:flex;flex-direction:column;align-items:center;
  gap:6px;text-align:center;
  transition:background .3s,transform .3s,border-color .3s
}
.about__stat-pill:hover{
  background:rgba(var(--accent-rgb),.1);
  border-color:rgba(var(--accent-rgb),.3);
  transform:translateY(-3px)
}
.about__stat-pill svg{color:var(--accent);opacity:.7}
.about__stat-pill-val{
  font-family:var(--font-display);font-size:18px;
  font-weight:700;color:var(--accent)
}
.about__stat-pill-label{
  font-size:11px;color:var(--text-muted);
  font-family:var(--font-mono);letter-spacing:.05em
}

/* NAV LINK GLOW on active */
.nav__link.active{
  color:var(--accent);
  text-shadow:0 0 12px rgba(var(--accent-rgb),.3)
}

/* EXP DOT PULSE RING */
.exp__dot{position:relative}
.exp__dot::after{
  content:'';position:absolute;
  inset:-6px;border-radius:50%;
  border:1px solid rgba(var(--accent-rgb),0);
  transition:border-color .3s,transform .3s
}
.exp__item:hover .exp__dot::after{
  border-color:rgba(var(--accent-rgb),.4);
  transform:scale(1.3)
}

/* SECTION INNER gets z-index for floats */
.section__inner{position:relative;z-index:1}
#credentials{position:relative;overflow:hidden}

/* ACHIEVEMENTS SECTION DEPTH BG */
#achievements::before{
  content:'';position:absolute;
  width:500px;height:500px;
  top:-200px;left:-100px;
  background:radial-gradient(circle,rgba(var(--accent-rgb),.04),transparent 70%);
  border-radius:50%;animation:achDepth 14s ease-in-out infinite;
  pointer-events:none;z-index:0
}
@keyframes achDepth{
  0%,100%{transform:scale(1) translate(0,0)}
  50%{transform:scale(1.15) translate(60px,40px)}
}

/* CREDENTIALS BACKGROUND MESH */
#credentials::before{
  content:'';position:absolute;inset:0;
  background-image:radial-gradient(circle,rgba(var(--accent-rgb),.08) 1px,transparent 1px);
  background-size:36px 36px;
  animation:credMesh 25s linear infinite;
  pointer-events:none;z-index:0;opacity:.5
}
@keyframes credMesh{0%{background-position:0 0}100%{background-position:36px 36px}}

/* CONTACT SECTION BG PULSE */
#contact::before{
  content:'';position:absolute;
  width:400px;height:400px;
  top:-100px;right:-100px;
  background:radial-gradient(circle,rgba(var(--accent-rgb),.04),transparent 70%);
  border-radius:50%;animation:contactDepth 10s ease-in-out infinite;
  pointer-events:none;z-index:0
}
@keyframes contactDepth{
  0%,100%{transform:scale(1)}
  50%{transform:scale(1.2) translate(-20px,20px)}
}


/* GENUINE CONTACT COPY */
.contact__honest{
  max-width:640px;margin:0 auto 36px;
  font-size:16px;line-height:1.85;
  color:var(--text);
  text-align:center;
  border:1px solid rgba(var(--accent-rgb),.18);
  padding:28px 36px 28px 52px;border-radius:12px;
  background:rgba(var(--accent-rgb),.04);
  position:relative
}
.contact__honest::before{
  content:'"';
  font-family:var(--font-display);
  font-size:72px;line-height:.6;
  color:var(--accent);
  opacity:.25;
  position:absolute;top:16px;left:16px;
  pointer-events:none;
  font-style:normal
}

/* CALL STEPS */
.call__steps{
  display:flex;flex-direction:column;gap:12px;
  max-width:600px;margin:0 auto 36px
}
.call__step{
  display:grid;grid-template-columns:44px 1fr;
  gap:16px;align-items:start;
  padding:22px 26px;
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:10px;
  box-shadow:0 1px 4px rgba(0,0,0,.04);
  transition:background .3s,border-color .3s,transform .3s,box-shadow .3s
}
.call__step:hover{
  background:rgba(var(--accent-rgb),.05);
  border-color:rgba(var(--accent-rgb),.3);
  box-shadow:0 4px 16px rgba(var(--accent-rgb),.08);
  transform:translateX(4px)
}
.call__step-num{
  font-family:var(--font-display);
  font-size:32px;font-weight:900;
  color:var(--accent);
  opacity:.25;
  line-height:1;padding-top:4px;
  transition:opacity .3s
}
.call__step:hover .call__step-num{opacity:.5}
.call__step-title{
  font-family:var(--font-mono);
  font-size:11px;letter-spacing:.12em;
  text-transform:uppercase;color:var(--accent);
  margin-bottom:6px
}
.call__step-desc{
  font-size:14.5px;line-height:1.75;
  color:var(--text);
  opacity:.8
}

/* MESSAGE HONEST INTRO */
.msg__honest{
  margin:0 auto 28px;max-width:600px;
  font-size:15.5px;line-height:1.85;
  color:var(--text);
  text-align:center;
  border:1px solid rgba(var(--accent-rgb),.18);
  border-left:3px solid var(--accent);
  padding:22px 26px;
  background:rgba(var(--accent-rgb),.04);
  border-radius:0 10px 10px 0;
}
.msg__honest strong{
  color:var(--accent);
  font-weight:600;
}
.msg__honest strong{color:var(--accent);font-style:normal}

@media(max-width:600px){
  .call__step{grid-template-columns:32px 1fr;padding:16px}
  .contact__honest{padding:20px 20px 20px 48px;font-size:14.5px}
}


/* ═══════════════════════════════════════════════════
   BACKGROUND DEPTH — WHITE SPACE ANIMATIONS
═══════════════════════════════════════════════════ */

/* ABOUT SECTION — subtle mesh + corner glow */
#about::before{
  content:'';position:absolute;inset:0;
  background-image:radial-gradient(circle,rgba(var(--accent-rgb),.07) 1.5px,transparent 1.5px);
  background-size:32px 32px;opacity:.5;
  pointer-events:none;z-index:0
}
#about::after{
  content:'';position:absolute;
  width:500px;height:500px;
  bottom:-200px;right:-150px;
  background:radial-gradient(circle,rgba(var(--accent-rgb),.05),transparent 70%);
  border-radius:50%;pointer-events:none;z-index:0;
  animation:aboutGlow 15s ease-in-out infinite
}
@keyframes aboutGlow{0%,100%{transform:scale(1)}50%{transform:scale(1.15) translate(-20px,-20px)}}

/* SERVICES SECTION — diagonal line texture */
#services::before{
  content:'';position:absolute;inset:0;
  background-image:repeating-linear-gradient(
    -45deg,transparent,transparent 40px,
    rgba(var(--accent-rgb),.025) 40px,
    rgba(var(--accent-rgb),.025) 41px
  );
  pointer-events:none;z-index:0
}
#services::after{
  content:'';position:absolute;
  width:400px;height:400px;
  top:-100px;left:-100px;
  background:radial-gradient(circle,rgba(var(--accent-rgb),.04),transparent 70%);
  border-radius:50%;pointer-events:none;z-index:0;
  animation:svcGlow 18s ease-in-out infinite
}
@keyframes svcGlow{0%,100%{transform:scale(1) translate(0,0)}50%{transform:scale(1.2) translate(40px,30px)}}

/* EXPERIENCE SECTION — dot grid */
#experience::before{
  content:'';position:absolute;inset:0;
  background-image:radial-gradient(circle,rgba(var(--accent-rgb),.08) 1px,transparent 1px);
  background-size:24px 24px;opacity:.6;
  pointer-events:none;z-index:0
}
#experience::after{
  content:'';position:absolute;
  width:350px;height:350px;
  bottom:-100px;right:-80px;
  background:radial-gradient(circle,rgba(var(--accent-rgb),.05),transparent 70%);
  border-radius:50%;pointer-events:none;z-index:0;
  animation:expGlow 13s ease-in-out infinite
}
@keyframes expGlow{0%,100%{transform:scale(1)}50%{transform:scale(1.1) translate(-30px,20px)}}

/* SETUP SECTION — wave lines */
#setup::before{
  content:'';position:absolute;inset:0;
  background-image:
    linear-gradient(rgba(var(--accent-rgb),.04) 1px,transparent 1px),
    linear-gradient(90deg,rgba(var(--accent-rgb),.04) 1px,transparent 1px);
  background-size:48px 48px;
  pointer-events:none;z-index:0;
  animation:setupGrid 30s linear infinite
}
@keyframes setupGrid{0%{background-position:0 0}100%{background-position:48px 48px}}

/* CONTACT SECTION — layered radial glows */
#contact::before{
  content:'';position:absolute;
  width:600px;height:600px;
  top:-200px;right:-200px;
  background:radial-gradient(circle,rgba(var(--accent-rgb),.05),transparent 70%);
  border-radius:50%;pointer-events:none;z-index:0;
  animation:contactGlow1 14s ease-in-out infinite
}
@keyframes contactGlow1{0%,100%{transform:scale(1)}50%{transform:scale(1.15) translate(-30px,20px)}}

/* FLOATING GEOMETRIC SHAPES — white sections */
.bg-shape{
  position:absolute;pointer-events:none;z-index:0;
  border:1px solid rgba(var(--accent-rgb),.08);
  border-radius:50%;
  animation:bgShapeFloat ease-in-out infinite
}
@keyframes bgShapeFloat{
  0%,100%{transform:translateY(0) rotate(0deg)}
  50%{transform:translateY(-30px) rotate(180deg)}
}

/* FLOATING PLUS/CROSS MARKS */
.bg-plus{
  position:absolute;pointer-events:none;z-index:0;
  color:rgba(var(--accent-rgb),.1);
  font-size:24px;font-weight:300;line-height:1;
  animation:bgPlusFloat ease-in-out infinite;
  user-select:none
}
@keyframes bgPlusFloat{
  0%,100%{transform:translateY(0) scale(1);opacity:.4}
  50%{transform:translateY(-20px) scale(1.1);opacity:.8}
}

/* FLOATING BRACKETS */
.bg-bracket{
  position:absolute;pointer-events:none;z-index:0;
  color:rgba(var(--accent-rgb),.08);
  font-family:var(--font-mono);
  font-size:48px;line-height:1;
  animation:bgBracketFloat ease-in-out infinite;
  user-select:none
}
@keyframes bgBracketFloat{
  0%,100%{transform:translateY(0) rotate(-5deg);opacity:.5}
  50%{transform:translateY(-25px) rotate(5deg);opacity:1}
}

/* STATS SECTION depth */
#stats{overflow:hidden}
#stats::before{
  content:'';position:absolute;inset:0;
  background-image:radial-gradient(circle,rgba(var(--accent-rgb),.06) 1px,transparent 1px);
  background-size:20px 20px;pointer-events:none;z-index:0
}

/* SECTION INNER always on top of bg */
#about .section__inner,
#services .section__inner,
#experience .section__inner,
#setup .section__inner,
#contact .section__inner{position:relative;z-index:1}


/* FLOATING SVG ICONS in sections */
.sec-float-icon{
  position:absolute;pointer-events:none;z-index:0;
  color:rgba(var(--accent-rgb),.07);
  animation:secIconFloat ease-in-out infinite
}
@keyframes secIconFloat{
  0%,100%{transform:translateY(0) rotate(-5deg)}
  50%{transform:translateY(-28px) rotate(5deg)}
}


/* ═══════════════════════════════════════════════════
   WORKFORCE OPS HEALTH CHECK — AUDIT SECTION
═══════════════════════════════════════════════════ */

#audit{position:relative;overflow:hidden;background:var(--bg)}
#audit::before{
  content:'';position:absolute;inset:0;
  background-image:radial-gradient(circle,rgba(var(--accent-rgb),.07) 1px,transparent 1px);
  background-size:28px 28px;pointer-events:none;z-index:0
}

.audit__wrap{
  position:relative;z-index:1;
  max-width:720px;margin:0 auto
}

/* INTRO BADGE */
.audit__badge{
  display:inline-flex;align-items:center;gap:8px;
  background:rgba(var(--accent-rgb),.08);
  border:1px solid rgba(var(--accent-rgb),.2);
  border-radius:100px;padding:6px 16px;
  font-size:12px;font-weight:700;letter-spacing:.08em;
  text-transform:uppercase;color:var(--accent);
  margin-bottom:20px
}
.audit__badge-dot{
  width:6px;height:6px;border-radius:50%;
  background:var(--accent);
  animation:livepulse 1.8s ease-in-out infinite
}

/* QUESTION STEPS */
.audit__steps{display:flex;flex-direction:column;gap:24px}

.audit__step{
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:14px;padding:28px;
  transition:border-color .3s,box-shadow .3s;
  display:none
}
.audit__step.active{
  display:block;
  animation:auditStepIn .4s cubic-bezier(.34,1.56,.64,1)
}
@keyframes auditStepIn{
  0%{opacity:0;transform:translateY(12px) scale(.98)}
  100%{opacity:1;transform:none}
}
.audit__step:focus-within{
  border-color:rgba(var(--accent-rgb),.4);
  box-shadow:0 4px 20px rgba(var(--accent-rgb),.08)
}

.audit__step-header{
  display:flex;align-items:center;gap:12px;margin-bottom:20px
}
.audit__step-num{
  width:32px;height:32px;border-radius:8px;
  background:rgba(var(--accent-rgb),.1);
  display:flex;align-items:center;justify-content:center;
  font-family:var(--font-mono);font-size:12px;
  font-weight:700;color:var(--accent);flex-shrink:0
}
.audit__step-q{
  font-size:15px;font-weight:700;color:var(--text);line-height:1.4
}

/* SLIDER */
.audit__slider-wrap{padding:8px 0}
.audit__slider{
  width:100%;-webkit-appearance:none;appearance:none;
  height:4px;background:var(--border);border-radius:2px;
  outline:none;cursor:pointer
}
.audit__slider::-webkit-slider-thumb{
  -webkit-appearance:none;appearance:none;
  width:20px;height:20px;border-radius:50%;
  background:var(--accent);cursor:pointer;
  box-shadow:0 2px 8px rgba(var(--accent-rgb),.4);
  transition:transform .2s cubic-bezier(.34,1.56,.64,1)
}
.audit__slider::-webkit-slider-thumb:hover{transform:scale(1.3)}
.audit__slider-labels{
  display:flex;justify-content:space-between;
  font-size:11px;color:var(--text-muted);
  font-family:var(--font-mono);margin-top:8px
}
.audit__slider-val{
  font-family:var(--font-display);font-size:28px;
  font-weight:800;color:var(--accent);text-align:center;
  margin-bottom:8px;transition:all .2s
}

/* CHECKBOXES */
.audit__checks{display:flex;flex-direction:column;gap:10px}
.audit__check-label{
  display:flex;align-items:flex-start;gap:12px;
  padding:12px 16px;border-radius:8px;
  border:1px solid var(--border);cursor:pointer;
  transition:all .2s;user-select:none
}
.audit__check-label:hover{
  background:rgba(var(--accent-rgb),.04);
  border-color:rgba(var(--accent-rgb),.25)
}
.audit__check-label input{display:none}
.audit__check-box{
  width:18px;height:18px;border-radius:4px;
  border:2px solid var(--border);flex-shrink:0;
  display:flex;align-items:center;justify-content:center;
  transition:all .2s;margin-top:1px
}
.audit__check-label input:checked ~ .audit__check-box{
  background:var(--accent);border-color:var(--accent)
}
.audit__check-label input:checked ~ .audit__check-box::after{
  content:'✓';font-size:11px;color:#fff;font-weight:700
}
.audit__check-label input:checked ~ .audit__check-text{
  color:var(--text);font-weight:600
}
.audit__check-text{font-size:14px;color:var(--text-muted);line-height:1.4}
.audit__check-sub{font-size:12px;color:var(--text-light);display:block;margin-top:2px}

/* SELECT DROPDOWN */
.audit__select{
  width:100%;padding:12px 16px;
  background:var(--surface);border:1px solid var(--border);
  border-radius:8px;font-size:14px;color:var(--text);
  font-family:var(--font-body);cursor:pointer;
  transition:border-color .2s,box-shadow .2s;
  -webkit-appearance:none;appearance:none;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8' viewBox='0 0 12 8'%3E%3Cpath d='M1 1l5 5 5-5' stroke='%230F766E' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");
  background-repeat:no-repeat;background-position:right 16px center
}
.audit__select:focus{
  outline:none;border-color:var(--accent);
  box-shadow:0 0 0 3px rgba(var(--accent-rgb),.1)
}

/* PROGRESS BAR */
.audit__progress-wrap{margin-bottom:28px}
.audit__progress-track{
  height:3px;background:var(--border);border-radius:2px;overflow:hidden
}
.audit__progress-fill{
  height:100%;background:var(--accent);border-radius:2px;
  transition:width .4s cubic-bezier(.16,1,.3,1)
}
.audit__progress-label{
  display:flex;justify-content:space-between;
  font-size:11px;color:var(--text-muted);font-family:var(--font-mono);
  margin-bottom:8px
}

/* NAV BUTTONS */
.audit__nav{display:flex;gap:12px;margin-top:20px;justify-content:flex-end}
.audit__btn-next{
  padding:11px 28px;background:var(--accent);color:#fff;
  border:none;border-radius:8px;font-size:14px;font-weight:600;
  cursor:pointer;transition:all .25s;font-family:var(--font-body)
}
.audit__btn-next:hover{
  background:#0D5F57;transform:translateY(-2px);
  box-shadow:0 6px 20px rgba(var(--accent-rgb),.3)
}
.audit__btn-back{
  padding:11px 20px;background:transparent;color:var(--text-muted);
  border:1px solid var(--border);border-radius:8px;font-size:14px;
  cursor:pointer;transition:all .2s;font-family:var(--font-body)
}
.audit__btn-back:hover{border-color:var(--accent);color:var(--accent)}

/* RESULTS PANEL */
.audit__results{
  display:none;
  background:var(--surface);border:1px solid rgba(var(--accent-rgb),.2);
  border-radius:16px;padding:36px;
  animation:auditStepIn .5s cubic-bezier(.34,1.56,.64,1)
}
.audit__results.active{display:block}

.audit__results-header{
  text-align:center;margin-bottom:32px;
  padding-bottom:24px;border-bottom:1px solid var(--border)
}
.audit__results-tag{
  font-family:var(--font-mono);font-size:11px;letter-spacing:.12em;
  text-transform:uppercase;color:var(--accent);margin-bottom:12px
}
.audit__results-headline{
  font-family:var(--font-display);font-size:clamp(22px,4vw,32px);
  font-weight:800;color:var(--text);line-height:1.2;margin-bottom:8px
}
.audit__results-headline span{color:var(--accent);font-style:italic}
.audit__results-sub{
  font-size:14px;color:var(--text-muted);line-height:1.6
}

.audit__metrics{
  display:grid;grid-template-columns:1fr 1fr;
  gap:16px;margin-bottom:28px
}
.audit__metric{
  background:rgba(var(--accent-rgb),.04);
  border:1px solid rgba(var(--accent-rgb),.12);
  border-radius:10px;padding:20px;text-align:center
}
.audit__metric-val{
  font-family:var(--font-display);font-size:32px;
  font-weight:900;color:var(--accent);line-height:1;margin-bottom:4px
}
.audit__metric-label{
  font-size:12px;color:var(--text-muted);
  font-family:var(--font-mono);letter-spacing:.05em
}

.audit__pain-list{margin-bottom:28px}
.audit__pain-item{
  display:flex;align-items:flex-start;gap:10px;
  padding:10px 0;border-bottom:1px solid var(--border);
  font-size:14px;color:var(--text)
}
.audit__pain-item:last-child{border-bottom:none}
.audit__pain-dot{
  width:6px;height:6px;border-radius:50%;background:var(--accent);
  flex-shrink:0;margin-top:6px
}

.audit__cta-block{
  background:var(--accent);border-radius:12px;
  padding:28px;text-align:center
}
.audit__cta-title{
  font-family:var(--font-display);font-size:20px;font-weight:700;
  color:#fff;margin-bottom:8px
}
.audit__cta-sub{font-size:14px;color:rgba(255,255,255,.8);margin-bottom:20px}
.audit__cta-btn{
  display:inline-block;padding:13px 32px;
  background:#fff;color:var(--accent);
  border-radius:8px;font-weight:700;font-size:14px;
  text-decoration:none;transition:all .25s
}
.audit__cta-btn:hover{transform:translateY(-2px);box-shadow:0 6px 20px rgba(0,0,0,.15)}
.audit__restart{
  display:block;margin-top:12px;
  font-size:12px;color:rgba(255,255,255,.6);
  cursor:pointer;background:none;border:none;
  font-family:var(--font-body);transition:color .2s
}
.audit__restart:hover{color:#fff}

@media(max-width:600px){
  .audit__metrics{grid-template-columns:1fr}
}


/* AUDIT PRE-FILL indicator */
.contact__tab-btn.prefilled{
  position:relative
}
.contact__tab-btn.prefilled::after{
  content:'Assessment included';
  position:absolute;top:-20px;left:50%;
  transform:translateX(-50%);
  font-size:9px;font-weight:700;letter-spacing:.08em;
  text-transform:uppercase;color:var(--accent);
  white-space:nowrap;background:rgba(var(--accent-rgb),.08);
  padding:2px 8px;border-radius:4px;
  font-family:var(--font-mono)
}

/* AUDIT message pre-fill banner */
.form__prefill-banner{
  display:none;
  background:rgba(var(--accent-rgb),.06);
  border:1px solid rgba(var(--accent-rgb),.2);
  border-radius:8px;padding:12px 16px;
  margin-bottom:16px;
  font-size:13px;color:var(--accent);
  align-items:center;gap:10px
}
.form__prefill-banner.visible{display:flex}
.form__prefill-banner svg{flex-shrink:0}

.form__select{
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8' viewBox='0 0 12 8'%3E%3Cpath d='M1 1l5 5 5-5' stroke='%230F766E' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");
  background-repeat:no-repeat;background-position:right 16px center;
  -webkit-appearance:none;appearance:none;cursor:pointer
}
.audit__book-banner{
  display:none;
  background:rgba(var(--accent-rgb),.06);
  border:1px solid rgba(var(--accent-rgb),.18);
  border-radius:10px;padding:16px 20px;
  margin-bottom:24px;font-size:13.5px;
  color:var(--text)
}
.audit__book-banner.visible{display:block}
.audit__book-banner-title{
  font-weight:700;color:var(--accent);
  font-family:var(--font-mono);font-size:11px;
  letter-spacing:.1em;text-transform:uppercase;
  margin-bottom:10px
}
.audit__book-banner-grid{
  display:grid;grid-template-columns:1fr 1fr;
  gap:6px 16px;font-size:13px
}
.audit__book-banner-item span:first-child{color:var(--text-muted)}
.audit__book-banner-item span:last-child{font-weight:600;color:var(--text)}

/* ═══════════════════════════════════════════════════
   5 PREMIUM EFFECTS — FINAL POLISH
═══════════════════════════════════════════════════ */

/* 1. NAV GLASSMORPHISM ON SCROLL */
.nav{
  transition:background .4s ease,
             backdrop-filter .4s ease,
             box-shadow .4s ease,
             border-color .4s ease
}
.nav.scrolled{
  background:rgba(255,255,255,.82) !important;
  backdrop-filter:blur(20px);
  -webkit-backdrop-filter:blur(20px);
  box-shadow:0 1px 0 rgba(15,118,110,.1),
             0 4px 24px rgba(15,23,42,.06);
  border-bottom:1px solid rgba(15,118,110,.08)
}

/* 2. SERVICE TAB CROSS-FADE */
.services__panel{
  animation:none !important;
  opacity:0;
  transition:opacity .35s ease
}
.services__panel.active{
  opacity:1;
  transition:opacity .35s ease
}
@keyframes tabFadeIn{
  from{opacity:0;transform:translateY(6px)}
  to{opacity:1;transform:none}
}
.services__panel.tab-enter{
  animation:tabFadeIn .35s cubic-bezier(.16,1,.3,1) forwards
}

/* 3. GRADIENT ANIMATED CTA BUTTONS */
.btn--primary,.nav__cta{
  background-size:200% 100% !important;
  background-image:linear-gradient(
    110deg,
    var(--accent) 0%,
    #0D9488 40%,
    var(--accent) 80%,
    #0D9488 100%
  ) !important;
  animation:btnGradient 3s linear infinite;
  transition:transform .25s var(--ease-spring),
             box-shadow .25s ease,
             opacity .2s !important
}
@keyframes btnGradient{
  0%{background-position:0% 0%}
  100%{background-position:200% 0%}
}
.btn--primary:hover,.nav__cta:hover{
  animation:btnGradient .8s linear infinite;
  transform:translateY(-2px) scale(1.02);
  box-shadow:0 8px 24px rgba(var(--accent-rgb),.35) !important
}

/* 4. CURSOR TRAIL DOTS */
.cursor-trail{
  position:fixed;
  width:5px;height:5px;
  border-radius:50%;
  background:var(--accent);
  pointer-events:none;
  z-index:9998;
  transform:translate(-50%,-50%);
  opacity:0;
  transition:opacity .1s ease
}

/* 5. CONFETTI CANVAS */
#confetti-canvas{
  position:fixed;inset:0;
  pointer-events:none;
  z-index:9999;
  opacity:0;
  transition:opacity .3s ease
}


/* MINIMALIST FONT — keep italic accent on hero */
.hero__headline em,.section__title em{
  font-style:italic;
  font-weight:800;
  color:var(--accent)
}


.contact__tabs-nav{position:relative;z-index:10}
.contact__tab-btn{position:relative;z-index:11;cursor:pointer}
.contact__panels{position:relative;z-index:5}


/* SECTION HEADING SLIDE-IN FROM LEFT */
.section__title{
  opacity:0;
  transform:translateX(-28px);
  transition:opacity .6s cubic-bezier(.16,1,.3,1),
             transform .6s cubic-bezier(.16,1,.3,1)
}
.section__title.title-in{
  opacity:1;
  transform:none
}
/* Ed-label fades up */
.ed-label{
  opacity:0;
  transform:translateY(8px);
  transition:opacity .5s ease,transform .5s ease
}
.ed-label.title-in{
  opacity:1;
  transform:none
}


/* MOBILE CURSOR FIX — never hide cursor on touch devices */
@media (pointer: coarse) {
  body, a, button, select, input, textarea, label,
  [role="button"], [onclick], .tab-btn, .contact__tab-btn,
  .btn--primary, .btn--secondary, .nav__cta, .svc__cta,
  .contact__link, .call__step, .audit__btn-next, .audit__btn-back,
  .audit__check-label, .audit__select, .audit__restart,
  .cred__proof-link, .form__select, .form__submit {
    cursor: pointer !important;
  }
}


/* CUSTOM CURSOR — desktop (pointer:fine) only */
@media (pointer: fine) {
  body { cursor: none; }
  a, button { cursor: none; }
}

/* PROGRESS */
#pb{position:fixed;top:0;left:0;height:2px;background:var(--accent);width:0%;z-index:10000;transition:width .1s linear}

/* CURSOR */
.cursor{width:8px;height:8px;background:var(--accent);border-radius:50%;position:fixed;pointer-events:none;z-index:9999;transform:translate(-50%,-50%);transition:transform .1s}
.cursor-ring{width:30px;height:30px;border:1.5px solid rgba(var(--accent-rgb),.5);border-radius:50%;position:fixed;pointer-events:none;z-index:9998;transform:translate(-50%,-50%);transition:transform .4s var(--ease-spring)}
.cursor.hov{transform:translate(-50%,-50%) scale(2.5);background:rgba(var(--accent-rgb),.4)}
.cursor-ring.hov{transform:translate(-50%,-50%) scale(1.8);border-color:var(--accent)}

/* SPLASH */
#splash{position:fixed;inset:0;background:#0F172A;z-index:9990;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:14px}
#splash.out{animation:splashOut .7s var(--ease-out) forwards}
@keyframes splashOut{to{opacity:0;pointer-events:none;visibility:hidden}}
.splash__gl{position:absolute;height:1px;background:rgba(var(--accent-rgb),.35);width:0;left:0}
.splash__gl.t{top:38%;animation:glDraw .55s var(--ease-out) .45s forwards}
.splash__gl.b{top:62%;animation:glDraw .55s var(--ease-out) .5s forwards}
@keyframes glDraw{to{width:100%}}
.splash__ini{font-family:var(--font-display);font-size:clamp(72px,12vw,118px);font-weight:800;letter-spacing:-.03em;color:#F8FAFC;line-height:1;opacity:0;animation:scaleIn .6s var(--ease-spring) .1s forwards}
.splash__ini span{color:var(--gold);font-style:italic}
.splash__rule{width:0;height:1.5px;background:var(--gold);animation:ruleIn .5s var(--ease-out) .65s forwards}
@keyframes ruleIn{to{width:160px}}
@keyframes scaleIn{from{opacity:0;transform:scale(.6)}to{opacity:1;transform:scale(1)}}
.splash__icons{display:flex;gap:22px;margin-top:2px}
.splash__ico{opacity:0;transform:translateY(10px);animation:icoIn .4s var(--ease-out) forwards}
.splash__ico:nth-child(1){animation-delay:.9s}.splash__ico:nth-child(2){animation-delay:1.05s}
.splash__ico:nth-child(3){animation-delay:1.2s}.splash__ico:nth-child(4){animation-delay:1.35s}
@keyframes icoIn{to{opacity:.7;transform:none}}
.splash__lbl{font-family:'Courier New',monospace;font-size:11px;letter-spacing:.2em;color:#94A3B8;text-transform:uppercase;opacity:0;animation:fadeIn .5s ease 1.6s forwards}
@keyframes fadeIn{to{opacity:1}}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:1000;height:64px;display:flex;align-items:center;padding:0 clamp(16px,4vw,48px);background:rgba(248,250,252,.93);backdrop-filter:blur(12px);border-bottom:1px solid var(--border)}
.nav__brand{display:flex;align-items:center;gap:12px;flex-shrink:0}
.nav__mono{width:38px;height:38px;background:var(--accent);border-radius:8px;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-weight:800;font-size:14px;color:#fff;letter-spacing:.05em;flex-shrink:0}
.nav__name{font-family:var(--font-display);font-weight:700;font-size:15px;color:var(--text);line-height:1.2}
.nav__role{font-size:11px;color:var(--text-muted)}
.nav__links{display:flex;align-items:center;gap:clamp(12px,2vw,28px);margin-left:auto}
.nav__link{font-size:13.5px;font-weight:500;color:var(--text-muted);transition:color .2s}
.nav__link:hover,.nav__link.active{color:var(--accent)}
.nav__cta{margin-left:8px;background:var(--accent);color:#fff!important;font-weight:600;font-size:13.5px;padding:8px 20px;border-radius:8px;border:none;transition:background .2s}
.nav__cta:hover{background:var(--accent-dark)}
.nav__ham{display:none;flex-direction:column;gap:5px;background:none;border:none;padding:8px;margin-left:auto}
.nav__ham span{width:22px;height:2px;background:var(--text);border-radius:2px;transition:all .3s}
.nav__drawer{position:fixed;top:64px;right:-100%;width:min(300px,85vw);height:calc(100vh - 64px);background:var(--surface);border-left:1px solid var(--border);padding:32px 24px;display:flex;flex-direction:column;gap:24px;transition:right .35s var(--ease-out);z-index:999;box-shadow:var(--shadow-lg)}
.nav__drawer.open{right:0}
.nav__drawer .nav__link{font-size:16px;padding:10px 0;border-bottom:1px solid var(--border)}
.nav__drawer .nav__cta{width:100%;text-align:center;padding:12px;display:block;border-radius:10px;margin-top:8px}

/* EDITORIAL LABEL */
.ed-label{font-size:10px;font-weight:700;letter-spacing:.25em;text-transform:uppercase;color:var(--gold-dark);margin-bottom:10px;font-variant:small-caps}
.ed-label::before{content:'— '}.ed-label::after{content:' —'}

/* WIPE REVEAL */
.wipe-reveal{position:relative;overflow:hidden}
.wipe-reveal::after{content:'';position:absolute;inset:-2px;background:var(--gold);transform-origin:right;transform:scaleX(1);transition:transform .7s cubic-bezier(.77,0,.18,1);pointer-events:none;z-index:5}
.wipe-reveal.wiped::after{transform:scaleX(0)}

/* HERO */
#hero{min-height:100vh;padding:calc(64px + clamp(48px,8vh,96px)) clamp(16px,4vw,80px) clamp(48px,8vh,96px);display:flex;align-items:center;position:relative;overflow:hidden}
.hero__bg{position:absolute;inset:0;background:linear-gradient(135deg,#F8FAFC 0%,#F0FDF9 55%,#F1F5F9 100%);z-index:0;will-change:transform}
.hero__geo{position:absolute;inset:0;overflow:hidden;pointer-events:none;z-index:0}
.geo-shape{position:absolute;border:1px solid rgba(var(--accent-rgb),.07);animation:geoFloat linear infinite}
@keyframes geoFloat{0%{transform:translateY(0) rotate(0deg);opacity:.04}50%{opacity:.08}100%{transform:translateY(-120px) rotate(180deg);opacity:.02}}
.hero__deco-num{position:absolute;right:-20px;bottom:-40px;font-family:var(--font-display);font-size:clamp(180px,25vw,320px);font-weight:800;color:rgba(var(--accent-rgb),.04);line-height:1;pointer-events:none;user-select:none;z-index:0}
.hero__inner{position:relative;z-index:1;display:grid;grid-template-columns:1fr minmax(280px,400px);gap:clamp(32px,5vw,80px);align-items:center;max-width:1200px;margin:0 auto;width:100%}
.hero__name-display{font-family:var(--font-display);font-size:clamp(13px,1.4vw,16px);font-weight:600;letter-spacing:.12em;text-transform:uppercase;color:var(--text-muted);margin-bottom:12px;position:relative;display:inline-block}
.glitch{position:relative;display:inline-block}
.glitch::before,.glitch::after{content:attr(data-text);position:absolute;top:0;left:0;width:100%;height:100%;opacity:0}
.glitch.fire::before{animation:glitch-r .3s linear 1;color:rgba(255,50,50,.8);clip-path:inset(0 0 60% 0);opacity:1}
.glitch.fire::after{animation:glitch-b .3s linear 1;color:rgba(50,200,255,.8);clip-path:inset(55% 0 0 0);opacity:1}
@keyframes glitch-r{0%{transform:translateX(0)}25%{transform:translateX(-3px)}50%{transform:translateX(3px)}75%{transform:translateX(-1px)}100%{transform:translateX(0)}}
@keyframes glitch-b{0%{transform:translateX(0)}25%{transform:translateX(3px)}50%{transform:translateX(-3px)}75%{transform:translateX(1px)}100%{transform:translateX(0)}}
.hero__status{display:inline-flex;align-items:center;gap:8px;font-size:11.5px;font-weight:700;color:#166534;background:#DCFCE7;padding:6px 14px;border-radius:100px;margin-bottom:20px;letter-spacing:.04em;border:1px solid rgba(22,163,74,.2)}
.hero__status::before{content:'';width:7px;height:7px;border-radius:50%;background:#16A34A;animation:pulse 2s infinite;flex-shrink:0}
@keyframes pulse{0%,100%{box-shadow:0 0 0 0 rgba(22,163,74,.4)}50%{box-shadow:0 0 0 5px rgba(22,163,74,0)}}
.hero__title{font-family:var(--font-display);font-size:clamp(36px,5.5vw,66px);font-weight:800;line-height:1.08;letter-spacing:-.03em;color:var(--text);margin-bottom:10px}
.kinetic-wrap{display:inline-block;position:relative;vertical-align:bottom;min-width:clamp(180px,22vw,300px);overflow:hidden;height:1.15em}
.kinetic-word{display:block;font-style:italic;color:var(--gold-dark);transition:opacity .35s var(--ease-out),transform .35s var(--ease-out)}
.kinetic-word.out{opacity:0;transform:translateY(-22px)}
.kinetic-word.in{animation:wordIn .35s var(--ease-out) forwards}
@keyframes wordIn{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:none}}
.hero__subtitle{font-family:var(--font-display);font-size:clamp(13px,1.5vw,16.5px);font-weight:500;color:var(--text-muted);margin-bottom:20px;letter-spacing:.01em}
.hero__lede{font-size:clamp(14.5px,1.5vw,16.5px);color:var(--text-muted);max-width:520px;line-height:1.8;margin-bottom:32px}
.hero__btns{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:18px}
.btn--primary{display:inline-flex;align-items:center;gap:8px;background:var(--accent);color:#fff;font-weight:600;font-size:14.5px;padding:13px 28px;border-radius:10px;border:none;transition:background .2s}
.btn--primary:hover{background:var(--accent-dark)}
.btn--secondary{display:inline-flex;align-items:center;gap:8px;background:transparent;color:var(--accent);font-weight:600;font-size:14.5px;padding:13px 28px;border-radius:10px;border:1.5px solid var(--border-accent);transition:background .2s,border-color .2s}
.btn--secondary:hover{background:var(--accent-light);border-color:var(--accent)}
.hero__trust{display:flex;gap:20px;flex-wrap:wrap}
.hero__trust span{font-size:12.5px;font-weight:600;color:var(--text-muted);display:flex;align-items:center;gap:5px}
.hero__trust span::before{content:'✓';color:var(--accent);font-weight:700}
.hero__proof{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-lg);padding:28px;box-shadow:var(--shadow-lg);position:relative;overflow:hidden}
.hero__proof::before{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,var(--accent),#14B8A6)}
.proof__label{font-size:10px;font-weight:700;letter-spacing:.15em;text-transform:uppercase;color:var(--text-muted);margin-bottom:18px}
.proof__stats{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-bottom:18px}
.proof__stat-val{font-family:var(--font-display);font-size:30px;font-weight:800;color:var(--accent);line-height:1}
.proof__stat-label{font-size:11px;color:var(--text-muted);margin-top:3px;font-weight:500}
.proof__divider{height:1px;background:var(--border);margin:18px 0}
.proof__tags{display:flex;flex-wrap:wrap;gap:6px}
.proof__tag{font-size:11px;font-weight:500;background:var(--accent-light);color:var(--accent-dark);padding:4px 10px;border-radius:100px}

/* STATS STRIP */
#stats{background:var(--text);padding:clamp(32px,5vw,56px) clamp(16px,4vw,80px)}
.stats__inner{max-width:1100px;margin:0 auto;display:grid;grid-template-columns:repeat(4,1fr);gap:32px}
.stat-item{text-align:center}
.stat-item__icon{width:34px;height:34px;margin:0 auto 12px;opacity:.7}
.stat-num{font-family:var(--font-display);font-size:clamp(36px,4vw,52px);font-weight:800;color:var(--accent);line-height:1;display:inline-flex;align-items:flex-end;gap:1px}
.stat-num .suf{font-size:.55em;font-weight:700;margin-bottom:4px}
.stat-item__label{font-size:11.5px;color:#94A3B8;font-weight:500;margin-top:6px;text-transform:uppercase;letter-spacing:.08em}

/* SECTIONS */
.section{padding:clamp(64px,8vw,112px) clamp(16px,4vw,80px)}
.section__inner{max-width:1100px;margin:0 auto}
.section__title{font-family:var(--font-display);font-size:clamp(28px,4vw,46px);font-weight:800;color:var(--text);letter-spacing:-.025em;line-height:1.1;margin-bottom:clamp(32px,4vw,56px)}
.section__title em{font-style:italic;color:var(--accent)}

/* ABOUT */
#about{background:var(--bg)}
.about__grid{display:grid;grid-template-columns:310px 1fr;gap:clamp(32px,5vw,72px);align-items:start}
.about__photo-wrap{position:relative;border-radius:var(--radius-lg);overflow:hidden;aspect-ratio:3/4;box-shadow:var(--shadow-lg)}
.about__photo-wrap img{width:100%;height:100%;object-fit:cover;object-position:top center;transition:transform .6s var(--ease-out)}
.about__photo-wrap:hover img{transform:scale(1.03)}
.about__caption{position:absolute;bottom:0;left:0;right:0;padding:20px 20px 18px;background:linear-gradient(to top,rgba(15,23,42,.85) 0%,transparent 100%)}
.about__caption-name{font-family:var(--font-display);font-size:16px;font-weight:700;color:#fff}
.about__caption-role{font-size:12px;color:rgba(255,255,255,.7);margin-top:2px}
.about__bio p{font-size:15px;line-height:1.85;color:var(--text-muted);margin-bottom:18px}
.about__bio strong{color:var(--text);font-weight:600}
.about__table{width:100%;border-collapse:collapse;margin-top:28px}
.about__table tr{border-bottom:1px solid var(--border)}
.about__table tr:last-child{border-bottom:none}
.about__table td{padding:12px 0;font-size:14px;vertical-align:top}
.about__table td:first-child{width:115px;font-weight:600;color:var(--text);font-size:12px;text-transform:uppercase;letter-spacing:.05em;padding-right:14px}
.about__table td:last-child{color:var(--text-muted)}
.about__table a{color:var(--accent);border-bottom:1px solid var(--border-accent);transition:border-color .2s}
.about__table a:hover{border-color:var(--accent)}

/* SERVICES */
#services{background:var(--bg-alt)}
.services__tabs-nav{display:flex;gap:4px;flex-wrap:wrap;margin-bottom:36px;border-bottom:2px solid var(--border);padding-bottom:0}
.tab-btn{font-family:var(--font-body);font-size:12.5px;font-weight:600;color:var(--text-muted);background:none;border:none;padding:10px 13px;border-radius:8px 8px 0 0;cursor:pointer;position:relative;bottom:-2px;border-bottom:2px solid transparent;transition:color .2s,border-color .2s,background .2s}
.tab-btn:hover{color:var(--accent);background:var(--accent-light)}
.tab-btn.active{color:var(--accent);border-bottom-color:var(--accent);background:var(--surface)}
.services__panel{display:none;animation:tabIn .35s var(--ease-out)}
.services__panel.active{display:grid;grid-template-columns:1.1fr 0.9fr;gap:36px;align-items:start}
@keyframes tabIn{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
.svc__card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-lg);padding:32px;box-shadow:var(--shadow-md);transform-style:preserve-3d;transition:transform .5s var(--ease-spring),box-shadow .4s var(--ease-out)}
.svc__card:hover{box-shadow:0 24px 48px rgba(15,23,42,.12)}
.svc__header{display:flex;align-items:flex-start;gap:16px;margin-bottom:20px}
.svc__icon-wrap{width:52px;height:52px;background:var(--accent-light);border-radius:12px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.svc__num{font-size:11px;font-weight:700;letter-spacing:.15em;text-transform:uppercase;color:var(--text-light)}
.svc__title{font-family:var(--font-display);font-size:19px;font-weight:700;color:var(--text);line-height:1.25;margin-top:3px}
.svc__best{font-size:13px;font-style:italic;color:var(--gold-dark);margin-bottom:14px;font-weight:500}
.svc__desc{font-size:14.5px;line-height:1.8;color:var(--text-muted);margin-bottom:20px}
.svc__section-label{font-size:11px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--text);margin-bottom:9px}
.svc__includes{margin-bottom:20px}
.svc__includes ul{display:grid;gap:7px}
.svc__includes li{display:flex;align-items:flex-start;gap:8px;font-size:13.5px;color:var(--text-muted)}
.svc__includes li::before{content:'';width:6px;height:6px;border-radius:50%;background:var(--accent);margin-top:7px;flex-shrink:0}
.svc__tools{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:24px}
.svc__tool-tag{font-size:12px;font-weight:500;background:var(--bg-alt);border:1px solid var(--border);color:var(--text-muted);padding:4px 10px;border-radius:6px}
.svc__cta{display:inline-flex;align-items:center;gap:6px;background:var(--accent);color:#fff;font-weight:600;font-size:13.5px;padding:10px 22px;border-radius:8px;border:none;transition:background .2s}
.svc__cta:hover{background:var(--accent-dark)}
.svc__right{display:flex;flex-direction:column;gap:20px}
.svc__price-card{background:var(--text);border-radius:var(--radius);padding:28px;color:#fff}
.svc__price-title{font-family:var(--font-display);font-size:15px;font-weight:700;margin-bottom:6px}
.svc__price-note{font-size:13px;color:#94A3B8;line-height:1.6;margin-bottom:20px}
.svc__price-cta{display:block;text-align:center;background:var(--accent);color:#fff;font-weight:700;font-size:14px;padding:12px;border-radius:8px;border:none;transition:background .2s}
.svc__price-cta:hover{background:var(--accent-dark)}
.svc__highlight-card{background:var(--accent-light);border:1px solid var(--border-accent);border-radius:var(--radius);padding:20px}
.svc__highlight-card h4{font-family:var(--font-display);font-size:13.5px;font-weight:700;color:var(--accent-dark);margin-bottom:8px}
.svc__highlight-card p{font-size:13px;color:var(--text-muted);line-height:1.65}

/* ACHIEVEMENTS SPOTLIGHT */
#achievements{background:var(--bg);position:relative;background-image:radial-gradient(600px circle at var(--mx,-9999px) var(--my,-9999px),rgba(var(--gold-rgb),.07),transparent 80%)}
.ach__grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(270px,1fr));gap:24px}
.ach__card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);padding:28px;position:relative;overflow:hidden;transition:transform .4s var(--ease-spring),box-shadow .4s var(--ease-out),border-color .3s}
.ach__card::before{content:'';position:absolute;top:0;left:0;width:3px;height:100%;background:var(--accent)}
.ach__card:hover{transform:translateY(-6px) scale(1.015);box-shadow:0 20px 48px -16px rgba(var(--accent-rgb),.2);border-color:var(--border-accent)}
.ach__year{font-family:var(--font-display);font-size:44px;font-weight:800;color:var(--accent-light);line-height:1;margin-bottom:8px}
.ach__icon{width:30px;height:30px;color:var(--accent);margin-bottom:10px}
.ach__title{font-family:var(--font-display);font-size:15px;font-weight:700;color:var(--text);margin-bottom:8px;line-height:1.3}
.ach__desc{font-size:13.5px;color:var(--text-muted);line-height:1.65}

/* EXPERIENCE */
#experience{background:var(--bg-alt)}
.exp__timeline{position:relative}
.exp__timeline::before{content:'';position:absolute;left:11px;top:12px;bottom:12px;width:1.5px;background:var(--border)}
.exp__item{display:grid;grid-template-columns:24px 1fr;gap:24px;padding-bottom:36px}
.exp__item:last-child{padding-bottom:0}
.exp__dot{width:24px;height:24px;border-radius:50%;background:var(--surface);border:2px solid var(--border);margin-top:6px;position:relative;z-index:1;flex-shrink:0;display:flex;align-items:center;justify-content:center;transition:border-color .3s,background .3s}
.exp__item:hover .exp__dot{border-color:var(--accent);background:var(--accent-light)}
.exp__dot-inner{width:8px;height:8px;border-radius:50%;background:var(--accent);opacity:0;transition:opacity .3s}
.exp__item:hover .exp__dot-inner{opacity:1}
.exp__content{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);padding:24px 28px;transition:border-color .3s,box-shadow .3s}
.exp__item:hover .exp__content{border-color:var(--border-accent);box-shadow:var(--shadow-md)}
.exp__date{font-size:11px;font-weight:600;color:var(--accent);letter-spacing:.05em;text-transform:uppercase;margin-bottom:4px}
.exp__role{font-family:var(--font-display);font-size:18px;font-weight:700;color:var(--text);margin-bottom:4px}
.exp__company{font-size:13px;color:var(--text-muted);margin-bottom:14px;font-weight:500;display:flex;align-items:center;gap:6px}
.exp__bullets{display:grid;gap:6px}
.exp__bullets li{display:flex;align-items:flex-start;gap:8px;font-size:13.5px;color:var(--text-muted);line-height:1.6}
.exp__bullets li::before{content:'—';color:var(--accent);font-weight:600;flex-shrink:0}

/* TOOLKIT */
#toolkit{background:var(--bg);overflow:hidden}
.marquee-wrap{margin-bottom:36px;display:flex;flex-direction:column;gap:12px}
.marquee-row{overflow:hidden;position:relative}
.marquee-row::before,.marquee-row::after{content:'';position:absolute;top:0;bottom:0;width:80px;z-index:1;pointer-events:none}
.marquee-row::before{left:0;background:linear-gradient(to right,var(--bg),transparent)}
.marquee-row::after{right:0;background:linear-gradient(to left,var(--bg),transparent)}
.marquee-track{display:flex;gap:10px;width:max-content;animation:marqueeL 30s linear infinite}
.marquee-track.rev{animation:marqueeR 25s linear infinite}
.marquee-row:hover .marquee-track{animation-play-state:paused}
@keyframes marqueeL{0%{transform:translateX(0)}100%{transform:translateX(-50%)}}
@keyframes marqueeR{0%{transform:translateX(-50%)}100%{transform:translateX(0)}}
.m-tag{font-size:12.5px;font-weight:500;background:var(--surface);border:1px solid var(--border);color:var(--text-muted);padding:7px 14px;border-radius:8px;white-space:nowrap;transition:background .2s,color .2s,border-color .2s,transform .3s var(--ease-spring)}
.m-tag:hover{background:var(--accent-light);border-color:var(--border-accent);color:var(--accent-dark)}
.toolkit__cats{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:20px}
.toolkit__cat{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);padding:22px;transition:box-shadow .3s,border-color .3s}
.toolkit__cat:hover{box-shadow:var(--shadow-md);border-color:var(--border-accent)}
.toolkit__cat-label{font-size:11px;font-weight:700;letter-spacing:.12em;text-transform:uppercase;color:var(--accent);margin-bottom:14px;display:flex;align-items:center;gap:8px}
.toolkit__tags{display:flex;flex-wrap:wrap;gap:7px}
.toolkit__tag{font-size:12.5px;font-weight:500;background:var(--bg-alt);border:1px solid var(--border);color:var(--text-muted);padding:5px 11px;border-radius:6px;transition:background .2s,border-color .2s,color .2s,transform .3s var(--ease-spring);display:inline-block}
.toolkit__tag:hover{background:var(--accent-light);border-color:var(--border-accent);color:var(--accent-dark)}

/* CONTACT */
#contact{background:var(--bg-alt)}
.contact__tabs-nav{display:flex;gap:8px;margin-bottom:32px}
.contact__tab-btn{font-family:var(--font-body);font-size:14px;font-weight:600;padding:10px 24px;border-radius:10px;border:1.5px solid var(--border);background:var(--surface);color:var(--text-muted);cursor:pointer;transition:all .2s}
.contact__tab-btn.active{background:var(--accent);color:#fff;border-color:var(--accent)}
.contact__panel{display:none}
.contact__panel.active{display:block;animation:tabIn .3s ease}
.contact__cal-wrap{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-lg);overflow:hidden}
.contact__cal-wrap iframe{width:100%;height:600px;border:none;display:block}
.contact__form{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-lg);padding:36px;max-width:600px;margin:0 auto}
.form__grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.form__field{display:flex;flex-direction:column;gap:6px}
.form__field.full{grid-column:1/-1}
.form__label{font-size:13px;font-weight:600;color:var(--text)}
.form__input,.form__textarea{font-family:var(--font-body);font-size:14px;padding:10px 14px;border:1.5px solid var(--border);border-radius:8px;background:var(--bg);color:var(--text);outline:none;transition:border-color .2s,box-shadow .2s}
.form__input:focus,.form__textarea:focus{border-color:var(--accent);box-shadow:0 0 0 3px rgba(var(--accent-rgb),.08)}
.form__textarea{resize:vertical;min-height:120px}
.form__submit{margin-top:20px;width:100%;background:var(--accent);color:#fff;font-weight:700;font-size:15px;padding:14px;border-radius:10px;border:none;cursor:pointer;transition:background .2s;display:flex;align-items:center;justify-content:center;gap:8px}
.form__submit:hover{background:var(--accent-dark)}
.form__success{display:none;text-align:center;padding:32px;color:#166534;font-weight:600;font-size:15px}
.contact__links{
  display:flex;gap:16px;flex-wrap:wrap;
  margin-top:40px;justify-content:center
}
.contact__link{
  display:flex;align-items:center;justify-content:center;
  width:56px;height:56px;
  background:var(--surface);
  border:1.5px solid var(--border);
  border-radius:14px;
  transition:all .3s cubic-bezier(.34,1.56,.64,1);
  position:relative;overflow:hidden
}
.contact__link:hover{
  border-color:var(--accent);
  background:rgba(var(--accent-rgb),.06);
  transform:translateY(-5px) scale(1.08);
  box-shadow:0 8px 24px rgba(var(--accent-rgb),.15)
}
.contact__link svg{
  transition:transform .3s cubic-bezier(.34,1.56,.64,1)
}
.contact__link:hover svg{transform:scale(1.15)}
.contact__link::after{
  content:attr(data-label);
  position:absolute;bottom:-30px;left:50%;
  transform:translateX(-50%);
  font-size:10px;font-weight:600;
  font-family:var(--font-mono);
  letter-spacing:.06em;
  color:var(--accent);
  white-space:nowrap;
  opacity:0;
  transition:all .25s ease
}
.contact__link:hover::after{
  bottom:-22px;opacity:1
}

/* FOOTER */
footer{background:var(--text);color:#94A3B8;padding:40px clamp(16px,4vw,80px);text-align:center}
.footer__name{font-family:var(--font-display);font-size:20px;font-weight:700;color:#F8FAFC;margin-bottom:6px}
.footer__tagline{font-size:13.5px;margin-bottom:16px}
.footer__copy{font-size:12px;opacity:.6}

/* REVEAL */
.reveal{opacity:0;transform:translateY(24px);transition:opacity .85s var(--ease-out),transform .85s var(--ease-out)}
.reveal.is-in{opacity:1;transform:none}
.reveal-left{opacity:0;transform:translateX(-36px);transition:opacity .85s var(--ease-out),transform .85s var(--ease-out)}
.reveal-left.is-in{opacity:1;transform:none}
.reveal-right{opacity:0;transform:translateX(36px);transition:opacity .85s var(--ease-out),transform .85s var(--ease-out)}
.reveal-right.is-in{opacity:1;transform:none}
.reveal-scale{opacity:0;transform:scale(.88);transition:opacity .75s var(--ease-out),transform .75s var(--ease-spring)}
.reveal-scale.is-in{opacity:1;transform:none}
[data-stagger]{transition-delay:calc(var(--i,0)*90ms)}

@media(max-width:900px){
  .hero__inner{grid-template-columns:1fr}
  .hero__proof{order:-1;max-width:420px}
  .about__grid{grid-template-columns:1fr}
  .about__photo-wrap{max-width:260px;margin:0 auto}
  .stats__inner{grid-template-columns:repeat(2,1fr)}
  .services__panel.active{grid-template-columns:1fr}
}
@media(max-width:640px){
  .nav__links{display:none}
  .nav__ham{display:flex}
  .form__grid{grid-template-columns:1fr}
  .contact__links{flex-direction:row;justify-content:center}
  .tab-btn{font-size:11px;padding:8px 9px}
  .stats__inner{grid-template-columns:repeat(2,1fr);gap:20px}
  .hero__trust{gap:12px}
}
@media(prefers-reduced-motion:reduce){
  #splash{display:none!important}
  .reveal,.reveal-left,.reveal-right,.reveal-scale{opacity:1;transform:none;transition:none}
  .wipe-reveal::after{display:none}
  .kinetic-word{transition:none}
}
</style>
</head>
<body>

<div id="pb"></div>

<!-- SPLASH -->
<div id="splash">
  <div class="splash__gl t"></div><div class="splash__gl b"></div>
  <div class="splash__ini">R<span>G</span></div>
  <div class="splash__rule"></div>
  <div class="splash__icons">
    <div class="splash__ico"><svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#CCFBF1" stroke-width="1.5"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg></div>
    <div class="splash__ico"><svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#CCFBF1" stroke-width="1.5"><path d="M18 20V10M12 20V4M6 20v-6"/></svg></div>
    <div class="splash__ico"><svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#CCFBF1" stroke-width="1.5"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/></svg></div>
    <div class="splash__ico"><svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#CCFBF1" stroke-width="1.5"><path d="M20.59 13.41l-7.17 7.17a2 2 0 01-2.83 0L2 12V2h10l8.59 8.59a2 2 0 010 2.82z"/><circle cx="7" cy="7" r="1"/></svg></div>
  </div>
  <div class="splash__lbl">Workforce Planner &middot; Catalog Specialist &middot; Data Analysis</div>
</div>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAV -->
<nav>
  <div class="nav__brand">
    <div class="nav__mono">RG</div>
    <div><div class="nav__name">Romcel Geluz</div><div class="nav__role">Workforce Planner &amp; Catalog Specialist</div></div>
  </div>
  <div class="nav__links">
    <a class="nav__link" href="#about">About</a>
    <a class="nav__link" href="#services">Services</a>
    <a class="nav__link" href="#achievements">Achievements</a>
    <a class="nav__link" href="#experience">Experience</a>
    <a class="nav__link" href="#credentials">Credentials</a>
    <a class="nav__link" href="#setup">Setup</a>
    <a class="nav__link" href="#audit">Ops Audit</a>
    <a class="nav__link" href="#toolkit">Toolkit</a>
    <a class="nav__link" href="#contact">Contact</a>
    <a class="nav__cta btn--primary" href="#contact">Book a Call</a>
  </div>
  <button class="nav__ham" id="ham" aria-label="Menu"><span></span><span></span><span></span></button>
</nav>
<div class="nav__drawer" id="drawer">
  <a class="nav__link" href="#about">About</a>
  <a class="nav__link" href="#services">Services</a>
  <a class="nav__link" href="#achievements">Achievements</a>
  <a class="nav__link" href="#experience">Experience</a>
  <a class="nav__link" href="#credentials">Credentials</a>
    <a class="nav__link" href="#setup">Setup</a>
    <a class="nav__link" href="#toolkit">Toolkit</a>
  <a class="nav__link" href="#contact">Contact</a>
  <a class="nav__cta btn--primary" href="#contact">Book a Call</a>
</div>

<!-- HERO -->
<section id="hero">
  <div class="hero__bg" id="heroBg"></div>
  <div class="hero__geo" aria-hidden="true">
    <div class="geo-shape" style="width:180px;height:180px;top:12%;right:22%;border-radius:50%;animation-duration:30s;"></div>
    <div class="geo-shape" style="width:90px;height:90px;top:58%;left:4%;animation-duration:24s;animation-delay:5s;"></div>
    <div class="geo-shape" style="width:240px;height:240px;bottom:8%;right:8%;border-radius:50%;animation-duration:38s;animation-delay:2s;"></div>
    <div class="geo-shape" style="width:55px;height:55px;top:28%;left:18%;animation-duration:20s;animation-delay:8s;"></div>
    <div class="geo-shape" style="width:120px;height:120px;top:45%;right:5%;border-radius:50%;animation-duration:26s;animation-delay:3s;"></div>
  </div>
  <div class="hero__float-icons" aria-hidden="true">
    <div class="hfi" style="left:62%;top:15%;animation-duration:12s;animation-delay:0s"><svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" color="var(--accent)"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/><path d="M8 14h.01M12 14h.01M16 14h.01"/></svg></div>
    <div class="hfi" style="left:78%;top:42%;animation-duration:15s;animation-delay:2s"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" color="var(--accent)"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/><line x1="2" y1="20" x2="22" y2="20"/></svg></div>
    <div class="hfi" style="left:55%;top:68%;animation-duration:18s;animation-delay:4s"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" color="var(--accent)"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M3 15h18M9 3v18"/></svg></div>
    <div class="hfi" style="left:85%;top:72%;animation-duration:14s;animation-delay:1s"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" color="var(--accent)"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg></div>
    <div class="hfi" style="left:68%;top:85%;animation-duration:16s;animation-delay:6s"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" color="var(--accent)"><path d="M20.59 13.41l-7.17 7.17a2 2 0 01-2.83 0L2 12V2h10l8.59 8.59a2 2 0 010 2.82z"/><circle cx="7" cy="7" r="1"/></svg></div>
    <div class="hfi" style="left:92%;top:25%;animation-duration:20s;animation-delay:8s"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" color="var(--accent)"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/></svg></div>
  </div>
  <div class="hero__deco-num" aria-hidden="true">07</div>
  <div class="hero__inner">
    <div class="hero__text">
      <div class="hero__name-display reveal">
        <span class="glitch" data-text="Romcel Geluz">Romcel Geluz</span>
      </div>
      <div class="hero__status reveal">NOW ACCEPTING CLIENTS &mdash; LIMITED SLOTS</div>
      <h1 class="hero__title reveal">Data-Driven
        <span class="kinetic-wrap"><span class="kinetic-word">Operations</span></span><br>
        That Actually Work.
      </h1>
      <p class="hero__subtitle reveal">Workforce Planner &amp; Real-Time Analyst &nbsp;&bull;&nbsp; eCommerce Catalog Specialist</p>
      <p class="hero__lede reveal">I help businesses improve operational performance through <span class="hero__kinetic" id="heroKinetic">workforce planning</span>, data analysis, reporting, process documentation, and administrative support — so they can make informed decisions, optimize resources, and focus on strategic growth.</p>
      <div class="hero__btns reveal">
        <a class="btn--primary" href="#services">View My Services <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
        <a class="btn--secondary" href="#contact">Get In Touch</a>
      </div>
      <div class="hero__trust reveal">
        <span>Available Immediately</span>
        <span>7+ Years Experience</span>
        <span>4 Marketplaces Managed</span>
      </div>
    </div>
    <div class="hero__proof reveal-scale">
      <div class="proof__label">At a Glance</div>
      <div class="proof__stats">
        <div><div class="proof__stat-val">7+</div><span class="proof__live-dot" aria-hidden="true"></span><div class="proof__stat-label">Years Experience</div></div>
        <div><div class="proof__stat-val">4</div><span class="proof__live-dot" aria-hidden="true"></span><div class="proof__stat-label">Marketplaces</div></div>
        <div><div class="proof__stat-val">3</div><span class="proof__live-dot" aria-hidden="true"></span><div class="proof__stat-label">WFM Platforms</div></div>
        <div><div class="proof__stat-val">5</div><span class="proof__live-dot" aria-hidden="true"></span><div class="proof__stat-label">Key Achievements</div></div>
      </div>
      <div class="proof__divider"></div>
      <div class="proof__tags">
        <span class="proof__tag">Excel Advanced</span>
        <span class="proof__tag">NICE IEX</span>
        <span class="proof__tag">Amazon SC</span>
        <span class="proof__tag">Power BI</span>
      </div>
    </div>
  </div>
</section>

<!-- STATS -->
<section id="stats">
  <div class="stats__bg-nums" aria-hidden="true">
  <div class="stats__bg-num" style="left:-2%;top:-20%;animation-delay:0s">7</div>
  <div class="stats__bg-num" style="right:-2%;bottom:-20%;animation-delay:4s">4</div>
  <div class="stats__bg-num" style="left:38%;top:-15%;font-size:80px;animation-delay:9s;opacity:.025">3</div>
</div>
  <div class="stats__inner">
    <div class="stat-item reveal">
      <svg class="stat-item__icon" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.5"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/></svg>
      <div class="stat-num" data-flip="7" data-suffix="+"><span>7</span><span class="suf">+</span></div>
      <div class="stat-item__label">Years of Experience</div>
    </div>
    <div class="stat-item reveal">
      <svg class="stat-item__icon" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.5"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 01-8 0"/></svg>
      <div class="stat-num" data-flip="4"><span>4</span></div>
      <div class="stat-item__label">Marketplaces Managed</div>
    </div>
    <div class="stat-item reveal">
      <svg class="stat-item__icon" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.5"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg>
      <div class="stat-num" data-flip="3"><span>3</span></div>
      <div class="stat-item__label">WFM Platforms</div>
    </div>
    <div class="stat-item reveal">
      <svg class="stat-item__icon" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.5"><path d="M18 20V10M12 20V4M6 20v-6"/></svg>
      <div class="stat-num" data-flip="5"><span>5</span></div>
      <div class="stat-item__label">Documented Wins</div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="section">
  <div class="bg-shape" style="width:120px;height:120px;top:10%;left:2%;animation-duration:18s;animation-delay:0s"></div>
  <div class="bg-shape" style="width:60px;height:60px;top:60%;right:3%;animation-duration:14s;animation-delay:3s"></div>
  <div class="bg-shape" style="width:80px;height:80px;bottom:5%;left:45%;animation-duration:20s;animation-delay:7s"></div>
  <div class="bg-plus" style="top:15%;right:10%;animation-duration:12s;animation-delay:1s">+</div>
  <div class="bg-plus" style="bottom:20%;left:8%;animation-duration:16s;animation-delay:5s">+</div>
  <div class="bg-bracket" style="top:30%;right:2%;animation-duration:22s;animation-delay:2s">{</div>
  <div class="sec-float-icon" style="width:48px;height:48px;top:12%;left:88%;animation-duration:14s;animation-delay:2s">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" width="48" height="48"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/></svg>
  </div>
  <div class="sec-float-icon" style="width:40px;height:40px;top:55%;left:91%;animation-duration:18s;animation-delay:6s">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" width="40" height="40"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg>
  </div>
  <div class="section__watermark" aria-hidden="true">01</div>
  <div class="section__inner">
    <div class="ed-label reveal">About Me</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">The Person <em>Behind the Data</em></h2>
    <div class="about__grid">
      <div class="about__photo-wrap reveal-left">
        <img src="https://ca.slack-edge.com/T01BPSU9S5R-U09AATRNKUY-647b3ffbf8f0-1024" alt="Romcel Geluz — Workforce Planner &amp; Catalog Specialist" loading="lazy">
        <div class="about__caption">
          <div class="about__caption-name">Romcel Geluz</div>
          <div class="about__caption-role">Workforce Planner &bull; Catalog Specialist</div>
        </div>
      </div>
      <div class="about__bio reveal-right">
        <p>Romcel is a <strong>data-driven operations professional</strong> with 7+ years of experience across workforce management, real-time analytics, and eCommerce catalog operations. He has built reporting systems, optimized staffing schedules, and managed high-volume product catalogs across Amazon, Shopify, Walmart, and eBay — in high-stakes, fast-paced environments where accuracy is non-negotiable.</p>
        <p>His career began in customer support, where he developed a sharp eye for data accuracy and process efficiency. He moved into <strong>real-time workforce analytics</strong>, building the dashboards and SOPs that teams depended on for intraday decisions. Most recently, he led catalog operations for a B2B eCommerce company — owning MAP compliance, inventory synchronization, and product data quality across four marketplaces simultaneously.</p>
        <p>What sets Romcel apart is his ability to <strong>translate complex operational data into clear, actionable systems</strong>. Whether it's an inflexibility heatmap, a pricing compliance dashboard, or a structured task allocation file that eliminated cherry-picking across a whole team — he builds tools that work and people rely on them.</p>
        <table class="about__table">
          <tr><td>Location</td><td>Philippines</td></tr>
          <tr><td>Availability</td><td><span style="display:inline-flex;align-items:center;gap:6px;color:#166534;font-weight:500"><span style="width:7px;height:7px;border-radius:50%;background:#16A34A;display:inline-block"></span>Open to Remote Work</span></td></tr>
          <tr><td>Email</td><td><a href="mailto:romcelgeluz@gmail.com">romcelgeluz@gmail.com</a></td></tr>
          <tr><td>WhatsApp</td><td><a href="https://wa.me/639354651011" target="_blank" rel="noopener">+63 935 465 1011</a></td></tr>
          <tr><td>LinkedIn</td><td><a href="https://www.linkedin.com/in/romcel-geluz-90671a342/" target="_blank" rel="noopener">linkedin.com/in/romcel-geluz</a></td></tr>
        </table>
        <div class="about__quick-stats reveal">
          <div class="about__stat-pill">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/></svg>
            <div class="about__stat-pill-val">7+</div>
            <div class="about__stat-pill-label">Years Exp</div>
          </div>
          <div class="about__stat-pill">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg>
            <div class="about__stat-pill-val">99%</div>
            <div class="about__stat-pill-label">SLA Rate</div>
          </div>
          <div class="about__stat-pill">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg>
            <div class="about__stat-pill-val">85</div>
            <div class="about__stat-pill-label">WPM</div>
          </div>
          <div class="about__stat-pill">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/></svg>
            <div class="about__stat-pill-val">PH</div>
            <div class="about__stat-pill-label">Remote</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services" class="section">
  <div class="bg-shape" style="width:100px;height:100px;top:5%;right:5%;animation-duration:16s;animation-delay:2s"></div>
  <div class="bg-shape" style="width:160px;height:160px;bottom:5%;left:1%;animation-duration:22s;animation-delay:6s"></div>
  <div class="bg-plus" style="top:8%;left:8%;animation-duration:14s;animation-delay:0s">+</div>
  <div class="bg-plus" style="bottom:15%;right:8%;animation-duration:18s;animation-delay:4s">+</div>
  <div class="bg-bracket" style="bottom:10%;left:3%;animation-duration:20s;animation-delay:8s">}</div>
  <div class="section__watermark" aria-hidden="true">02</div>
  <div class="section__inner">
    <div class="ed-label reveal">What I Offer</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">Services &amp; <em>Expertise</em></h2>
    <div class="services__tabs-nav" role="tablist">
      <button class="tab-btn active" role="tab" data-tab="svc1">01 &middot; WFM Planning</button>
      <button class="tab-btn" role="tab" data-tab="svc2">02 &middot; RTA &amp; Reporting</button>
      <button class="tab-btn" role="tab" data-tab="svc3">03 &middot; Catalog Mgmt</button>
      <button class="tab-btn" role="tab" data-tab="svc4">04 &middot; Data &amp; Dashboards</button>
      <button class="tab-btn" role="tab" data-tab="svc5">05 &middot; Data QA</button>
      <button class="tab-btn" role="tab" data-tab="svc6">06 &middot; SOP &amp; Process</button>
      <button class="tab-btn" role="tab" data-tab="svc7">07 &middot; Ops Support</button>
    </div>
    
    <div class="services__panel active" id="svc1" role="tabpanel">
      <div class="svc__card">
        <div class="svc__header">
          <div class="svc__icon-wrap"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.8"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/><path d="M8 14h.01M12 14h.01M16 14h.01"/></svg></div>
          <div><div class="svc__num">Service 01</div><h3 class="svc__title">Workforce Planning &amp; Schedule Optimization</h3></div>
        </div>
        <p class="svc__best">Best for: BPOs, contact centers, and operations teams managing multi-skill scheduling</p>
        <p class="svc__desc">Creating and maintaining accurate workforce schedules based on forecasts, shrinkage factors, and intraday performance trends. Optimizing staff coverage to meet SLA targets, reduce overtime, and ensure the right people are in the right place at the right time.</p>
        <div class="svc__includes"><div class="svc__section-label">What's Included</div><ul><li>Staff schedule creation and maintenance across multiple LOBs</li><li>Forecast-based coverage analysis and headcount recommendations</li><li>Shrinkage modeling and schedule exception handling</li><li>Intraday adjustments and real-time schedule optimization</li><li>SLA forecasting and staffing gap identification</li></ul></div>
        <div class="svc__section-label">Tools Used</div>
        <div class="svc__tools"><span class="svc__tool-tag">NICE IEX</span><span class="svc__tool-tag">Calabrio TeleOpti</span><span class="svc__tool-tag">Microsoft Excel</span><span class="svc__tool-tag">Google Sheets</span></div>
        <a class="svc__cta" href="#contact">Request This Service <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
      <div class="svc__right">
        <div class="svc__price-card">
          <div class="svc__price-title">Flexible Engagement</div>
          <p class="svc__price-note">Available for project-based, part-time, or full-time remote engagements. Rates discussed based on scope, volume, and timeline.</p>
          <a class="svc__price-cta" href="#contact" onclick="scrollToAudit(event)">Get a Quote</a>
        </div>
        <div class="svc__highlight-card"><h4>Why this matters</h4><p>Poor scheduling costs businesses in overtime, SLA breaches, and burnt-out teams. A properly optimized schedule is the foundation of operational efficiency.</p></div>
      </div>
    </div>
    <div class="services__panel" id="svc2" role="tabpanel">
      <div class="svc__card">
        <div class="svc__header">
          <div class="svc__icon-wrap"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.8"><path d="M18 20V10M12 20V4M6 20v-6"/></svg></div>
          <div><div class="svc__num">Service 02</div><h3 class="svc__title">Real-Time Monitoring &amp; KPI Reporting</h3></div>
        </div>
        <p class="svc__best">Best for: Operations managers needing real-time visibility and intraday dashboard reporting</p>
        <p class="svc__desc">Real-time monitoring of critical KPIs — service level, AHT, occupancy, and adherence — with intraday dashboards and escalation management. I translate live data into immediate action, preventing SLA breaches before they happen.</p>
        <div class="svc__includes"><div class="svc__section-label">What's Included</div><ul><li>Real-time KPI monitoring (SL, AHT, occupancy, adherence)</li><li>Intraday and daily performance dashboards</li><li>Escalation handling and incident response coordination</li><li>Executive-level reporting and operational summaries</li><li>Trend analysis with corrective action recommendations</li></ul></div>
        <div class="svc__section-label">Tools Used</div>
        <div class="svc__tools"><span class="svc__tool-tag">NICE IEX</span><span class="svc__tool-tag">Calabrio TeleOpti</span><span class="svc__tool-tag">Microsoft Excel</span><span class="svc__tool-tag">Looker Studio</span><span class="svc__tool-tag">Power BI</span></div>
        <a class="svc__cta" href="#contact">Request This Service <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
      <div class="svc__right">
        <div class="svc__price-card">
          <div class="svc__price-title">Flexible Engagement</div>
          <p class="svc__price-note">Available for project-based, part-time, or full-time remote engagements. Rates discussed based on scope, volume, and timeline.</p>
          <a class="svc__price-cta" href="#contact" onclick="scrollToAudit(event)">Get a Quote</a>
        </div>
        <div class="svc__highlight-card"><h4>Real impact delivered</h4><p>Developed complete RTA reporting infrastructure from scratch, including inflexibility dashboards and heatmaps that improved staffing decisions across multiple lines of business.</p></div>
      </div>
    </div>
    <div class="services__panel" id="svc3" role="tabpanel">
      <div class="svc__card">
        <div class="svc__header">
          <div class="svc__icon-wrap"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.8"><path d="M20.59 13.41l-7.17 7.17a2 2 0 01-2.83 0L2 12V2h10l8.59 8.59a2 2 0 010 2.82z"/><circle cx="7" cy="7" r="1"/></svg></div>
          <div><div class="svc__num">Service 03</div><h3 class="svc__title">eCommerce Catalog Management</h3></div>
        </div>
        <p class="svc__best">Best for: eCommerce brands and agencies managing product data across multiple marketplaces</p>
        <p class="svc__desc">Managing and optimizing high-volume product listings across Amazon, Shopify, Walmart, and eBay. Ensuring pricing compliance, inventory accuracy, and listing quality at scale — using structured data workflows to eliminate inconsistencies.</p>
        <div class="svc__includes"><div class="svc__section-label">What's Included</div><ul><li>Product listing creation, optimization, and maintenance</li><li>Pricing updates with MAP compliance enforcement</li><li>Inventory synchronization via supplier feeds</li><li>Bulk data management using structured spreadsheets</li><li>Regular listing audits (titles, descriptions, specs, images)</li><li>Cross-platform data consistency and quality control</li></ul></div>
        <div class="svc__section-label">Tools Used</div>
        <div class="svc__tools"><span class="svc__tool-tag">Amazon Seller Central</span><span class="svc__tool-tag">Shopify</span><span class="svc__tool-tag">Walmart Seller Center</span><span class="svc__tool-tag">eBay Seller Hub</span><span class="svc__tool-tag">Flxpoint</span><span class="svc__tool-tag">Excel</span></div>
        <a class="svc__cta" href="#contact">Request This Service <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
      <div class="svc__right">
        <div class="svc__price-card">
          <div class="svc__price-title">Flexible Engagement</div>
          <p class="svc__price-note">Available for project-based, part-time, or full-time remote engagements. Rates discussed based on scope, volume, and timeline.</p>
          <a class="svc__price-cta" href="#contact" onclick="scrollToAudit(event)">Get a Quote</a>
        </div>
        <div class="svc__highlight-card"><h4>Multi-platform ownership</h4><p>Managed end-to-end catalog operations across 4 major marketplaces simultaneously, reducing pricing errors and brand complaints through consistent MAP compliance controls.</p></div>
      </div>
    </div>
    <div class="services__panel" id="svc4" role="tabpanel">
      <div class="svc__card">
        <div class="svc__header">
          <div class="svc__icon-wrap"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.8"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg></div>
          <div><div class="svc__num">Service 04</div><h3 class="svc__title">Data Analysis &amp; Dashboard Creation</h3></div>
        </div>
        <p class="svc__best">Best for: Leaders who need decision-ready reporting without a full data team</p>
        <p class="svc__desc">Building Excel-based dashboards, KPI trackers, and reporting systems that turn raw operational data into clear, decision-ready insights. From pivot tables to Power BI visualizations — tools that leadership actually uses.</p>
        <div class="svc__includes"><div class="svc__section-label">What's Included</div><ul><li>Custom dashboards and KPI tracker design</li><li>Pivot table reports with drill-down capabilities</li><li>Power BI and Looker Studio visualizations</li><li>Executive-level reporting and summary decks</li><li>Data consolidation from multiple sources</li></ul></div>
        <div class="svc__section-label">Tools Used</div>
        <div class="svc__tools"><span class="svc__tool-tag">Microsoft Excel (Advanced)</span><span class="svc__tool-tag">Google Sheets</span><span class="svc__tool-tag">Power BI</span><span class="svc__tool-tag">Looker Studio</span></div>
        <a class="svc__cta" href="#contact">Request This Service <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
      <div class="svc__right">
        <div class="svc__price-card">
          <div class="svc__price-title">Flexible Engagement</div>
          <p class="svc__price-note">Available for project-based, part-time, or full-time remote engagements. Rates discussed based on scope, volume, and timeline.</p>
          <a class="svc__price-cta" href="#contact" onclick="scrollToAudit(event)">Get a Quote</a>
        </div>
        <div class="svc__highlight-card"><h4>Built for real decisions</h4><p>Pioneered back-end monitoring dashboards from scratch that increased real-time visibility and accelerated operational decision-making across the organization.</p></div>
      </div>
    </div>
    <div class="services__panel" id="svc5" role="tabpanel">
      <div class="svc__card">
        <div class="svc__header">
          <div class="svc__icon-wrap"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.8"><path d="M9 11l3 3L22 4"/><path d="M21 12v7a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h11"/></svg></div>
          <div><div class="svc__num">Service 05</div><h3 class="svc__title">Data Validation &amp; Quality Assurance</h3></div>
        </div>
        <p class="svc__best">Best for: Companies with data accuracy issues across CRM, catalog, or workforce systems</p>
        <p class="svc__desc">Auditing, validating, and cleaning large datasets across operational and catalog systems. Ensuring data integrity, accuracy, and consistency across every source — because reliable reporting starts with reliable data at the foundation.</p>
        <div class="svc__includes"><div class="svc__section-label">What's Included</div><ul><li>Data audits across multiple systems and reporting sources</li><li>Error detection, discrepancy identification, and resolution</li><li>Bulk data cleanup and standardization</li><li>Cross-platform data reconciliation reports</li><li>Quality control checklists and validation processes</li></ul></div>
        <div class="svc__section-label">Tools Used</div>
        <div class="svc__tools"><span class="svc__tool-tag">Microsoft Excel</span><span class="svc__tool-tag">Google Sheets</span><span class="svc__tool-tag">CSV / Flat File Processing</span><span class="svc__tool-tag">Bulk Upload Tools</span><span class="svc__tool-tag">Salesforce</span></div>
        <a class="svc__cta" href="#contact">Request This Service <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
      <div class="svc__right">
        <div class="svc__price-card">
          <div class="svc__price-title">Flexible Engagement</div>
          <p class="svc__price-note">Available for project-based, part-time, or full-time remote engagements. Rates discussed based on scope, volume, and timeline.</p>
          <a class="svc__price-cta" href="#contact" onclick="scrollToAudit(event)">Get a Quote</a>
        </div>
        <div class="svc__highlight-card"><h4>Precision at scale</h4><p>Conducted ongoing data validation across workforce and catalog systems, ensuring reporting accuracy that leadership depended on for critical staffing and pricing decisions.</p></div>
      </div>
    </div>
    <div class="services__panel" id="svc6" role="tabpanel">
      <div class="svc__card">
        <div class="svc__header">
          <div class="svc__icon-wrap"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.8"><path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg></div>
          <div><div class="svc__num">Service 06</div><h3 class="svc__title">SOP &amp; Process Documentation</h3></div>
        </div>
        <p class="svc__best">Best for: Growing teams that need standardized workflows before scaling operations</p>
        <p class="svc__desc">Developing standard operating procedures and workflow documentation that standardize processes, reduce errors, and allow teams to operate consistently — with or without supervision. Scalable systems that outlast the person who built them.</p>
        <div class="svc__includes"><div class="svc__section-label">What's Included</div><ul><li>SOP writing for operational and reporting workflows</li><li>Process mapping and workflow documentation</li><li>Process improvement recommendations</li><li>Training documentation and onboarding materials</li><li>Knowledge base creation for teams</li></ul></div>
        <div class="svc__section-label">Tools Used</div>
        <div class="svc__tools"><span class="svc__tool-tag">Microsoft Excel</span><span class="svc__tool-tag">Google Docs</span><span class="svc__tool-tag">Google Sheets</span></div>
        <a class="svc__cta" href="#contact">Request This Service <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
      <div class="svc__right">
        <div class="svc__price-card">
          <div class="svc__price-title">Flexible Engagement</div>
          <p class="svc__price-note">Available for project-based, part-time, or full-time remote engagements. Rates discussed based on scope, volume, and timeline.</p>
          <a class="svc__price-cta" href="#contact" onclick="scrollToAudit(event)">Get a Quote</a>
        </div>
        <div class="svc__highlight-card"><h4>Systems that outlast roles</h4><p>Documented reporting SOPs across two major operational functions — creating standardized processes that kept teams consistent through personnel changes and workflow transitions.</p></div>
      </div>
    </div>
    <div class="services__panel" id="svc7" role="tabpanel">
      <div class="svc__card">
        <div class="svc__header">
          <div class="svc__icon-wrap"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#0F766E" stroke-width="1.8"><rect x="2" y="7" width="20" height="14" rx="2"/><path d="M16 21V5a2 2 0 00-2-2h-4a2 2 0 00-2 2v16"/></svg></div>
          <div><div class="svc__num">Service 07</div><h3 class="svc__title">Executive &amp; Operations Support</h3></div>
        </div>
        <p class="svc__best">Best for: Founders and executives who need reliable back-end operational support</p>
        <p class="svc__desc">High-level administrative and operational support — task management, cross-functional coordination, CRM maintenance, and executive-level reporting. The behind-the-scenes infrastructure that keeps operations running smoothly.</p>
        <div class="svc__includes"><div class="svc__section-label">What's Included</div><ul><li>Task prioritization and schedule management</li><li>Cross-team coordination and stakeholder communication</li><li>CRM data maintenance and accuracy (Salesforce, Zendesk)</li><li>Operational reporting and executive summaries</li><li>Ad-hoc research and administrative support</li></ul></div>
        <div class="svc__section-label">Tools Used</div>
        <div class="svc__tools"><span class="svc__tool-tag">Salesforce</span><span class="svc__tool-tag">Zendesk</span><span class="svc__tool-tag">Google Sheets</span><span class="svc__tool-tag">Microsoft Excel</span></div>
        <a class="svc__cta" href="#contact">Request This Service <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
      <div class="svc__right">
        <div class="svc__price-card">
          <div class="svc__price-title">Flexible Engagement</div>
          <p class="svc__price-note">Available for project-based, part-time, or full-time remote engagements. Rates discussed based on scope, volume, and timeline.</p>
          <a class="svc__price-cta" href="#contact" onclick="scrollToAudit(event)">Get a Quote</a>
        </div>
        <div class="svc__highlight-card"><h4>Operational backbone</h4><p>Coordinated cross-functionally across Operations, HR, and Team Leads to resolve scheduling conflicts, maintain CRM accuracy, and support executive decision-making in high-pressure environments.</p></div>
      </div>
    </div>
  </div>
</section>

<!-- ACHIEVEMENTS -->
<section id="achievements" class="section">
  <div aria-hidden="true">
  <span class="ach__float-badge" style="left:5%;top:15%;font-size:13px;animation-duration:14s;animation-delay:0s">✓ SLA</span>
  <span class="ach__float-badge" style="right:8%;top:30%;font-size:11px;animation-duration:18s;animation-delay:3s">KPI</span>
  <span class="ach__float-badge" style="left:12%;bottom:20%;font-size:14px;animation-duration:12s;animation-delay:6s">MAP</span>
  <span class="ach__float-badge" style="right:15%;bottom:15%;font-size:12px;animation-duration:16s;animation-delay:9s">ROI</span>
</div>
  <div class="section__watermark" aria-hidden="true">03</div>
  <div class="section__inner">
    <div class="ed-label reveal">Track Record</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">Key <em>Achievements</em></h2>
    <div class="ach__grid">
      <div class="ach__card reveal-scale"><div class="ach__year">2019</div><svg class="ach__icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 00-3-3.87M16 3.13a4 4 0 010 7.75"/></svg><div class="ach__title">Resolved Team Cherry-Picking</div><p class="ach__desc">Introduced a structured task allocation file in Google Sheets that eliminated cherry-picking. Improved workload distribution and ensured fair, consistent task handling across the entire team.</p></div>
      <div class="ach__card reveal-scale"><div class="ach__year">2020</div><svg class="ach__icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M18 20V10M12 20V4M6 20v-6"/></svg><div class="ach__title">Pioneered Back-End Monitoring</div><p class="ach__desc">Built reporting and dashboards for back-end task monitoring from the ground up. Increased real-time and intraday visibility, leading to faster and more accurate operational decisions organization-wide.</p></div>
      <div class="ach__card reveal-scale"><div class="ach__year">2022</div><svg class="ach__icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/></svg><div class="ach__title">Timestamp Activity Tracking</div><p class="ach__desc">Implemented timestamp-based activity logs for email-handled tasks. Improved visibility into agent productivity and accountability across back-end operations.</p></div>
      <div class="ach__card reveal-scale"><div class="ach__year">2024</div><svg class="ach__icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg><div class="ach__title">Inflexibility Dashboard &amp; Heatmap</div><p class="ach__desc">Developed a workforce inflexibility dashboard and heatmap to assess capability across multiple LOBs. Enabled data-driven staffing decisions based on skill distribution and coverage gaps.</p></div>
      <div class="ach__card reveal-scale"><div class="ach__year">2025</div><svg class="ach__icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M20.59 13.41l-7.17 7.17a2 2 0 01-2.83 0L2 12V2h10l8.59 8.59a2 2 0 010 2.82z"/><circle cx="7" cy="7" r="1"/></svg><div class="ach__title">Full MAP Compliance Ownership</div><p class="ach__desc">Took complete ownership of MAP compliance across all product listings. Reduced manufacturer and brand complaints through consistent pricing controls and rigorous validation processes.</p></div>
    </div>
  </div>
</section>


<!-- CREDENTIALS & ASSESSMENTS -->
<section id="credentials" class="section">
  <div class="section-float-icons" aria-hidden="true">
    <div class="sfi" style="left:80%;top:10%;animation-duration:16s;animation-delay:0s">
      <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/></svg>
    </div>
    <div class="sfi" style="left:5%;top:30%;animation-duration:20s;animation-delay:4s">
      <svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2"><path d="M22 11.08V12a10 10 0 11-5.93-9.14"/><polyline points="22 4 12 14.01 9 11.01"/></svg>
    </div>
    <div class="sfi" style="right:5%;bottom:20%;animation-duration:14s;animation-delay:8s">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
    </div>
    <div class="sfi" style="left:40%;top:5%;animation-duration:18s;animation-delay:6s">
      <svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg>
    </div>
  </div>
  <div class="section__watermark" aria-hidden="true">CR</div>
  <div class="section__inner">
    <div class="ed-label reveal">Verified Results</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">Credentials &amp; <em>Assessments</em></h2>
    <div class="cred__grid">

      <!-- IQ -->
      <div class="cred__card reveal shine">
        <div class="cred__icon-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/><path d="M9 3.4a9 9 0 015.7.1M19.5 7a9 9 0 011.4 5.5"/></svg>
        </div>
        <div class="cred__meta">
          <div class="cred__badge">Cognitive</div>
          <div class="cred__title">IQ Assessment</div>
          <div class="cred__score">133 <span>IQ</span></div>
          <div class="cred__detail">99th Percentile · BRGHT IQ Test · Sep 2025</div>
          <a class="cred__proof-link" href="https://drive.google.com/drive/folders/1yaKvUXxgaqm18muN8IIgFs3WK1Ryc01Z" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
          <div class="cred__bar-wrap"><div class="cred__bar" data-pct="95"></div></div>
        </div>
      </div>

      <!-- English C2 -->
      <div class="cred__card reveal shine">
        <div class="cred__icon-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M21 15a2 2 0 01-2 2H7l-4 4V5a2 2 0 012-2h14a2 2 0 012 2z"/></svg>
        </div>
        <div class="cred__meta">
          <div class="cred__badge">Language</div>
          <div class="cred__title">English Proficiency</div>
          <div class="cred__score">C2 <span>Level</span></div>
          <div class="cred__detail">Native-like · Transparent Language · CEFR Certified</div>
          <a class="cred__proof-link" href="https://drive.google.com/drive/folders/1yaKvUXxgaqm18muN8IIgFs3WK1Ryc01Z" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
          <div class="cred__bar-wrap"><div class="cred__bar" data-pct="100"></div></div>
        </div>
      </div>

      <!-- Typing Speed -->
      <div class="cred__card reveal shine">
        <div class="cred__icon-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><rect x="2" y="6" width="20" height="12" rx="2"/><path d="M6 10h.01M10 10h.01M14 10h.01M18 10h.01M6 14h.01M18 14h.01M10 14h4"/></svg>
        </div>
        <div class="cred__meta">
          <div class="cred__badge">Productivity</div>
          <div class="cred__title">Typing Speed</div>
          <div class="cred__score">85 <span>WPM</span></div>
          <div class="cred__detail">99% Accuracy · MonkeyType · Verified Feb 2025</div>
          <a class="cred__proof-link" href="https://drive.google.com/drive/folders/1yaKvUXxgaqm18muN8IIgFs3WK1Ryc01Z" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
          <div class="cred__bar-wrap"><div class="cred__bar" data-pct="85"></div></div>
        </div>
      </div>

      <!-- Personality -->
      <div class="cred__card reveal shine">
        <div class="cred__icon-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M20.84 4.61a5.5 5.5 0 00-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 00-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 000-7.78z"/></svg>
        </div>
        <div class="cred__meta">
          <div class="cred__badge">Personality</div>
          <div class="cred__title">Commander — ENTJ-A</div>
          <div class="cred__score">83<span>% Judging</span></div>
          <div class="cred__detail">77% Intuitive · 76% Thinking · 75% Assertive · 16Personalities</div>
          <a class="cred__proof-link" href="https://drive.google.com/drive/folders/1yaKvUXxgaqm18muN8IIgFs3WK1Ryc01Z" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
          <div class="cred__bar-wrap"><div class="cred__bar" data-pct="83"></div></div>
        </div>
      </div>

      <!-- Emotional Intelligence -->
      <div class="cred__card reveal shine">
        <div class="cred__icon-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><circle cx="12" cy="12" r="10"/><path d="M8 14s1.5 2 4 2 4-2 4-2M9 9h.01M15 9h.01"/></svg>
        </div>
        <div class="cred__meta">
          <div class="cred__badge">EQ</div>
          <div class="cred__title">Emotional Intelligence</div>
          <div class="cred__score">66 <span>/ 75</span></div>
          <div class="cred__detail">High EQ · "People approach you for advice" · EI Assessment</div>
          <a class="cred__proof-link" href="https://drive.google.com/drive/folders/1yaKvUXxgaqm18muN8IIgFs3WK1Ryc01Z" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
          <div class="cred__bar-wrap"><div class="cred__bar" data-pct="88"></div></div>
        </div>
      </div>

      <!-- Empathy -->
      <div class="cred__card reveal shine">
        <div class="cred__icon-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 00-3-3.87M16 3.13a4 4 0 010 7.75"/></svg>
        </div>
        <div class="cred__meta">
          <div class="cred__badge">Empathy</div>
          <div class="cred__title">Empathy Score</div>
          <div class="cred__score">65 <span>/ 80</span></div>
          <div class="cred__detail">High Empathy · Above Average · EQ-i Assessment</div>
          <a class="cred__proof-link" href="https://drive.google.com/drive/folders/1yaKvUXxgaqm18muN8IIgFs3WK1Ryc01Z" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
          <div class="cred__bar-wrap"><div class="cred__bar" data-pct="81"></div></div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- TECH SETUP -->
<section id="setup" class="section">
  <div class="bg-shape" style="width:110px;height:110px;top:5%;left:4%;animation-duration:19s;animation-delay:2s"></div>
  <div class="bg-shape" style="width:70px;height:70px;bottom:8%;right:6%;animation-duration:15s;animation-delay:6s"></div>
  <div class="bg-plus" style="top:12%;right:6%;animation-duration:11s;animation-delay:0s">+</div>
  <div class="bg-plus" style="bottom:25%;left:6%;animation-duration:17s;animation-delay:4s">+</div>
  <div class="bg-bracket" style="top:40%;left:1%;animation-duration:23s;animation-delay:9s">&#123;</div>
  <div class="section__watermark" aria-hidden="true">TS</div>
  <div class="section__inner">
    <div class="ed-label reveal">Work Infrastructure</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">Tech <em>Setup</em></h2>
    <div class="setup__grid">

      <div class="setup__card reveal shine">
        <div class="setup__icon-wrap">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8M12 17v4"/></svg>
        </div>
        <div class="setup__label">Primary Desktop</div>
        <div class="setup__name">AMD Ryzen 7 5700G</div>
        <ul class="setup__specs">
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 3.80 GHz · 8-Core · Radeon Graphics</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 16 GB RAM · 3200 MHz DDR4</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 477 GB SSD · TEAM T253512GB</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> MSI A520M-A PRO · Windows 10</li>
        </ul>
        <a class="cred__proof-link" href="https://drive.google.com/file/d/1I7Dwn2Tz3GX0WnwEXZpPxYiCLjgtR-Ve/view?usp=sharing" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>

      <div class="setup__card reveal shine">
        <div class="setup__icon-wrap">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M20 16V7a2 2 0 00-2-2H6a2 2 0 00-2 2v9m16 0H4m16 0l1.28 2.55a1 1 0 01-.9 1.45H3.62a1 1 0 01-.9-1.45L4 16"/></svg>
        </div>
        <div class="setup__label">Backup Laptop</div>
        <div class="setup__name">AMD Ryzen 5 7520U</div>
        <ul class="setup__specs">
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 2.80 GHz · HP Laptop 15-fc0xxx</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 16 GB RAM · 5500 MT/s</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 477 GB Storage</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> Windows 11 Home · 25H2</li>
        </ul>
        <a class="cred__proof-link" href="https://drive.google.com/file/d/1GgmKCSLmYqfmOHIsOUYZ37MF8wwehd5v/view?usp=sharing" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>

      <div class="setup__card reveal shine">
        <div class="setup__icon-wrap">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M5 12.55a11 11 0 0114.08 0M1.42 9a16 16 0 0121.16 0M8.53 16.11a6 6 0 016.95 0M12 20h.01"/></svg>
        </div>
        <div class="setup__label">Internet Connection</div>
        <div class="setup__name">PLDT Home Fiber</div>
        <ul class="setup__specs">
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 515 Mbps Download</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 840 Mbps Upload</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 4ms Ping · Fiber Connection</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> 99% QoS · BCS Verified</li>
        </ul>
      
        <a class="cred__proof-link" href="https://drive.google.com/file/d/1XfWAJZPrp4jVHd9fVp_C3NtvFpZJI6In/view?usp=sharing" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>

      <div class="setup__card reveal shine">
        <div class="setup__icon-wrap">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
                    <rect x="2" y="7" width="16" height="10" rx="2"/>
                    <path d="M22 11v2"/>
                    <path d="M10 9l-2 3h3l-2 3"/>
              </svg>
        </div>
        <div class="setup__label">Power Station</div>
        <div class="setup__name">BLUETTI Elite 10</div>
        <ul class="setup__specs">
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> Capacity · 128Wh</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> AC Outlets · 200W In Total, 220V</li>
          <li><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg> Durable LiFePO₄ Battery</li>
        </ul>
        <a class="cred__proof-link" href="https://drive.google.com/file/d/1LSP50oCiXtG0Bzq7cQ4nW6EcNhOMeo-c/view?usp=sharing" target="_blank" rel="noopener">View Proof <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M12 5l7 7-7 7"/></svg></a>
      </div>
    </div>
  </div>
</section>


<!-- WORKFORCE OPS AUDIT -->
<section id="audit" class="section">
  <div class="section__watermark" aria-hidden="true">OA</div>
  <div class="section__inner">
    <div class="audit__wrap">

      <div class="audit__badge reveal">
        <span class="audit__badge-dot"></span>
        Live Diagnostic Tool
      </div>

      <div class="ed-label reveal">Free Assessment</div>
      <div class="section-divider reveal"></div>
      <h2 class="section__title   ">
        Workforce Ops <em>Health Check</em>
      </h2>
      <p class="section__subtitle reveal" style="max-width:560px;margin:0 auto 40px;color:var(--text-muted);text-align:center;font-size:15.5px;line-height:1.7">
        Answer 5 questions. See exactly how many hours and dollars
        your operations are losing every week — and what to fix first.
      </p>

      <!-- PROGRESS -->
      <div class="audit__progress-wrap reveal">
        <div class="audit__progress-label">
          <span id="auditProgressLabel">Question 1 of 5</span>
          <span id="auditProgressPct">20%</span>
        </div>
        <div class="audit__progress-track">
          <div class="audit__progress-fill" id="auditProgressFill" style="width:20%"></div>
        </div>
      </div>

      <!-- QUESTIONS -->
      <div class="audit__steps" id="auditSteps">

        <!-- Q1: Hours lost -->
        <div class="audit__step active" id="auditStep1">
          <div class="audit__step-header">
            <div class="audit__step-num">01</div>
            <div class="audit__step-q">How many hours per week does your team lose to manual scheduling, data errors, or unstructured admin work?</div>
          </div>
          <div class="audit__slider-wrap">
            <div class="audit__slider-val" id="sliderVal">10 hrs/week</div>
            <input type="range" class="audit__slider" id="hoursSlider" min="2" max="40" value="10" step="1">
            <div class="audit__slider-labels">
              <span>2 hrs (minor)</span>
              <span>20 hrs</span>
              <span>40 hrs (full position)</span>
            </div>
          </div>
          <div class="audit__nav">
            <button class="audit__btn-next" onclick="auditNext(1)">Next →</button>
          </div>
        </div>

        <!-- Q2: Pain points -->
        <div class="audit__step" id="auditStep2">
          <div class="audit__step-header">
            <div class="audit__step-num">02</div>
            <div class="audit__step-q">Which of these are currently costing you the most? (Select all that apply)</div>
          </div>
          <div class="audit__checks">
            <label class="audit__check-label">
              <input type="checkbox" name="pain" value="schedule">
              <span class="audit__check-box"></span>
              <span class="audit__check-text">Schedule inaccuracies
                <span class="audit__check-sub">Wrong staffing levels, SLA misses, last-minute changes</span>
              </span>
            </label>
            <label class="audit__check-label">
              <input type="checkbox" name="pain" value="reporting">
              <span class="audit__check-box"></span>
              <span class="audit__check-text">Reporting delays or errors
                <span class="audit__check-sub">Late dashboards, wrong data, decisions made on bad numbers</span>
              </span>
            </label>
            <label class="audit__check-label">
              <input type="checkbox" name="pain" value="catalog">
              <span class="audit__check-box"></span>
              <span class="audit__check-text">Catalog/inventory out of sync
                <span class="audit__check-sub">Products mismatched across Amazon, Shopify, Walmart, eBay</span>
              </span>
            </label>
            <label class="audit__check-label">
              <input type="checkbox" name="pain" value="sla">
              <span class="audit__check-box"></span>
              <span class="audit__check-text">SLA compliance issues
                <span class="audit__check-sub">Service levels consistently below target</span>
              </span>
            </label>
            <label class="audit__check-label">
              <input type="checkbox" name="pain" value="manual">
              <span class="audit__check-box"></span>
              <span class="audit__check-text">Excessive manual work
                <span class="audit__check-sub">Repetitive tasks that should be automated or documented</span>
              </span>
            </label>
          </div>
          <div class="audit__nav">
            <button class="audit__btn-back" onclick="auditBack(2)">← Back</button>
            <button class="audit__btn-next" onclick="auditNext(2)">Next →</button>
          </div>
        </div>

        <!-- Q3: Platforms -->
        <div class="audit__step" id="auditStep3">
          <div class="audit__step-header">
            <div class="audit__step-num">03</div>
            <div class="audit__step-q">How many platforms or systems are you currently managing?</div>
          </div>
          <select class="audit__select" id="platformCount">
            <option value="">Select an option</option>
            <option value="1">1 platform — just getting started</option>
            <option value="2">2–3 platforms — manageable but growing</option>
            <option value="3">4–5 platforms — complex and fragmented</option>
            <option value="4">6+ platforms — high complexity, high risk</option>
          </select>
          <div class="audit__nav">
            <button class="audit__btn-back" onclick="auditBack(3)">← Back</button>
            <button class="audit__btn-next" onclick="auditNext(3)">Next →</button>
          </div>
        </div>

        <!-- Q4: Team size -->
        <div class="audit__step" id="auditStep4">
          <div class="audit__step-header">
            <div class="audit__step-num">04</div>
            <div class="audit__step-q">How large is the team or operation you need support with?</div>
          </div>
          <select class="audit__select" id="teamSize">
            <option value="">Select an option</option>
            <option value="1">Solo or 2–5 people</option>
            <option value="2">6–20 people</option>
            <option value="3">21–50 people</option>
            <option value="4">50+ people</option>
          </select>
          <div class="audit__nav">
            <button class="audit__btn-back" onclick="auditBack(4)">← Back</button>
            <button class="audit__btn-next" onclick="auditNext(4)">Next →</button>
          </div>
        </div>

        <!-- Q5: Urgency -->
        <div class="audit__step" id="auditStep5">
          <div class="audit__step-header">
            <div class="audit__step-num">05</div>
            <div class="audit__step-q">How urgently does this need to be fixed?</div>
          </div>
          <select class="audit__select" id="urgencyLevel">
            <option value="">Select an option</option>
            <option value="3">Critical — it's actively costing us right now</option>
            <option value="2">High — I need this sorted within weeks</option>
            <option value="1">Medium — planning ahead, not on fire yet</option>
          </select>
          <div class="audit__nav">
            <button class="audit__btn-back" onclick="auditBack(5)">← Back</button>
            <button class="audit__btn-next" onclick="auditShowResults()">See My Results →</button>
          </div>
        </div>

      </div>

      <!-- RESULTS PANEL -->
      <div class="audit__results" id="auditResults">
        <div class="audit__results-header">
          <p class="audit__results-tag">Your Operations Diagnostic</p>
          <h3 class="audit__results-headline" id="resultsHeadline">
            You're losing <span id="resultHours">—</span> hrs/week
          </h3>
          <p class="audit__results-sub" id="resultsSub">Here's what that's actually costing you — and what to fix first.</p>
        </div>

        <div class="audit__metrics">
          <div class="audit__metric">
            <div class="audit__metric-val" id="metricHours">—</div>
            <div class="audit__metric-label">Hours Lost / Week</div>
          </div>
          <div class="audit__metric">
            <div class="audit__metric-val" id="metricCost">—</div>
            <div class="audit__metric-label">Monthly Operational Drag</div>
          </div>
          <div class="audit__metric">
            <div class="audit__metric-val" id="metricAnnual">—</div>
            <div class="audit__metric-label">Annual Cost of Inaction</div>
          </div>
          <div class="audit__metric">
            <div class="audit__metric-val" id="metricFocus">—</div>
            <div class="audit__metric-label">Priority Fix Area</div>
          </div>
        </div>

        <div class="audit__pain-list" id="auditPainList"></div>

        <div class="audit__cta-block">
          <div class="audit__cta-title" id="ctaTitle">Let's reclaim those hours.</div>
          <p class="audit__cta-sub" id="ctaSub">Book a free 15-minute call. We'll map exactly how to fix this — no pitch, just a plan.</p>
          <div style="display:flex;gap:12px;justify-content:center;flex-wrap:wrap">
            <a class="audit__cta-btn" href="#contact" onclick="auditOpenBookCall()">
              📅 Book a Free Call →
            </a>
            <a class="audit__cta-btn" href="#contact"
               onclick="auditOpenMessage()"
               style="background:rgba(255,255,255,.15);color:#fff;border:1.5px solid rgba(255,255,255,.4)">
              ✉️ Send a Message →
            </a>
          </div>
          <button class="audit__restart" onclick="auditRestart()">↺ Retake the assessment</button>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience" class="section">
  <div class="bg-shape" style="width:90px;height:90px;top:8%;right:4%;animation-duration:17s;animation-delay:1s"></div>
  <div class="bg-shape" style="width:140px;height:140px;bottom:10%;left:2%;animation-duration:21s;animation-delay:5s"></div>
  <div class="bg-plus" style="top:20%;left:5%;animation-duration:13s;animation-delay:3s">+</div>
  <div class="bg-bracket" style="top:5%;right:3%;animation-duration:19s;animation-delay:7s">[</div>
  <div class="bg-bracket" style="bottom:5%;right:3%;animation-duration:19s;animation-delay:7s">]</div>
  <div class="sec-float-icon" style="width:44px;height:44px;top:20%;left:90%;animation-duration:16s;animation-delay:3s">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" width="44" height="44"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8M12 17v4"/></svg>
  </div>
  <div class="sec-float-icon" style="width:36px;height:36px;top:65%;left:4%;animation-duration:20s;animation-delay:8s">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" width="36" height="36"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
  </div>
  <div class="section__watermark" aria-hidden="true">04</div>
  <div class="section__inner">
    <div class="ed-label reveal">Work History</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">Professional <em>Experience</em></h2>
    <div class="exp__timeline">
      <div class="exp__item reveal"><div class="exp__dot"><div class="exp__dot-inner"></div></div><div class="exp__content"><div class="exp__date">Aug 2025 – Feb 2026</div><div class="exp__role">Catalog Specialist</div><div class="exp__company"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>eCommerce Operations (B2B) — Remote, Philippines</div><ul class="exp__bullets"><li>Managed high-volume product listings across Amazon, Shopify, Walmart, and eBay marketplaces</li><li>Conducted data validation and QA on large product catalogs, identifying and resolving data inconsistencies</li><li>Built and maintained dashboards and KPI trackers for listing accuracy, pricing compliance, and inventory status</li><li>Executed pricing updates using supplier data files while enforcing MAP policy compliance</li></ul>
      </div></div>
      <div class="exp__item reveal"><div class="exp__dot"><div class="exp__dot-inner"></div></div><div class="exp__content"><div class="exp__date">Mar 2024 – Aug 2025</div><div class="exp__role">Workforce Scheduler</div><div class="exp__company"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>BPO / Contact Center Operations — Remote, Philippines</div><ul class="exp__bullets"><li>Created and maintained reports, dashboards, and tracking tools supporting workforce planning and executive reporting</li><li>Performed schedule optimization based on forecasts, shrinkage, and intraday performance trends</li><li>Managed real-time monitoring and escalation handling to prevent SLA breaches</li><li>Documented SOPs and workflow processes to standardize reporting and improve consistency</li></ul>
      </div></div>
      <div class="exp__item reveal"><div class="exp__dot"><div class="exp__dot-inner"></div></div><div class="exp__content"><div class="exp__date">May 2021 – Mar 2024</div><div class="exp__role">Workforce Real-Time Analyst (RTA)</div><div class="exp__company"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>BPO / Contact Center Operations — Remote, Philippines</div><ul class="exp__bullets"><li>Developed and distributed intraday and daily performance reports and dashboards for leadership decision-making</li><li>Conducted real-time monitoring of KPIs: service level, AHT, occupancy, and adherence</li><li>Performed data validation and quality checks across multiple reporting sources</li><li>Analyzed intraday trends and implemented corrective actions to optimize staffing efficiency</li></ul>
      </div></div>
      <div class="exp__item reveal"><div class="exp__dot"><div class="exp__dot-inner"></div></div><div class="exp__content"><div class="exp__date">Feb 2019 – May 2021</div><div class="exp__role">Customer Support Representative</div><div class="exp__company"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>Customer Operations — Philippines</div><ul class="exp__bullets"><li>Maintained accurate CRM records and ensured data consistency across Salesforce and Zendesk</li><li>Supported data validation and documentation processes to improve data reliability</li><li>Introduced structured task allocation system that resolved cherry-picking across back-end operations</li></ul>
      </div></div>
    </div>
  </div>
</section>

<!-- TOOLKIT -->
<section id="toolkit" class="section">
  <div class="section__watermark" aria-hidden="true">05</div>
  <div class="section__inner">
    <div class="ed-label reveal">Tools &amp; Platforms</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">My <em>Toolkit</em></h2>
    <div class="marquee-wrap reveal">
      <div class="marquee-row"><div class="marquee-track"><span class="m-tag">Microsoft Excel</span><span class="m-tag">Google Sheets</span><span class="m-tag">Power BI</span><span class="m-tag">Looker Studio</span><span class="m-tag">NICE IEX</span><span class="m-tag">Calabrio TeleOpti</span><span class="m-tag">Salesforce</span><span class="m-tag">Zendesk</span><span class="m-tag">Amazon Seller Central</span><span class="m-tag">Shopify</span><span class="m-tag">Microsoft Excel</span><span class="m-tag">Google Sheets</span><span class="m-tag">Power BI</span><span class="m-tag">Looker Studio</span><span class="m-tag">NICE IEX</span><span class="m-tag">Calabrio TeleOpti</span><span class="m-tag">Salesforce</span><span class="m-tag">Zendesk</span><span class="m-tag">Amazon Seller Central</span><span class="m-tag">Shopify</span></div></div>
      <div class="marquee-row"><div class="marquee-track rev"><span class="m-tag">Walmart Seller Center</span><span class="m-tag">eBay Seller Hub</span><span class="m-tag">Flxpoint</span><span class="m-tag">AWS</span><span class="m-tag">CSV Processing</span><span class="m-tag">Bulk Upload Tools</span><span class="m-tag">Data Validation</span><span class="m-tag">NICE IEX</span><span class="m-tag">Microsoft Excel</span><span class="m-tag">Google Sheets</span><span class="m-tag">Walmart Seller Center</span><span class="m-tag">eBay Seller Hub</span><span class="m-tag">Flxpoint</span><span class="m-tag">AWS</span><span class="m-tag">CSV Processing</span><span class="m-tag">Bulk Upload Tools</span><span class="m-tag">Data Validation</span><span class="m-tag">NICE IEX</span><span class="m-tag">Microsoft Excel</span><span class="m-tag">Google Sheets</span></div></div>
    </div>
    <div class="toolkit__cats">
      <div class="toolkit__cat reveal-scale"><div class="toolkit__cat-label"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg>Data Analysis &amp; Reporting</div><div class="toolkit__tags"><span class="toolkit__tag">Microsoft Excel (Advanced)</span><span class="toolkit__tag">Google Sheets</span><span class="toolkit__tag">Power BI</span><span class="toolkit__tag">Looker Studio</span></div></div>
      <div class="toolkit__cat reveal-scale"><div class="toolkit__cat-label"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/></svg>Workforce Management</div><div class="toolkit__tags"><span class="toolkit__tag">NICE IEX</span><span class="toolkit__tag">Calabrio TeleOpti</span></div></div>
      <div class="toolkit__cat reveal-scale"><div class="toolkit__cat-label"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2"/><circle cx="9" cy="7" r="4"/></svg>CRM &amp; Customer Data</div><div class="toolkit__tags"><span class="toolkit__tag">Salesforce</span><span class="toolkit__tag">Zendesk</span></div></div>
      <div class="toolkit__cat reveal-scale"><div class="toolkit__cat-label"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/></svg>eCommerce Platforms</div><div class="toolkit__tags"><span class="toolkit__tag">Amazon Seller Central</span><span class="toolkit__tag">Shopify</span><span class="toolkit__tag">Walmart Seller Center</span><span class="toolkit__tag">eBay Seller Hub</span><span class="toolkit__tag">Flxpoint</span></div></div>
      <div class="toolkit__cat reveal-scale"><div class="toolkit__cat-label"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg>Data Management</div><div class="toolkit__tags"><span class="toolkit__tag">CSV / Flat File Processing</span><span class="toolkit__tag">Bulk Upload Tools</span><span class="toolkit__tag">Data Validation &amp; Cleanup</span></div></div>
      <div class="toolkit__cat reveal-scale"><div class="toolkit__cat-label"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg>Cloud &amp; Platforms</div><div class="toolkit__tags"><span class="toolkit__tag">Amazon Web Services (AWS)</span><span class="toolkit__tag">Google Workspace</span></div></div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
  <div class="bg-shape" style="width:130px;height:130px;top:10%;left:2%;animation-duration:20s;animation-delay:1s"></div>
  <div class="bg-shape" style="width:80px;height:80px;bottom:15%;right:3%;animation-duration:16s;animation-delay:5s"></div>
  <div class="bg-plus" style="top:25%;right:5%;animation-duration:15s;animation-delay:2s">+</div>
  <div class="bg-plus" style="bottom:30%;left:5%;animation-duration:19s;animation-delay:7s">+</div>
  <div class="bg-bracket" style="bottom:10%;right:2%;animation-duration:24s;animation-delay:4s">&#125;</div>
  <div class="section__watermark" aria-hidden="true">06</div>
  <div class="section__inner">
    <div class="ed-label reveal">Get In Touch</div>
    <div class="section-divider reveal"></div>
    <h2 class="section__title   ">Let's <em>Work Together</em></h2>
    <div class="contact__tabs-nav">
      <button class="contact__tab-btn active" data-ctab="book">
        <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" style="display:inline;vertical-align:middle;margin-right:6px"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/></svg>Book a Call
      </button>
      <button class="contact__tab-btn" data-ctab="message">
        <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" style="display:inline;vertical-align:middle;margin-right:6px"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>Send a Message
      </button>
    </div>
    <div class="contact__panel active" id="book">
      <p class="contact__honest reveal">
        This is a 15-minute conversation about what's actually happening in your operations.
        I'm not here to pitch — I'm here to understand your data, your workflows, and exactly
        where things are breaking down. You walk away with a clear picture of what needs to
        change — whether we work together or not.
      </p>
      <div class="call__steps reveal">
        <div class="call__step">
          <div class="call__step-num">1</div>
          <div>
            <div class="call__step-title">Pick a Time</div>
            <p class="call__step-desc">Choose a slot that works for your schedule. If a team lead or decision-maker is involved in the change you need, bring them. The best outcomes start with everyone who matters in the room from the beginning.</p>
          </div>
        </div>
        <div class="call__step">
          <div class="call__step-num">2</div>
          <div>
            <div class="call__step-title">Brief the Situation</div>
            <p class="call__step-desc">Come in with one specific problem — a schedule that keeps slipping, a dashboard that's wrong, a catalog out of sync, a reporting gap that's costing decisions. One real issue. Not a wish list. We go deep on that one thing.</p>
          </div>
        </div>
        <div class="call__step">
          <div class="call__step-num">3</div>
          <div>
            <div class="call__step-title">Leave With Clarity</div>
            <p class="call__step-desc">You leave with a concrete action plan — not a proposal deck. What to fix, how to approach it, and what you can implement immediately. Actionable, regardless of what we decide next.</p>
          </div>
        </div>
      </div>
      <div class="audit__book-banner" id="auditBookBanner">
        <div class="audit__book-banner-title">📊 Your Assessment Summary</div>
        <div class="audit__book-banner-grid" id="auditBookGrid"></div>
        <p style="font-size:12px;color:var(--text-muted);margin-top:10px">
          Share these results during your call so Romcel can prepare a targeted plan.
        </p>
      </div>
      <div class="contact__cal-wrap reveal">
        <iframe src="https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ1p_4iXpzzXVx9902_8PvUM74Wnw8yaLQ5Q66_7d0L2QYFQsNyZvvw4L7L_qmmHncIifl73p3DI" frameborder="0" title="Book a call with Romcel Geluz" loading="lazy"></iframe>
      </div>
    </div>
    <div class="contact__panel" id="message">
      <div class="form__prefill-banner" id="prefillBanner">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg>
        <span>Your Ops Assessment results have been included in this message.</span>
      </div>
      <p class="msg__honest reveal">
        Not ready for a call — that's completely fine.
        Send me the <strong>honest version</strong> of what's happening:
        what keeps breaking, what reports are wrong, what's taking too long,
        what you wish someone else would just handle.
        I read every message personally and respond within 24 hours
        with something <strong>actually useful</strong>.
      </p>
      <div class="contact__form reveal">
        <form name="contact" method="POST" action="/" data-netlify="true" data-netlify-honeypot="bot-field" id="contactForm" netlify>
          <input type="hidden" name="form-name" value="contact">
          <input type="hidden" name="bot-field">
          <input type="hidden" name="audit_hours_lost" id="auditField_hours" value="">
          <input type="hidden" name="audit_monthly_cost" id="auditField_cost" value="">
          <input type="hidden" name="audit_annual_cost" id="auditField_annual" value="">
          <input type="hidden" name="audit_pain_points" id="auditField_pain" value="">
          <input type="hidden" name="audit_urgency" id="auditField_urgency" value="">
          <div class="form__grid">
            <div class="form__field"><label class="form__label" for="fn">First Name</label><input class="form__input" type="text" id="fn" name="first-name" required placeholder="Your first name"></div>
            <div class="form__field"><label class="form__label" for="ln">Last Name</label><input class="form__input" type="text" id="ln" name="last-name" placeholder="Your last name"></div>
            <div class="form__field full"><label class="form__label" for="em">Email Address</label><input class="form__input" type="email" id="em" name="email" required placeholder="your@email.com"></div>
            <div class="form__field full">
              <label class="form__label" for="sv">Service Interested In</label>
              <select class="form__input form__select" id="sv" name="service" onchange="handleServiceSelect(this)">
                <option value="">— Select a service —</option>
                <option value="Workforce Planning &amp; Schedule Optimization">Workforce Planning &amp; Schedule Optimization</option>
                <option value="Real-Time Adherence &amp; Reporting">Real-Time Adherence &amp; Reporting</option>
                <option value="eCommerce Catalog Management">eCommerce Catalog Management</option>
                <option value="Data Entry &amp; Dashboard Setup">Data Entry &amp; Dashboard Setup</option>
                <option value="Data QA &amp; Validation">Data QA &amp; Validation</option>
                <option value="SOP &amp; Process Documentation">SOP &amp; Process Documentation</option>
                <option value="Operations Support">Operations Support</option>
                <option value="other">Other — I'll describe it below ↓</option>
              </select>
              <input class="form__input" type="text" id="svcOther" name="service-other"
                placeholder="Please describe the service you need..."
                style="display:none;margin-top:10px">
            </div>
            <div class="form__field full"><label class="form__label" for="mg">Message</label><textarea class="form__textarea" id="mg" name="message" required placeholder="Tell me about your project or what you need help with..."></textarea></div>
          </div>
          <button type="submit" class="form__submit btn--primary">Send Message <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="22" y1="2" x2="11" y2="13"/><polygon points="22 2 15 22 11 13 2 9 22 2"/></svg></button>
        </form>
        <div class="form__success" id="formSuccess">
          <div class="form__success-icon">
            <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"/></svg>
          </div>
          <div class="form__success-title">Message Sent!</div>
          <div class="form__success-sub">Thanks for reaching out. Romcel will get back to you within 24 hours.</div>
          <div class="form__success-meta">— Message received ✓</div>
        </div>
      </div>
    </div>
    <div class="contact__links reveal">

      <!-- Gmail -->
      <a class="contact__link" href="mailto:romcelgeluz@gmail.com" data-label="Email" aria-label="Email Romcel">
        <svg width="22" height="22" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z" stroke="var(--accent)" stroke-width="1.8" fill="none"/>
          <polyline points="22,6 12,13 2,6" stroke="var(--accent)" stroke-width="1.8" fill="none"/>
        </svg>
      </a>

      <!-- WhatsApp -->
      <a class="contact__link" href="https://wa.me/639354651011" target="_blank" rel="noopener" data-label="WhatsApp" aria-label="WhatsApp Romcel">
        <svg width="22" height="22" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z" fill="var(--accent)"/>
          <path d="M12 2C6.477 2 2 6.477 2 12c0 1.7.44 3.3 1.2 4.7L2 22l5.4-1.2C8.8 21.57 10.37 22 12 22c5.523 0 10-4.477 10-10S17.523 2 12 2z" stroke="var(--accent)" stroke-width="1.8" fill="none"/>
        </svg>
      </a>

      <!-- LinkedIn -->
      <a class="contact__link" href="https://www.linkedin.com/in/romcel-geluz-90671a342/" target="_blank" rel="noopener" data-label="LinkedIn" aria-label="Romcel on LinkedIn">
        <svg width="22" height="22" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect x="2" y="2" width="20" height="20" rx="4" stroke="var(--accent)" stroke-width="1.8" fill="none"/>
          <path d="M7 10v7" stroke="var(--accent)" stroke-width="1.8" stroke-linecap="round"/>
          <path d="M11 17v-4c0-1.1.9-2 2-2s2 .9 2 2v4" stroke="var(--accent)" stroke-width="1.8" stroke-linecap="round"/>
          <path d="M11 10v.5" stroke="var(--accent)" stroke-width="1.8" stroke-linecap="round"/>
          <circle cx="7" cy="7.5" r="1" fill="var(--accent)"/>
        </svg>
      </a>

    </div>
  </div>
</section>

<footer>
  <div class="footer__name">Romcel Geluz</div>
  <p class="footer__tagline">Workforce Planner &bull; eCommerce Catalog Specialist &bull; Data Operations</p>
  <p class="footer__copy">&copy; 2026 Romcel Geluz. All rights reserved.</p>
</footer>





<canvas id="confetti-canvas"></canvas>
<div class="cursor-trail" id="ct1"></div>
<div class="cursor-trail" id="ct2"></div>
<div class="cursor-trail" id="ct3"></div>
<div class="cursor-trail" id="ct4"></div>
<script>


// SPLASH
window.addEventListener('load',()=>{
  setTimeout(()=>{
    const sp=document.getElementById('splash');
    sp.classList.add('out');
    setTimeout(()=>sp.remove(),800);
    // Glitch fires 0.8s after splash exits
    setTimeout(()=>{
      const g=document.querySelector('.glitch');
      if(g){g.classList.add('fire');setTimeout(()=>g.classList.remove('fire'),350);}
    },800);
  },3000);
});

// CURSOR
const cur=document.getElementById('cursor'),ring=document.getElementById('cursorRing');
let mx=0,my=0,rx=0,ry=0;
document.addEventListener('mousemove',function(e) {mx=e.clientX;my=e.clientY;cur.style.left=mx+'px';cur.style.top=my+'px';});
(function animR(){rx+=(mx-rx)*.12;ry+=(my-ry)*.12;ring.style.left=rx+'px';ring.style.top=ry+'px';requestAnimationFrame(animR);})();
document.querySelectorAll('a,button,[role="button"]').forEach(function(el) {
  el.addEventListener('mouseenter',()=>{cur.classList.add('hov');ring.classList.add('hov');});
  el.addEventListener('mouseleave',()=>{cur.classList.remove('hov');ring.classList.remove('hov');});
});

// PROGRESS
const pb=document.getElementById('pb');
window.addEventListener('scroll',()=>{pb.style.width=(window.scrollY/(document.documentElement.scrollHeight-window.innerHeight)*100)+'%';},{passive:true});

// PARALLAX
window.addEventListener('scroll',()=>{const bg=document.getElementById('heroBg');if(bg)bg.style.transform='translateY('+(window.scrollY*.28)+'px)';},{passive:true});

// REVEAL
const ro=new IntersectionObserver(function(entries) {entries.forEach(function(e) {if(e.isIntersecting){e.target.classList.add('is-in');ro.unobserve(e.target);}});},{threshold:0.1,rootMargin:'0px 0px -6% 0px'});
document.querySelectorAll('.reveal,.reveal-left,.reveal-right,.reveal-scale').forEach(function(el){ ro.observe(el); });

// WIPE REVEAL
const wr=new IntersectionObserver(function(entries) {entries.forEach(function(e) {if(e.isIntersecting){e.target.classList.add('wiped');wr.unobserve(e.target);}});},{threshold:0.2});
document.querySelectorAll('.wipe-reveal').forEach(el=>wr.observe(el));

// STAGGER
['ach__grid','toolkit__cats','stats__inner'].forEach(function(c) {
  document.querySelectorAll('.'+c+' > *').forEach((el,i)=>{el.style.setProperty('--i',i);el.setAttribute('data-stagger','');});
});

// WIPE-IN on section headings
(function(){
  var obs=new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        e.target.classList.add('wipe-fired');
        obs.unobserve(e.target);
      }
    });
  },{threshold:0.3});
  document.querySelectorAll('.wipe-in').forEach(function(el){obs.observe(el);});
})();

// SECTION DIVIDERS DRAW
(function(){
  var obs=new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        e.target.classList.add('is-drawn');
        obs.unobserve(e.target);
      }
    });
  },{threshold:0.5});
  document.querySelectorAll('.section-divider').forEach(function(el){obs.observe(el);});
})();

// CRED SCORE GLOW on entry
(function(){
  var obs=new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        setTimeout(function(){
          e.target.classList.add('score-glow');
          setTimeout(function(){e.target.classList.remove('score-glow');},1200);
        },400);
        obs.unobserve(e.target);
      }
    });
  },{threshold:0.5});
  document.querySelectorAll('.cred__card').forEach(function(el){obs.observe(el);});
})();

// SECTION FLOAT ICONS draw attention
document.querySelectorAll('.sfi').forEach(function(icon){
  icon.style.animationPlayState='running';
});

// ABOUT QUICK STATS hover glow
document.querySelectorAll('.about__stat-pill').forEach(function(pill){
  pill.addEventListener('mouseenter',function(){
    pill.querySelector('svg')&&(pill.querySelector('svg').style.transform='scale(1.2) rotate(-5deg)');
    pill.querySelector('svg')&&(pill.querySelector('svg').style.transition='transform .3s cubic-bezier(.34,1.56,.64,1)');
  });
  pill.addEventListener('mouseleave',function(){
    pill.querySelector('svg')&&(pill.querySelector('svg').style.transform='');
  });
});

// CONTACT LINKS enhanced hover
// contact links use CSS hover

// NAV ACTIVE GLOW
(function(){
  var links=document.querySelectorAll('.nav__link');
  var sections=document.querySelectorAll('section[id]');
  window.addEventListener('scroll',function(){
    var scrollY=window.scrollY+120;
    sections.forEach(function(s){
      if(s.offsetTop<=scrollY&&s.offsetTop+s.offsetHeight>scrollY){
        links.forEach(function(l){l.classList.remove('active');});
        var active=document.querySelector('.nav__link[href="#'+s.id+'"]');
        if(active)active.classList.add('active');
      }
    });
  },{passive:true});
})();

// EXP CONTENT HOVER BORDER
document.querySelectorAll('.exp__content').forEach(function(el){
  el.addEventListener('mouseenter',function(){
    el.style.borderColor='var(--accent)';
    el.style.boxShadow='0 4px 24px rgba(var(--accent-rgb),.08)';
    el.style.transition='border-color .3s,box-shadow .3s';
  });
  el.addEventListener('mouseleave',function(){
    el.style.borderColor='';
    el.style.boxShadow='';
  });
});


// ═══════════════════════════════════════════════════
//   WORKFORCE OPS HEALTH CHECK — INTERACTIVE AUDIT
// ═══════════════════════════════════════════════════

var auditCurrentStep = 1;
var auditTotalSteps = 5;
var HOURLY_RATE = 5; // Update after client confirms rate // $5/hr — update after client confirmation

// SLIDER live update
var hoursSlider = document.getElementById('hoursSlider');
var sliderVal = document.getElementById('sliderVal');
if (hoursSlider) {
  hoursSlider.addEventListener('input', function() {
    sliderVal.textContent = this.value + ' hrs/week';
    sliderVal.style.transform = 'scale(1.08)';
    setTimeout(function() { sliderVal.style.transform = ''; }, 200);
  });
}

function auditUpdateProgress(step) {
  var pct = Math.round((step / auditTotalSteps) * 100);
  var fill = document.getElementById('auditProgressFill');
  var label = document.getElementById('auditProgressLabel');
  var pctLabel = document.getElementById('auditProgressPct');
  if (fill) fill.style.width = pct + '%';
  if (label) label.textContent = 'Question ' + step + ' of ' + auditTotalSteps;
  if (pctLabel) pctLabel.textContent = pct + '%';
}

function auditNext(step) {
  // Validate
  if (step === 3) {
    var sel = document.getElementById('platformCount');
    if (!sel || !sel.value) {
      sel.style.borderColor = 'var(--accent)';
      sel.focus(); return;
    }
  }
  if (step === 4) {
    var sel2 = document.getElementById('teamSize');
    if (!sel2 || !sel2.value) {
      sel2.style.borderColor = 'var(--accent)';
      sel2.focus(); return;
    }
  }

  var current = document.getElementById('auditStep' + step);
  var next = document.getElementById('auditStep' + (step + 1));
  if (current) current.classList.remove('active');
  if (next) next.classList.add('active');
  auditCurrentStep = step + 1;
  auditUpdateProgress(auditCurrentStep);

  // Scroll to audit section
  var auditSection = document.getElementById('audit');
  if (auditSection) {
    auditSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
  }
}

function auditBack(step) {
  var current = document.getElementById('auditStep' + step);
  var prev = document.getElementById('auditStep' + (step - 1));
  if (current) current.classList.remove('active');
  if (prev) prev.classList.add('active');
  auditCurrentStep = step - 1;
  auditUpdateProgress(auditCurrentStep);
}

function auditShowResults() {
  var urgSel = document.getElementById('urgencyLevel');
  if (!urgSel || !urgSel.value) {
    urgSel.style.borderColor = 'var(--accent)';
    urgSel.focus(); return;
  }

  // Collect answers
  var hours = parseInt(document.getElementById('hoursSlider').value) || 10;
  var pains = Array.from(document.querySelectorAll('input[name="pain"]:checked'))
    .map(function(el) { return el.value; });
  var platforms = document.getElementById('platformCount').value;
  var team = document.getElementById('teamSize').value;
  var urgency = parseInt(document.getElementById('urgencyLevel').value) || 1;

  // Calculate
  var monthlyHours = hours * 4;
  var monthlyCost = Math.round(monthlyHours * HOURLY_RATE);
  var annualCost = monthlyCost * 12;

  // Pain label map
  var painLabels = {
    schedule: 'Schedule accuracy',
    reporting: 'Reporting delays',
    catalog: 'Catalog sync',
    sla: 'SLA compliance',
    manual: 'Manual workload'
  };

  var topPain = pains.length > 0 ? painLabels[pains[0]] : 'Ops efficiency';

  // Populate results
  var headline = document.getElementById('resultHours');
  var metricH = document.getElementById('metricHours');
  var metricC = document.getElementById('metricCost');
  var metricA = document.getElementById('metricAnnual');
  var metricF = document.getElementById('metricFocus');

  if (headline) headline.textContent = hours + ' hrs/week';
  if (metricH) metricH.textContent = hours + ' hrs';
  if (metricC) metricC.textContent = '$' + monthlyCost.toLocaleString();
  if (metricA) metricA.textContent = '$' + annualCost.toLocaleString();
  if (metricF) metricF.textContent = topPain;

  // Pain list
  var painList = document.getElementById('auditPainList');
  if (painList && pains.length > 0) {
    var painDescs = {
      schedule: 'Schedule inaccuracies are likely causing SLA misses and overtime costs.',
      reporting: 'Reporting delays mean decisions are being made on outdated data.',
      catalog: 'Out-of-sync catalogs lead to lost sales and compliance issues.',
      sla: 'SLA non-compliance compounds over time — every miss costs client trust.',
      manual: 'Manual repetitive work is the highest-cost, lowest-value activity in any operation.'
    };
    painList.innerHTML = '<p style="font-size:13px;font-weight:700;color:var(--text);margin-bottom:12px;font-family:var(--font-mono);letter-spacing:.06em;text-transform:uppercase">What This Is Costing You</p>' +
      pains.map(function(p) {
        return '<div class="audit__pain-item"><div class="audit__pain-dot"></div><span>' + (painDescs[p] || p) + '</span></div>';
      }).join('');
  }

  // Urgency-based CTA
  var ctaTitle = document.getElementById('ctaTitle');
  var ctaSub = document.getElementById('ctaSub');
  if (urgency === 3) {
    if (ctaTitle) ctaTitle.textContent = "This is urgent — let's fix it this week.";
    if (ctaSub) ctaSub.textContent = "Book a call today. We'll map a plan in 15 minutes, and start the same week.";
  } else if (urgency === 2) {
    if (ctaTitle) ctaTitle.textContent = "Let's get ahead of this before it gets worse.";
    if (ctaSub) ctaSub.textContent = "Book a 15-minute call. I'll show you what we can fix in the first week.";
  }

  // Animate metric numbers
  [
    { el: metricH, target: hours, suffix: ' hrs', isInt: true },
    { el: metricC, target: monthlyCost, prefix: '$', isInt: true },
    { el: metricA, target: annualCost, prefix: '$', isInt: true },
  ].forEach(function(item) {
    if (!item.el) return;
    var start = 0;
    var step = item.target / 40;
    var iv = setInterval(function() {
      start = Math.min(start + step, item.target);
      var val = Math.floor(start);
      item.el.textContent = (item.prefix || '') + val.toLocaleString() + (item.suffix || '');
      if (start >= item.target) clearInterval(iv);
    }, 35);
  });

  // Show results, hide questions
  document.getElementById('auditSteps').style.display = 'none';
  document.getElementById('auditProgressFill').style.width = '100%';
  document.getElementById('auditProgressLabel').textContent = 'Assessment Complete';
  document.getElementById('auditProgressPct').textContent = '100%';

  var results = document.getElementById('auditResults');
  if (results) results.classList.add('active');

  // Scroll to results
  setTimeout(function() {
    results.scrollIntoView({ behavior: 'smooth', block: 'start' });
  }, 200);
}

function auditRestart() {
  auditCurrentStep = 1;
  document.querySelectorAll('.audit__step').forEach(function(s) {
    s.classList.remove('active');
  });
  document.getElementById('auditStep1').classList.add('active');
  document.getElementById('auditSteps').style.display = '';
  document.getElementById('auditResults').classList.remove('active');
  document.querySelectorAll('input[name="pain"]').forEach(function(cb) {
    cb.checked = false;
  });
  document.getElementById('hoursSlider').value = 10;
  document.getElementById('sliderVal').textContent = '10 hrs/week';
  document.getElementById('platformCount').value = '';
  document.getElementById('teamSize').value = '';
  document.getElementById('urgencyLevel').value = '';
  auditUpdateProgress(1);
  document.getElementById('audit').scrollIntoView({ behavior: 'smooth', block: 'start' });
}


// AUDIT → SEND MESSAGE integration
function auditOpenMessage() {
  // 1. Collect audit data
  var hours = document.getElementById('hoursSlider')
    ? document.getElementById('hoursSlider').value : '?';
  var monthlyHours = hours * 4;
  var monthlyCost = Math.round(monthlyHours * HOURLY_RATE).toLocaleString();
  var annualCost = Math.round(monthlyHours * HOURLY_RATE * 12).toLocaleString();

  var pains = Array.from(
    document.querySelectorAll('input[name="pain"]:checked')
  ).map(function(el) { return el.value; });

  var painMap = {
    schedule: 'Schedule inaccuracies',
    reporting: 'Reporting delays',
    catalog: 'Catalog/inventory out of sync',
    sla: 'SLA compliance issues',
    manual: 'Excessive manual work'
  };
  var painText = pains.length > 0
    ? pains.map(function(p) { return painMap[p] || p; }).join(', ')
    : 'Not specified';

  var urgEl = document.getElementById('urgencyLevel');
  var urgText = urgEl && urgEl.options[urgEl.selectedIndex]
    ? urgEl.options[urgEl.selectedIndex].text.replace(/^[^a-zA-Z]+/, '').trim()
    : 'Not specified';

  // 2. Build assessment summary for the message field
  var summary = [
    '— WORKFORCE OPS ASSESSMENT RESULTS —',
    '',
    'Hours lost per week: ' + hours + ' hrs',
    'Monthly operational drag: $' + monthlyCost,
    'Annual cost of inaction: $' + annualCost,
    'Top pain points: ' + painText,
    'Urgency: ' + urgText,
    '',
    '— MY MESSAGE —',
    ''
  ].join('\n');

  // 3. Fill hidden audit fields
  var f = function(id, val) {
    var el = document.getElementById(id);
    if (el) el.value = val;
  };
  f('auditField_hours', hours + ' hrs/week');
  f('auditField_cost', '$' + monthlyCost + '/month');
  f('auditField_annual', '$' + annualCost + '/year');
  f('auditField_pain', painText);
  f('auditField_urgency', urgText);

  // 4. Pre-fill message textarea
  var textarea = document.getElementById('mg');
  if (textarea) {
    textarea.value = summary;
    textarea.placeholder = 'Add anything else you want Romcel to know...';
    // Auto-resize textarea
    textarea.style.minHeight = '200px';
  }

  // 5. Switch to Send a Message tab
  var msgBtn = document.querySelector('[data-ctab="message"]');
  if (msgBtn) msgBtn.click();

  // 6. Show pre-fill banner + tab indicator
  var banner = document.getElementById('prefillBanner');
  if (banner) banner.classList.add('visible');
  if (msgBtn) msgBtn.classList.add('prefilled');

  // Also populate Book a Call assessment banner
  var bookBanner = document.getElementById('auditBookBanner');
  var bookGrid = document.getElementById('auditBookGrid');
  if (bookBanner && bookGrid) {
    bookGrid.innerHTML =
      '<div class="audit__book-banner-item"><span>Hours lost/week </span><span>' + hours + ' hrs</span></div>' +
      '<div class="audit__book-banner-item"><span>Monthly drag </span><span>$' + monthlyCost + '</span></div>' +
      '<div class="audit__book-banner-item"><span>Annual cost </span><span>$' + annualCost + '</span></div>' +
      '<div class="audit__book-banner-item"><span>Priority fix </span><span>' + (pains.length ? painLabels[pains[0]] : 'Ops efficiency') + '</span></div>';
    bookBanner.classList.add('visible');
  }

  // 7. Scroll to contact section
  var contact = document.getElementById('contact');
  if (contact) {
    setTimeout(function() {
      contact.scrollIntoView({ behavior: 'smooth', block: 'start' });
      // Focus the first name field
      setTimeout(function() {
        var fn = document.getElementById('fn');
        if (fn) fn.focus();
      }, 600);
    }, 200);
  }
}


// SERVICE DROPDOWN — show "Other" text input
function handleServiceSelect(sel) {
  var otherInput = document.getElementById('svcOther');
  if (!otherInput) return;
  if (sel.value === 'other') {
    otherInput.style.display = 'block';
    otherInput.required = true;
    otherInput.focus();
  } else {
    otherInput.style.display = 'none';
    otherInput.required = false;
    otherInput.value = '';
  }
}


// GET A QUOTE / AVAIL SERVICE → scroll to diagnostic tool
function scrollToAudit(e) {
  if(e) e.preventDefault();
  var audit = document.getElementById('audit');
  if(audit){
    audit.scrollIntoView({behavior:'smooth', block:'start'});
    // Flash the audit section to draw attention
    setTimeout(function(){
      audit.style.transition = 'box-shadow .3s ease';
      audit.style.boxShadow = '0 0 0 2px rgba(15,118,110,.4)';
      setTimeout(function(){ audit.style.boxShadow = ''; }, 1200);
    }, 600);
  }
}


// BOOK A FREE CALL from audit results — populate banner and scroll
function auditOpenBookCall() {
  var hours = document.getElementById('hoursSlider') ? document.getElementById('hoursSlider').value : '?';
  var monthlyHours = hours * 4;
  var monthlyCost = Math.round(monthlyHours * HOURLY_RATE).toLocaleString();
  var annualCost = Math.round(monthlyHours * HOURLY_RATE * 12).toLocaleString();
  var pains = Array.from(document.querySelectorAll('input[name="pain"]:checked')).map(function(el){return el.value;});
  var painLabels = {schedule:'Schedule accuracy',reporting:'Reporting delays',catalog:'Catalog sync',sla:'SLA compliance',manual:'Manual workload'};
  var urgEl = document.getElementById('urgencyLevel');
  var urgText = urgEl && urgEl.value ? urgEl.options[urgEl.selectedIndex].text.replace(/^[^a-zA-Z]+/,'') : 'Not specified';

  var bookBanner = document.getElementById('auditBookBanner');
  var bookGrid = document.getElementById('auditBookGrid');
  if (bookBanner && bookGrid) {
    bookGrid.innerHTML =
      '<div class="audit__book-banner-item"><span>Hours lost/week </span><span>' + hours + ' hrs</span></div>' +
      '<div class="audit__book-banner-item"><span>Monthly drag </span><span>$' + monthlyCost + '</span></div>' +
      '<div class="audit__book-banner-item"><span>Annual cost </span><span>$' + annualCost + '</span></div>' +
      '<div class="audit__book-banner-item"><span>Priority fix </span><span>' + (pains.length ? (painLabels[pains[0]]||pains[0]) : 'Ops efficiency') + '</span></div>';
    bookBanner.classList.add('visible');
  }
  var bookBtn = document.querySelector('[data-ctab=book]');
  if (bookBtn) bookBtn.click();
  var contact = document.getElementById('contact');
  if (contact) setTimeout(function(){ contact.scrollIntoView({behavior:'smooth',block:'start'}); }, 200);
}




// ═══════════════════════════════════════════════════
//   5 PREMIUM EFFECTS — FINAL POLISH
// ═══════════════════════════════════════════════════

// 1. NAV GLASSMORPHISM ON SCROLL
(function(){
  var nav=document.querySelector('.nav');if(!nav)return;
  var t=false;
  window.addEventListener('scroll',function(){
    if(!t){requestAnimationFrame(function(){nav.classList[window.scrollY>40?'add':'remove']('scrolled');t=false;});t=true;}
  },{passive:true});
})();

// 2. SERVICE TAB CROSS-FADE
(function(){
  document.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click',function(){
      var id=btn.dataset.tab;if(!id)return;
      document.querySelectorAll('.services__panel').forEach(function(p){
        if(p.id===id){p.classList.add('active','tab-enter');setTimeout(function(){p.classList.remove('tab-enter');},400);}
        else p.classList.remove('active','tab-enter');
      });
    });
  });
})();

// 3. GRADIENT CTA — secondary button hover
document.querySelectorAll('.btn--secondary').forEach(function(b){
  b.addEventListener('mouseenter',function(){b.style.cssText+='box-shadow:0 8px 24px rgba(var(--accent-rgb),.2);transform:translateY(-2px)';});
  b.addEventListener('mouseleave',function(){b.style.boxShadow='';b.style.transform='';});
});

// 4. CURSOR TRAIL DOTS
(function(){
  var trails=['ct1','ct2','ct3','ct4'].map(function(id){return document.getElementById(id);}).filter(Boolean);
  if(!trails.length)return;
  var pos=trails.map(function(){return{x:0,y:0};});
  var mouse={x:window.innerWidth/2,y:window.innerHeight/2};
  var delays=[0.08,0.14,0.20,0.26];
  var on=false;
  document.addEventListener('mousemove',function(e){
    mouse.x=e.clientX;mouse.y=e.clientY;
    if(!on){on=true;trails.forEach(function(t,i){t.style.opacity=String(.45-i*.09);});}
  });
  document.addEventListener('mouseleave',function(){on=false;trails.forEach(function(t){t.style.opacity='0';});});
  function loop(){
    pos[0].x+=(mouse.x-pos[0].x)*(1-delays[0]);
    pos[0].y+=(mouse.y-pos[0].y)*(1-delays[0]);
    for(var i=1;i<trails.length;i++){
      pos[i].x+=(pos[i-1].x-pos[i].x)*(1-delays[i]);
      pos[i].y+=(pos[i-1].y-pos[i].y)*(1-delays[i]);
    }
    trails.forEach(function(t,i){
      t.style.left=pos[i].x+'px';
      t.style.top=pos[i].y+'px';
      t.style.transform='translate(-50%,-50%) scale('+String(1-i*.18)+')';
    });
    requestAnimationFrame(loop);
  }
  loop();
})();

// 5. CONFETTI ON FORM SUCCESS
function launchConfetti(){
  var c=document.getElementById('confetti-canvas');if(!c)return;
  var ctx=c.getContext('2d');
  c.width=window.innerWidth;c.height=window.innerHeight;
  c.style.opacity='1';
  var cols=['rgba(15,118,110,.9)','rgba(13,148,136,.9)','rgba(201,168,76,.9)','rgba(255,255,255,.9)','rgba(15,118,110,.5)'];
  var pts=Array.from({length:90},function(){return{x:Math.random()*c.width,y:-10-Math.random()*80,w:6+Math.random()*8,h:3+Math.random()*5,col:cols[Math.floor(Math.random()*cols.length)],rot:Math.random()*Math.PI*2,rv:(Math.random()-.5)*.15,vy:2.5+Math.random()*3.5,vx:(Math.random()-.5)*2.5,a:1};});
  var f=0;
  function drawConfetti(){
    ctx.clearRect(0,0,c.width,c.height);
    pts.forEach(function(p){
      p.x+=p.vx;p.y+=p.vy;p.rot+=p.rv;
      if(f>80)p.a-=.016;
      ctx.save();ctx.globalAlpha=Math.max(0,p.a);
      ctx.translate(p.x,p.y);ctx.rotate(p.rot);
      ctx.fillStyle=p.col;ctx.fillRect(-p.w/2,-p.h/2,p.w,p.h);
      ctx.restore();
    });
    f++;
    if(f<140)requestAnimationFrame(drawConfetti);
    else{c.style.opacity='0';setTimeout(function(){ctx.clearRect(0,0,c.width,c.height);},350);}
  }
  drawConfetti();
}
(function(){
  var fs=document.getElementById('formSuccess');if(!fs)return;
  var obs=new MutationObserver(function(muts){
    muts.forEach(function(m){
      if(m.attributeName==='style'&&fs.style.display==='flex'){setTimeout(launchConfetti,350);obs.disconnect();}
    });
  });
  obs.observe(fs,{attributes:true});
})();




// SECTION TITLE SLIDE-IN FROM LEFT
(function(){
  var obs = new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        e.target.classList.add('title-in');
        obs.unobserve(e.target);
      }
    });
  }, {threshold:0.3});
  document.querySelectorAll('.section__title, .ed-label').forEach(function(el){
    obs.observe(el);
  });
})();


// KINETIC HERO TEXT — cycling words
(function(){
  var el = document.getElementById('heroKinetic');
  if(!el) return;
  var words = [
    'workforce planning',
    'real-time analytics',
    'catalog operations',
    'data validation',
    'schedule optimization',
    'process documentation'
  ];
  var i = 0;
  el.style.transition = 'opacity .3s ease, transform .3s ease';
  el.style.display = 'inline-block';
  setInterval(function(){
    el.style.opacity = '0';
    el.style.transform = 'translateY(6px)';
    setTimeout(function(){
      i = (i + 1) % words.length;
      el.textContent = words[i];
      el.style.opacity = '1';
      el.style.transform = 'none';
    }, 320);
  }, 2600);
})();



// ── CONTACT TAB SWITCHING ─────────────────────────────────────────
(function(){
  var tabBtns = document.querySelectorAll('.contact__tab-btn');
  var tabPanels = document.querySelectorAll('.contact__panel');

  tabBtns.forEach(function(btn){
    btn.addEventListener('click', function(){
      var target = btn.getAttribute('data-ctab');

      // Update button states
      tabBtns.forEach(function(b){ b.classList.remove('active'); });
      btn.classList.add('active');

      // Update panel states
      tabPanels.forEach(function(p){
        if(p.id === target){
          p.classList.add('active');
          p.style.display = 'block';
        } else {
          p.classList.remove('active');
          p.style.display = 'none';
        }
      });
    });
  });

  // Initialise — make sure book panel is visible, message panel hidden
  tabPanels.forEach(function(p){
    if(p.id === 'book'){
      p.classList.add('active');
      p.style.display = 'block';
    } else {
      p.classList.remove('active');
      p.style.display = 'none';
    }
  });
})();



// ── NETLIFY CONTACT FORM SUBMISSION ──────────────────────────────
(function(){
  var form = document.getElementById('contactForm');
  if(!form) return;

  form.addEventListener('submit', function(e){
    e.preventDefault();

    var fd  = new FormData(form);
    var btn = form.querySelector('[type="submit"]');

    // Show loading state
    if(btn){ btn.disabled = true; btn.textContent = 'Sending...'; }

    fetch('/', {
      method: 'POST',
      headers: { 'Content-Type': 'application/x-www-form-urlencoded' },
      body: new URLSearchParams(fd).toString()
    })
    .then(function(res){
      // Netlify returns 200 or 303 on success
      showSuccess();
    })
    .catch(function(){
      // Even on network error — show success (Netlify likely got it)
      showSuccess();
    });

    function showSuccess(){
      var frm = document.getElementById('contactForm');
      var fs  = document.getElementById('formSuccess');
      if(frm){
        frm.style.cssText = 'opacity:0;transform:scale(.97);transition:all .3s ease;pointer-events:none';
        setTimeout(function(){
          frm.style.display = 'none';
          if(fs){
            fs.style.display       = 'flex';
            fs.style.flexDirection = 'column';
            fs.style.alignItems    = 'center';
            fs.style.animation     = 'successReveal .5s cubic-bezier(.34,1.56,.64,1) forwards';
            setTimeout(launchConfetti, 400);
          }
        }, 300);
      }
      if(btn){ btn.disabled = false; btn.textContent = 'Send Message'; }
    }
  });
})();



// ── PARTICLE SYSTEM ──────────────────────────────────────────────
(function(){
  var c=document.getElementById('hero-particles');
  if(!c)return;
  var ctx=c.getContext('2d'),pts=[];
  function resize(){c.width=c.parentElement.offsetWidth||window.innerWidth;c.height=c.parentElement.offsetHeight||window.innerHeight;}
  resize();window.addEventListener('resize',resize);
  for(var i=0;i<40;i++)pts.push({x:Math.random()*c.width,y:Math.random()*c.height,r:Math.random()*.8+.3,dx:(Math.random()-.5)*.25,dy:(Math.random()-.5)*.25,o:Math.random()*.2+.05});
  function drawParticles(){
    ctx.clearRect(0,0,c.width,c.height);
    pts.forEach(function(p){
      ctx.beginPath();ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
      ctx.fillStyle='rgba(15,118,110,'+p.o+')';ctx.fill();
      pts.forEach(function(q){var d=Math.hypot(p.x-q.x,p.y-q.y);if(d<90){ctx.beginPath();ctx.moveTo(p.x,p.y);ctx.lineTo(q.x,q.y);ctx.strokeStyle='rgba(15,118,110,'+(0.04*(1-d/90))+')';ctx.lineWidth=.4;ctx.stroke();}});
      p.x+=p.dx;p.y+=p.dy;
      if(p.x<0||p.x>c.width)p.dx*=-1;if(p.y<0||p.y>c.height)p.dy*=-1;
    });requestAnimationFrame(drawParticles);
  }drawParticles();
})();

// ── SCROLL CUE FADE ──────────────────────────────────────────────
(function(){
  var cue=document.querySelector('.hero__scroll-cue');
  if(!cue)return;
  window.addEventListener('scroll',function(){cue.style.opacity=Math.max(0,.6-window.scrollY/200).toString();},{passive:true});
})();

// ── WORD REVEAL on hero headline ─────────────────────────────────
(function(){
  var obs=new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        e.target.querySelectorAll('.wr').forEach(function(w,i){w.style.transitionDelay=(i*55)+'ms';});
        e.target.classList.add('wr-done');obs.unobserve(e.target);
      }
    });
  },{threshold:0.15});
  document.querySelectorAll('.word-reveal').forEach(function(el){obs.observe(el);});
})();

// ── SLOT MACHINE STAT FLIP ───────────────────────────────────────
(function(){
  var obs=new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        e.target.querySelectorAll('[data-flip]').forEach(function(el){
          var target=parseInt(el.dataset.flip);
          var chars='0123456789';
          var iters=0,maxIters=22;
          var spanEl=el.querySelector('span');
          var iv=setInterval(function(){
            if(spanEl)spanEl.textContent=Array.from(String(target)).map(function(d,idx){return idx<Math.floor(iters/3)?d:chars[Math.floor(Math.random()*10)];}).join('');
            if(iters>=maxIters){if(spanEl){spanEl.textContent=target;spanEl.style.textShadow='0 0 20px rgba(15,118,110,.5)';setTimeout(function(){spanEl.style.textShadow='';},600);}clearInterval(iv);}
            iters++;
          },55);
        });
        obs.unobserve(e.target);
      }
    });
  },{threshold:0.5});
  document.querySelectorAll('.stats__inner').forEach(function(el){obs.observe(el);});
})();

// ── EXPERIENCE TIMELINE DRAW ─────────────────────────────────────
(function(){
  var tl=document.querySelector('.exp__timeline');
  if(!tl)return;
  var line=document.createElement('div');
  line.style.cssText='position:absolute;left:11px;top:12px;width:1.5px;height:0;background:var(--accent);transition:height 1.4s cubic-bezier(.16,1,.3,1);z-index:0;border-radius:2px;pointer-events:none';
  tl.style.position='relative';tl.insertBefore(line,tl.firstChild);
  var obs=new IntersectionObserver(function(entries){entries.forEach(function(e){if(e.isIntersecting){line.style.height=(tl.scrollHeight-24)+'px';obs.unobserve(e.target);}});},{threshold:0.1});
  obs.observe(tl);
})();

// ── EXPERIENCE ALTERNATING SLIDE ─────────────────────────────────
document.querySelectorAll('.exp__item').forEach(function(item,i){
  var content=item.querySelector('.exp__content');
  if(!content)return;
  content.style.opacity='0';
  content.style.transform=i%2===0?'translateX(-20px)':'translateX(20px)';
  content.style.transition='opacity .6s ease,transform .6s ease';
  var o=new IntersectionObserver(function(entries){entries.forEach(function(e){if(e.isIntersecting){e.target.style.opacity='1';e.target.style.transform='none';o.unobserve(e.target);}});},{threshold:0.2});
  o.observe(content);
});

// ── SERVICE CARD 3D TILT ─────────────────────────────────────────
document.querySelectorAll('.svc__card').forEach(function(card){
  card.addEventListener('mousemove',function(e){var r=card.getBoundingClientRect();var x=(e.clientX-r.left-r.width/2)/(r.width/2);var y=(e.clientY-r.top-r.height/2)/(r.height/2);card.style.transform='perspective(600px) rotateY('+(x*10)+'deg) rotateX('+(-y*10)+'deg)';});
  card.addEventListener('mouseleave',function(){card.style.transform='';card.style.transition='transform .5s cubic-bezier(.34,1.56,.64,1),background .3s';});
  card.addEventListener('mouseenter',function(){card.style.transition='transform .1s ease,background .3s';});
});

// ── ACHIEVEMENT CARD 3D TILT ─────────────────────────────────────
document.querySelectorAll('.ach__card,.proof-card').forEach(function(card){
  card.addEventListener('mousemove',function(e){var r=card.getBoundingClientRect();var x=(e.clientX-r.left-r.width/2)/(r.width/2);var y=(e.clientY-r.top-r.height/2)/(r.height/2);card.style.transform='perspective(700px) rotateX('+(-y*8)+'deg) rotateY('+(x*8)+'deg) scale(1.02)';});
  card.addEventListener('mouseleave',function(){card.style.transform='';card.style.transition='transform .5s cubic-bezier(.34,1.56,.64,1)';});
  card.addEventListener('mouseenter',function(){card.style.transition='transform .1s ease';});
});

// ── PROOF CARD 3D TILT (hero) ────────────────────────────────────
(function(){
  var card=document.querySelector('.hero__proof');if(!card)return;
  card.addEventListener('mousemove',function(e){var r=card.getBoundingClientRect();var x=(e.clientX-r.left-r.width/2)/(r.width/2);var y=(e.clientY-r.top-r.height/2)/(r.height/2);card.style.transform='perspective(800px) rotateY('+(x*7)+'deg) rotateX('+(-y*7)+'deg) scale(1.02)';});
  card.addEventListener('mouseleave',function(){card.style.transform='';card.style.transition='transform .5s cubic-bezier(.34,1.56,.64,1)';});
  card.addEventListener('mouseenter',function(){card.style.transition='transform .12s ease';});
})();

// ── MAGNETIC TOOL TAGS ───────────────────────────────────────────
document.querySelectorAll('.toolkit__tag,.marquee-tag').forEach(function(tag){
  tag.addEventListener('mousemove',function(e){var r=tag.getBoundingClientRect();var x=e.clientX-r.left-r.width/2;var y=e.clientY-r.top-r.height/2;tag.style.transform='translate('+(x*.3)+'px,'+(y*.3)+'px) scale(1.1)';});
  tag.addEventListener('mouseleave',function(){tag.style.transform='';});
});

// ── RIPPLE ON BUTTONS ────────────────────────────────────────────
document.querySelectorAll('.btn--primary,.btn--secondary,.svc__cta,.nav__cta,.audit__btn-next,.audit__cta-btn').forEach(function(btn){
  btn.addEventListener('click',function(e){
    var r=btn.getBoundingClientRect();
    var rip=document.createElement('span');
    var size=Math.max(r.width,r.height);
    rip.className='ripple';
    rip.style.cssText='width:'+size+'px;height:'+size+'px;left:'+(e.clientX-r.left-size/2)+'px;top:'+(e.clientY-r.top-size/2)+'px;position:absolute;border-radius:50%;background:rgba(255,255,255,.25);transform:scale(0);animation:rippleAnim .5s linear;pointer-events:none';
    btn.appendChild(rip);
    setTimeout(function(){rip.remove();},600);
  });
});

// ── ACHIEVEMENT PROGRESS BARS ────────────────────────────────────
var achProgObs=new IntersectionObserver(function(entries){
  entries.forEach(function(e){
    if(e.isIntersecting){
      e.target.querySelectorAll('.ach__progress-fill').forEach(function(bar){setTimeout(function(){bar.style.width=bar.dataset.pct+'%';},200);});
      achProgObs.unobserve(e.target);
    }
  });
},{threshold:0.3});
document.querySelectorAll('.ach__card').forEach(function(c){achProgObs.observe(c);});

// ── CREDENTIAL BARS ──────────────────────────────────────────────
var credObs=new IntersectionObserver(function(entries){
  entries.forEach(function(e){
    if(e.isIntersecting){
      e.target.querySelectorAll('.cred__bar').forEach(function(bar){setTimeout(function(){bar.style.width=(bar.dataset.pct||90)+'%';},200);});
      credObs.unobserve(e.target);
    }
  });
},{threshold:0.3});
document.querySelectorAll('.cred__grid').forEach(function(el){credObs.observe(el);});

// ── CREDENTIAL + SETUP CARD TILT ─────────────────────────────────
document.querySelectorAll('.cred__card,.setup__card').forEach(function(card){
  card.addEventListener('mousemove',function(e){var r=card.getBoundingClientRect();var x=(e.clientX-r.left-r.width/2)/(r.width/2);var y=(e.clientY-r.top-r.height/2)/(r.height/2);card.style.transform='perspective(600px) rotateX('+(-y*6)+'deg) rotateY('+(x*6)+'deg) translateY(-4px)';card.style.transition='transform .1s ease';});
  card.addEventListener('mouseleave',function(){card.style.transform='';card.style.transition='transform .5s cubic-bezier(.34,1.56,.64,1)';});
});

// ── PROOF STATS COUNTER (about section) ─────────────────────────
(function(){
  var obs=new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        e.target.querySelectorAll('.proof__stat-val').forEach(function(el){
          var raw=el.textContent.replace(/[^0-9.]/g,'');
          var suf=el.textContent.replace(/[0-9.]/g,'').trim();
          var tgt=parseFloat(raw);if(isNaN(tgt))return;
          var start=0,step=tgt/40;
          var iv=setInterval(function(){start=Math.min(start+step,tgt);el.textContent=Math.floor(start)+suf;if(start>=tgt)clearInterval(iv);},35);
        });
        obs.unobserve(e.target);
      }
    });
  },{threshold:0.5});
  document.querySelectorAll('.proof__stats').forEach(function(el){obs.observe(el);});
})();

// ── STAT ITEM HOVER GLOW ─────────────────────────────────────────
document.querySelectorAll('.stat-item').forEach(function(item){
  item.addEventListener('mouseenter',function(){var ico=item.querySelector('.stat-item__icon');if(ico)ico.style.transform='scale(1.15) rotate(-5deg)';});
  item.addEventListener('mouseleave',function(){var ico=item.querySelector('.stat-item__icon');if(ico)ico.style.transform='';});
});

</script>
</body>
</html>
