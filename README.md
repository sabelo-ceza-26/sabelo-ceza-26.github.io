<style>
/* ---------- CV hero ---------- */
/* Hide the GitHub Pages theme's duplicate site title; the hero below carries the name. */
.markdown-body > h1:first-child {
  display: none;
}

.cv-hero {
  text-align: center;
  padding: 2.5rem 1rem 1.5rem;
}

h2#quick-navigation {
  margin: 2.5rem 0 1rem;
  padding-bottom: 0 !important;
  border-bottom: 0 !important;
  text-align: center;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 5px;
  text-transform: uppercase;
  color: #94a3b8;
}

.cv-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 8px 20px;
  border-radius: 999px;
  background: linear-gradient(135deg, rgba(66, 185, 131, 0.16) 0%, rgba(82, 125, 122, 0.16) 100%);
  border: 1px solid rgba(66, 185, 131, 0.6);
  color: #0f766e;
  font-weight: 700;
  letter-spacing: 5px;
  text-transform: uppercase;
  font-size: 11px;
}

.cv-name {
  margin: 1.2rem 0 0.4rem;
  font-size: 46px;
  font-weight: 800;
  letter-spacing: -1.2px;
  color: #0f172a;
  line-height: 1.1;
}

.cv-tagline {
  margin: 0 0 1.4rem;
  color: #475569;
  font-size: 16px;
  font-weight: 500;
}

.cv-hero-meta {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
}

.cv-hero-pill {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 8px 16px;
  border-radius: 999px;
  background: linear-gradient(135deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e2e8f0;
  color: #334155;
  font-size: 13px;
  font-weight: 600;
  box-shadow: 0 12px 30px -24px rgba(15, 23, 42, 0.9);
}

.cv-hero-pill svg {
  width: 15px;
  height: 15px;
  color: #0f766e;
}

/* ---------- Section headings ---------- */
.cv-section {
  margin: 3rem 0;
}

.cv-section-head {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 1.4rem;
}

.cv-section-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 auto;
  width: 46px;
  height: 46px;
  border-radius: 14px;
  background: linear-gradient(135deg, #42b983 0%, #527d7a 100%);
  color: #ffffff;
  box-shadow: 0 20px 40px -22px rgba(66, 185, 131, 0.9);
}

.cv-section-icon svg {
  width: 22px;
  height: 22px;
}

.cv-section-kicker {
  display: block;
  margin-bottom: 2px;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #94a3b8;
}

.cv-section-title {
  margin: 0;
  font-size: 24px;
  font-weight: 800;
  line-height: 1.2;
  color: #0f172a;
}

.cv-name,
.cv-section-title,
.cv-role,
.cv-edu-title,
.cv-ref-name,
.cv-video-title,
.wil-card-title {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
}

.cv-section-note {
  margin: -0.6rem 0 1.4rem;
  color: #64748b;
  font-size: 14px;
}

/* ---------- Cards ---------- */
.cv-card {
  position: relative;
  padding: 28px 32px;
  border-radius: 20px;
  background: radial-gradient(circle at top left, rgba(66, 185, 131, 0.1), transparent 45%), linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e5e7eb;
  box-shadow: 0 40px 70px -55px rgba(15, 23, 42, 0.9);
  transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
}

.cv-card:hover {
  transform: translateY(-4px);
  border-color: rgba(66, 185, 131, 0.7);
  box-shadow: 0 45px 75px -50px rgba(66, 185, 131, 0.45);
}

.cv-card + .cv-card {
  margin-top: 18px;
}

.cv-card-head {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 16px;
  margin-bottom: 18px;
}

.cv-role {
  margin: 0;
  font-size: 20px;
  font-weight: 700;
  color: #0f172a;
}

.cv-org {
  margin: 4px 0 0;
  font-size: 14px;
  font-weight: 600;
  color: #0f766e;
}

.cv-date-pill {
  display: inline-flex;
  align-items: center;
  padding: 6px 14px;
  border-radius: 999px;
  background: rgba(66, 185, 131, 0.12);
  border: 1px solid rgba(66, 185, 131, 0.35);
  color: #0f766e;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.5px;
  white-space: nowrap;
}

.cv-summary {
  margin: 0;
  color: #475569;
  font-size: 16px;
  line-height: 1.9;
}

.cv-summary strong {
  color: #0f172a;
}

.cv-list {
  list-style: none;
  margin: 0;
  padding: 0;
}

.cv-list li {
  position: relative;
  margin: 0 0 10px;
  padding-left: 24px;
  color: #475569;
  font-size: 15px;
  line-height: 1.8;
}

.cv-list li:last-child {
  margin-bottom: 0;
}

.cv-list li::before {
  content: "";
  position: absolute;
  top: 0.72em;
  left: 2px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: linear-gradient(135deg, #42b983 0%, #527d7a 100%);
  box-shadow: 0 0 0 3px rgba(66, 185, 131, 0.14);
}

/* ---------- Contact ---------- */
.cv-contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 14px;
}

.cv-contact {
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 16px 18px;
  border-radius: 16px;
  text-decoration: none !important;
  background: linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e2e8f0;
  box-shadow: 0 24px 50px -40px rgba(15, 23, 42, 0.8);
  transition: all 0.25s ease;
}

.cv-contact:hover {
  transform: translateY(-3px);
  border-color: rgba(66, 185, 131, 0.8);
  box-shadow: 0 30px 60px -35px rgba(66, 185, 131, 0.5);
}

.cv-contact-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 auto;
  width: 38px;
  height: 38px;
  border-radius: 12px;
  background: rgba(66, 185, 131, 0.12);
  color: #0f766e;
}

.cv-contact-icon svg {
  width: 18px;
  height: 18px;
}

.cv-contact-label {
  display: block;
  margin-bottom: 2px;
  font-size: 9px;
  font-weight: 700;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #94a3b8;
}

.cv-contact-value {
  display: block;
  color: #1e293b;
  font-size: 14px;
  font-weight: 600;
  word-break: break-word;
}

/* ---------- Education ---------- */
.cv-edu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
  gap: 18px;
}

.cv-edu {
  display: flex;
  flex-direction: column;
  gap: 8px;
  padding: 24px;
  border-radius: 18px;
  background: linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e5e7eb;
  box-shadow: 0 30px 60px -50px rgba(15, 23, 42, 0.9);
  transition: all 0.25s ease;
}

.cv-edu:hover {
  transform: translateY(-4px);
  border-color: rgba(66, 185, 131, 0.7);
  box-shadow: 0 40px 70px -45px rgba(66, 185, 131, 0.4);
}

