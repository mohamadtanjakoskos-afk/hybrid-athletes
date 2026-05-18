<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Hybrid Athlete System — Build Muscle. Run Faster. Perform Better.</title>
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet" />
<style>
  /* ============================================================
     DESIGN TOKENS
  ============================================================ */
  :root {
    --black:     #050505;
    --off-black: #0d0d0d;
    --card-bg:   #111111;
    --border:    rgba(255,255,255,0.08);
    --border-md: rgba(255,255,255,0.14);
    --white:     #ffffff;
    --off-white: #e8e8e8;
    --muted:     #888888;
    --accent:    #ffffff;
    --mono:      'DM Mono', monospace;
    --display:   'Bebas Neue', sans-serif;
    --body:      'DM Sans', sans-serif;

    --section-pad: clamp(80px, 10vw, 140px) clamp(20px, 6vw, 80px);
    --radius-sm: 6px;
    --radius-md: 12px;
    --radius-lg: 20px;
  }

  /* ============================================================
     RESET & BASE
  ============================================================ */
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    font-family: var(--body);
    background: var(--black);
    color: var(--white);
    -webkit-font-smoothing: antialiased;
    overflow-x: hidden;
    cursor: none;
  }

  /* Custom cursor */
  .cursor {
    width: 10px; height: 10px;
    background: #fff;
    border-radius: 50%;
    position: fixed; top: 0; left: 0;
    pointer-events: none; z-index: 9999;
    transform: translate(-50%,-50%);
    transition: transform 0.08s linear, width 0.2s, height 0.2s, opacity 0.2s;
  }
  .cursor-ring {
    width: 36px; height: 36px;
    border: 1px solid rgba(255,255,255,0.4);
    border-radius: 50%;
    position: fixed; top: 0; left: 0;
    pointer-events: none; z-index: 9998;
    transform: translate(-50%,-50%);
    transition: transform 0.18s ease, width 0.3s, height 0.3s;
  }

  a { color: inherit; text-decoration: none; }
  img { display: block; max-width: 100%; }

  /* ============================================================
     TYPOGRAPHY HELPERS
  ============================================================ */
  .label {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--muted);
  }

  .display-xl {
    font-family: var(--display);
    font-size: clamp(72px, 12vw, 160px);
    line-height: 0.92;
    letter-spacing: 0.01em;
  }

  .display-lg {
    font-family: var(--display);
    font-size: clamp(52px, 8vw, 96px);
    line-height: 0.94;
    letter-spacing: 0.01em;
  }

  .display-md {
    font-family: var(--display);
    font-size: clamp(36px, 5vw, 64px);
    line-height: 0.96;
    letter-spacing: 0.01em;
  }

  .body-lg {
    font-size: clamp(16px, 1.4vw, 19px);
    line-height: 1.7;
    color: var(--off-white);
    font-weight: 300;
  }

  .body-md {
    font-size: 15px;
    line-height: 1.6;
    color: var(--muted);
    font-weight: 300;
  }

  /* ============================================================
     UTILITY
  ============================================================ */
  .container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 clamp(20px, 5vw, 60px);
  }

  .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; }
  .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; }
  .grid-4 { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; }

  .divider {
    width: 100%;
    height: 1px;
    background: var(--border);
    margin: 0;
  }

  /* ============================================================
     ANIMATIONS
  ============================================================ */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(32px); }
    to   { opacity: 1; transform: translateY(0); }
  }
  @keyframes fadeIn {
    from { opacity: 0; }
    to   { opacity: 1; }
  }
  @keyframes slideRight {
    from { width: 0; }
    to   { width: 100%; }
  }
  @keyframes pulse-ring {
    0%   { transform: translate(-50%,-50%) scale(1); opacity: 0.6; }
    100% { transform: translate(-50%,-50%) scale(2.4); opacity: 0; }
  }
  @keyframes ticker {
    0%   { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  @keyframes float {
    0%, 100% { transform: translateY(0px); }
    50%       { transform: translateY(-8px); }
  }
  @keyframes scan {
    0%   { top: 0; opacity: 0.7; }
    100% { top: 100%; opacity: 0; }
  }

  .reveal {
    opacity: 0;
    transform: translateY(28px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }
  .reveal-delay-1 { transition-delay: 0.1s; }
  .reveal-delay-2 { transition-delay: 0.2s; }
  .reveal-delay-3 { transition-delay: 0.3s; }
  .reveal-delay-4 { transition-delay: 0.4s; }
  .reveal-delay-5 { transition-delay: 0.5s; }

  /* ============================================================
     NAV
  ============================================================ */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    padding: 20px clamp(20px, 5vw, 60px);
    display: flex;
    align-items: center;
    justify-content: space-between;
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    background: rgba(5,5,5,0.85);
    border-bottom: 1px solid var(--border);
    transition: padding 0.3s ease;
  }

  .nav-logo {
    font-family: var(--display);
    font-size: 20px;
    letter-spacing: 0.08em;
  }
  .nav-logo span { color: var(--muted); }

  .nav-links {
    display: flex;
    gap: 36px;
    list-style: none;
  }
  .nav-links a {
    font-size: 12px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--muted);
    transition: color 0.2s;
    font-family: var(--mono);
  }
  .nav-links a:hover { color: var(--white); }

  .btn-nav {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    padding: 10px 22px;
    border: 1px solid var(--border-md);
    border-radius: var(--radius-sm);
    background: transparent;
    color: var(--white);
    cursor: none;
    transition: background 0.2s, border-color 0.2s;
  }
  .btn-nav:hover {
    background: rgba(255,255,255,0.07);
    border-color: rgba(255,255,255,0.3);
  }

  /* ============================================================
     BUTTONS
  ============================================================ */
  .btn-primary {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    font-family: var(--mono);
    font-size: 12px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    padding: 16px 36px;
    background: var(--white);
    color: var(--black);
    border-radius: var(--radius-sm);
    cursor: none;
    border: none;
    font-weight: 500;
    transition: transform 0.2s, box-shadow 0.2s, background 0.2s;
    position: relative;
    overflow: hidden;
  }
  .btn-primary::after {
    content: '';
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.08);
    opacity: 0;
    transition: opacity 0.2s;
  }
  .btn-primary:hover { transform: translateY(-2px); box-shadow: 0 12px 40px rgba(255,255,255,0.15); }
  .btn-primary:hover::after { opacity: 1; }

  .btn-secondary {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    font-family: var(--mono);
    font-size: 12px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    padding: 16px 36px;
    background: transparent;
    color: var(--white);
    border-radius: var(--radius-sm);
    cursor: none;
    border: 1px solid var(--border-md);
    transition: border-color 0.2s, background 0.2s, transform 0.2s;
  }
  .btn-secondary:hover {
    border-color: rgba(255,255,255,0.4);
    background: rgba(255,255,255,0.04);
    transform: translateY(-2px);
  }

  /* ============================================================
     TICKER
  ============================================================ */
  .ticker-wrap {
    width: 100%;
    overflow: hidden;
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    padding: 14px 0;
    background: var(--off-black);
  }
  .ticker {
    display: flex;
    gap: 0;
    animation: ticker 28s linear infinite;
    white-space: nowrap;
    width: max-content;
  }
  .ticker-item {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--muted);
    padding: 0 36px;
  }
  .ticker-item span { color: var(--white); }

  /* ============================================================
     HERO SECTION
  ============================================================ */
  #hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 clamp(20px, 5vw, 60px) 60px;
    position: relative;
    overflow: hidden;
  }

  .hero-bg {
    position: absolute;
    inset: 0;
    background:
      radial-gradient(ellipse 80% 60% at 60% 20%, rgba(255,255,255,0.035) 0%, transparent 70%),
      radial-gradient(ellipse 50% 50% at 20% 80%, rgba(255,255,255,0.02) 0%, transparent 60%);
  }

  .hero-grid-lines {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(rgba(255,255,255,0.025) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.025) 1px, transparent 1px);
    background-size: 80px 80px;
    mask-image: radial-gradient(ellipse 90% 80% at 50% 50%, black 0%, transparent 100%);
  }

  .hero-eyebrow {
    display: flex;
    align-items: center;
    gap: 16px;
    margin-bottom: 28px;
    animation: fadeIn 1s ease both;
  }
  .hero-eyebrow-line {
    width: 40px;
    height: 1px;
    background: var(--muted);
  }

  .hero-headline {
    max-width: 1100px;
    margin-bottom: 32px;
    position: relative;
    z-index: 2;
    animation: fadeUp 0.9s 0.1s ease both;
  }

  .hero-headline .line-1 { display: block; }
  .hero-headline .line-2 { display: block; color: transparent; -webkit-text-stroke: 1px rgba(255,255,255,0.5); }
  .hero-headline .line-3 { display: block; }

  .hero-sub {
    max-width: 560px;
    margin-bottom: 44px;
    animation: fadeUp 0.9s 0.2s ease both;
  }

  .hero-ctas {
    display: flex;
    gap: 14px;
    flex-wrap: wrap;
    animation: fadeUp 0.9s 0.3s ease both;
    margin-bottom: 72px;
  }

  .hero-stats {
    display: flex;
    gap: 48px;
    animation: fadeUp 0.9s 0.4s ease both;
    padding-top: 48px;
    border-top: 1px solid var(--border);
  }

  .hero-stat-num {
    font-family: var(--display);
    font-size: 40px;
    line-height: 1;
    letter-spacing: 0.02em;
  }
  .hero-stat-label {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    margin-top: 6px;
  }

  /* Dashboard mockup */
  .hero-dashboard {
    position: absolute;
    right: -20px;
    top: 50%;
    transform: translateY(-50%);
    width: min(560px, 45vw);
    animation: fadeUp 1s 0.3s ease both, float 6s 1.3s ease-in-out infinite;
    z-index: 1;
  }

  .dashboard-card {
    background: var(--card-bg);
    border: 1px solid var(--border-md);
    border-radius: var(--radius-lg);
    overflow: hidden;
    box-shadow:
      0 40px 100px rgba(0,0,0,0.8),
      0 0 0 1px rgba(255,255,255,0.04),
      inset 0 1px 0 rgba(255,255,255,0.07);
  }

  .db-header {
    padding: 16px 20px;
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .db-dots { display: flex; gap: 6px; }
  .db-dot { width: 8px; height: 8px; border-radius: 50%; }
  .db-dot-r { background: #ff5f57; }
  .db-dot-y { background: #febc2e; }
  .db-dot-g { background: #28c840; }

  .db-title {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.1em;
    color: var(--muted);
    text-transform: uppercase;
  }

  .db-body { padding: 20px; }

  .db-greeting {
    font-family: var(--display);
    font-size: 24px;
    letter-spacing: 0.04em;
    margin-bottom: 16px;
  }

  .db-metrics {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin-bottom: 16px;
  }

  .db-metric {
    background: rgba(255,255,255,0.04);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 12px;
  }
  .db-metric-val {
    font-family: var(--display);
    font-size: 22px;
    letter-spacing: 0.02em;
    line-height: 1;
  }
  .db-metric-label {
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--muted);
    margin-top: 4px;
  }

  .db-chart {
    background: rgba(255,255,255,0.03);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 14px;
    margin-bottom: 12px;
    height: 90px;
    display: flex;
    align-items: flex-end;
    gap: 6px;
    overflow: hidden;
    position: relative;
  }
  .db-chart-scan {
    position: absolute;
    left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.15), transparent);
    animation: scan 3s linear infinite;
  }
  .db-bar {
    flex: 1;
    border-radius: 3px 3px 0 0;
    background: rgba(255,255,255,0.18);
    transition: background 0.2s;
  }
  .db-bar.active { background: rgba(255,255,255,0.85); }

  .db-tasks {
    display: flex;
    flex-direction: column;
    gap: 7px;
  }
  .db-task {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 9px 12px;
    background: rgba(255,255,255,0.03);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
  }
  .db-task-check {
    width: 14px; height: 14px;
    border-radius: 3px;
    border: 1px solid rgba(255,255,255,0.25);
    display: flex; align-items: center; justify-content: center;
    font-size: 8px;
    flex-shrink: 0;
  }
  .db-task-check.done { background: var(--white); color: var(--black); border-color: var(--white); }
  .db-task-text { font-family: var(--mono); font-size: 10px; letter-spacing: 0.06em; color: var(--off-white); }
  .db-task-badge {
    margin-left: auto;
    font-family: var(--mono);
    font-size: 9px;
    padding: 2px 7px;
    border-radius: 20px;
    background: rgba(255,255,255,0.08);
    color: var(--muted);
    letter-spacing: 0.08em;
  }

  /* ============================================================
     PROBLEM SECTION
  ============================================================ */
  #problem {
    padding: var(--section-pad);
    position: relative;
    overflow: hidden;
  }

  .problem-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: center;
    margin-top: 60px;
  }

  .problem-copy h2 {
    font-family: var(--display);
    font-size: clamp(42px, 6vw, 72px);
    line-height: 0.96;
    letter-spacing: 0.01em;
    margin-bottom: 24px;
  }

  .problem-list {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 0;
  }
  .problem-item {
    display: flex;
    align-items: flex-start;
    gap: 16px;
    padding: 20px 0;
    border-bottom: 1px solid var(--border);
  }
  .problem-item:first-child { border-top: 1px solid var(--border); }

  .problem-num {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.12em;
    color: var(--muted);
    margin-top: 4px;
    flex-shrink: 0;
  }
  .problem-text h4 {
    font-size: 15px;
    font-weight: 500;
    margin-bottom: 4px;
    letter-spacing: 0.01em;
  }
  .problem-text p { font-size: 13px; color: var(--muted); line-height: 1.6; font-weight: 300; }

  .problem-visual {
    position: relative;
  }

  .problem-quote {
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 40px;
    background: var(--card-bg);
    position: relative;
  }
  .problem-quote::before {
    content: '"';
    font-family: var(--display);
    font-size: 120px;
    line-height: 1;
    color: rgba(255,255,255,0.06);
    position: absolute;
    top: -10px;
    left: 24px;
  }
  .problem-quote p {
    font-size: clamp(18px, 2vw, 24px);
    font-weight: 300;
    line-height: 1.5;
    color: var(--off-white);
    position: relative;
    z-index: 1;
  }
  .problem-quote cite {
    display: block;
    margin-top: 20px;
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--muted);
    font-style: normal;
  }

  /* ============================================================
     SOLUTION SECTION
  ============================================================ */
  #solution {
    padding: var(--section-pad);
    background: var(--off-black);
    position: relative;
    overflow: hidden;
  }
  #solution::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 70% 60% at 50% 50%, rgba(255,255,255,0.025) 0%, transparent 70%);
    pointer-events: none;
  }

  .solution-header {
    text-align: center;
    max-width: 760px;
    margin: 0 auto 72px;
  }

  .solution-pillars {
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    gap: 12px;
    margin-top: 60px;
  }

  .pillar {
    padding: 28px 16px;
    border: 1px solid var(--border);
    border-radius: var(--radius-md);
    text-align: center;
    background: rgba(255,255,255,0.025);
    transition: border-color 0.3s, background 0.3s, transform 0.3s;
    cursor: none;
  }
  .pillar:hover {
    border-color: rgba(255,255,255,0.2);
    background: rgba(255,255,255,0.05);
    transform: translateY(-4px);
  }

  .pillar-icon {
    width: 36px; height: 36px;
    margin: 0 auto 14px;
    border-radius: 8px;
    background: rgba(255,255,255,0.07);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 16px;
  }

  .pillar-name {
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--off-white);
    line-height: 1.5;
  }

  /* ============================================================
     FEATURES SECTION
  ============================================================ */
  #features {
    padding: var(--section-pad);
  }

  .features-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    margin-bottom: 56px;
  }

  .feature-cards {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 16px;
  }

  .feature-card {
    border: 1px solid var(--border);
    border-radius: var(--radius-md);
    padding: 28px 24px;
    background: var(--card-bg);
    position: relative;
    overflow: hidden;
    cursor: none;
    transition: border-color 0.3s, transform 0.3s, box-shadow 0.3s;
  }
  .feature-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.15), transparent);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .feature-card:hover { border-color: rgba(255,255,255,0.18); transform: translateY(-3px); box-shadow: 0 20px 60px rgba(0,0,0,0.5); }
  .feature-card:hover::before { opacity: 1; }

  .feature-card.large { grid-column: span 2; }

  .fc-icon {
    width: 44px; height: 44px;
    border-radius: var(--radius-sm);
    background: rgba(255,255,255,0.06);
    border: 1px solid var(--border);
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
    margin-bottom: 20px;
  }

  .fc-num {
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.14em;
    color: var(--muted);
    margin-bottom: 10px;
    text-transform: uppercase;
  }

  .fc-title {
    font-family: var(--display);
    font-size: 22px;
    letter-spacing: 0.03em;
    margin-bottom: 10px;
    line-height: 1.1;
  }

  .fc-desc {
    font-size: 13px;
    color: var(--muted);
    line-height: 1.65;
    font-weight: 300;
  }

  .fc-tag {
    display: inline-block;
    margin-top: 16px;
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 4px 10px;
    border: 1px solid var(--border);
    border-radius: 20px;
    color: var(--muted);
  }

  /* ============================================================
     SYSTEM PREVIEW
  ============================================================ */
  #preview {
    padding: var(--section-pad);
    background: var(--off-black);
  }

  .preview-header { margin-bottom: 56px; }

  .preview-tabs {
    display: flex;
    gap: 0;
    margin-bottom: 32px;
    border-bottom: 1px solid var(--border);
  }

  .preview-tab {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 12px 20px;
    color: var(--muted);
    cursor: none;
    border-bottom: 2px solid transparent;
    margin-bottom: -1px;
    transition: color 0.2s, border-color 0.2s;
  }
  .preview-tab.active { color: var(--white); border-bottom-color: var(--white); }
  .preview-tab:hover { color: var(--off-white); }

  .preview-screen {
    border: 1px solid var(--border-md);
    border-radius: var(--radius-lg);
    overflow: hidden;
    background: var(--card-bg);
    box-shadow: 0 40px 100px rgba(0,0,0,0.7);
  }

  .preview-screen-header {
    background: var(--off-black);
    border-bottom: 1px solid var(--border);
    padding: 14px 20px;
    display: flex;
    align-items: center;
    gap: 20px;
  }

  .preview-screen-body {
    padding: 24px;
    display: grid;
    grid-template-columns: 240px 1fr;
    gap: 20px;
    min-height: 380px;
  }

  .ps-sidebar {
    border-right: 1px solid var(--border);
    padding-right: 20px;
    display: flex;
    flex-direction: column;
    gap: 6px;
  }
  .ps-sidebar-item {
    padding: 10px 12px;
    border-radius: var(--radius-sm);
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.08em;
    color: var(--muted);
    display: flex;
    align-items: center;
    gap: 10px;
    cursor: none;
    transition: background 0.2s, color 0.2s;
  }
  .ps-sidebar-item:hover, .ps-sidebar-item.active {
    background: rgba(255,255,255,0.06);
    color: var(--white);
  }
  .ps-sidebar-dot {
    width: 6px; height: 6px;
    border-radius: 50%;
    background: rgba(255,255,255,0.2);
    flex-shrink: 0;
  }
  .ps-sidebar-item.active .ps-sidebar-dot { background: var(--white); }

  .ps-main {
    display: flex;
    flex-direction: column;
    gap: 16px;
  }

  .ps-widget {
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 16px;
    background: rgba(255,255,255,0.02);
  }

  .ps-widget-title {
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 12px;
  }

  .ps-progress-row {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 8px;
  }
  .ps-progress-label {
    font-size: 12px;
    color: var(--off-white);
    width: 100px;
    flex-shrink: 0;
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.06em;
  }
  .ps-progress-bar {
    flex: 1;
    height: 4px;
    background: rgba(255,255,255,0.08);
    border-radius: 2px;
    overflow: hidden;
  }
  .ps-progress-fill {
    height: 100%;
    background: var(--white);
    border-radius: 2px;
    transition: width 1s ease;
  }
  .ps-progress-val {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--muted);
    width: 32px;
    text-align: right;
    flex-shrink: 0;
  }

  .ps-mini-grid {
    display: grid;
    grid-template-columns: repeat(7, 1fr);
    gap: 4px;
  }
  .ps-day {
    aspect-ratio: 1;
    border-radius: 3px;
    background: rgba(255,255,255,0.06);
    border: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: var(--mono);
    font-size: 9px;
    color: var(--muted);
  }
  .ps-day.done { background: rgba(255,255,255,0.7); color: var(--black); border-color: transparent; }
  .ps-day.today { border-color: rgba(255,255,255,0.4); color: var(--white); }

  /* ============================================================
     BENEFITS SECTION
  ============================================================ */
  #benefits {
    padding: var(--section-pad);
    position: relative;
  }

  .benefits-layout {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    align-items: center;
    margin-top: 60px;
  }

  .benefit-row {
    padding: 24px 0;
    border-bottom: 1px solid var(--border);
    display: flex;
    gap: 20px;
    align-items: flex-start;
    cursor: none;
    transition: padding-left 0.2s;
  }
  .benefit-row:first-child { border-top: 1px solid var(--border); }
  .benefit-row:hover { padding-left: 8px; }

  .benefit-arrow {
    font-size: 18px;
    margin-top: 2px;
    flex-shrink: 0;
    color: rgba(255,255,255,0.5);
    transition: color 0.2s, transform 0.2s;
  }
  .benefit-row:hover .benefit-arrow { color: var(--white); transform: translateX(4px); }

  .benefit-content h4 {
    font-size: 17px;
    font-weight: 500;
    margin-bottom: 6px;
    letter-spacing: 0.01em;
  }
  .benefit-content p { font-size: 13px; color: var(--muted); line-height: 1.6; font-weight: 300; }

  .benefits-visual {
    position: relative;
    display: flex;
    flex-direction: column;
    gap: 12px;
  }

  .bv-card {
    border: 1px solid var(--border);
    border-radius: var(--radius-md);
    padding: 24px;
    background: var(--card-bg);
    position: relative;
    overflow: hidden;
  }
  .bv-card::after {
    content: '';
    position: absolute;
    top: 0; right: 0;
    width: 80px; height: 80px;
    background: radial-gradient(circle, rgba(255,255,255,0.05) 0%, transparent 70%);
  }

  .bv-num {
    font-family: var(--display);
    font-size: 48px;
    line-height: 1;
    letter-spacing: 0.02em;
  }
  .bv-label { font-size: 13px; color: var(--muted); margin-top: 4px; font-weight: 300; }
  .bv-sub { font-family: var(--mono); font-size: 9px; letter-spacing: 0.14em; text-transform: uppercase; color: var(--muted); margin-top: 4px; }

  /* ============================================================
     WHO IT IS FOR
  ============================================================ */
  #audience {
    padding: var(--section-pad);
    background: var(--off-black);
  }

  .audience-header { margin-bottom: 56px; }

  .audience-cards {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 16px;
  }

  .audience-card {
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 36px 28px;
    position: relative;
    overflow: hidden;
    background: var(--card-bg);
    cursor: none;
    transition: border-color 0.3s, transform 0.3s;
  }
  .audience-card:hover { border-color: rgba(255,255,255,0.2); transform: translateY(-4px); }

  .ac-number {
    font-family: var(--display);
    font-size: 72px;
    line-height: 1;
    color: rgba(255,255,255,0.05);
    position: absolute;
    top: 20px; right: 24px;
    letter-spacing: 0.01em;
  }
  .ac-icon {
    font-size: 28px;
    margin-bottom: 16px;
  }
  .ac-title {
    font-family: var(--display);
    font-size: 26px;
    letter-spacing: 0.02em;
    margin-bottom: 12px;
    line-height: 1.1;
  }
  .ac-desc { font-size: 13px; color: var(--muted); line-height: 1.65; font-weight: 300; }
  .ac-tag {
    display: inline-block;
    margin-top: 20px;
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--muted);
    padding: 4px 10px;
    border: 1px solid var(--border);
    border-radius: 20px;
  }

  /* ============================================================
     TESTIMONIALS
  ============================================================ */
  #testimonials {
    padding: var(--section-pad);
  }

  .testimonials-header { margin-bottom: 56px; }

  .testimonial-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
  }

  .testimonial-card {
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 32px;
    background: var(--card-bg);
    position: relative;
    overflow: hidden;
    cursor: none;
    transition: border-color 0.3s, transform 0.3s;
  }
  .testimonial-card:hover { border-color: rgba(255,255,255,0.16); transform: translateY(-2px); }

  .tc-stars {
    display: flex;
    gap: 3px;
    margin-bottom: 16px;
  }
  .tc-star { font-size: 12px; }

  .tc-quote {
    font-size: 14px;
    line-height: 1.7;
    color: var(--off-white);
    font-weight: 300;
    margin-bottom: 24px;
  }

  .tc-author {
    display: flex;
    align-items: center;
    gap: 12px;
    padding-top: 20px;
    border-top: 1px solid var(--border);
  }
  .tc-avatar {
    width: 38px; height: 38px;
    border-radius: 50%;
    background: rgba(255,255,255,0.08);
    border: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: var(--display);
    font-size: 14px;
    flex-shrink: 0;
  }
  .tc-name { font-size: 13px; font-weight: 500; }
  .tc-meta { font-family: var(--mono); font-size: 9px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--muted); margin-top: 2px; }

  .tc-featured {
    background: rgba(255,255,255,0.04);
    border-color: rgba(255,255,255,0.12);
  }
  .tc-featured-label {
    position: absolute;
    top: 20px; right: 20px;
    font-family: var(--mono);
    font-size: 8px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    padding: 4px 9px;
    border-radius: 20px;
    background: rgba(255,255,255,0.08);
    color: var(--muted);
    border: 1px solid var(--border);
  }

  /* ============================================================
     PRICING
  ============================================================ */
  #pricing {
    padding: var(--section-pad);
    background: var(--off-black);
    position: relative;
    overflow: hidden;
  }
  #pricing::before {
    content: '';
    position: absolute;
    inset: 0;
    background:
      radial-gradient(ellipse 60% 80% at 50% 50%, rgba(255,255,255,0.03) 0%, transparent 70%);
    pointer-events: none;
  }

  .pricing-header { text-align: center; margin-bottom: 60px; }

  .pricing-card {
    max-width: 540px;
    margin: 0 auto;
    border: 1px solid rgba(255,255,255,0.18);
    border-radius: var(--radius-lg);
    overflow: hidden;
    background: var(--card-bg);
    box-shadow: 0 40px 100px rgba(0,0,0,0.6), inset 0 1px 0 rgba(255,255,255,0.07);
    position: relative;
  }

  .pricing-card-header {
    background: rgba(255,255,255,0.04);
    border-bottom: 1px solid var(--border);
    padding: 32px 40px;
    text-align: center;
  }

  .pricing-label {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 12px;
  }

  .pricing-title {
    font-family: var(--display);
    font-size: 36px;
    letter-spacing: 0.06em;
    margin-bottom: 8px;
  }

  .pricing-badge {
    display: inline-block;
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    padding: 5px 12px;
    border: 1px solid var(--border-md);
    border-radius: 20px;
    color: var(--muted);
  }

  .pricing-card-body {
    padding: 36px 40px;
  }

  .pricing-price {
    text-align: center;
    margin-bottom: 36px;
  }
  .pricing-price-num {
    font-family: var(--display);
    font-size: 80px;
    line-height: 1;
    letter-spacing: 0.02em;
  }
  .pricing-price-note {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--muted);
    margin-top: 8px;
  }

  .pricing-includes {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 0;
    margin-bottom: 36px;
  }
  .pricing-include {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 14px 0;
    border-bottom: 1px solid var(--border);
    font-size: 14px;
    font-weight: 300;
  }
  .pricing-include:first-child { border-top: 1px solid var(--border); }
  .pi-check {
    width: 18px; height: 18px;
    border-radius: 50%;
    background: rgba(255,255,255,0.08);
    border: 1px solid var(--border-md);
    display: flex; align-items: center; justify-content: center;
    font-size: 9px;
    flex-shrink: 0;
  }

  .pricing-cta {
    width: 100%;
    text-align: center;
    justify-content: center;
    font-size: 13px;
    padding: 18px;
  }

  .pricing-guarantee {
    text-align: center;
    margin-top: 20px;
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--muted);
  }

  /* ============================================================
     FAQ
  ============================================================ */
  #faq {
    padding: var(--section-pad);
  }

  .faq-layout {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 80px;
    margin-top: 60px;
    align-items: flex-start;
  }

  .faq-sidebar h3 {
    font-family: var(--display);
    font-size: 40px;
    line-height: 1;
    letter-spacing: 0.02em;
    margin-bottom: 16px;
  }
  .faq-sidebar p { font-size: 14px; color: var(--muted); line-height: 1.6; font-weight: 300; }

  .faq-list {
    display: flex;
    flex-direction: column;
    gap: 0;
  }

  .faq-item {
    border-bottom: 1px solid var(--border);
    padding: 0;
    overflow: hidden;
  }
  .faq-item:first-child { border-top: 1px solid var(--border); }

  .faq-q {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 22px 0;
    cursor: none;
    gap: 20px;
  }
  .faq-q h4 {
    font-size: 15px;
    font-weight: 400;
    letter-spacing: 0.01em;
  }
  .faq-toggle {
    width: 24px; height: 24px;
    border-radius: 50%;
    border: 1px solid var(--border-md);
    display: flex; align-items: center; justify-content: center;
    font-size: 14px;
    flex-shrink: 0;
    color: var(--muted);
    transition: transform 0.3s, background 0.2s, color 0.2s;
  }
  .faq-item.open .faq-toggle {
    transform: rotate(45deg);
    background: rgba(255,255,255,0.08);
    color: var(--white);
  }
  .faq-a {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.35s ease, padding 0.35s ease;
  }
  .faq-item.open .faq-a { max-height: 200px; padding-bottom: 22px; }
  .faq-a p { font-size: 14px; color: var(--muted); line-height: 1.7; font-weight: 300; }

  /* ============================================================
     FINAL CTA
  ============================================================ */
  #final-cta {
    padding: var(--section-pad);
    background: var(--off-black);
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  #final-cta::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 80% 100% at 50% 50%, rgba(255,255,255,0.04) 0%, transparent 70%);
    pointer-events: none;
  }

  .final-eyebrow {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
    margin-bottom: 32px;
  }
  .final-eyebrow-line { width: 48px; height: 1px; background: var(--muted); }

  .final-headline {
    font-family: var(--display);
    font-size: clamp(56px, 9vw, 120px);
    line-height: 0.93;
    letter-spacing: 0.01em;
    max-width: 900px;
    margin: 0 auto 24px;
  }

  .final-sub {
    max-width: 480px;
    margin: 0 auto 44px;
    font-size: 16px;
    color: var(--muted);
    font-weight: 300;
    line-height: 1.6;
  }

  .final-ctas {
    display: flex;
    justify-content: center;
    gap: 14px;
    flex-wrap: wrap;
    margin-bottom: 48px;
  }

  .final-note {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--muted);
  }

  /* ============================================================
     FOOTER
  ============================================================ */
  footer {
    padding: 40px clamp(20px, 5vw, 60px);
    border-top: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
  }

  .footer-logo {
    font-family: var(--display);
    font-size: 18px;
    letter-spacing: 0.08em;
    color: var(--muted);
  }

  .footer-note {
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: rgba(255,255,255,0.2);
  }

  .footer-links {
    display: flex;
    gap: 28px;
    list-style: none;
  }
  .footer-links a {
    font-family: var(--mono);
    font-size: 9px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: rgba(255,255,255,0.2);
    transition: color 0.2s;
  }
  .footer-links a:hover { color: var(--muted); }

  /* ============================================================
     RESPONSIVE
  ============================================================ */
  @media (max-width: 1024px) {
    .hero-dashboard { display: none; }
    .feature-cards { grid-template-columns: repeat(2, 1fr); }
    .feature-card.large { grid-column: span 1; }
    .solution-pillars { grid-template-columns: repeat(3, 1fr); }
    .preview-screen-body { grid-template-columns: 1fr; }
    .ps-sidebar { display: none; }
  }
  @media (max-width: 768px) {
    .nav-links { display: none; }
    .problem-grid { grid-template-columns: 1fr; gap: 40px; }
    .benefits-layout { grid-template-columns: 1fr; gap: 40px; }
    .audience-cards { grid-template-columns: repeat(2, 1fr); }
    .testimonial-grid { grid-template-columns: 1fr; }
    .faq-layout { grid-template-columns: 1fr; gap: 40px; }
    .hero-stats { gap: 28px; flex-wrap: wrap; }
    .grid-3 { grid-template-columns: 1fr; }
    .features-header { flex-direction: column; align-items: flex-start; gap: 20px; }
  }
  @media (max-width: 540px) {
    .audience-cards { grid-template-columns: 1fr; }
    .feature-cards { grid-template-columns: 1fr; }
    .btn-primary, .btn-secondary { padding: 14px 24px; }
    .solution-pillars { grid-template-columns: repeat(2, 1fr); }
    footer { justify-content: center; text-align: center; }
    .footer-links { flex-wrap: wrap; justify-content: center; }
  }
