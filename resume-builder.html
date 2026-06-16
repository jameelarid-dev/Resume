<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Resume Builder</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=Inter:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --ink: #1a1a2e;
    --ink-soft: #4a4a6a;
    --ink-faint: #9898b8;
    --paper: #f7f6f2;
    --paper-warm: #eeeae0;
    --accent: #2d6a4f;
    --accent-light: #52b788;
    --accent-pale: #d8f3dc;
    --rule: #dddad0;
    --white: #ffffff;
    --danger: #c1121f;
    --serif: 'DM Serif Display', Georgia, serif;
    --sans: 'Inter', system-ui, sans-serif;
    --mono: 'JetBrains Mono', monospace;
    --shadow: 0 4px 24px rgba(26,26,46,0.10);
    --shadow-lg: 0 8px 48px rgba(26,26,46,0.16);
  }

  body {
    font-family: var(--sans);
    background: var(--paper);
    color: var(--ink);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }

  /* ── HEADER ── */
  header {
    background: var(--ink);
    padding: 18px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: sticky;
    top: 0;
    z-index: 100;
  }
  .logo {
    font-family: var(--serif);
    font-size: 1.5rem;
    color: var(--white);
    letter-spacing: -0.5px;
  }
  .logo span { color: var(--accent-light); }
  .header-actions { display: flex; gap: 12px; }
  .btn {
    font-family: var(--sans);
    font-size: 0.8rem;
    font-weight: 600;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    padding: 9px 20px;
    border-radius: 6px;
    border: none;
    cursor: pointer;
    transition: all 0.18s;
  }
  .btn-ghost {
    background: transparent;
    color: var(--paper-warm);
    border: 1.5px solid rgba(247,246,242,0.25);
  }
  .btn-ghost:hover { border-color: var(--accent-light); color: var(--accent-light); }
  .btn-primary {
    background: var(--accent);
    color: var(--white);
  }
  .btn-primary:hover { background: var(--accent-light); }
  .btn-danger {
    background: transparent;
    color: var(--danger);
    border: 1.5px solid var(--danger);
    font-size: 0.72rem;
    padding: 5px 12px;
  }
  .btn-danger:hover { background: var(--danger); color: #fff; }
  .btn-add {
    background: var(--accent-pale);
    color: var(--accent);
    border: none;
    font-size: 0.78rem;
    padding: 8px 16px;
    margin-top: 12px;
  }
  .btn-add:hover { background: var(--accent-light); color: #fff; }

  /* ── LAYOUT ── */
  .workspace {
    flex: 1;
    display: grid;
    grid-template-columns: 420px 1fr;
    min-height: calc(100vh - 58px);
  }

  /* ── EDITOR PANEL ── */
  .editor-panel {
    background: var(--white);
    border-right: 1px solid var(--rule);
    overflow-y: auto;
    max-height: calc(100vh - 58px);
    position: sticky;
    top: 58px;
  }

  .section-tabs {
    display: flex;
    border-bottom: 1px solid var(--rule);
    padding: 0 24px;
    gap: 0;
    overflow-x: auto;
  }
  .section-tabs button {
    font-family: var(--sans);
    font-size: 0.75rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    padding: 16px 16px;
    border: none;
    background: transparent;
    color: var(--ink-faint);
    cursor: pointer;
    border-bottom: 2.5px solid transparent;
    margin-bottom: -1px;
    white-space: nowrap;
    transition: all 0.15s;
  }
  .section-tabs button.active {
    color: var(--accent);
    border-bottom-color: var(--accent);
  }
  .section-tabs button:hover:not(.active) { color: var(--ink-soft); }

  .editor-section { display: none; padding: 28px 28px 40px; }
  .editor-section.active { display: block; }

  .field-group { margin-bottom: 20px; }
  .field-group label {
    display: block;
    font-size: 0.72rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.07em;
    color: var(--ink-soft);
    margin-bottom: 6px;
  }
  .field-group input,
  .field-group textarea,
  .field-group select {
    width: 100%;
    font-family: var(--sans);
    font-size: 0.88rem;
    color: var(--ink);
    background: var(--paper);
    border: 1.5px solid var(--rule);
    border-radius: 6px;
    padding: 10px 14px;
    transition: border-color 0.15s;
    outline: none;
  }
  .field-group input:focus,
  .field-group textarea:focus { border-color: var(--accent-light); background: var(--white); }
  .field-group textarea { resize: vertical; min-height: 80px; line-height: 1.5; }

  .field-row { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }

  .card-item {
    background: var(--paper);
    border: 1.5px solid var(--rule);
    border-radius: 10px;
    padding: 18px;
    margin-bottom: 14px;
    position: relative;
  }
  .card-item-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 14px;
  }
  .card-item-title {
    font-family: var(--mono);
    font-size: 0.72rem;
    font-weight: 500;
    color: var(--ink-soft);
    text-transform: uppercase;
    letter-spacing: 0.08em;
  }

  .skill-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 10px; }
  .skill-tag {
    display: flex;
    align-items: center;
    gap: 6px;
    background: var(--accent-pale);
    color: var(--accent);
    font-size: 0.78rem;
    font-weight: 500;
    padding: 5px 12px;
    border-radius: 20px;
  }
  .skill-tag button {
    background: none;
    border: none;
    cursor: pointer;
    font-size: 14px;
    color: var(--accent);
    line-height: 1;
    padding: 0;
  }
  .skill-input-row { display: flex; gap: 8px; }
  .skill-input-row input { flex: 1; }
  .skill-input-row .btn-primary { padding: 10px 16px; font-size: 0.78rem; text-transform: none; letter-spacing: 0; }

  /* ── PREVIEW PANEL ── */
  .preview-panel {
    overflow-y: auto;
    max-height: calc(100vh - 58px);
    padding: 40px;
    display: flex;
    flex-direction: column;
    align-items: center;
    background: #c9c4bb;
  }

  /* ── RESUME DOCUMENT ── */
  .resume-doc {
    background: var(--white);
    width: 794px;
    min-height: 1123px;
    box-shadow: var(--shadow-lg);
    padding: 64px 68px;
    font-family: var(--sans);
    color: var(--ink);
    position: relative;
  }

  /* Resume Header */
  .r-header { margin-bottom: 36px; padding-bottom: 28px; border-bottom: 2px solid var(--ink); }
  .r-name {
    font-family: var(--serif);
    font-size: 2.8rem;
    font-weight: 400;
    line-height: 1.1;
    letter-spacing: -1px;
    margin-bottom: 4px;
  }
  .r-title {
    font-size: 0.95rem;
    font-weight: 500;
    color: var(--accent);
    text-transform: uppercase;
    letter-spacing: 0.15em;
    margin-bottom: 14px;
  }
  .r-contact {
    display: flex;
    flex-wrap: wrap;
    gap: 6px 20px;
  }
  .r-contact-item {
    display: flex;
    align-items: center;
    gap: 5px;
    font-size: 0.78rem;
    color: var(--ink-soft);
  }
  .r-contact-item svg { flex-shrink: 0; }

  /* Resume Body */
  .r-body { display: grid; grid-template-columns: 2fr 1fr; gap: 36px; }

  .r-section { margin-bottom: 28px; }
  .r-section-title {
    font-family: var(--mono);
    font-size: 0.68rem;
    font-weight: 500;
    text-transform: uppercase;
    letter-spacing: 0.14em;
    color: var(--accent);
    border-bottom: 1px solid var(--accent-pale);
    padding-bottom: 6px;
    margin-bottom: 16px;
  }

  /* Summary */
  .r-summary {
    font-size: 0.85rem;
    line-height: 1.65;
    color: var(--ink-soft);
  }

  /* Experience / Education entries */
  .r-entry { margin-bottom: 20px; }
  .r-entry:last-child { margin-bottom: 0; }
  .r-entry-header { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 2px; }
  .r-entry-title { font-size: 0.9rem; font-weight: 600; }
  .r-entry-date {
    font-family: var(--mono);
    font-size: 0.7rem;
    color: var(--ink-faint);
    white-space: nowrap;
    margin-left: 8px;
    margin-top: 2px;
  }
  .r-entry-sub {
    font-size: 0.78rem;
    color: var(--accent);
    font-weight: 500;
    margin-bottom: 6px;
  }
  .r-entry-desc {
    font-size: 0.78rem;
    line-height: 1.6;
    color: var(--ink-soft);
  }

  /* Skills sidebar */
  .r-skills-list { display: flex; flex-direction: column; gap: 6px; }
  .r-skill-item { font-size: 0.78rem; color: var(--ink-soft); display: flex; align-items: center; gap: 8px; }
  .r-skill-dot {
    width: 5px; height: 5px;
    border-radius: 50%;
    background: var(--accent-light);
    flex-shrink: 0;
  }

  /* empty state */
  .r-empty {
    font-family: var(--mono);
    font-size: 0.72rem;
    color: var(--ink-faint);
    font-style: italic;
  }

  /* accent bar */
  .resume-doc::before {
    content: '';
    position: absolute;
    top: 0; left: 0;
    width: 5px;
    height: 100%;
    background: var(--accent);
    border-radius: 0;
  }

  .section-head {
    font-family: var(--serif);
    font-size: 1.4rem;
    color: var(--ink);
    margin-bottom: 4px;
  }
  .section-sub {
    font-size: 0.8rem;
    color: var(--ink-faint);
    margin-bottom: 24px;
    line-height: 1.4;
  }

  /* ── PRINT ── */
  @media print {
    header, .editor-panel, .preview-panel { display: none !important; }
    body { background: white; }
    .resume-doc { box-shadow: none; width: 100%; padding: 0; }
  }

  @media (max-width: 960px) {
    .workspace { grid-template-columns: 1fr; }
    .editor-panel { position: static; max-height: none; }
    .preview-panel { padding: 20px; }
    .resume-doc { width: 100%; min-height: auto; padding: 40px 32px; }
    .r-body { grid-template-columns: 1fr; }
  }

  /* Scrollbar */
  .editor-panel::-webkit-scrollbar,
  .preview-panel::-webkit-scrollbar { width: 5px; }
  .editor-panel::-webkit-scrollbar-track,
  .preview-panel::-webkit-scrollbar-track { background: transparent; }
  .editor-panel::-webkit-scrollbar-thumb,
  .preview-panel::-webkit-scrollbar-thumb { background: var(--rule); border-radius: 10px; }