.cv-edu-type {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #0f766e;
}

.cv-edu-title {
  margin: 0;
  font-size: 17px;
  font-weight: 700;
  line-height: 1.4;
  color: #0f172a;
}

.cv-edu-org {
  margin: 0;
  color: #475569;
  font-size: 14px;
  font-weight: 600;
}

.cv-edu .cv-date-pill {
  align-self: flex-start;
  margin-top: 8px;
}

/* ---------- Tags ---------- */
.cv-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 18px;
}

.cv-tag {
  padding: 6px 14px;
  border-radius: 999px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  color: #334155;
  font-size: 12px;
  font-weight: 600;
}

/* ---------- Projects grid ---------- */
.cv-projects-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 26px;
  margin: 2.5rem 0;
}

@media (max-width: 860px) {
  .cv-projects-grid {
    grid-template-columns: 1fr;
  }
}

/* Keep the metadata pills compact inside the narrower project cards. */
.cv-projects-grid .wil-card-meta {
  grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
}

.cv-projects-grid .wil-card-content {
  padding: 26px;
}

.cv-projects-grid .wil-card-title {
  font-size: 22px;
}

/* ---------- Skills ---------- */
.cv-skill-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
  gap: 18px;
}

.cv-skill {
  padding: 24px;
  border-radius: 18px;
  background: linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e5e7eb;
  box-shadow: 0 30px 60px -50px rgba(15, 23, 42, 0.9);
  transition: all 0.25s ease;
}

.cv-skill:hover {
  transform: translateY(-4px);
  border-color: rgba(66, 185, 131, 0.7);
  box-shadow: 0 40px 70px -45px rgba(66, 185, 131, 0.4);
}

.cv-skill-head {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 14px;
}

.cv-skill-dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: linear-gradient(135deg, #42b983 0%, #527d7a 100%);
}

.cv-skill-label {
  font-size: 11px;
  font-weight: 800;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #0f766e;
}

.cv-skill-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.cv-skill-badges img {
  height: 26px;
  width: auto;
}

/* ---------- References ---------- */
.cv-ref-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 18px;
}

.cv-ref {
  padding: 24px;
  border-radius: 18px;
  background: linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e5e7eb;
  box-shadow: 0 30px 60px -50px rgba(15, 23, 42, 0.9);
}

.cv-ref-name {
  margin: 0 0 2px;
  font-size: 17px;
  font-weight: 700;
  color: #0f172a;
}

.cv-ref-role {
  margin: 0 0 14px;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #0f766e;
}

.cv-ref-details {
  margin-top: 4px;
}

.cv-ref-details summary {
  cursor: pointer;
  color: #0f766e;
  font-size: 13px;
  font-weight: 700;
}

.cv-ref-details[open] summary {
  margin-bottom: 10px;
}

.cv-ref-links {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.cv-ref-link {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  color: #475569 !important;
  font-size: 14px;
  font-weight: 600;
  text-decoration: none !important;
}

.cv-ref-link:hover {
  color: #0f766e !important;
}

.cv-ref-link svg {
  width: 15px;
  height: 15px;
  color: #0f766e;
}

/* ---------- Video ---------- */
.cv-video-card {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 22px;
  padding: 28px 32px;
  border-radius: 20px;
  background: radial-gradient(circle at top left, rgba(66, 185, 131, 0.14), transparent 50%), linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e5e7eb;
  box-shadow: 0 40px 70px -55px rgba(15, 23, 42, 0.9);
}

.cv-video-left {
  display: flex;
  align-items: center;
  gap: 18px;
}

.cv-play {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 auto;
  width: 52px;
  height: 52px;
  border-radius: 50%;
  background: linear-gradient(135deg, #42b983 0%, #527d7a 100%);
  color: #ffffff;
  box-shadow: 0 24px 50px -24px rgba(66, 185, 131, 0.95);
}

.cv-play svg {
  width: 22px;
  height: 22px;
}

.cv-video-title {
  margin: 0 0 4px;
  font-size: 17px;
  font-weight: 700;
  color: #0f172a;
}

.cv-video-text {
  margin: 0;
  color: #64748b;
  font-size: 14px;
}

.cv-btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 11px 22px;
  border-radius: 999px;
  background: linear-gradient(135deg, #42b983 0%, #527d7a 100%);
  color: #ffffff !important;
  font-size: 13px;
  font-weight: 700;
  text-decoration: none !important;
  box-shadow: 0 24px 50px -24px rgba(66, 185, 131, 0.95);
  transition: all 0.25s ease;
}

.cv-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 30px 60px -22px rgba(66, 185, 131, 0.9);
}

.cv-btn svg {
  width: 16px;
  height: 16px;
}

/* ---------- Reflection tables ---------- */
.cv-table {
  display: table;
  width: 100%;
  border-collapse: collapse;
  font-size: 14px;
}

.cv-table th {
  padding: 12px 14px;
  border: 0;
  background: rgba(66, 185, 131, 0.1);
  color: #0f766e;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 2px;
  text-align: left;
  text-transform: uppercase;
}

.cv-table td {
  padding: 12px 14px;
  border: 0;
  border-top: 1px solid #eef2f7;
  color: #475569;
  line-height: 1.75;
  vertical-align: top;
}

.cv-table td:first-child {
  color: #1e293b;
  font-weight: 700;
  white-space: nowrap;
}

/* ---------- Responsive ---------- */
@media (max-width: 640px) {
  .cv-name {
    font-size: 32px;
  }

  .cv-card,
  .cv-video-card {
    padding: 22px;
  }

  .cv-table td:first-child {
    white-space: normal;
  }
}
</style>

<div class="cv-hero" id="top">
  <span class="cv-eyebrow">Curriculum Vitae · 2026</span>
  <h1 class="cv-name">Sabelo Ceza</h1>
  <p class="cv-tagline">Applications Development Student · Intern Developer</p>
  <div class="cv-hero-meta">
    <span class="cv-hero-pill">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5"/></svg>
      <span>CPUT</span>
    </span>
    <span class="cv-hero-pill">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z"/></svg>
      <span>Intern Developer</span>
    </span>
    <span class="cv-hero-pill">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"/></svg>
      <span>Goodwood, Cape Town</span>
    </span>
  </div>
</div>
 
## Quick Navigation

<style>
.nav-container {
  display: flex;
  flex-direction: column;
  gap: 12px;
  margin: 1.5rem 0 2rem;
}

.nav-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
}