</style>
</head>
<body>

<!-- Custom cursor -->
<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- ================================================================
     NAV
================================================================ -->
<nav id="nav">
  <div class="nav-logo">HYBRID<span>ATHLETE</span></div>
  <ul class="nav-links">
    <li><a href="#problem">Problem</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#preview">Preview</a></li>
    <li><a href="#pricing">Pricing</a></li>
    <li><a href="#faq">FAQ</a></li>
  </ul>
  <a href="#pricing" class="btn-nav">Get Access</a>
</nav>

<!-- ================================================================
     HERO
================================================================ -->
<section id="hero">
  <div class="hero-bg"></div>
  <div class="hero-grid-lines"></div>

  <!-- Dashboard mockup (desktop) -->
  <div class="hero-dashboard">
    <div class="dashboard-card">
      <div class="db-header">
        <div class="db-dots">
          <div class="db-dot db-dot-r"></div>
          <div class="db-dot db-dot-y"></div>
          <div class="db-dot db-dot-g"></div>
        </div>
        <div class="db-title">Daily Dashboard</div>
        <div style="font-family:var(--mono);font-size:9px;letter-spacing:0.1em;color:var(--muted);">WEEK 7 / DAY 3</div>
      </div>
      <div class="db-body">
        <div class="db-greeting">GOOD MORNING, ATHLETE.</div>
        <div class="db-metrics">
          <div class="db-metric">
            <div class="db-metric-val">82%</div>
            <div class="db-metric-label">Week Score</div>
          </div>
          <div class="db-metric">
            <div class="db-metric-val">5.2K</div>
            <div class="db-metric-label">Cals Burned</div>
          </div>
          <div class="db-metric">
            <div class="db-metric-val">47</div>
            <div class="db-metric-label">Day Streak</div>
          </div>
        </div>
        <div class="db-chart">
          <div class="db-chart-scan"></div>
          <div class="db-bar" style="height:45%"></div>
          <div class="db-bar" style="height:62%"></div>
          <div class="db-bar" style="height:38%"></div>
          <div class="db-bar" style="height:70%"></div>
          <div class="db-bar" style="height:55%"></div>
          <div class="db-bar active" style="height:85%"></div>
          <div class="db-bar" style="height:30%"></div>
        </div>
        <div class="db-tasks">
          <div class="db-task">
            <div class="db-task-check done">✓</div>
            <div class="db-task-text">Morning run — 5km tempo</div>
            <div class="db-task-badge">Done</div>
          </div>
          <div class="db-task">
            <div class="db-task-check done">✓</div>
            <div class="db-task-text">Strength — Upper A session</div>
            <div class="db-task-badge">Done</div>
          </div>
          <div class="db-task">
            <div class="db-task-check"></div>
            <div class="db-task-text">Evening nutrition log</div>
            <div class="db-task-badge">Pending</div>
          </div>
          <div class="db-task">
            <div class="db-task-check"></div>
            <div class="db-task-text">Recovery checklist</div>
            <div class="db-task-badge">Pending</div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div style="position:relative;z-index:2;max-width:1200px;margin:0 auto;width:100%;">
    <div class="hero-eyebrow">
      <div class="hero-eyebrow-line"></div>
      <span class="label">The Complete Performance System</span>
    </div>

    <h1 class="display-xl hero-headline">
      <span class="line-1">BUILD</span>
      <span class="line-2">MUSCLE.</span>
      <span class="line-3">RUN FASTER.</span>
    </h1>

    <p class="body-lg hero-sub">
      A complete hybrid performance system combining strength, endurance, discipline, nutrition, and daily tracking — engineered for athletes who refuse to choose.
    </p>

    <div class="hero-ctas">
      <a href="#pricing" class="btn-primary">
        Get Instant Access
        <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M1 7h12M8 2l5 5-5 5" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </a>
      <a href="#preview" class="btn-secondary">
        Preview System
        <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><circle cx="7" cy="7" r="5.5" stroke="currentColor" stroke-width="1.3"/><path d="M5.5 5.5l3 1.5-3 1.5V5.5z" fill="currentColor"/></svg>
      </a>
    </div>

    <div class="hero-stats">
      <div>
        <div class="hero-stat-num">12</div>
        <div class="hero-stat-label">Week program</div>
      </div>
      <div>
        <div class="hero-stat-num">8</div>
        <div class="hero-stat-label">Modules included</div>
      </div>
      <div>
        <div class="hero-stat-num">340+</div>
        <div class="hero-stat-label">Training sessions</div>
      </div>
      <div>
        <div class="hero-stat-num">∞</div>
        <div class="hero-stat-label">Lifetime updates</div>
      </div>
    </div>
  </div>
