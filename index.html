<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>privshell · Android power tools</title>
<meta name="description" content="Open-source Android power tools by privshell: root, KernelSU, Shizuku and ADB. VOID, PULSE and KernelSU WebUI modules.">
<meta property="og:title" content="privshell · Android power tools">
<meta property="og:description" content="Root, KernelSU, Shizuku and ADB tools. Open source.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://privshell.github.io/">
<meta property="og:image" content="https://privshell.github.io/og.jpg">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image" content="https://privshell.github.io/og.jpg">
<meta name="theme-color" content="#f7f5fa">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 32 32'%3E%3Crect x='7' y='4' width='18' height='24' rx='2' fill='%231e1a1a'/%3E%3Ccircle cx='11' cy='8' r='1.6' fill='%23eadd17'/%3E%3Cpath d='M3 9h4M3 14h4M3 19h4M3 24h4M25 9h4M25 14h4M25 19h4M25 24h4' stroke='%238942bd' stroke-width='2'/%3E%3C/svg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=IBM+Plex+Mono:wght@400;600&family=Nunito:wght@400;600;800&display=swap">
<style>
/* privshell data book
   Subject: one developer's open-source Android power tools (root, KernelSU, Shizuku, ADB).
   Spine: a 1970s semiconductor data book. Each project is a part; the hero is a DIP-8 chip
   whose pins are the real interfaces the tools talk to. Pins are the filters.
   Color jobs: violet = root / KernelSU, teal = no-root (Shizuku, ADB), yellow = signal + stars, ink = chip body. */
:root{
  --paper:oklch(0.975 0.006 308); --card:oklch(0.993 0.003 308); --ink:#1e1a1a; --text:oklch(0.285 0.022 308);
  --muted:oklch(0.496 0.034 308); --line:oklch(0.9 0.012 308);
  --violet:#8942bd; --violet-soft:oklch(0.575 0.17 307 / .12); --teal:#0f8d7b; --teal-soft:oklch(0.55 0.1 180 / .12); --yellow:#eadd17;
  --mono:"IBM Plex Mono",ui-monospace,monospace; --disp:"Bebas Neue",Impact,sans-serif; --body:Nunito,system-ui,sans-serif;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--text);font:16px/1.55 var(--body);-webkit-font-smoothing:antialiased}
a{color:inherit}
.wrap{max-width:1180px;margin:0 auto;padding:0 22px}
header.top{display:flex;justify-content:space-between;align-items:center;padding:20px 0}
.mark{font:600 14px var(--mono);letter-spacing:.04em;text-decoration:none}
.mark b{color:var(--violet)}
.toplinks{display:flex;gap:18px;font:14px var(--mono)}
.toplinks a{text-decoration:none;border-bottom:2px solid transparent}
.toplinks a:hover{border-color:var(--yellow)}

