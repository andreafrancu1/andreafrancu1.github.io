---
layout: default
title: Projects
---

<style>
/* neat, consistent thumbnails */
.card-img-top, .project-thumb {
  aspect-ratio: 16 / 9;
  max-height: 180px;
  width: 100%;
  object-fit: contain;
  background: #fff;        /* hides fake “transparent” checkerboards */
  border-radius: 12px;
  padding: 8px;
}
</style>

# Projects

<p>Hand-picked work I’m proud of. More on my 
  <a href="https://github.com/andreafrancu1" target="_blank" rel="noopener">GitHub</a>.
</p>

<div class="row row-cols-1 row-cols-md-2 g-4">

  <!-- Project 1 -->
  <div class="col">
    <div class="card h-100">
      <img src="{{ '/assets/img/netflix_logo.png' | relative_url }}" 
           class="project-thumb" alt="Netflix Data Exploration thumbnail" loading="lazy">
      <div class="card-body">
        <h5 class="card-title">Netflix Data Exploration</h5>
        <p class="card-text">Cleaning + imputation + skew fixes on multi-CSV Netflix-style data. EDA, joins, and metrics.</p>
        <a href="https://github.com/andreafrancu1/netflix-explorer" 
           class="btn btn-primary" target="_blank" rel="noopener">View Repo</a>
      </div>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="col">
    <div class="card h-100">
      <img src="{{ '/assets/img/grapes_logo.png' | relative_url }}" 
           class="project-thumb" alt="Wine clustering project thumbnail" loading="lazy">
      <div class="card-body">
        <h5 class="card-title">Grape Clusters — Unsupervised Learning for Wine</h5>
        <p class="card-text">Clustering wines with classic unsupervised methods → basis for new recs.</p>
        <a href="https://github.com/andreafrancu1/grape-clusters" 
           class="btn btn-primary" target="_blank" rel="noopener">View Repo</a>
      </div>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="col">
    <div class="card h-100">
      <img src="{{ '/assets/img/car_logo.png' | relative_url }}" 
           class="project-thumb" alt="Autonomous vehicle sentiment thumbnail" loading="lazy">
      <div class="card-body">
        <h5 class="card-title">Autonomous Vehicle Sentiment Analysis</h5>
        <p class="card-text">NLP + web scraping of Reddit to analyze sentiment and topics around AVs.</p>
        <a href="https://github.com/andreafrancu1/AV-sentiment-analysis" 
           class="btn btn-primary" target="_blank" rel="noopener">View Repo</a>
      </div>
    </div>
  </div>

</div>