</section>

<!-- ================================================================
     TICKER
================================================================ -->
<div class="ticker-wrap">
  <div class="ticker">
    <span class="ticker-item">Strength Training</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Running Performance</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Nutrition System</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Daily Discipline</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Recovery Protocols</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Progress Analytics</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Body Transformation</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Elite Performance Habits</span>
    <span class="ticker-item">·</span>
    <!-- duplicate for seamless loop -->
    <span class="ticker-item">Strength Training</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Running Performance</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Nutrition System</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Daily Discipline</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Recovery Protocols</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Progress Analytics</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Body Transformation</span>
    <span class="ticker-item">·</span>
    <span class="ticker-item">Elite Performance Habits</span>
    <span class="ticker-item">·</span>
  </div>
</div>

<!-- ================================================================
     PROBLEM SECTION
================================================================ -->
<section id="problem">
  <div class="container">
    <div class="problem-grid">
      <div class="problem-copy reveal">
        <p class="label" style="margin-bottom:16px;">The Real Problem</p>
        <h2>Most athletes train hard.<br>Almost none train <em style="font-style:italic;color:var(--muted);">right.</em></h2>
        <p class="body-md" style="margin:20px 0 36px;max-width:480px;">You show up. You put in the work. But weeks pass and the needle barely moves. The problem isn't effort — it's the absence of a real system.</p>
        <ul class="problem-list">
          <li class="problem-item reveal reveal-delay-1">
            <span class="problem-num">01</span>
            <div class="problem-text">
              <h4>Random, Disconnected Workouts</h4>
              <p>No programming logic. No progression model. Just isolated sessions that don't build toward anything meaningful.</p>
            </div>
          </li>
          <li class="problem-item reveal reveal-delay-2">
            <span class="problem-num">02</span>
            <div class="problem-text">
              <h4>Zero Structured Progression</h4>
              <p>Without progressive overload and structured phases, your body adapts and stops growing. You plateau — fast.</p>
            </div>
          </li>
          <li class="problem-item reveal reveal-delay-3">
            <span class="problem-num">03</span>
            <div class="problem-text">
              <h4>Muscle vs. Endurance Conflict</h4>
              <p>Trying to run and lift without a hybrid protocol destroys both. You need a system built for both goals simultaneously.</p>
            </div>
          </li>
          <li class="problem-item reveal reveal-delay-4">
            <span class="problem-num">04</span>
            <div class="problem-text">
              <h4>No Tracking, No Accountability</h4>
              <p>What gets measured gets improved. Without daily tracking, progress is invisible — and invisible progress dies.</p>
            </div>
          </li>
          <li class="problem-item reveal reveal-delay-5">
            <span class="problem-num">05</span>
            <div class="problem-text">
              <h4>Inconsistent Discipline</h4>
              <p>Motivation is unreliable. Without a habit system built into your training, even the best program fails.</p>
            </div>
          </li>
        </ul>
      </div>

      <div class="problem-visual reveal reveal-delay-2">
        <div class="problem-quote">
          <p>I trained for two years straight and never looked or performed like an athlete. The missing piece wasn't effort — it was a complete, integrated system that tied everything together.</p>
          <cite>— The mindset behind the Hybrid Athlete System</cite>
        </div>
        <div style="margin-top:20px;display:grid;grid-template-columns:1fr 1fr;gap:12px;">
          <div style="border:1px solid var(--border);border-radius:var(--radius-md);padding:20px;background:var(--card-bg);">
            <div style="font-family:var(--display);font-size:36px;letter-spacing:0.02em;margin-bottom:4px;">73%</div>
            <div style="font-size:12px;color:var(--muted);font-weight:300;line-height:1.5;">of athletes quit within 8 weeks due to lack of structure</div>
          </div>
          <div style="border:1px solid var(--border);border-radius:var(--radius-md);padding:20px;background:var(--card-bg);">
            <div style="font-family:var(--display);font-size:36px;letter-spacing:0.02em;margin-bottom:4px;">91%</div>
            <div style="font-size:12px;color:var(--muted);font-weight:300;line-height:1.5;">of hybrid athletes fail from conflicting, unstructured programs</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ================================================================
     SOLUTION SECTION