.nav-pill {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 10px 18px;
  border-radius: 999px;
  text-decoration: none !important;
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 0.2px;
  background: linear-gradient(135deg, #ffffff 0%, #f8fafc 100%);
  color: #1e293b !important;
  border: 1px solid #e2e8f0;
  box-shadow: 0 2px 8px rgba(15, 23, 42, 0.04), inset 0 1px 0 rgba(255, 255, 255, 0.8);
  transition: all 0.25s ease;
  position: relative;
  overflow: hidden;
}

.nav-pill::before {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, rgba(66, 185, 131, 0.12) 0%, rgba(82, 125, 122, 0.12) 100%);
  opacity: 0;
  transition: opacity 0.25s ease;
}

.nav-pill span,
.nav-pill svg {
  position: relative;
  z-index: 1;
}

.nav-pill:hover {
  transform: translateY(-3px);
  border-color: rgba(66, 185, 131, 0.8);
  color: #0f766e !important;
  box-shadow: 0 10px 30px rgba(66, 185, 131, 0.18);
}

.nav-pill:hover::before {
  opacity: 1;
}

.nav-pill:active {
  transform: translateY(-1px);
}

.nav-pill svg {
  width: 16px;
  height: 16px;
}
</style>

<div class="nav-container">
  <div class="nav-row">
    <a class="nav-pill" href="#career-summary">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z"/></svg>
      <span>Career Summary</span>
    </a>
    <a class="nav-pill" href="#contact-details">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"/></svg>
      <span>Contact Details</span>
    </a>
    <a class="nav-pill" href="#work-experience">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z"/></svg>
      <span>Work Experience</span>
    </a>
    <a class="nav-pill" href="#education">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5"/></svg>
      <span>Education</span>
    </a>
  </div>
  <div class="nav-row">
    <a class="nav-pill" href="#projects">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M3.75 9.776c.112-.017.227-.026.344-.026h15.812c.117 0 .232.009.344.026m-16.5 0a2.25 2.25 0 00-1.883 2.542l.857 6a2.25 2.25 0 002.227 1.932H19.05a2.25 2.25 0 002.227-1.932l.857-6a2.25 2.25 0 00-1.883-2.542m-16.5 0V6A2.25 2.25 0 016 3.75h3.879a1.5 1.5 0 011.06.44l2.122 2.12a1.5 1.5 0 001.06.44H18A2.25 2.25 0 0120.25 6v3.776"/></svg>
      <span>Projects</span>
    </a>
    <a class="nav-pill" href="#technical-skills">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M11.42 15.17L17.25 21A2.652 2.652 0 0021 17.25l-5.877-5.877M11.42 15.17l2.496-3.03c.317-.384.74-.626 1.208-.766M11.42 15.17l-4.655 5.653a2.548 2.548 0 11-3.586-3.586l6.837-5.63m5.108-.233c.55-.164 1.163-.188 1.743-.14a4.5 4.5 0 004.486-6.336l-3.276 3.277a3.004 3.004 0 01-2.25-2.25l3.276-3.276a4.5 4.5 0 00-6.336 4.486c.091 1.076-.071 2.264-.904 2.95l-.102.085m-1.745 1.437L5.909 7.5H4.5L2.25 3.75l1.5-1.5L7.5 4.5v1.409l4.26 4.26m-1.745 1.437l1.745-1.437m6.615 8.206L15.75 15.75M4.867 19.125h.008v.008h-.008v-.008z"/></svg>
      <span>Technical Skills</span>
    </a>
    <a class="nav-pill" href="#references">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 003.741-.479 3 3 0 00-4.682-2.72m.94 3.198l.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0112 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 016 18.719m12 0a5.971 5.971 0 00-.941-3.197m0 0A5.995 5.995 0 0012 12.75a5.995 5.995 0 00-5.058 2.772m0 0a3 3 0 00-4.681 2.72 8.986 8.986 0 003.74.477m.94-3.197a5.971 5.971 0 00-.94 3.197M15 6.75a3 3 0 11-6 0 3 3 0 016 0zm6 3a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0zm-13.5 0a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0z"/></svg>
      <span>References</span>
    </a>
    <a class="nav-pill" href="#mock-interview-video">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15.91 11.672a.375.375 0 010 .656l-5.603 3.113a.375.375 0 01-.557-.328V8.887c0-.286.307-.466.557-.327l5.603 3.112z"/></svg>
      <span>Mock Interview Video</span>
    </a>
    <a class="nav-pill" href="#wil-portfolio">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25"/></svg>
      <span>WIL Portfolio</span>
    </a>
  </div>
</div>
 
<a name="career-summary"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">About me</span>
      <h2 class="cv-section-title">Career Summary</h2>
    </div>
  </div>
  <div class="cv-card">
    <p class="cv-summary">I am a <strong>3rd-year Applications Development student at the Cape Peninsula University of Technology (CPUT)</strong> with a strong interest in software development, UX design, database design, and building user-friendly digital solutions that solve real-world problems. I am also gaining practical industry experience as an <strong>Intern Developer at Full Stack</strong>.</p>
    <p class="cv-summary" style="margin-top: 14px;">Working at the company has helped me understand how software is developed in a professional team, from fixing bugs and implementing features to connecting applications with other business systems. I am eager to continue learning, improve my technical skills, and apply my knowledge to real-world projects. I enjoy working with others, taking on new challenges, and contributing to the development of useful and reliable software.</p>
  </div>
