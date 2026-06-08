---
title: Home
description: 
published: true
date: 2026-06-08T05:08:57.960Z
tags: 
editor: markdown
dateCreated: 2026-05-18T10:47:40.657Z
---

<style>
.landing-wrapper {
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px 10px;
  font-family: 'Inter', sans-serif;
}
.ascii-glow {
  color: #ff00ff;
  text-shadow: 0 0 8px rgba(255, 0, 255, 0.6), 0 0 15px rgba(255, 0, 255, 0.3);
  font-family: monospace;
  font-size: 9px;
  line-height: 1.15;
  background: transparent;
  border: none;
  padding: 0;
  margin: 40px 0;
  text-align: center;
  overflow-x: auto;
  white-space: pre;
  display: block;
}
.hero-text {
  text-align: center;
  font-size: 1.35em;
  color: #00ffff;
  margin-bottom: 45px;
  text-shadow: 0 0 8px rgba(0, 255, 255, 0.3);
}
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 25px;
  margin-top: 20px;
}
.wiki-card {
  background: radial-gradient(circle at top left, rgba(43, 16, 85, 0.35), rgba(15, 8, 29, 0.55));
  border: 1px solid rgba(255, 0, 255, 0.15);
  border-radius: 12px;
  padding: 30px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.4);
  transition: all 0.3s ease;
  text-decoration: none !important;
  color: inherit !important;
  display: flex;
  flex-direction: column;
}
.wiki-card:hover {
  transform: translateY(-5px);
  border-color: #ff00ff;
  box-shadow: 0 8px 30px rgba(255, 0, 255, 0.25);
}
.card-icon {
  font-size: 36px;
  margin-bottom: 15px;
}
.card-title {
  color: #00ffff;
  font-size: 1.45em;
  margin: 0 0 10px 0;
  font-weight: bold;
}
.card-desc {
  font-size: 0.95em;
  line-height: 1.5;
  color: #b0b0b0;
  margin: 0;
}
</style>

<div class="landing-wrapper">
  
  <pre class="ascii-glow">
         _  _         _       _     _     _____ _ _             
   /\   | || |  /\   (_)     | |   | |   / ____(_) |            
  /  \  | || | /  \   _  __ _| |__ | |_ | |     _| |_ _   _     
 / /\ \ | || |/ /\ \ | |/ _` | '_ \| __|| |    | | __| | | |    
/ ____ \| || / ____ \| | (_| | | | | |_ | |____| | |_| |_| |    
/_/    \_\_||_/_/    \_\_|\__, |_| |_|\__| \_____|_|\__|\__, |    
                           __/ |                         __/ |  
                          |___/                         |___/   
  </pre>

  <p class="hero-text">
    Welcome to the central knowledge vault for allnight.city. Choose a node below to begin.
  </p>

  <div class="grid-container">
    <a href="/en/games" class="wiki-card">
      <div class="card-icon">🎮</div>
      <h2 class="card-title">Games & Guides</h2>
      <p class="card-desc">Comprehensive setups, high-definition textures, custom waypoints, addons, and connectivity guides for game servers.</p>
    </a>

    <a href="/en/blog" class="wiki-card">
      <div class="card-icon">📺</div>
      <h2 class="card-title">Streams & Blog</h2>
      <p class="card-desc">Keep track of the live streaming schedules, update logs, gameplay notes, and personal thoughts.</p>
    </a>

    <a href="/en/contact" class="wiki-card">
      <div class="card-icon">✉️</div>
      <h2 class="card-title">Contact</h2>
      <p class="card-desc">Connect with the community on Discord, visit streaming channels, or reach out for inquiries.</p>
    </a>
  </div>

</div>