================================================================ -->
<section id="solution">
  <div class="container">
    <div class="solution-header reveal">
      <p class="label" style="margin-bottom:16px;">The Complete Answer</p>
      <h2 class="display-lg">One system.<br>Every dimension.</h2>
      <p class="body-lg" style="margin-top:24px;max-width:600px;margin-left:auto;margin-right:auto;">
        The Hybrid Athlete System is the first complete performance framework that engineers both strength and endurance simultaneously — backed by progressive programming, daily accountability, and measurable results.
      </p>
    </div>

    <div class="solution-pillars">
      <div class="pillar reveal reveal-delay-1">
        <div class="pillar-icon">🏋️</div>
        <div class="pillar-name">Structured<br>Training</div>
      </div>
      <div class="pillar reveal reveal-delay-2">
        <div class="pillar-icon">🏃</div>
        <div class="pillar-name">Running<br>Performance</div>
      </div>
      <div class="pillar reveal reveal-delay-3">
        <div class="pillar-icon">🔥</div>
        <div class="pillar-name">Daily<br>Discipline</div>
      </div>
      <div class="pillar reveal reveal-delay-4">
        <div class="pillar-icon">🥗</div>
        <div class="pillar-name">Nutrition<br>System</div>
      </div>
      <div class="pillar reveal reveal-delay-5">
        <div class="pillar-icon">⚡</div>
        <div class="pillar-name">Recovery<br>Protocols</div>
      </div>
      <div class="pillar reveal reveal-delay-5">
        <div class="pillar-icon">📊</div>
        <div class="pillar-name">Progress<br>Analytics</div>
      </div>
    </div>

    <div style="margin-top:60px;padding:40px;border:1px solid var(--border);border-radius:var(--radius-lg);background:rgba(255,255,255,0.025);text-align:center;" class="reveal">
      <p class="label" style="margin-bottom:16px;">System Architecture</p>
      <p style="font-size:clamp(17px,1.8vw,22px);line-height:1.6;color:var(--off-white);font-weight:300;max-width:720px;margin:0 auto;">
        Six interconnected modules. One unified daily workflow. Built to create an athlete who is strong, fast, conditioned, lean, and mentally disciplined — all at once.
      </p>
    </div>
  </div>