</div>
 
 
<a name="contact-details"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">Get in touch</span>
      <h2 class="cv-section-title">Contact Details</h2>
    </div>
  </div>
  <div class="cv-contact-grid">
    <a class="cv-contact" href="mailto:220094489@mycput.ac.za">
      <span class="cv-contact-icon">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"/></svg>
      </span>
      <span>
        <span class="cv-contact-label">Email</span>
        <span class="cv-contact-value">220094489@mycput.ac.za</span>
      </span>
    </a>
    <a class="cv-contact" href="https://www.linkedin.com/in/sabelo-ceza-240b831b6" target="_blank" rel="noopener">
      <span class="cv-contact-icon">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="M20.45 20.45h-3.55v-5.57c0-1.33-.02-3.04-1.85-3.04-1.85 0-2.14 1.45-2.14 2.94v5.67H9.35V9h3.41v1.56h.05c.48-.9 1.64-1.85 3.37-1.85 3.6 0 4.27 2.37 4.27 5.46v6.28zM5.34 7.43a2.06 2.06 0 110-4.12 2.06 2.06 0 010 4.12zM7.12 20.45H3.56V9h3.56v11.45z"/></svg>
      </span>
      <span>
        <span class="cv-contact-label">LinkedIn</span>
        <span class="cv-contact-value">Sabelo Ceza</span>
      </span>
    </a>
    <a class="cv-contact" href="https://github.com/sabelo-ceza-26" target="_blank" rel="noopener">
      <span class="cv-contact-icon">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="M12 .5C5.73.5.5 5.73.5 12c0 5.08 3.29 9.39 7.86 10.91.58.11.79-.25.79-.56v-2.17c-3.2.7-3.87-1.36-3.87-1.36-.53-1.33-1.29-1.69-1.29-1.69-1.05-.72.08-.71.08-.71 1.16.08 1.77 1.19 1.77 1.19 1.03 1.77 2.7 1.26 3.36.96.1-.75.4-1.26.73-1.55-2.55-.29-5.24-1.28-5.24-5.68 0-1.26.45-2.29 1.19-3.1-.12-.29-.52-1.46.11-3.05 0 0 .97-.31 3.18 1.18a11 11 0 015.79 0c2.2-1.49 3.17-1.18 3.17-1.18.63 1.59.23 2.76.11 3.05.74.81 1.19 1.84 1.19 3.1 0 4.41-2.69 5.38-5.25 5.67.41.36.78 1.06.78 2.14v3.17c0 .31.21.67.8.56A11.51 11.51 0 0023.5 12C23.5 5.73 18.27.5 12 .5z"/></svg>
      </span>
      <span>
        <span class="cv-contact-label">GitHub</span>
        <span class="cv-contact-value">sabelo-ceza-26</span>
      </span>
    </a>
    <a class="cv-contact" href="tel:0739820683">
      <span class="cv-contact-icon">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
      </span>
      <span>
        <span class="cv-contact-label">Phone</span>
        <span class="cv-contact-value">073 982 0683</span>
      </span>
    </a>
    <a class="cv-contact" href="https://www.google.com/maps/search/?api=1&amp;query=Goodwood%2C%20Cape%20Town%2C%207460" target="_blank" rel="noopener">
      <span class="cv-contact-icon">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"/></svg>
      </span>
      <span>
        <span class="cv-contact-label">Location</span>
        <span class="cv-contact-value">Goodwood, Cape Town</span>
      </span>
    </a>
  </div>
</div>
 
<a name="work-experience"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">Professional experience</span>
      <h2 class="cv-section-title">Work Experience</h2>
    </div>
  </div>

  <article class="cv-card">
    <div class="cv-card-head">
      <div>
        <h3 class="cv-role">Intern Developer</h3>
        <p class="cv-org">Full Stack</p>
      </div>
      <span class="cv-date-pill">17 September 2026 – Present</span>
    </div>
    <ul class="cv-list">
      <li>Developing a bilingual (Afrikaans/English) Progressive Web App using .NET 9 and Blazor WebAssembly</li>
      <li>Connecting the app to other business systems and building features from start to finish</li>
      <li>Working in an agile team, using Kanban to plan and track tasks</li>
    </ul>
  </article>

  <article class="cv-card">
    <div class="cv-card-head">
      <div>
        <h3 class="cv-role">Optical Dispenser</h3>
        <p class="cv-org">Aayuni Optical</p>
      </div>
      <span class="cv-date-pill">Mar 2022 – Dec 2023</span>
    </div>
    <ul class="cv-list">
      <li>Provided friendly customer service and helped patients choose suitable eyewear based on their needs and prescriptions</li>
      <li>Worked effectively with team members to ensure daily operations ran smoothly</li>
    </ul>
  </article>
</div>
 
 
 
<a name="education"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">Academic background</span>
      <h2 class="cv-section-title">Education</h2>
    </div>
  </div>
  <div class="cv-edu-grid">
    <article class="cv-edu">
      <span class="cv-edu-type">Diploma · Current</span>
      <h3 class="cv-edu-title">Diploma in ICT in Applications Development</h3>
      <p class="cv-edu-org">Cape Peninsula University of Technology (CPUT)</p>
      <span class="cv-date-pill">2024 – Present</span>
    </article>
    <article class="cv-edu">
      <span class="cv-edu-type">Programme</span>
      <h3 class="cv-edu-title">App Development Programme</h3>
      <p class="cv-edu-org">FNB App Academy</p>
      <span class="cv-date-pill">May 2025 – July 2025</span>
    </article>
    <article class="cv-edu">
      <span class="cv-edu-type">Diploma</span>
      <h3 class="cv-edu-title">Diploma in Opticianry</h3>
      <p class="cv-edu-org">Cape Peninsula University of Technology (CPUT)</p>
      <span class="cv-date-pill">2020 – 2022</span>
    </article>
    <article class="cv-edu">
      <span class="cv-edu-type">National Senior Certificate</span>
      <h3 class="cv-edu-title">Grade 12</h3>
      <p class="cv-edu-org">Hector Petersen High School</p>
      <span class="cv-date-pill">2013 – 2017</span>
    </article>
  </div>
