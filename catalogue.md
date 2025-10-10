---
title: catalogue
layout: default
---

# catalogue

<p>This page cites a curated collection of vital biodiversity example projects and useful datasets. A short description highlights how it meets the requirements of the design brief. Click on a project to learn more about the creators' work.</p>

<!-- GRID ONLY CONTAINS CARDS -->
<div class="catalogue-grid">

  <!-- Project Card 1 -->
  <div class="catalogue-card" onclick="openModal(1)">
    <div class="catalogue-content">
      <h3>Project 1 Title</h3>
      <p>This is a short description of Project 1. Replace with your actual text.</p>
    </div>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project1-1.jpg" alt="Project 1 image 1">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project1-2.jpg" alt="Project 1 image 2">
      </div>
    </div>
  </div>

  <!-- Project Card 2 -->
  <div class="catalogue-card" onclick="openModal(2)">
    <div class="catalogue-content">
      <h3>Project 2 Title</h3>
      <p>This is a short description of Project 2. Replace with your actual text.</p>
    </div>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project2-1.jpg" alt="Project 2 image 1">
      </div>
    </div>
  </div>

  <!-- Project Card 3 -->
  <div class="catalogue-card" onclick="openModal(3)">
    <div class="catalogue-content">
      <h3>Project 3 Title</h3>
      <p>This is a short description of Project 3. Replace with your actual text.</p>
    </div>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project3-1.jpg" alt="Project 3 image 1">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project3-2.jpg" alt="Project 3 image 2">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project3-3.jpg" alt="Project 3 image 3">
      </div>
    </div>
  </div>

  <!-- Project Card 4 -->
  <div class="catalogue-card" onclick="openModal(4)">
    <div class="catalogue-content">
      <h3>Project 4 Title</h3>
      <p>This is a short description of Project 4. Replace with your actual text.</p>
    </div>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project4-1.jpg" alt="Project 4 image 1">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project4-2.jpg" alt="Project 4 image 2">
      </div>
    </div>
  </div>

</div> <!-- END OF GRID -->


<!-- MODALS GO BELOW GRID (outside) -->

<div id="modal-1" class="catalogue-modal">
  <div class="catalogue-modal-content">
    <span class="catalogue-modal-close" onclick="closeModal(1)">&times;</span>
    <h2>Project 1 Title</h2>
    <p>This is a longer description for Project 1. You can add more details here.</p>
    <a href="https://example.com" class="catalogue-link" target="_blank">Visit Project</a>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project1-1.jpg" alt="">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project1-2.jpg" alt="">
      </div>
    </div>
  </div>
</div>

<div id="modal-2" class="catalogue-modal">
  <div class="catalogue-modal-content">
    <span class="catalogue-modal-close" onclick="closeModal(2)">&times;</span>
    <h2>Project 2 Title</h2>
    <p>This is a longer description for Project 2. You can add more details here.</p>
    <a href="https://example.com" class="catalogue-link" target="_blank">Visit Project</a>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project2-1.jpg" alt="">
      </div>
    </div>
  </div>
</div>

<div id="modal-3" class="catalogue-modal">
  <div class="catalogue-modal-content">
    <span class="catalogue-modal-close" onclick="closeModal(3)">&times;</span>
    <h2>Project 3 Title</h2>
    <p>This is a longer description for Project 3. You can add more details here.</p>
    <a href="https://example.com" class="catalogue-link" target="_blank">Visit Project</a>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project3-1.jpg" alt="">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project3-2.jpg" alt="">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project3-3.jpg" alt="">
      </div>
    </div>
  </div>
</div>

<div id="modal-4" class="catalogue-modal">
  <div class="catalogue-modal-content">
    <span class="catalogue-modal-close" onclick="closeModal(4)">&times;</span>
    <h2>Project 4 Title</h2>
    <p>This is a longer description for Project 4. You can add more details here.</p>
    <a href="https://example.com" class="catalogue-link" target="_blank">Visit Project</a>
    <div class="catalogue-images">
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project4-1.jpg" alt="">
      </div>
      <div class="catalogue-image-wrapper">
        <img src="/assets/catalogue/project4-2.jpg" alt="">
      </div>
    </div>
  </div>
</div>