</section>

<!-- ================================================================
     FEATURES SECTION
================================================================ -->
<section id="features">
  <div class="container">
    <div class="features-header">
      <div class="reveal">
        <p class="label" style="margin-bottom:12px;">What's Inside</p>
        <h2 class="display-md">8 complete<br>modules.</h2>
      </div>
      <p class="body-md reveal reveal-delay-2" style="max-width:320px;">Every component is engineered to work independently and together — a complete ecosystem for athlete development.</p>
    </div>

    <div class="feature-cards">
      <div class="feature-card large reveal">
        <div class="fc-num">MODULE 01</div>
        <div class="fc-icon">📅</div>
        <div class="fc-title">12-WEEK HYBRID TRAINING PROGRAM</div>
        <div class="fc-desc">A fully periodized 12-week training protocol that intelligently combines strength, hypertrophy, and endurance blocks. Structured in phases that prevent interference and maximize adaptation across both muscle growth and cardiovascular performance.</div>
        <span class="fc-tag">Core Module</span>
      </div>
      <div class="feature-card reveal reveal-delay-1">
        <div class="fc-num">MODULE 02</div>
        <div class="fc-icon">⚡</div>
        <div class="fc-title">DAILY PERFORMANCE TRACKER</div>
        <div class="fc-desc">Your complete daily command center. Log workouts, runs, nutrition, sleep, energy levels, and mood. Built-in scoring makes progress visible every single day.</div>
        <span class="fc-tag">Daily Use</span>
      </div>
      <div class="feature-card reveal reveal-delay-2">
        <div class="fc-num">MODULE 03</div>
        <div class="fc-icon">🏃</div>
        <div class="fc-title">RUNNING PROGRESSION SYSTEM</div>
        <div class="fc-desc">A structured 12-week running plan with zone training, tempo runs, long runs, and speed work. Built to complement the strength program without crushing your recovery.</div>
        <span class="fc-tag">Performance</span>
      </div>
      <div class="feature-card reveal reveal-delay-1">
        <div class="fc-num">MODULE 04</div>
        <div class="fc-icon">🥗</div>
        <div class="fc-title">NUTRITION SYSTEM</div>
        <div class="fc-desc">A complete nutrition framework: calorie targets, macro splits, meal timing, pre/post-workout fuel, and weekly tracking sheets. Designed for body recomposition and athletic performance simultaneously.</div>
        <span class="fc-tag">Nutrition</span>
      </div>
      <div class="feature-card reveal reveal-delay-2">
        <div class="fc-num">MODULE 05</div>
        <div class="fc-icon">💤</div>
        <div class="fc-title">RECOVERY DASHBOARD</div>
        <div class="fc-desc">Track sleep quality, soreness, readiness, and HRV trends. Includes recovery protocols: mobility work, breathing, cold exposure guidance, and weekly deload programming.</div>
        <span class="fc-tag">Recovery</span>
      </div>
      <div class="feature-card reveal reveal-delay-3">
        <div class="fc-num">MODULE 06</div>
        <div class="fc-icon">📈</div>
        <div class="fc-title">BODY TRANSFORMATION TRACKER</div>
        <div class="fc-desc">Monthly check-in protocols with body composition tracking, strength benchmarks, running performance metrics, and visual progress documentation. Your transformation, made measurable.</div>
        <span class="fc-tag">Analytics</span>
      </div>
      <div class="feature-card reveal reveal-delay-4">
        <div class="fc-num">MODULE 07</div>
        <div class="fc-icon">🎯</div>
        <div class="fc-title">HABIT DISCIPLINE TRACKER</div>
        <div class="fc-desc">A daily and weekly habit system that builds the behavioral infrastructure of an elite athlete. Track non-negotiables, build streaks, and develop unbreakable discipline through systems, not willpower.</div>
        <span class="fc-tag">Discipline</span>
      </div>
      <div class="feature-card reveal reveal-delay-5">
        <div class="fc-num">MODULE 08</div>
        <div class="fc-icon">🔄</div>
        <div class="fc-title">WEEKLY REVIEW SYSTEM</div>
        <div class="fc-desc">A structured weekly review process covering training adherence, performance analysis, nutrition compliance, and next-week planning. Keeps the entire system self-correcting and continuously improving.</div>
        <span class="fc-tag">System</span>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ================================================================
     SYSTEM PREVIEW