</div>
 
 
<a name="projects"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M3.75 9.776c.112-.017.227-.026.344-.026h15.812c.117 0 .232.009.344.026m-16.5 0a2.25 2.25 0 00-1.883 2.542l.857 6a2.25 2.25 0 002.227 1.932H19.05a2.25 2.25 0 002.227-1.932l.857-6a2.25 2.25 0 00-1.883-2.542m-16.5 0V6A2.25 2.25 0 016 3.75h3.879a1.5 1.5 0 011.06.44l2.122 2.12a1.5 1.5 0 001.06.44H18A2.25 2.25 0 0120.25 6v3.776"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">Selected work · 2026</span>
      <h2 class="cv-section-title">Projects</h2>
    </div>
  </div>
  <p class="cv-section-note">January 2026 – Present</p>

  <div class="cv-projects-grid">
  <article class="wil-card" id="project-atkv">
      <div class="wil-card-content">
        <div class="wil-card-header">
          <div class="wil-card-title-group">
            <span class="wil-card-subtitle">Industry Placement</span>
            <h2 class="wil-card-title">📱 ATKV Mobile Application</h2>
            <p class="wil-card-lead">Afrikaans Taal- en Kultuurvereniging</p>
          </div>
          <div class="wil-card-index">01</div>
        </div>
        <div class="wil-card-meta">
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Project Type</span>
            <span class="wil-meta-value">Industry Placement</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Company</span>
            <span class="wil-meta-value">Full Stack</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Status</span>
            <span class="wil-meta-value">Ongoing</span>
          </div>
        </div>
        <ul class="cv-list">
          <li>Developing a bilingual (Afrikaans and English) application using .NET 9 and Blazor WebAssembly.</li>
          <li>Bringing member profiles, digital wallets, rewards, news, and booking services together in one place.</li>
          <li>Connecting the app to other business systems.</li>
          <li>Developing features and improving the user experience.</li>
        </ul>
        <div class="cv-tags">
          <span class="cv-tag">.NET 9</span>
          <span class="cv-tag">Blazor WebAssembly</span>
          <span class="cv-tag">Azure</span>
        </div>
      </div>
    </article>

  <article class="wil-card" id="project-laundry">
      <div class="wil-card-content">
        <div class="wil-card-header">
          <div class="wil-card-title-group">
            <span class="wil-card-subtitle">Academic Project</span>
            <h2 class="wil-card-title">🧺 Laundry Pickup Pro</h2>
            <p class="wil-card-lead">Laundry Collection &amp; Delivery</p>
          </div>
          <div class="wil-card-index">02</div>
        </div>
        <div class="wil-card-meta">
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Role</span>
            <span class="wil-meta-value">Agile Lead</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Areas</span>
            <span class="wil-meta-value">Maitland · Observatory · Woodstock</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Focus</span>
            <span class="wil-meta-value">Product &amp; Delivery</span>
          </div>
        </div>
        <ul class="cv-list">
          <li>Working on a team project to make laundry collection and delivery easier for customers in Maitland, Observatory, and Woodstock.</li>
          <li>Agile Lead for the team, running the agile process and the product backlog</li>
          <li>Planned the database and security with <strong>Supabase</strong></li>
          <li>Designed wireframes and a prototype, and built customer screens with order tracking and live location</li>
          <li>Managed tasks on a Trello board and set up VS Code and GitHub for the team</li>
        </ul>
        <div class="cv-tags">
          <span class="cv-tag">Supabase</span>
          <span class="cv-tag">Trello</span>
          <span class="cv-tag">Figma</span>
          <span class="cv-tag">VS Code</span>
        </div>
      </div>
    </article>

  <article class="wil-card" id="project-campus">
      <div class="wil-card-content">
        <div class="wil-card-header">
          <div class="wil-card-title-group">
            <span class="wil-card-subtitle">Academic Project</span>
            <h2 class="wil-card-title">🛒 Campus Marketplace</h2>
            <p class="wil-card-lead">Student &amp; Vendor Marketplace</p>
          </div>
          <div class="wil-card-index">03</div>
        </div>
        <div class="wil-card-meta">
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Status</span>
            <span class="wil-meta-value">Ongoing</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Platform</span>
            <span class="wil-meta-value">Mobile</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Stack</span>
            <span class="wil-meta-value">React Native</span>
          </div>
        </div>
        <ul class="cv-list">
          <li>Developing a marketplace app with <strong>React Native</strong> and <strong>TypeScript</strong> for students and local vendors to buy and sell products</li>
          <li>Built product listings, search, and secure user authentication</li>
        </ul>
        <div class="cv-tags">
          <span class="cv-tag">React Native</span>
          <span class="cv-tag">TypeScript</span>
        </div>
      </div>
    </article>

  <article class="wil-card" id="project-clinic">
      <div class="wil-card-content">
        <div class="wil-card-header">
          <div class="wil-card-title-group">
            <span class="wil-card-subtitle">Academic Project</span>
            <h2 class="wil-card-title">🏥 ClinicConnect</h2>
            <p class="wil-card-lead">Clinic Appointment Booking</p>
          </div>
          <div class="wil-card-index">04</div>
        </div>
        <div class="wil-card-meta">
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Status</span>
            <span class="wil-meta-value">Ongoing</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Platform</span>
            <span class="wil-meta-value">Web</span>
          </div>
          <div class="wil-meta-pill">
            <span class="wil-meta-label">Stack</span>
            <span class="wil-meta-value">React · TypeScript · Firebase</span>
          </div>
        </div>
        <ul class="cv-list">
          <li>Developing an online clinic appointment booking application with <strong>React</strong> and <strong>TypeScript</strong></li>
          <li>Implemented <strong>Supabase</strong> for secure user authentication and real-time data storage</li>
          <li>Created different dashboards for users (patients, doctors, nurses, admin)</li>
          <li>Used object-oriented programming principles to keep the code clean, reusable, and easy to maintain</li>
        </ul>
        <div class="cv-tags">
          <span class="cv-tag">React</span>
          <span class="cv-tag">TypeScript</span>
          <span class="cv-tag">Supabase</span>
        </div>
      </div>
    </article>
  </div>
</div>
 
 
 
