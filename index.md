---
layout: default
title: Welcome to My Portfolio
---

<img src="{{ site.baseurl }}/assets/images/profile.jpeg" alt="Anime-inspired female with glasses smiling" width="150" style="border-radius: 50%;">

# Hello, I'm Isabella 👋

Welcome to my virtual consumer electronics documentation portfolio! 

Click on the folders below to explore my work.

<!-- INTERACTIVE FOLDER HTML DIRECTLY BELOW THIS LINE -->

<!-- Interactive Folder Dropdown Container -->
<div class="desktop-folder-wrapper" style="margin-top: 25px;">
  
  <!-- The Folder Button Trigger -->
  <button class="folder-btn" onclick="toggleFolder('projects-content', this)" aria-expanded="false" aria-controls="projects-content">
    <!-- Dynamic Folder Icon Frame -->
    <span class="folder-icon-frame">
      <!-- Closed Folder SVG (Visible by default) -->
      <svg class="folder-closed" aria-hidden="true" focusable="false" xmlns="http://w3.org" width="22" height="22" viewBox="0 0 24 24" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 20a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2h-7.9a2 2 0 0 1-1.69-.9L9.6 3.9A2 2 0 0 0 7.93 3H4a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2Z"/></svg> 
      <!-- Open Folder SVG (Revealed on hover via CSS) -->
      <svg class="folder-open" aria-hidden="true" focusable="false" xmlns="http://w3.org" width="22" height="22" viewBox="0 0 24 24" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 14 1.45-2.9A2 2 0 0 1 9.24 10H20a2 2 0 0 1 1.94 2.5l-1.55 6a2 2 0 0 1-1.94 1.5H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h3.9a2 2 0 0 1 1.69.9l.81 1.2A2 2 0 0 0 12.1 6H20a2 2 0 0 1 2 2v2"/></svg>
    </span>
    <span class="folder-text">My Projects</span>
  </button>

  <!-- Hidden Sub-Files (Reveals downward when clicked) -->
  <div id="projects-content" class="folder-sub-files" style="display: none;">
    <a href="#" class="file-link">
      <!-- File SVG Icon -->
      <svg class="file-icon" aria-hidden="true" focusable="false" xmlns="http://w3.org" width="18" height="18" viewBox="0 0 24 24" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z"/><path d="M14 2v4a2 2 0 0 0 2 2h4"/></svg>
      project_one.html
    </a>
    <a href="#" class="file-link">
      <svg class="file-icon" aria-hidden="true" focusable="false" xmlns="http://w3.org" width="18" height="18" viewBox="0 0 24 24" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z"/><path d="M14 2v4a2 2 0 0 0 2 2h4"/></svg>
      project_two.html
    </a>
  </div>

</div>