================================================================ -->
<section id="preview">
  <div class="container">
    <div class="preview-header reveal">
      <p class="label" style="margin-bottom:12px;">Inside the System</p>
      <h2 class="display-md">Your daily<br>performance hub.</h2>
      <p class="body-md" style="margin-top:16px;max-width:480px;">A premium digital experience designed for athletes who take their performance seriously. Everything in one place, every day.</p>
    </div>

    <div class="preview-tabs reveal reveal-delay-1">
      <div class="preview-tab active">Daily Dashboard</div>
      <div class="preview-tab">Training Log</div>
      <div class="preview-tab">Running Tracker</div>
      <div class="preview-tab">Progress Analytics</div>
    </div>

    <div class="preview-screen reveal reveal-delay-2">
      <div class="preview-screen-header">
        <div class="db-dots">
          <div class="db-dot db-dot-r"></div>
          <div class="db-dot db-dot-y"></div>
          <div class="db-dot db-dot-g"></div>
        </div>
        <div style="font-family:var(--mono);font-size:10px;letter-spacing:0.1em;color:var(--muted);text-transform:uppercase;">Hybrid Athlete System — Daily Dashboard</div>
        <div style="margin-left:auto;display:flex;gap:12px;align-items:center;">
          <div style="font-family:var(--mono);font-size:9px;letter-spacing:0.1em;color:var(--muted);text-transform:uppercase;">Week 7 of 12</div>
          <div style="width:80px;height:4px;background:rgba(255,255,255,0.08);border-radius:2px;overflow:hidden;">
            <div style="height:100%;width:58%;background:var(--white);border-radius:2px;"></div>
          </div>
        </div>
      </div>
      <div class="preview-screen-body">
        <div class="ps-sidebar">
          <div style="font-family:var(--mono);font-size:9px;letter-spacing:0.14em;text-transform:uppercase;color:rgba(255,255,255,0.2);padding:4px 12px;margin-bottom:4px;">Navigation</div>
          <div class="ps-sidebar-item active">
            <div class="ps-sidebar-dot"></div>Dashboard
          </div>
          <div class="ps-sidebar-item">
            <div class="ps-sidebar-dot"></div>Training Calendar
          </div>
          <div class="ps-sidebar-item">
            <div class="ps-sidebar-dot"></div>Running Tracker
          </div>
          <div class="ps-sidebar-item">
            <div class="ps-sidebar-dot"></div>Meal Tracker
          </div>
          <div class="ps-sidebar-item">
            <div class="ps-sidebar-dot"></div>Progress Analytics
          </div>
          <div class="ps-sidebar-item">
            <div class="ps-sidebar-dot"></div>Weekly Review
          </div>
          <div class="ps-sidebar-item">
            <div class="ps-sidebar-dot"></div>Recovery Log
          </div>
          <div class="ps-sidebar-item">
            <div class="ps-sidebar-dot"></div>Habit Tracker
          </div>
        </div>
        <div class="ps-main">
          <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:10px;">
            <div class="ps-widget" style="text-align:center;">
              <div style="font-family:var(--display);font-size:28px;line-height:1;letter-spacing:0.02em;">47</div>
              <div class="ps-widget-title" style="margin-top:6px;margin-bottom:0;">Day Streak</div>
            </div>
            <div class="ps-widget" style="text-align:center;">
              <div style="font-family:var(--display);font-size:28px;line-height:1;letter-spacing:0.02em;">82%</div>
              <div class="ps-widget-title" style="margin-top:6px;margin-bottom:0;">Week Score</div>
            </div>
            <div class="ps-widget" style="text-align:center;">
              <div style="font-family:var(--display);font-size:28px;line-height:1;letter-spacing:0.02em;">38km</div>
              <div class="ps-widget-title" style="margin-top:6px;margin-bottom:0;">Week Miles</div>
            </div>
            <div class="ps-widget" style="text-align:center;">
              <div style="font-family:var(--display);font-size:28px;line-height:1;letter-spacing:0.02em;">5/6</div>
              <div class="ps-widget-title" style="margin-top:6px;margin-bottom:0;">Sessions</div>
            </div>
          </div>
          <div class="ps-widget">
            <div class="ps-widget-title">Weekly Performance</div>
            <div class="ps-progress-row">
              <div class="ps-progress-label">Strength</div>
              <div class="ps-progress-bar"><div class="ps-progress-fill" style="width:88%"></div></div>
              <div class="ps-progress-val">88%</div>
            </div>
            <div class="ps-progress-row">
              <div class="ps-progress-label">Running</div>
              <div class="ps-progress-bar"><div class="ps-progress-fill" style="width:74%"></div></div>
              <div class="ps-progress-val">74%</div>
            </div>
            <div class="ps-progress-row">
              <div class="ps-progress-label">Nutrition</div>
              <div class="ps-progress-bar"><div class="ps-progress-fill" style="width:91%"></div></div>
              <div class="ps-progress-val">91%</div>
            </div>
            <div class="ps-progress-row">
              <div class="ps-progress-label">Recovery</div>
              <div class="ps-progress-bar"><div class="ps-progress-fill" style="width:67%"></div></div>
              <div class="ps-progress-val">67%</div>
            </div>
            <div class="ps-progress-row">
              <div class="ps-progress-label">Habits</div>
              <div class="ps-progress-bar"><div class="ps-progress-fill" style="width:96%"></div></div>
              <div class="ps-progress-val">96%</div>
            </div>
          </div>
          <div class="ps-widget">
            <div class="ps-widget-title">Month Consistency</div>
            <div class="ps-mini-grid">
              <div class="ps-day done">M</div>
              <div class="ps-day done">T</div>
              <div class="ps-day done">W</div>
              <div class="ps-day done">T</div>
              <div class="ps-day done">F</div>
              <div class="ps-day">S</div>
              <div class="ps-day done">S</div>
              <div class="ps-day done">M</div>
              <div class="ps-day done">T</div>
              <div class="ps-day done">W</div>
              <div class="ps-day done">T</div>
              <div class="ps-day done">F</div>
              <div class="ps-day done">S</div>
              <div class="ps-day">S</div>
              <div class="ps-day done">M</div>
              <div class="ps-day done">T</div>
              <div class="ps-day done">W</div>
              <div class="ps-day today">T</div>
              <div class="ps-day">F</div>
              <div class="ps-day">S</div>
              <div class="ps-day">S</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ================================================================
     BENEFITS SECTION