<a name="technical-skills"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M11.42 15.17L17.25 21A2.652 2.652 0 0021 17.25l-5.877-5.877M11.42 15.17l2.496-3.03c.317-.384.74-.626 1.208-.766M11.42 15.17l-4.655 5.653a2.548 2.548 0 11-3.586-3.586l6.837-5.63m5.108-.233c.55-.164 1.163-.188 1.743-.14a4.5 4.5 0 004.486-6.336l-3.276 3.277a3.004 3.004 0 01-2.25-2.25l3.276-3.276a4.5 4.5 0 00-6.336 4.486c.091 1.076-.071 2.264-.904 2.95l-.102.085m-1.745 1.437L5.909 7.5H4.5L2.25 3.75l1.5-1.5L7.5 4.5v1.409l4.26 4.26m-1.745 1.437l1.745-1.437m6.615 8.206L15.75 15.75M4.867 19.125h.008v.008h-.008v-.008z"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">Toolbox</span>
      <h2 class="cv-section-title">Technical Skills</h2>
    </div>
  </div>
  <div class="cv-skill-grid">
    <article class="cv-skill">
      <div class="cv-skill-head">
        <span class="cv-skill-dot"></span>
        <span class="cv-skill-label">Core Skills</span>
      </div>
      <div class="cv-skill-badges">
        <img src="https://img.shields.io/badge/Troubleshooting-8A2BE2?style=for-the-badge" alt="Troubleshooting">
        <img src="https://img.shields.io/badge/Problem--Solving-FF6F61?style=for-the-badge" alt="Problem Solving">
      </div>
    </article>
    <article class="cv-skill">
      <div class="cv-skill-head">
        <span class="cv-skill-dot"></span>
        <span class="cv-skill-label">Languages</span>
      </div>
      <div class="cv-skill-badges">
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&amp;logo=css3&amp;logoColor=white" alt="CSS3">
        <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&amp;logo=openjdk&amp;logoColor=white" alt="Java">
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" alt="JavaScript">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" alt="TypeScript">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&amp;logo=php&amp;logoColor=white" alt="PHP">
        <img src="https://img.shields.io/badge/SQL_(MySQL)-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" alt="SQL (MySQL)">
      </div>
    </article>
    <article class="cv-skill">
      <div class="cv-skill-head">
        <span class="cv-skill-dot"></span>
        <span class="cv-skill-label">IDEs &amp; Tools</span>
      </div>
      <div class="cv-skill-badges">
        <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&amp;logo=intellijidea&amp;logoColor=white" alt="IntelliJ IDEA">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&amp;logo=figma&amp;logoColor=white" alt="Figma">
        <img src="https://img.shields.io/badge/NetBeans-1B6AC6?style=for-the-badge&amp;logo=apachenetbeanside&amp;logoColor=white" alt="NetBeans">
        <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&amp;logo=visualstudiocode&amp;logoColor=white" alt="VS Code">
        <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&amp;logo=pycharm&amp;logoColor=white" alt="PyCharm">
        <img src="https://img.shields.io/badge/Thonny-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Thonny">
        <img src="https://img.shields.io/badge/MySQL_Workbench-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" alt="MySQL Workbench">
        <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&amp;logo=canva&amp;logoColor=white" alt="Canva">
        <img src="https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&amp;logo=xampp&amp;logoColor=white" alt="XAMPP">
      </div>
    </article>
    <article class="cv-skill">
      <div class="cv-skill-head">
        <span class="cv-skill-dot"></span>
        <span class="cv-skill-label">Frameworks &amp; Platforms</span>
      </div>
      <div class="cv-skill-badges">
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&amp;logo=react&amp;logoColor=61DAFB" alt="React">
        <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&amp;logo=react&amp;logoColor=61DAFB" alt="React Native">
        <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&amp;logo=blazor&amp;logoColor=white" alt="Blazor">
        <img src="https://img.shields.io/badge/.NET_9-512BD4?style=for-the-badge&amp;logo=dotnet&amp;logoColor=white" alt=".NET 9">
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&amp;logo=laravel&amp;logoColor=white" alt="Laravel">
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&amp;logo=springboot&amp;logoColor=white" alt="Spring Boot">
        <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&amp;logo=firebase&amp;logoColor=black" alt="Firebase">
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&amp;logo=supabase&amp;logoColor=white" alt="Supabase">
      </div>
    </article>
  </div>
</div>
 
 
<a name="references"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 003.741-.479 3 3 0 00-4.682-2.72m.94 3.198l.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0112 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 016 18.719m12 0a5.971 5.971 0 00-.941-3.197m0 0A5.995 5.995 0 0012 12.75a5.995 5.995 0 00-5.058 2.772m0 0a3 3 0 00-4.681 2.72 8.986 8.986 0 003.74.477m.94-3.197a5.971 5.971 0 00-.94 3.197M15 6.75a3 3 0 11-6 0 3 3 0 016 0zm6 3a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0zm-13.5 0a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0z"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">People in my corner</span>
      <h2 class="cv-section-title">References</h2>
    </div>
  </div>
  <p class="cv-section-note">People who can provide further information about my academic progress and professional experience.</p>
  <div class="cv-ref-grid">
    <article class="cv-ref">
      <h3 class="cv-ref-name">Mandisa Msongelwa</h3>
      <p class="cv-ref-role">ICT Mentor</p>
      <details class="cv-ref-details">
        <summary>Contact details</summary>
        <div class="cv-ref-links">
        <a class="cv-ref-link" href="tel:0786912208">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
          <span>078 691 2208</span>
        </a>
        </div>
      </details>
    </article>
    <article class="cv-ref">
      <h3 class="cv-ref-name">Mrs Rebecca Bure</h3>
      <p class="cv-ref-role">CPUT Lecturer</p>
      <details class="cv-ref-details">
        <summary>Contact details</summary>
        <div class="cv-ref-links">
        <a class="cv-ref-link" href="tel:0747054403">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
          <span>074 705 4403</span>
        </a>
        <a class="cv-ref-link" href="mailto:burer@cput.ac.za">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"/></svg>
          <span>burer@cput.ac.za</span>
        </a>
        </div>
      </details>
    </article>
  </div>
</div>

 
 
<a name="mock-interview-video"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15.91 11.672a.375.375 0 010 .656l-5.603 3.113a.375.375 0 01-.557-.328V8.887c0-.286.307-.466.557-.327l5.603 3.112z"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">Watch</span>
      <h2 class="cv-section-title">Mock Interview Video</h2>
    </div>
  </div>
  <div class="cv-video-card">
    <div class="cv-video-left">
      <span class="cv-play">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
      </span>
      <div>
        <p class="cv-video-title">Interview</p>
        <p class="cv-video-text">A recorded mock interview.</p>
      </div>
    </div>
    <a class="cv-btn" href="assets/Mock_Interview_Vide.mp4">
      <span>Watch the video</span>
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
    </a>
  </div>
</div>

---
 
<a name="reflections"></a>

