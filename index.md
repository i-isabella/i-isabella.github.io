---
layout: default
title: Welcome to My Portfolio
---

<!-- MAIN INTRO CONTAINER (Disappears when folder opens) -->
<div id="home-intro">
  <img src="{{ site.baseurl }}/assets/images/profile.jpeg" alt="Anime-inspired female with glasses smiling" style="width: 100%; max-width: 220px; height: auto; border-radius: 50%; display: block; margin-bottom: 20px;">

  <h1>Hello, I'm Isabella 👋</h1>

  <p>Welcome to my virtual Consumer Electronics Documentation Portfolio!</p>

  <p>Click on the folder below to explore my work.</p>
</div>

<!-- NEW IMAGE CONTAINER (Hidden by default, displays when folder opens) -->
<div id="folder-opened-view" style="display: none; text-align: center; margin-top: 10px;">
  <img src="{{ site.baseurl }}/assets/images/writing.jpeg" alt="Female with eyeglasses typing on computer" style="max-width: 100%; border-radius: 8px;">
</div>

<!-- INTERACTIVE FOLDER HTML -->
<div class="desktop-folder-wrapper" style="margin-top: 25px;">
  
  <button class="folder-btn" onclick="toggleFolder('projects-content', this)" aria-expanded="false" aria-controls="projects-content" style="cursor: pointer; display: inline-flex; align-items: center; gap: 8px; padding: 8px 12px; border-radius: 6px; border: 1px solid #444; background: #222; color: #fff;">
    <span class="folder-icon-frame" style="display: inline-flex; align-items: center; font-size: 18px;">
      <!-- Closed Folder (Visible by default) -->
      <i class="fa-solid fa-folder-closed folder-closed" style="display: inline-block;"></i>
      <!-- Open Folder (Hidden by default, swapped via JS) -->
      <i class="fa-solid fa-folder-open folder-open" style="display: none;"></i>
    </span>   
    <span class="folder-text">My Projects</span>
  </button>

  <!-- Hidden Sub-Files -->
  <div id="projects-content" class="folder-sub-files" style="display: none; flex-direction: column; gap: 8px; margin-top: 15px;">
    <a href="#" class="file-link" style="display: inline-flex; align-items: center; gap: 6px;">
      <i class="fa-regular fa-file-lines file-icon"></i>
      project_one.html
    </a>
    <a href="#" class="file-link" style="display: inline-flex; align-items: center; gap: 6px;">
      <i class="fa-regular fa-file-lines file-icon"></i>
      project_two.html
    </a>
  </div>

</div>