================================================================ -->
<section id="benefits">
  <div class="container">
    <div style="text-align:center;margin-bottom:60px;" class="reveal">
      <p class="label" style="margin-bottom:12px;">What You'll Achieve</p>
      <h2 class="display-md">Outcomes that<br>are measurable.</h2>
    </div>

    <div class="benefits-layout">
      <div class="reveal">
        <div class="benefit-row">
          <div class="benefit-arrow">→</div>
          <div class="benefit-content">
            <h4>Build an Athletic Physique</h4>
            <p>Gain lean muscle mass while staying conditioned. The hybrid protocol is specifically designed to optimize body composition without sacrificing performance in either domain.</p>
          </div>
        </div>
        <div class="benefit-row">
          <div class="benefit-arrow">→</div>
          <div class="benefit-content">
            <h4>Dramatically Improve Endurance</h4>
            <p>Progress from wherever you are to completing 5K, 10K, and beyond — with improving pace, better zone control, and real cardiovascular adaptation built over 12 structured weeks.</p>
          </div>
        </div>
        <div class="benefit-row">
          <div class="benefit-arrow">→</div>
          <div class="benefit-content">
            <h4>Build Unshakeable Discipline</h4>
            <p>Daily habit systems and accountability tools turn discipline from a feeling into a process. You'll build the behavioral infrastructure that makes consistency automatic.</p>
          </div>
        </div>
        <div class="benefit-row">
          <div class="benefit-arrow">→</div>
          <div class="benefit-content">
            <h4>Track Real, Measurable Progress</h4>
            <p>Daily tracking and monthly check-ins make progress visible. When you can see it, you believe it. When you believe it, you accelerate it.</p>
          </div>
        </div>
        <div class="benefit-row">
          <div class="benefit-arrow">→</div>
          <div class="benefit-content">
            <h4>Develop Elite Performance Habits</h4>
            <p>Nutrition, recovery, training, and mindset habits compound over 12 weeks to create an athlete identity — not just a phase, but a permanent lifestyle upgrade.</p>
          </div>
        </div>
      </div>

      <div class="benefits-visual reveal reveal-delay-2">
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:12px;">
          <div class="bv-card">
            <div class="bv-num">+18%</div>
            <div class="bv-label">Average strength increase in 12 weeks</div>
            <div class="bv-sub" style="margin-top:8px;">Compound lifts</div>
          </div>
          <div class="bv-card">
            <div class="bv-num">−12%</div>
            <div class="bv-label">Average body fat reduction</div>
            <div class="bv-sub" style="margin-top:8px;">Body composition</div>
          </div>
        </div>
        <div class="bv-card">
          <div style="display:flex;gap:32px;align-items:flex-end;">
            <div>
              <div class="bv-num">4:31</div>
              <div class="bv-label">Average 1km improvement by end of program</div>
            </div>
            <div style="margin-left:auto;text-align:right;">
              <div style="font-family:var(--mono);font-size:10px;letter-spacing:0.12em;text-transform:uppercase;color:var(--muted);">Running pace</div>
              <div style="font-family:var(--display);font-size:48px;line-height:1;letter-spacing:0.02em;margin-top:4px;color:rgba(255,255,255,0.25);">→</div>
            </div>
          </div>
          <div class="bv-sub" style="margin-top:12px;">Per kilometer</div>
        </div>
        <div class="bv-card" style="margin-top:12px;">
          <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:16px;text-align:center;">
            <div>
              <div style="font-family:var(--display);font-size:32px;letter-spacing:0.02em;">89%</div>
              <div style="font-size:11px;color:var(--muted);margin-top:4px;font-weight:300;">Completion rate</div>
            </div>
            <div>
              <div style="font-family:var(--display);font-size:32px;letter-spacing:0.02em;">12w</div>
              <div style="font-size:11px;color:var(--muted);margin-top:4px;font-weight:300;">Full program</div>
            </div>
            <div>
              <div style="font-family:var(--display);font-size:32px;letter-spacing:0.02em;">8x</div>
              <div style="font-size:11px;color:var(--muted);margin-top:4px;font-weight:300;">Modules included</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ================================================================
     AUDIENCE
================================================================ -->
<section id="audience">
  <div class="container">
    <div class="audience-header reveal">
      <p class="label" style="margin-bottom:12px;">Who It's Built For</p>
      <h2 class="display-md">You don't have to<br>choose anymore.</h2>
    </div>

    <div class="audience-cards">
      <div class="audience-card reveal reveal-delay-1">
        <div class="ac-number">01</div>
        <div class="ac-icon">🏋️</div>
        <div class="ac-title">THE LIFTER WANTING ENDURANCE</div>
        <div class="ac-desc">You've built a solid physique but get gassed running to the mailbox. The Hybrid System adds elite conditioning without touching your hard-earned muscle.</div>
        <span class="ac-tag">Strength → Endurance</span>
      </div>
      <div class="audience-card reveal reveal-delay-2">
        <div class="ac-number">02</div>
        <div class="ac-icon">🏃</div>
        <div class="ac-title">THE RUNNER WANTING MUSCLE</div>
        <div class="ac-desc">You can run for days but look the same every year. The Hybrid System builds functional muscle that makes you faster, stronger, and more powerful on every run.</div>
        <span class="ac-tag">Endurance → Strength</span>
      </div>
      <div class="audience-card reveal reveal-delay-3">
        <div class="ac-number">03</div>
        <div class="ac-icon">⚡</div>
        <div class="ac-title">THE ATHLETE NEEDING STRUCTURE</div>
        <div class="ac-desc">You're athletic but training randomly. The Hybrid System gives you a complete 12-week architecture that transforms athletic potential into measurable, consistent performance.</div>
        <span class="ac-tag">Potential → Performance</span>
      </div>
      <div class="audience-card reveal reveal-delay-4">
        <div class="ac-number">04</div>
        <div class="ac-icon">🎯</div>
        <div class="ac-title">THE TRANSFORMER GOING ALL IN</div>
        <div class="ac-desc">You want a total lifestyle overhaul — body, performance, habits, nutrition, mindset. The Hybrid System is the complete blueprint for a full transformation, starting today.</div>
        <span class="ac-tag">Now → Elite</span>
      </div>
    </div>
  </div>
</section>

<!-- ================================================================
     TESTIMONIALS
================================================================ -->
<section id="testimonials">
  <div class="container">
    <div class="testimonials-header reveal">
      <p class="label" style="margin-bottom:12px;">Results</p>
      <h2 class="display-md">Real athletes.<br>Real outcomes.</h2>
    </div>

    <div class="testimonial-grid">
      <div class="testimonial-card tc-featured reveal">
        <span class="tc-featured-label">Featured</span>
        <div class="tc-stars">
          <span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span>
        </div>
        <p class="tc-quote">"12 weeks in and I've dropped 9kg of body fat, added 15kg to my squat, and just ran my first sub-25 minute 5K. I've been training for 4 years and never saw results like this. The system just works."</p>
        <div class="tc-author">
          <div class="tc-avatar">MR</div>
          <div>
            <div class="tc-name">Marcus R.</div>
            <div class="tc-meta">Week 12 · Full Program Completion</div>
          </div>
        </div>
      </div>
      <div class="testimonial-card reveal reveal-delay-1">
        <div class="tc-stars">
          <span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span>
        </div>
        <p class="tc-quote">"I was a marathon runner with zero upper body strength. Eight weeks into this program and I've put on 4kg of muscle without slowing my running pace. The programming is genuinely intelligent."</p>
        <div class="tc-author">
          <div class="tc-avatar">SK</div>
          <div>
            <div class="tc-name">Sarah K.</div>
            <div class="tc-meta">Week 8 · Runner → Hybrid Athlete</div>
          </div>
        </div>
      </div>
      <div class="testimonial-card reveal reveal-delay-2">
        <div class="tc-stars">
          <span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span>
        </div>
        <p class="tc-quote">"The daily tracker alone changed everything. Seeing my numbers every day made me obsessed with improvement. I've never been this consistent in my life — 9 weeks straight, zero missed sessions."</p>
        <div class="tc-author">
          <div class="tc-avatar">JT</div>
          <div>
            <div class="tc-name">James T.</div>
            <div class="tc-meta">Week 9 · 63-Day Streak</div>
          </div>
        </div>
      </div>
      <div class="testimonial-card reveal reveal-delay-1">
        <div class="tc-stars">
          <span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span>
        </div>
        <p class="tc-quote">"I tried every hybrid program I could find. This is the first one that actually accounts for recovery and interference. My CNS isn't fried. My lifts are going up AND my 5K time is dropping."</p>
        <div class="tc-author">
          <div class="tc-avatar">AL</div>
          <div>
            <div class="tc-name">Alex L.</div>
            <div class="tc-meta">Week 10 · Hybrid Conversion</div>
          </div>
        </div>
      </div>
      <div class="testimonial-card reveal reveal-delay-2">
        <div class="tc-stars">
          <span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span>
        </div>
        <p class="tc-quote">"The nutrition system is what I was missing. Not a diet — an athlete's fueling protocol. I'm eating more than ever and my body composition has completely transformed. Down 11lbs, visibly more muscular."</p>
        <div class="tc-author">
          <div class="tc-avatar">NP</div>
          <div>
            <div class="tc-name">Nina P.</div>
            <div class="tc-meta">Week 12 · Body Recomposition</div>
          </div>
        </div>
      </div>
      <div class="testimonial-card reveal reveal-delay-3">
        <div class="tc-stars">
          <span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span><span class="tc-star">★</span>
        </div>
        <p class="tc-quote">"Week 1 I couldn't run 2km without stopping. Week 12 I completed a 10K. I also deadlifted 140kg for the first time. This system gave me an athletic identity I never thought possible."</p>
        <div class="tc-author">
          <div class="tc-avatar">DW</div>
          <div>
            <div class="tc-name">David W.</div>
            <div class="tc-meta">Week 12 · Complete Transformation</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ================================================================
     PRICING