<div class="cv-section">
  <div class="cv-section-head">
    <div class="cv-section-icon">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 18v-5.25m0 0a6.01 6.01 0 001.5-.189m-1.5.189a6.01 6.01 0 01-1.5-.189m3.75 7.478a12.06 12.06 0 01-4.5 0m3.75 2.383a14.406 14.406 0 01-3 0M14.25 18v-.192c0-.983.658-1.823 1.508-2.316a7.5 7.5 0 10-7.517 0c.85.493 1.509 1.333 1.509 2.316V18"/></svg>
    </div>
    <div>
      <span class="cv-section-kicker">Looking back</span>
      <h2 class="cv-section-title">Reflections</h2>
    </div>
  </div>

  <a name="reflection-markdown"></a>
  <article class="cv-card">
    <h3 class="cv-role" style="margin-bottom: 14px;">Reflection on Coding Using Markdown</h3>
    <table class="cv-table">
      <thead>
        <tr><th>Element</th><th>Reflection</th></tr>
      </thead>
      <tbody>
        <tr><td>Situation</td><td>For this assignment, I was given a task to create a portfolio and code my CV using the Markdown language.</td></tr>
        <tr><td>Task</td><td>My goal was to figure out how the language works and create a CV that looked clean and professional using Markdown syntax.</td></tr>
        <tr><td>Action</td><td>I spent time watching tutorial videos, doing some research, and asking for help from people who understood Markdown better than I did. After getting all the information, I used what I learned to code the CV and create a well-organised portfolio.</td></tr>
        <tr><td>Result</td><td>I managed to completely code my CV using the Markdown language and produced a well-organised portfolio. Finishing this task successfully helped me feel more confident in learning Markdown and using it to create something clear and well organised, even though I did not know it before.</td></tr>
      </tbody>
    </table>
  </article>

  <a name="reflection-interview"></a>
  <article class="cv-card" style="margin-top: 18px;">
    <h3 class="cv-role" style="margin-bottom: 14px;">Reflection on Mock Video Interview</h3>
    <table class="cv-table">
      <thead>
        <tr><th>Element</th><th>Reflection</th></tr>
      </thead>
      <tbody>
        <tr><td>Situation</td><td>I was tasked to make a mock interview video where I had to answer a few interview questions. The purpose of this video was to train me for real job interviews.</td></tr>
        <tr><td>Task</td><td>I had to produce a professional mock video where I had to speak clearly and with confidence while answering the questions using the STAR method.</td></tr>
        <tr><td>Action</td><td>I took some time to understand the questions clearly and practise my answers before recording the video. As I kept going, I started to feel more comfortable talking to the camera. I took time getting the task done because while recording I was considering all the aspects I was told to consider, like being audible, having no background noise, and maintaining eye contact.</td></tr>
        <tr><td>Result</td><td>I successfully finished the task with all the questions answered, and the experience gave me a glimpse of how real interviews will be. I produced a professional mock video interview.</td></tr>
      </tbody>
    </table>
  </article>

  <a name="reflection-github"></a>
  <article class="cv-card" style="margin-top: 18px;">
    <h3 class="cv-role" style="margin-bottom: 14px;">Reflection on GitHub Pages</h3>
    <table class="cv-table">
      <thead>
        <tr><th>Element</th><th>Reflection</th></tr>
      </thead>
      <tbody>
        <tr><td>Situation</td><td>I was given a task to publish my portfolio using GitHub Pages so that it could be viewed online.</td></tr>
        <tr><td>Task</td><td>My goal was to understand how GitHub Pages works and publish my portfolio as required for the assignment.</td></tr>
        <tr><td>Action</td><td>I followed the study guide step by step and tested the live website to check that it displayed correctly.</td></tr>
        <tr><td>Result</td><td>I successfully published my portfolio using GitHub Pages. Seeing my work online gave me confidence that I could publish a website.</td></tr>
      </tbody>
    </table>
  </article>
</div>
 
<a name="wil-portfolio"></a>

<style>
.wil-header {
  text-align: center;
  margin: 2.5rem 0 1.5rem;
}

.wil-badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 8px 20px;
  border-radius: 999px;
  background: linear-gradient(135deg, rgba(66, 185, 131, 0.16) 0%, rgba(82, 125, 122, 0.16) 100%);
  border: 1px solid rgba(66, 185, 131, 0.6);
  color: #0f766e;
  font-weight: 700;
  letter-spacing: 5px;
  text-transform: uppercase;
  font-size: 11px;
}

.wil-intro {
  max-width: 900px;
  margin: 0 auto 2.8rem;
  text-align: center;
  color: #475569;
  line-height: 1.9;
  font-size: 15px;
}

.wil-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 26px;
  margin: 2.5rem 0;
}

.wil-card {
  position: relative;
  border-radius: 20px;
  overflow: hidden;
  background: radial-gradient(circle at top, rgba(66, 185, 131, 0.14), transparent 55%), linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e5e7eb;
  box-shadow: 0 40px 70px -50px rgba(15, 23, 42, 0.9);
  transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
}

.wil-card:hover {
  transform: translateY(-8px);
  border-color: rgba(66, 185, 131, 0.85);
  box-shadow: 0 50px 80px -45px rgba(66, 185, 131, 0.38);
}

.wil-card-content {
  position: relative;
  z-index: 1;
  display: flex;
  flex-direction: column;
  gap: 18px;
  padding: 32px;
}

.wil-card-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 18px;
}

.wil-card-title-group {
  display: flex;
  flex-direction: column;
  gap: 6px;
}

.wil-card-subtitle {
  text-transform: uppercase;
  letter-spacing: 7px;
  font-size: 10px;
  color: #94a3b8;
}

.wil-card-title {
  margin: 0;
  font-size: 26px;
  font-weight: 700;
  color: #0f172a;
}

.wil-card-lead {
  margin: 0;
  color: #475569;
  font-weight: 600;
}

.wil-card-index {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 auto;
  width: 48px;
  height: 48px;
  border-radius: 14px;
  background: linear-gradient(135deg, #42b983 0%, #527d7a 100%);
  color: #ffffff;
  font-size: 15px;
  font-weight: 800;
  letter-spacing: 1px;
  box-shadow: 0 24px 50px -24px rgba(66, 185, 131, 0.95);
}

.wil-card-meta {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 12px;
}

.wil-meta-pill {
  display: flex;
  flex-direction: column;
  gap: 4px;
  padding: 12px 18px;
  border-radius: 14px;
  background: rgba(248, 250, 252, 0.95);
  border: 1px solid rgba(226, 232, 240, 0.9);
}

.wil-meta-label {
  font-size: 10px;
  text-transform: uppercase;
  letter-spacing: 5px;
  color: #94a3b8;
}

.wil-meta-value {
  font-weight: 600;
  color: #1e293b;
}

.wil-card-text {
  margin: 0;
  color: #475569;
  line-height: 1.95;
}

.wil-docs-header {
  display: flex;
  align-items: center;
  gap: 10px;
  font-weight: 700;
  color: #0f172a;
}

.wil-docs-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 12px;
}