/* hero */
.hero{display:grid;grid-template-columns:.9fr 1.1fr;align-items:center;gap:24px;padding:24px 0 40px;min-height:min(78vh,720px)}
.hero h1{font:400 clamp(92px,15.5vw,210px)/.8 var(--disp);letter-spacing:.005em;color:var(--ink);margin:0}
.hero h1 span{color:var(--violet)}
.tag{font:800 clamp(20px,2.4vw,28px)/1.25 var(--body);color:var(--ink);margin:22px 0 0;max-width:22ch}
.tag em{font-style:normal;background:linear-gradient(transparent 62%,var(--yellow) 62%)}
.stats{display:flex;flex-wrap:wrap;gap:8px 22px;margin-top:26px;font:14px var(--mono);color:var(--muted)}
.stats b{color:var(--ink);font-weight:600}
.chipbox{position:relative}
svg.chip{width:100%;height:auto;display:block;overflow:visible}
.pin{cursor:pointer}
.pin .leg{fill:#b9b3c0;transition:fill .25s}
.pin .trace{stroke:var(--line);stroke-width:3;transition:stroke .25s}
.pin text{font:600 24px var(--mono);fill:var(--muted);transition:fill .25s;letter-spacing:.02em}
.pin .num{font:400 15px var(--mono);fill:#8c8496}
.pin:hover text,.pin:focus-visible text{fill:var(--ink)}
.pin.lit .leg{fill:var(--yellow)}
.pin.on .leg{fill:var(--violet)} .pin.on .trace{stroke:var(--violet)} .pin.on text{fill:var(--violet)}
.pin.on.nr .leg{fill:var(--teal)} .pin.on.nr .trace{stroke:var(--teal)} .pin.on.nr text{fill:var(--teal)}
.pin:focus{outline:none}
.pin:focus-visible .hit{stroke:var(--violet);stroke-width:2;stroke-dasharray:4 4}
.body-label{font:400 118px var(--disp);fill:var(--paper)}
.body-sub{font:400 15px var(--mono);fill:#a59fb0;letter-spacing:.12em}
.led{fill:var(--yellow);animation:led 3.2s ease-in-out infinite}
@keyframes led{0%,100%{opacity:.35}50%{opacity:1}}
.sig{fill:var(--yellow)}
.hint{font:14px var(--mono);color:var(--muted);text-align:center;margin-top:6px}
.hint b{color:var(--ink);font-weight:600}

/* series */
.series{padding:56px 0 8px}
.shead{display:flex;align-items:baseline;gap:18px;flex-wrap:wrap;margin-bottom:22px}
.shead h2{font:400 clamp(56px,8vw,104px)/.85 var(--disp);color:var(--ink);margin:0}
.shead p{margin:0;font:800 18px var(--body);color:var(--muted)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(290px,1fr));gap:14px}
.part{position:relative;background:var(--card);border-radius:6px;padding:20px 20px 18px;text-decoration:none;display:flex;flex-direction:column;gap:10px;
  box-shadow:0 1px 0 var(--line),0 0 0 1px var(--line);transition:transform .25s,box-shadow .25s,opacity .35s}
.part:hover{transform:translateY(-3px);box-shadow:0 0 0 1px var(--line),0 14px 30px -18px oklch(0.3 0.08 308 / .45)}
.part.wide{grid-column:span 2}
.part.root{border-top:5px solid var(--violet)} .part.nr{border-top:5px solid var(--teal)} .part.plain{border-top:5px solid var(--ink)}
.part h3{margin:0;font:400 40px/.9 var(--disp);color:var(--ink);letter-spacing:.01em}
.part.wide h3{font-size:58px}
.part h3 i{font-style:normal;color:var(--violet)} .part.nr h3 i{color:var(--teal)}
.part p{margin:0;font-size:16px;max-width:46ch}
.pins{display:flex;flex-wrap:wrap;gap:6px;margin-top:auto;padding-top:6px}
.pins span{font:600 14px var(--mono);padding:2px 8px;border-radius:3px;background:var(--violet-soft);color:var(--violet)}
.pins span.nr{background:var(--teal-soft);color:var(--teal)}
.pins span.n{background:oklch(0.9 0.01 308);color:var(--text)}
.meta{display:flex;justify-content:space-between;align-items:center;font:14px var(--mono);color:var(--muted)}
.meta .st{color:var(--ink)} .meta .st::before{content:"★ ";color:#c9b800}
.soon{position:absolute;top:16px;right:16px;font:600 14px var(--mono);color:var(--ink);background:var(--yellow);padding:1px 8px;border-radius:3px}
.part.dim{opacity:.18;transform:none;pointer-events:none}
.series.empty{display:none}

footer{margin-top:80px;background:var(--ink);color:#d9d3e2}
footer .wrap{display:flex;justify-content:space-between;align-items:end;gap:24px;flex-wrap:wrap;padding:46px 22px 40px}
footer h2{font:400 clamp(48px,7vw,88px)/.85 var(--disp);color:var(--paper);margin:0}
footer h2 span{color:var(--yellow)}
footer p{margin:10px 0 0;font:15px var(--mono);color:#a59fb0}
footer .links{display:flex;gap:10px;flex-wrap:wrap}
footer .links a{font:600 14px var(--mono);text-decoration:none;padding:10px 14px;border-radius:4px;background:#2c2630;color:var(--paper)}
footer .links a.p{background:var(--yellow);color:var(--ink)}
footer .links a:hover{filter:brightness(1.15)}

@media (max-width:820px){
  .hero{grid-template-columns:1fr;min-height:0;padding-top:8px;gap:8px}
  .part.wide{grid-column:auto} .part.wide h3{font-size:46px}
  .toplinks a.hide-s{display:none}
}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<div class="wrap">
  <header class="top">
    <a class="mark" href="#">privshell<b>#</b></a>
    <nav class="toplinks"><a href="#void">VOID</a><a href="#pulse" class="hide-s">PULSE</a><a href="#modules">Modules</a><a href="https://github.com/privshell">GitHub ↗</a></nav>
  </header>

  <section class="hero">
    <div>
      <h1>PRIV<br><span>SHELL</span></h1>
      <p class="tag">Open-source <em>Android power tools.</em> Root when you have it, Shizuku when you don't.</p>
      <div class="stats" id="stats"><span><b id="sN">8</b> projects</span><span><b id="sS">38</b> stars</span><span>updated <b id="sU">this week</b></span></div>
    </div>
    <div class="chipbox">
      <svg class="chip" id="chip" viewBox="0 0 600 330" role="group" aria-label="Filter projects by interface"></svg>
      <div class="hint" id="hint">Tap a pin to filter · <b>RST</b> shows all</div>
    </div>
  </section>
</div>

<main class="wrap" id="catalog"></main>

<footer>
  <div class="wrap">
    <div><h2>BUILT ON THE<br><span>DEVICE IT RUNS ON.</span></h2><p>Every release is tested on a rooted Redmi Note 14 first.</p></div>
    <div class="links"><a class="p" href="https://github.com/privshell">github.com/privshell</a><a href="https://github.com/privshell/privshell/blob/main/DONATE.md">Support the work</a></div>
  </div>
</footer>

<script>
'use strict';
const USER = 'privshell';
const NR = new Set(['SHIZUKU', 'ADB']);            /* no-root interfaces get teal */
const PINS = ['ROOT', 'KSU', 'SHIZUKU', 'ADB', 'APP', 'SHEVERY', 'WEBUI', 'RST'];
const SERIES = [
  { id: 'void', name: 'VOID', line: 'Own every app, packet and wake-up.' },
  { id: 'pulse', name: 'PULSE', line: 'Battery and installs, done properly.' },
  { id: 'modules', name: '// MODULES', line: 'KernelSU tools with a WebUI, inside your root manager.' },
  { id: 'lab', name: 'LAB', line: 'Hubs, audits and experiments.' }
];
/* Curated parts. Live stars and dates come from the GitHub API. */
const PARTS = [
  { r: 'void-apps', n: 'VOID // APPS', s: 'void', d: 'Power app manager: freeze, debloat, permissions, services and boot.', p: ['ROOT', 'SHIZUKU', 'ADB', 'APP'], l: 'Kotlin', st: 14, w: 1 },
  { r: 'pulse-battery', n: 'PULSE // BATTERY', s: 'pulse', d: 'Battery and wakelock doctor, with a built-in backup vault.', p: ['SHIZUKU', 'ROOT', 'APP'], l: 'Kotlin', st: 13, w: 1 },
  { r: 'orbit-store', n: 'ORBIT // STORE', s: 'modules', d: 'A module store inside your root manager. Four catalogs, curated lists, sha256 checked.', p: ['ROOT', 'KSU', 'WEBUI'], st: 0, w: 1 },
  { r: 'aegis-firewall', n: 'AEGIS // FIREWALL', s: 'modules', d: 'Kernel-level per-app firewall.', p: ['ROOT', 'KSU', 'WEBUI'], st: 0 },
  { r: 'apex-apps', n: 'APEX // APPS', s: 'modules', d: 'App manager with snapshots and reversible states.', p: ['ROOT', 'KSU', 'WEBUI'], st: 0 },
  { r: 'selinux-manager', n: 'SELINUX // MANAGER', s: 'modules', d: 'Modes, policy rules and a denial inspector. Every change is read back.', p: ['ROOT', 'KSU', 'WEBUI'], st: 0 },
  { r: 'android-app-hub', n: 'APP // HUB', s: 'lab', d: 'Seven Android app directories in one self-hosted Termux dashboard.', p: [], tags: ['TERMUX'], l: 'Python', st: 4 },
  { r: 'awesome-shizuku', n: 'AWESOME // SHIZUKU', s: 'lab', d: 'Curated list of awesome Android apps making use of Shizuku.', p: ['SHIZUKU'], l: 'Python', st: 2 }
];
const HIDE = new Set([USER, USER + '.github.io']);
let filter = '';

const esc = s => String(s == null ? '' : s).replace(/[&<>"']/g, c => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[c]));
const kind = p => p.p.includes('ROOT') && !p.p.some(x => NR.has(x)) ? 'root' : p.p.some(x => NR.has(x)) ? 'nr' : 'plain';
function ago(iso) {
  const d = (Date.now() - Date.parse(iso)) / 86400000; if (!isFinite(d)) return '';
  if (d < 1) return 'today'; if (d < 2) return 'yesterday'; if (d < 30) return `${d | 0} days ago`;
  return new Date(iso).toLocaleDateString('en', { month: 'short', year: 'numeric' });
}
function nameHtml(n) { const i = n.indexOf('//'); return i < 0 ? esc(n) : `${esc(n.slice(0, i))}<i>//</i>${esc(n.slice(i + 2))}`; }

/* ---------- chip ---------- */
const svg = document.getElementById('chip'), NS = 'http://www.w3.org/2000/svg';
const el = (t, a, p) => { const e = document.createElementNS(NS, t); for (const k in a) e.setAttribute(k, a[k]); (p || svg).appendChild(e); return e; };
const ROWS = [80, 140, 200, 260];
const pinEls = [], traces = [];
let chipCount, chipSub;
function chipText() { const n = PARTS.filter(p => !filter || p.p.includes(filter)).length; chipCount.textContent = n; chipSub.textContent = (filter || 'ALL') + ' · PROJECTS'; }
function buildChip() {
  el('rect', { x: 180, y: 30, width: 240, height: 270, rx: 10, fill: '#1e1a1a' });
  el('path', { d: 'M282 30a18 18 0 0 0 36 0', fill: 'oklch(0.975 0.006 308)' });
  el('circle', { class: 'led', cx: 208, cy: 58, r: 8 });
  chipCount = el('text', { class: 'body-label', x: 300, y: 196, 'text-anchor': 'middle' });
  chipSub = el('text', { class: 'body-sub', x: 300, y: 230, 'text-anchor': 'middle' });
  const sub2 = el('text', { class: 'body-sub', x: 300, y: 278, 'text-anchor': 'middle' }); sub2.textContent = 'PRIVSHELL · MT6789';
  PINS.forEach((name, i) => {
    const left = i < 4, y = left ? ROWS[i] : ROWS[7 - i];
    const g = el('g', { class: 'pin' + (NR.has(name) ? ' nr' : ''), tabindex: 0, role: 'button', 'aria-label': name === 'RST' ? 'Show all projects' : 'Show ' + name + ' projects', 'data-pin': name });
    const x0 = left ? 30 : 450, x1 = left ? 150 : 570;
    el('rect', { class: 'hit', x: left ? 14 : 446, y: y - 40, width: 156, height: 56, fill: 'transparent', rx: 6 }, g);
    el('line', { class: 'trace', x1: x0, y1: y, x2: x1, y2: y }, g);
    el('rect', { class: 'leg', x: left ? 150 : 420, y: y - 9, width: 30, height: 18, rx: 2 }, g);
    const t = el('text', { x: left ? 30 : 570, y: y - 12, 'text-anchor': left ? 'start' : 'end' }, g); t.textContent = name;
    const nm = el('text', { class: 'num', x: left ? 192 : 408, y: y + 5, 'text-anchor': left ? 'start' : 'end' }, g); nm.textContent = i + 1;
    g.addEventListener('click', () => setFilter(name));
    g.addEventListener('keydown', e => { if (e.key === 'Enter' || e.key === ' ') { e.preventDefault(); setFilter(name); } });
    pinEls.push(g); traces.push({ left, y });
  });
}
/* power-on: pins light 1 to 8, then a signal keeps travelling out along the traces */
function powerOn() {
  if (matchMedia('(prefers-reduced-motion: reduce)').matches) return;
  pinEls.forEach((g, i) => setTimeout(() => { g.classList.add('lit'); setTimeout(() => g.classList.remove('lit'), 420); }, 260 + i * 110));
  const dots = [];
  function spawn() {
    const k = filter && filter !== 'RST' ? PINS.indexOf(filter) : Math.random() * 7 | 0;
    const t = traces[k]; if (!t) return;
    dots.push({ c: el('circle', { class: 'sig', r: 5, cy: t.y, cx: t.left ? 150 : 450 }), t, x: t.left ? 150 : 450, v: t.left ? -2.2 : 2.2 });
  }
  let last = 0;
  (function tick(ts) {
    if (ts - last > (filter && filter !== 'RST' ? 700 : 1500)) { spawn(); last = ts; }
    for (let i = dots.length - 1; i >= 0; i--) {
      const d = dots[i]; d.x += d.v; d.c.setAttribute('cx', d.x);
      const end = d.t.left ? d.x < 30 : d.x > 570;
      d.c.setAttribute('opacity', Math.max(0, Math.min(1, Math.abs(d.x - (d.t.left ? 30 : 570)) / 40)));
      if (end) { d.c.remove(); dots.splice(i, 1); }
    }
    requestAnimationFrame(tick);
  })(0);
}

/* ---------- catalog ---------- */
function partHtml(p) {
  const k = kind(p);
  const pins = p.p.map(x => `<span class="${NR.has(x) ? 'nr' : ''}">${esc(x)}</span>`).concat((p.tags || []).map(x => `<span class="n">${esc(x)}</span>`));
  const meta = [p.l || 'JavaScript', p.upd ? 'updated ' + ago(p.upd) : ''].filter(Boolean).join(' · ');
  return `<a class="part ${k}${p.w ? ' wide' : ''}" href="https://github.com/${USER}/${esc(p.r)}" data-pins="${esc(p.p.join(' '))}">
    ${p.soon ? '<span class="soon">TESTING</span>' : ''}<h3>${nameHtml(p.n)}</h3><p>${esc(p.d)}</p>
    <div class="pins">${pins.join('')}</div><div class="meta"><span>${esc(meta)}</span>${p.st ? `<span class="st">${p.st}</span>` : ''}</div></a>`;
}
function render() {
  document.getElementById('catalog').innerHTML = SERIES.map(s => {
    const list = PARTS.filter(p => p.s === s.id);
    if (!list.length) return '';
    return `<section class="series" id="${s.id}"><div class="shead"><h2>${esc(s.name)}</h2><p>${esc(s.line)}</p></div><div class="grid">${list.map(partHtml).join('')}</div></section>`;
  }).join('');
  applyFilter(); chipText();
  const stars = PARTS.reduce((a, p) => a + (p.st || 0), 0);
  const latest = PARTS.map(p => p.upd).filter(Boolean).sort().pop();
  document.getElementById('sN').textContent = PARTS.length;
  document.getElementById('sS').textContent = stars;
  if (latest) document.getElementById('sU').textContent = ago(latest);
}
function setFilter(name) {
  filter = name === 'RST' || name === filter ? '' : name;
  pinEls.forEach(g => g.classList.toggle('on', g.dataset.pin === filter));
  const n = PARTS.filter(p => !filter || p.p.includes(filter)).length;
  document.getElementById('hint').innerHTML = filter ? `<b>${esc(filter)}</b> · ${n} project${n === 1 ? '' : 's'} · RST shows all` : 'Tap a pin to filter · <b>RST</b> shows all';
  applyFilter(); chipText();
  if (filter) { const first = document.querySelector('.part:not(.dim)'); if (first && first.getBoundingClientRect().top > innerHeight) first.closest('.series').scrollIntoView({ behavior: 'smooth' }); }
}
function applyFilter() {
  document.querySelectorAll('.part').forEach(a => a.classList.toggle('dim', !!filter && !a.dataset.pins.split(' ').includes(filter)));
  document.querySelectorAll('.series').forEach(s => s.classList.toggle('empty', !!filter && !s.querySelector('.part:not(.dim)')));
}
/* hovering a part lights its pins on the chip */
document.addEventListener('mouseover', e => {
  const a = e.target.closest('.part'); const set = a ? a.dataset.pins.split(' ') : [];
  pinEls.forEach(g => g.classList.toggle('lit', set.includes(g.dataset.pin)));
});

/* ---------- live data ---------- */
const TOPIC = { root: 'ROOT', kernelsu: 'KSU', shizuku: 'SHIZUKU', adb: 'ADB', 'shevery-modules': 'SHEVERY', webui: 'WEBUI' };
async function live() {
  try {
    const res = await fetch(`https://api.github.com/users/${USER}/repos?per_page=100&sort=pushed`);
    if (!res.ok) return;
    const repos = await res.json();
    const byName = new Map(repos.map(r => [r.name.toLowerCase(), r]));
    PARTS.forEach(p => { const r = byName.get(p.r.toLowerCase()); if (r) { p.st = r.stargazers_count; p.upd = r.pushed_at; if (r.language) p.l = r.language; } });
    const known = new Set(PARTS.map(p => p.r.toLowerCase()));
    repos.filter(r => !r.fork && !r.archived && !known.has(r.name.toLowerCase()) && !HIDE.has(r.name)).forEach(r => {
      const pins = [...new Set((r.topics || []).map(t => TOPIC[t]).filter(Boolean))];
      const desc = (r.description || '').split(':').slice(-1)[0].trim() || 'New project.';
      PARTS.push({ r: r.name, n: r.name.replace(/[-_]+/g, ' ').toUpperCase(), s: 'lab', d: desc.length > 110 ? desc.slice(0, 107) + '...' : desc, p: pins, l: r.language, st: r.stargazers_count, upd: r.pushed_at });
    });
    render();
  } catch (e) { /* offline or rate limited: the curated copy stays */ }
}

buildChip(); render(); powerOn(); live();
</script>
</body>
</html>
