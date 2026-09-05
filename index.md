---
layout: default
title: Welcome to My Portfolio
---

<!-- MAIN INTRO CONTAINER (Disappears when folder opens) -->
<div id="home-intro">
  <img src="{{ site.baseurl }}/assets/images/profile.jpeg" alt="Anime-inspired female with glasses smiling" style="width: 100%; max-width: 220px; height: auto; border-radius: 50%; display: block; margin-bottom: 20px;">

  <h1>Hello, I'm Name 👋</h1>

  <p>Welcome to my virtual Consumer Electronics Documentation Portfolio!</p>

  <p>Click on the folder below to explore my work.</p>
</div>

<!-- NEW IMAGE CONTAINER (Hidden by default, displays when folder opens) -->
<div id="folder-opened-view" style="display: none; text-align: center; margin-top: 10px;">
  <img src="{{ site.baseurl }}/assets/images/writing.jpeg" alt="Female with eyeglasses typing on computer" style="max-width: 100%; border-radius: 8px;">
</div>

<!-- INTERACTIVE FOLDER HTML -->
<div class="desktop-folder-wrapper" style="margin-top: 25px;">
  
  <button class="folder-btn" onclick="toggleFolder('projects-content', this)" aria-expanded="false" aria-controls="projects-content">
    <span class="folder-icon-frame" style="display: inline-flex; align-items: center; font-size: 18px;">
      <!-- Closed Folder (Visible by default) -->
      <svg class="folder-closed" aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/>
      </svg>
      <!-- Open Folder -->
      <svg class="folder-open" aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="m6 14 1.5-2.9A2 2 0 0 1 9.3 10H20a2 2 0 0 1 1.8 2.8l-2 5a2 2 0 0 1-1.8 1.2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h3.9a2 2 0 0 1 1.7.9l1.4 2.2H20a2 2 0 0 1 2 2v2"/>
      </svg>
    </span>   
    <span class="folder-text">My Projects</span>
  </button>

  <!-- Hidden Sub-Files -->
  <div id="projects-content" class="folder-sub-files" style="display: none;">
    <!-- Link to Project One -->
    <a href="{{ '/projects/project_one.html' | relative_url }}" class="file-link">
      <svg aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/>
        <polyline points="14 2 14 8 20 8"/>
        <line x1="16" y1="13" x2="8" y2="13"/>
        <line x1="16" y1="17" x2="8" y2="17"/>
        <line x1="10" y1="9" x2="8" y2="9"/>
      </svg>
      project_one.html
    </a>
    <!-- Link to Project Two -->
    <a href="#" class="file-link">
      <svg aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/>
        <polyline points="14 2 14 8 20 8"/>
        <line x1="16" y1="13" x2="8" y2="13"/>
        <line x1="16" y1="17" x2="8" y2="17"/>
        <line x1="10" y1="9" x2="8" y2="9"/>
      </svg>
      project_two.html
    </a>
  </div>

</div>