================================================================ -->
<section id="pricing">
  <div class="container">
    <div class="pricing-header reveal">
      <p class="label" style="margin-bottom:12px;">Invest in Your Performance</p>
      <h2 class="display-md">One price.<br>Lifetime access.</h2>
      <p class="body-md" style="margin-top:16px;max-width:440px;margin-left:auto;margin-right:auto;">No subscriptions. No monthly fees. Pay once and own the complete system — including all future updates.</p>
    </div>

    <div class="pricing-card reveal reveal-delay-1">
      <div class="pricing-card-header">
        <div class="pricing-label">Complete System</div>
        <div class="pricing-title">HYBRID ATHLETE SYSTEM</div>
        <span class="pricing-badge">One-Time Payment · Instant Access</span>
      </div>
      <div class="pricing-card-body">
        <div class="pricing-price">
          <div style="font-family:var(--mono);font-size:10px;letter-spacing:0.14em;text-transform:uppercase;color:var(--muted);margin-bottom:8px;">Investment</div>
          <div class="pricing-price-num">$97</div>
          <div class="pricing-price-note">One-time · No subscription · Lifetime access</div>
        </div>

        <ul class="pricing-includes">
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            12-Week Hybrid Training Program
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Daily Performance Tracker
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Running Progression System
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Complete Nutrition System
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Recovery Dashboard
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Body Transformation Tracker
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Habit Discipline Tracker
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Weekly Review System
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Instant Digital Download
          </li>
          <li class="pricing-include">
            <div class="pi-check">✓</div>
            Lifetime Updates Included
          </li>
        </ul>

        <a href="#" class="btn-primary pricing-cta">
          Start Your Transformation
          <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M1 7h12M8 2l5 5-5 5" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </a>
      </div>
    </div>

    <p class="pricing-guarantee reveal reveal-delay-2">
      ✦ &nbsp; 30-Day Money-Back Guarantee &nbsp; · &nbsp; Instant Digital Access &nbsp; · &nbsp; Available Worldwide &nbsp; ✦
    </p>
  </div>
</section>

<!-- ================================================================
     FAQ
================================================================ -->
<section id="faq">
  <div class="container">
    <div class="faq-layout">
      <div class="faq-sidebar reveal">
        <p class="label" style="margin-bottom:12px;">FAQ</p>
        <h3>Questions<br>answered.</h3>
        <p style="margin-top:16px;">Everything you need to know before starting your transformation. Still unsure? The system speaks for itself.</p>
      </div>

      <div class="faq-list reveal reveal-delay-1">
        <div class="faq-item open">
          <div class="faq-q">
            <h4>Is this beginner friendly?</h4>
            <div class="faq-toggle">+</div>
          </div>
          <div class="faq-a">
            <p>Yes. The Hybrid Athlete System is designed for all fitness levels. Week 1 starts conservatively and builds progressively. The program includes beginner modifications for all exercises and an onboarding guide that sets appropriate starting points for both training and running based on your current fitness level.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">
            <h4>How long is the program?</h4>
            <div class="faq-toggle">+</div>
          </div>
          <div class="faq-a">
            <p>The core system is 12 weeks (3 training phases of 4 weeks each). After completing the program, the tracking systems, nutrition framework, and habit infrastructure are yours to continue using indefinitely. Many users run the program multiple times with increased targets.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">
            <h4>Do I need gym access?</h4>
            <div class="faq-toggle">+</div>
          </div>
          <div class="faq-a">
            <p>The primary program is designed for gym access (barbells, dumbbells, pull-up bar). A home/minimal equipment alternative is included for each training session. The running program requires no equipment — just a safe place to run outdoors or a treadmill.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">
            <h4>How do I access the system?</h4>
            <div class="faq-toggle">+</div>
          </div>
          <div class="faq-a">
            <p>Immediately after purchase, you'll receive a download link via email. The system is delivered as premium digital files (PDF and spreadsheet formats) designed to work on any device. You can use it on desktop, tablet, or mobile — or print any component you prefer physical copies of.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">
            <h4>Can I do this alongside my current training?</h4>
            <div class="faq-toggle">+</div>
          </div>
          <div class="faq-a">
            <p>For best results, we recommend following the Hybrid Athlete System as your primary training protocol for the full 12 weeks. The program is already comprehensive — adding significant volume on top risks overtraining. The system is designed to be your complete performance framework, not a supplement to another program.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">
            <h4>What if it doesn't work for me?</h4>
            <div class="faq-toggle">+</div>
          </div>
          <div class="faq-a">
            <p>The system comes with a 30-day money-back guarantee. If you follow the program and are not satisfied with your progress, contact us within 30 days of purchase for a full refund. No questions asked. We're confident in the system — and want you to be too.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ================================================================
     FINAL CTA
================================================================ -->
<section id="final-cta">
  <div class="container">
    <div class="final-eyebrow reveal">
      <div class="final-eyebrow-line"></div>
      <span class="label">Your Turning Point</span>
      <div class="final-eyebrow-line"></div>
    </div>

    <h2 class="final-headline reveal reveal-delay-1">
      Stop Training<br>Randomly.
    </h2>

    <p class="body-lg" style="margin-top:0;text-align:center;" class="reveal">
      &nbsp;
    </p>

    <div style="font-family:var(--display);font-size:clamp(32px,5vw,56px);letter-spacing:0.01em;line-height:1;color:rgba(255,255,255,0.3);text-align:center;margin-bottom:40px;" class="reveal reveal-delay-2">
      Start Performing With Structure.
    </div>

    <p class="final-sub reveal reveal-delay-2">
      12 weeks. 8 modules. One complete system. Everything you need to become the athlete you've been working toward.
    </p>

    <div class="final-ctas reveal reveal-delay-3">
      <a href="#pricing" class="btn-primary" style="padding:18px 48px;font-size:13px;">
        Get Instant Access
        <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M1 7h12M8 2l5 5-5 5" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </a>
    </div>

    <p class="final-note reveal reveal-delay-4">
      ✦ &nbsp; One-Time Payment &nbsp; · &nbsp; Instant Access &nbsp; · &nbsp; 30-Day Guarantee &nbsp; ✦
    </p>
  </div>
</section>

<!-- ================================================================
     FOOTER
================================================================ -->
<footer>
  <div class="footer-logo">HYBRID ATHLETE SYSTEM</div>
  <div class="footer-note">© 2025 Hybrid Athlete System · All rights reserved</div>
  <ul class="footer-links">
    <li><a href="#">Privacy</a></li>
    <li><a href="#">Terms</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Refund Policy</a></li>
  </ul>
</footer>

<!-- ================================================================
     SCRIPTS
================================================================ -->
<script>
  // Custom cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mouseX = 0, mouseY = 0, ringX = 0, ringY = 0;

  document.addEventListener('mousemove', e => {
    mouseX = e.clientX; mouseY = e.clientY;
    cursor.style.left = mouseX + 'px';
    cursor.style.top  = mouseY + 'px';
  });

  function animateRing() {
    ringX += (mouseX - ringX) * 0.12;
    ringY += (mouseY - ringY) * 0.12;
    ring.style.left = ringX + 'px';
    ring.style.top  = ringY + 'px';
    requestAnimationFrame(animateRing);
  }
  animateRing();

  document.querySelectorAll('a, button, .pillar, .feature-card, .audience-card, .testimonial-card, .preview-tab, .faq-q, .benefit-row').forEach(el => {
    el.addEventListener('mouseenter', () => {
      cursor.style.width = '14px';
      cursor.style.height = '14px';
      ring.style.width = '50px';
      ring.style.height = '50px';
    });
    el.addEventListener('mouseleave', () => {
      cursor.style.width = '10px';
      cursor.style.height = '10px';
      ring.style.width = '36px';
      ring.style.height = '36px';
    });
  });

  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) { e.target.classList.add('visible'); }
    });
  }, { threshold: 0.12 });
  reveals.forEach(el => observer.observe(el));

  // FAQ accordion
  document.querySelectorAll('.faq-q').forEach(btn => {
    btn.addEventListener('click', () => {
      const item = btn.parentElement;
      const isOpen = item.classList.contains('open');
      document.querySelectorAll('.faq-item.open').forEach(i => i.classList.remove('open'));
      if (!isOpen) item.classList.add('open');
    });
  });

  // Preview tabs
  document.querySelectorAll('.preview-tab').forEach(tab => {
    tab.addEventListener('click', () => {
      document.querySelectorAll('.preview-tab').forEach(t => t.classList.remove('active'));
      tab.classList.add('active');
    });
  });

  // Nav scroll behavior
  window.addEventListener('scroll', () => {
    const nav = document.getElementById('nav');
    if (window.scrollY > 60) {
      nav.style.padding = '14px clamp(20px, 5vw, 60px)';
    } else {
      nav.style.padding = '20px clamp(20px, 5vw, 60px)';
    }
  });

  // Smooth scroll for nav links
  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', e => {
      const target = document.querySelector(a.getAttribute('href'));
      if (target) {
        e.preventDefault();
        target.scrollIntoView({ behavior: 'smooth' });
      }
    });
  });
</script>
</body>
</html>