</style>
</head>
<body>

<header>
  <div class="logo">re<span>sume</span>.build</div>
  <div class="header-actions">
    <button class="btn btn-ghost" onclick="clearAll()">Clear All</button>
    <button class="btn btn-primary" onclick="downloadPDF()">⬇ Download PDF</button>
  </div>
</header>

<div class="workspace">

  <!-- ── EDITOR ── -->
  <aside class="editor-panel">
    <nav class="section-tabs">
      <button class="active" onclick="switchTab(this,'tab-info')">Info</button>
      <button onclick="switchTab(this,'tab-summary')">Summary</button>
      <button onclick="switchTab(this,'tab-experience')">Experience</button>
      <button onclick="switchTab(this,'tab-education')">Education</button>
      <button onclick="switchTab(this,'tab-skills')">Skills</button>
    </nav>

    <!-- INFO -->
    <div id="tab-info" class="editor-section active">
      <p class="section-head">Personal Info</p>
      <p class="section-sub">Your identity at the top of the page.</p>
      <div class="field-group"><label>Full Name</label>
        <input id="name" type="text" placeholder="Jane Doe" oninput="render()"></div>
      <div class="field-group"><label>Job Title</label>
        <input id="title" type="text" placeholder="Senior Product Designer" oninput="render()"></div>
      <div class="field-row">
        <div class="field-group"><label>Email</label>
          <input id="email" type="email" placeholder="jane@example.com" oninput="render()"></div>
        <div class="field-group"><label>Phone</label>
          <input id="phone" type="tel" placeholder="+1 555 000 0000" oninput="render()"></div>
      </div>
      <div class="field-row">
        <div class="field-group"><label>Location</label>
          <input id="location" type="text" placeholder="San Francisco, CA" oninput="render()"></div>
        <div class="field-group"><label>Website / LinkedIn</label>
          <input id="website" type="text" placeholder="linkedin.com/in/jane" oninput="render()"></div>
      </div>
    </div>

    <!-- SUMMARY -->
    <div id="tab-summary" class="editor-section">
      <p class="section-head">Summary</p>
      <p class="section-sub">2–3 sentences that sell your story fast.</p>
      <div class="field-group"><label>Professional Summary</label>
        <textarea id="summary" rows="5" placeholder="Describe your background, what you bring, and what you're looking for..." oninput="render()"></textarea>
      </div>
    </div>

    <!-- EXPERIENCE -->
    <div id="tab-experience" class="editor-section">
      <p class="section-head">Experience</p>
      <p class="section-sub">List most recent first.</p>
      <div id="exp-list"></div>
      <button class="btn btn-add" onclick="addEntry('exp')">+ Add Position</button>
    </div>

    <!-- EDUCATION -->
    <div id="tab-education" class="editor-section">
      <p class="section-head">Education</p>
      <p class="section-sub">Degrees, certifications, bootcamps.</p>
      <div id="edu-list"></div>
      <button class="btn btn-add" onclick="addEntry('edu')">+ Add Education</button>
    </div>

    <!-- SKILLS -->
    <div id="tab-skills" class="editor-section">
      <p class="section-head">Skills</p>
      <p class="section-sub">Add tools, languages, and competencies.</p>
      <div class="skill-tags" id="skill-tags"></div>
      <div class="skill-input-row">
        <input id="skill-input" type="text" placeholder="e.g. Figma, Python, Leadership…" onkeydown="if(event.key==='Enter')addSkill()">
        <button class="btn btn-primary" onclick="addSkill()">Add</button>
      </div>
    </div>

  </aside>

  <!-- ── PREVIEW ── -->
  <main class="preview-panel">
    <div class="resume-doc" id="resume-doc">

      <!-- HEADER -->
      <div class="r-header">
        <div class="r-name" id="r-name">Your Name</div>
        <div class="r-title" id="r-title">Your Job Title</div>
        <div class="r-contact" id="r-contact"></div>
      </div>

      <!-- BODY -->
      <div class="r-body">
        <div class="r-main">

          <!-- Summary -->
          <div class="r-section" id="r-section-summary" style="display:none">
            <div class="r-section-title">Profile</div>
            <div class="r-summary" id="r-summary"></div>
          </div>

          <!-- Experience -->
          <div class="r-section">
            <div class="r-section-title">Experience</div>
            <div id="r-experience"><span class="r-empty">No experience added yet.</span></div>
          </div>

          <!-- Education -->
          <div class="r-section">
            <div class="r-section-title">Education</div>
            <div id="r-education"><span class="r-empty">No education added yet.</span></div>
          </div>

        </div>
        <div class="r-sidebar">

          <!-- Skills -->
          <div class="r-section">
            <div class="r-section-title">Skills</div>
            <div class="r-skills-list" id="r-skills"><span class="r-empty">No skills added yet.</span></div>
          </div>

        </div>
      </div>

    </div>
  </main>