.wil-doc-link {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 14px;
  padding: 12px 20px;
  border-radius: 999px;
  text-decoration: none !important;
  background: linear-gradient(135deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e2e8f0;
  color: #1e293b !important;
  font-weight: 600;
  box-shadow: 0 16px 40px -30px rgba(15, 23, 42, 0.9);
  transition: all 0.25s ease;
}

.wil-doc-link:hover {
  transform: translateX(6px);
  border-color: rgba(66, 185, 131, 0.9);
  color: #0f766e !important;
  box-shadow: 0 24px 60px -28px rgba(66, 185, 131, 0.4);
}

.wil-doc-link svg {
  width: 18px;
  height: 18px;
}

/* ---------- Flat white surfaces ---------- */
/* Keep every large surface plain white; colour stays in the icons, borders and text. */
body,
html,
.markdown-body,
.cv-hero-pill,
.cv-eyebrow,
.cv-card,
.cv-contact,
.cv-contact-icon,
.cv-date-pill,
.cv-edu,
.cv-skill,
.cv-ref,
.cv-video-card,
.cv-table th,
.nav-pill,
.wil-card,
.wil-badge,
.wil-meta-pill,
.wil-doc-link {
  background: #ffffff;
}

.cv-table th {
  border-bottom: 1px solid #e5e7eb;
}

/* Remove the tinted hover wash so pills stay white on hover. */
.nav-pill::before {
  display: none;
}
</style>

<div class="wil-header">
  <div class="wil-badge">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25"/></svg>
    <span>Work Integrated Learning Portfolio · 2026</span>
  </div>
</div>

<p class="wil-intro">
  This portfolio showcases my progress and practical experience during my Work Integrated Learning journey. It highlights my industry placement at <strong>Full Stack</strong> on the <strong>ATKV</strong> bilingual mobile application, as well as the <strong>Laundry Pickup Pro</strong> entrepreneurial project where I served as the <strong>Agile Lead</strong>. Both projects demonstrate my ability to apply Agile practices, collaborate within teams, and deliver practical solutions to real-world problems.
</p>

<div class="wil-grid">
  <article class="wil-card" id="atkv">
    <div class="wil-card-content">
      <div class="wil-card-header">
        <div class="wil-card-title-group">
          <span class="wil-card-subtitle">Industry Placement</span>
          <h2 class="wil-card-title">01 · ATKV</h2>
          <p class="wil-card-lead">Afrikaanse Taal- en Kultuurvereniging</p>
        </div>
        <div class="wil-card-index">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z"/></svg>
        </div>
      </div>
      <div class="wil-card-meta">
        <div class="wil-meta-pill">
          <span class="wil-meta-label">Project Type</span>
          <span class="wil-meta-value">Industry Placement</span>
        </div>
        <div class="wil-meta-pill">
          <span class="wil-meta-label">Company</span>
          <span class="wil-meta-value">Full Stack</span>
        </div>
        <div class="wil-meta-pill">
          <span class="wil-meta-label">Location</span>
          <span class="wil-meta-value">Century City</span>
        </div>
        <div class="wil-meta-pill">
          <span class="wil-meta-label">Start Date</span>
          <span class="wil-meta-value">17 September 2026</span>
        </div>
      </div>
      <p class="wil-card-text">
        The ATKV project forms part of my industry placement at Full Stack. I work with the team to develop and improve the application, connecting it to existing ATKV systems whilst gaining valuable hands-on experience in professional software development.
      </p>
      <div>
        <div class="wil-docs-header">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z"/></svg>
          <span>Project Documentation</span>
        </div>
        <div class="wil-docs-grid">
          <a class="wil-doc-link" href="./ATKV/Agile-charter.html">
            <span>Agile Team Charter</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./ATKV/User-stories.html">
            <span>User Stories and Tasks</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./ATKV/Product-backlog.html">
            <span>Product Backlog</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./ATKV/Sprint-backlog.html">
            <span>Sprint Backlog</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./ATKV/Logbooks.html">
            <span>Agile Logbooks</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
        </div>
      </div>
    </div>
  </article>

  <article class="wil-card" id="laundry">
    <div class="wil-card-content">
      <div class="wil-card-header">
        <div class="wil-card-title-group">
          <span class="wil-card-subtitle">Entrepreneurial WIL Project</span>
          <h2 class="wil-card-title">02 · Laundry Pickup Pro</h2>
          <p class="wil-card-lead">Smart Laundry Collection &amp; Delivery</p>
        </div>
        <div class="wil-card-index">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9.568 3H5.25A2.25 2.25 0 003 5.25v4.318c0 .597.237 1.17.659 1.591l9.581 9.581c.699.699 1.78.872 2.607.33a18.095 18.095 0 005.223-5.223c.542-.827.369-1.908-.33-2.607L11.16 3.66A2.25 2.25 0 009.568 3z"/><path stroke-linecap="round" stroke-linejoin="round" d="M6 6h.008v.008H6V6z"/></svg>
        </div>
      </div>
      <div class="wil-card-meta">
        <div class="wil-meta-pill">
          <span class="wil-meta-label">Project Type</span>
          <span class="wil-meta-value">Entrepreneurial WIL Project</span>
        </div>
        <div class="wil-meta-pill">
          <span class="wil-meta-label">Start Date</span>
          <span class="wil-meta-value">1 July 2026</span>
        </div>
        <div class="wil-meta-pill">
          <span class="wil-meta-label">End Date</span>
          <span class="wil-meta-value">16 September 2026</span>
        </div>
        <div class="wil-meta-pill">
          <span class="wil-meta-label">Role</span>
          <span class="wil-meta-value">Agile Lead</span>
        </div>
      </div>
      <p class="wil-card-text">
        Laundry Pickup Pro was developed to make laundry collection and delivery easier for customers in <strong>Maitland</strong>, <strong>Observatory</strong> and <strong>Woodstock</strong>. As the Agile Lead, I facilitated the Agile process, managed the product backlog, planned the database, designed wireframes, and led the team to deliver a practical, user-focused solution.
      </p>
      <div>
        <div class="wil-docs-header">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z"/></svg>
          <span>Project Documentation</span>
        </div>
        <div class="wil-docs-grid">
          <a class="wil-doc-link" href="./LAUNDRY%20PICKUP%20PRO/Agile-charter.html">
            <span>Agile Team Charter</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./LAUNDRY%20PICKUP%20PRO/User-stories.html">
            <span>User Stories and Tasks</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./LAUNDRY%20PICKUP%20PRO/Product-backlog.html">
            <span>Product Backlog</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./LAUNDRY%20PICKUP%20PRO/Sprint-backlog.html">
            <span>Sprint Backlog</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
          <a class="wil-doc-link" href="./LAUNDRY%20PICKUP%20PRO/Logbooks.html">
            <span>Agile Logbooks</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
          </a>
        </div>
      </div>
    </div>
  </article>
</div>

<div style="text-align: center; margin: 3rem 0 2rem;">
  <a class="cv-btn" href="#top" style="background: #ffffff; color: #1e293b !important; border: 1px solid #e2e8f0; box-shadow: 0 12px 40px -28px rgba(15, 23, 42, 0.9);">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M4.5 10.5L12 3m0 0l7.5 7.5M12 3v18"/></svg>
    <span>Back to Top</span>
  </a>
</div>
