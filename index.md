---
layout: default
title: Welcome to My Portfolio
---

<!-- MAIN INTRO CONTAINER (Disappears when folder opens) -->
<div id="home-intro">
  <img src="{{ site.baseurl }}/assets/images/profile.jpeg" alt="Anime-inspired female with glasses smiling" width="150" style="border-radius: 50%;">

  # Hello, I'm Isabella 👋

  Welcome to my virtual Consumer Electronics Documentation Portfolio! 

  Click on the folder below to explore my work.
</div>

<!-- NEW IMAGE CONTAINER (Hidden by default, displays when folder opens) -->
<div id="folder-opened-view" style="display: none; text-align: center; margin-top: 10px;">
  <img src="{{ site.baseurl }}/assets/images/writing.jpeg" alt="Female with eyeglasses typing on computer" style="max-width: 100%; border-radius: 8px;">
</div>

<!-- INTERACTIVE FOLDER HTML -->
<div class="desktop-folder-wrapper" style="margin-top: 25px;">
  
  <!-- Pass 'projects-content' and 'this' to the updated function -->
  <button class="folder-btn" onclick="toggleFolder('projects-content', this)" aria-expanded="false" aria-controls="projects-content" style="cursor: pointer; display: inline-flex; align-items: center; gap: 8px; padding: 8px 12px;">
    <span class="folder-icon-frame" style="display: inline-flex; align-items: center;">
      <!-- Closed Folder SVG (Visible by default) -->
      <svg class="folder-closed" aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 20a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2h-7.9a2 2 0 0 1-1.69-.9L9.6 3.9A2 2 0 0 0 7.93 3H4a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2Z"/></svg> 
      <!-- Open Folder SVG (Hidden by default, swapped via JS) -->
      <svg class="folder-open" aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="display: none;"><path d="m6 14 1.45-2.9A2 2 0 0 1 9.24 10H20a2 2 0 0 1 1.94 2.5l-1.55 6a2 2 0 0 1-1.94 1.5H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h3.9a2 2 0 0 1 1.69.9l.81 1.2A2 2 0 0 0 12.1 6H20a2 2 0 0 1 2 2v2"/></svg>
    </span>
    <span class="folder-text">My Projects</span>
  </button>

  <!-- Hidden Sub-Files -->
  <div id="projects-content" class="folder-sub-files" style="display: none; flex-direction: column; gap: 8px; margin-top: 15px;">
    <a href="#" class="file-link" style="display: inline-flex; align-items: center; gap: 6px;">
      <svg class="file-icon" aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z"/><path d="M14 2v4a2 2 0 0 0 2 2h4"/></svg>
      project_one.html
    </a>
    <a href="#" class="file-link" style="display: inline-flex; align-items: center; gap: 6px;">
      <svg class="file-icon" aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z"/><path d="M14 2v4a2 2 0 0 0 2 2h4"/></svg>
      project_two.html
    </a>
  </div>

</div>