</div>

<script>
  // ── STATE ──
  const state = {
    exp: [],
    edu: [],
    skills: []
  };

  // ── TABS ──
  function switchTab(btn, id) {
    document.querySelectorAll('.section-tabs button').forEach(b => b.classList.remove('active'));
    document.querySelectorAll('.editor-section').forEach(s => s.classList.remove('active'));
    btn.classList.add('active');
    document.getElementById(id).classList.add('active');
  }

  // ── DYNAMIC ENTRIES ──
  function addEntry(type) {
    const id = Date.now();
    if (type === 'exp') {
      state.exp.push({ id, company: '', role: '', start: '', end: '', desc: '' });
    } else {
      state.edu.push({ id, school: '', degree: '', year: '', desc: '' });
    }
    renderEditor(type);
    render();
  }

  function removeEntry(type, id) {
    if (type === 'exp') state.exp = state.exp.filter(e => e.id !== id);
    else state.edu = state.edu.filter(e => e.id !== id);
    renderEditor(type);
    render();
  }

  function renderEditor(type) {
    const list = document.getElementById(type === 'exp' ? 'exp-list' : 'edu-list');
    list.innerHTML = '';
    const entries = type === 'exp' ? state.exp : state.edu;

    entries.forEach((entry, i) => {
      const card = document.createElement('div');
      card.className = 'card-item';

      if (type === 'exp') {
        card.innerHTML = `
          <div class="card-item-header">
            <span class="card-item-title">Position ${i + 1}</span>
            <button class="btn btn-danger" onclick="removeEntry('exp',${entry.id})">Remove</button>
          </div>
          <div class="field-row">
            <div class="field-group"><label>Company</label>
              <input type="text" value="${esc(entry.company)}" placeholder="Acme Inc." oninput="state.exp[${i}].company=this.value;render()"></div>
            <div class="field-group"><label>Role</label>
              <input type="text" value="${esc(entry.role)}" placeholder="Product Manager" oninput="state.exp[${i}].role=this.value;render()"></div>
          </div>
          <div class="field-row">
            <div class="field-group"><label>Start</label>
              <input type="text" value="${esc(entry.start)}" placeholder="Jan 2021" oninput="state.exp[${i}].start=this.value;render()"></div>
            <div class="field-group"><label>End</label>
              <input type="text" value="${esc(entry.end)}" placeholder="Present" oninput="state.exp[${i}].end=this.value;render()"></div>
          </div>
          <div class="field-group"><label>Description</label>
            <textarea placeholder="Describe key responsibilities and achievements…" oninput="state.exp[${i}].desc=this.value;render()">${esc(entry.desc)}</textarea>
          </div>`;
      } else {
        card.innerHTML = `
          <div class="card-item-header">
            <span class="card-item-title">Entry ${i + 1}</span>
            <button class="btn btn-danger" onclick="removeEntry('edu',${entry.id})">Remove</button>
          </div>
          <div class="field-row">
            <div class="field-group"><label>School</label>
              <input type="text" value="${esc(entry.school)}" placeholder="MIT" oninput="state.edu[${i}].school=this.value;render()"></div>
            <div class="field-group"><label>Degree</label>
              <input type="text" value="${esc(entry.degree)}" placeholder="B.S. Computer Science" oninput="state.edu[${i}].degree=this.value;render()"></div>
          </div>
          <div class="field-group"><label>Year / Duration</label>
            <input type="text" value="${esc(entry.year)}" placeholder="2015 – 2019" oninput="state.edu[${i}].year=this.value;render()"></div>
          <div class="field-group"><label>Notes (optional)</label>
            <textarea placeholder="GPA, honors, relevant coursework…" oninput="state.edu[${i}].desc=this.value;render()">${esc(entry.desc)}</textarea>
          </div>`;
      }
      list.appendChild(card);
    });
  }

  // ── SKILLS ──
  function addSkill() {
    const input = document.getElementById('skill-input');
    const val = input.value.trim();
    if (!val || state.skills.includes(val)) return;
    state.skills.push(val);
    input.value = '';
    renderSkillTags();
    render();
  }

  function removeSkill(s) {
    state.skills = state.skills.filter(x => x !== s);
    renderSkillTags();
    render();
  }

  function renderSkillTags() {
    const el = document.getElementById('skill-tags');
    el.innerHTML = state.skills.map(s => `
      <span class="skill-tag">${esc(s)}
        <button onclick="removeSkill('${esc(s)}')" title="Remove">×</button>
      </span>`).join('');
  }

  // ── RENDER PREVIEW ──
  function render() {
    const name = v('name') || 'Your Name';
    const title = v('title') || 'Your Job Title';
    const email = v('email');
    const phone = v('phone');
    const location = v('location');
    const website = v('website');
    const summary = v('summary');

    document.getElementById('r-name').textContent = name;
    document.getElementById('r-title').textContent = title;

    // Contact
    const contactEl = document.getElementById('r-contact');
    const contacts = [
      email && `<span class="r-contact-item">${icon('email')}${esc(email)}</span>`,
      phone && `<span class="r-contact-item">${icon('phone')}${esc(phone)}</span>`,
      location && `<span class="r-contact-item">${icon('loc')}${esc(location)}</span>`,
      website && `<span class="r-contact-item">${icon('web')}${esc(website)}</span>`,
    ].filter(Boolean);
    contactEl.innerHTML = contacts.join('') || '<span class="r-empty">Add contact details</span>';

    // Summary
    const summarySection = document.getElementById('r-section-summary');
    if (summary) {
      summarySection.style.display = '';
      document.getElementById('r-summary').textContent = summary;
    } else {
      summarySection.style.display = 'none';
    }

    // Experience
    const expEl = document.getElementById('r-experience');
    if (state.exp.length === 0) {
      expEl.innerHTML = '<span class="r-empty">No experience added yet.</span>';
    } else {
      expEl.innerHTML = state.exp.map(e => `
        <div class="r-entry">
          <div class="r-entry-header">
            <span class="r-entry-title">${esc(e.role || 'Role')}</span>
            <span class="r-entry-date">${esc(e.start)}${e.start && e.end ? ' – ' : ''}${esc(e.end)}</span>
          </div>
          <div class="r-entry-sub">${esc(e.company || 'Company')}</div>
          ${e.desc ? `<div class="r-entry-desc">${esc(e.desc).replace(/\n/g,'<br>')}</div>` : ''}
        </div>`).join('');
    }

    // Education
    const eduEl = document.getElementById('r-education');
    if (state.edu.length === 0) {
      eduEl.innerHTML = '<span class="r-empty">No education added yet.</span>';
    } else {
      eduEl.innerHTML = state.edu.map(e => `
        <div class="r-entry">
          <div class="r-entry-header">
            <span class="r-entry-title">${esc(e.degree || 'Degree')}</span>
            <span class="r-entry-date">${esc(e.year)}</span>
          </div>
          <div class="r-entry-sub">${esc(e.school || 'School')}</div>
          ${e.desc ? `<div class="r-entry-desc">${esc(e.desc)}</div>` : ''}
        </div>`).join('');
    }

    // Skills
    const skillsEl = document.getElementById('r-skills');
    if (state.skills.length === 0) {
      skillsEl.innerHTML = '<span class="r-empty">No skills added yet.</span>';
    } else {
      skillsEl.innerHTML = state.skills.map(s =>
        `<div class="r-skill-item"><div class="r-skill-dot"></div>${esc(s)}</div>`).join('');
    }
  }

  // ── UTILS ──
  function v(id) { return document.getElementById(id)?.value?.trim() || ''; }

  function esc(s) {
    if (!s) return '';
    return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');
  }

  function icon(type) {
    const icons = {
      email: `<svg width="12" height="12" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>`,
      phone: `<svg width="12" height="12" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 9.81 19.79 19.79 0 01.01 1.18 2 2 0 012 0h3a2 2 0 012 1.72c.13 1.05.37 2.07.71 3.06a2 2 0 01-.45 2.11L6.09 8.06a16 16 0 006.85 6.85l1.17-1.17a2 2 0 012.11-.45c.99.34 2.01.58 3.06.71A2 2 0 0122 16.92z"/></svg>`,
      loc: `<svg width="12" height="12" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>`,
      web: `<svg width="12" height="12" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"/></svg>`,
    };
    return icons[type] || '';
  }

  function clearAll() {
    if (!confirm('Clear all resume data?')) return;
    ['name','title','email','phone','location','website','summary'].forEach(id => {
      const el = document.getElementById(id);
      if (el) el.value = '';
    });
    state.exp = [];
    state.edu = [];
    state.skills = [];
    renderEditor('exp');
    renderEditor('edu');
    renderSkillTags();
    render();
  }

  function downloadPDF() {
    window.print();
  }

  // ── INIT ──
  render();
</script>
</body>
</html>
