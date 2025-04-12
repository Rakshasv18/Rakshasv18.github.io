---
layout: default
title: "Raksha Varahamurthy"
permalink: /
---

<style>
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.card {
  background-color: #f9fafb;
  border: 1px solid #e5e7eb;
  border-radius: 1rem;
  padding: 1.5rem;
  text-align: center;
  box-shadow: 0 6px 12px rgba(0,0,0,0.05);
  transition: transform 0.2s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.card a {
  text-decoration: none;
  color: #0a2540;
  font-weight: 600;
  font-size: 1.1rem;
}
</style>

<div style="text-align:center">
  <h1>Hi, I'm Raksha 👋</h1>
  <p style="max-width:700px;margin:0 auto;">
    Welcome to my portfolio — built at the intersection of speech, vision, and machine learning.  
    Explore my work in research, real-world applications, and open-source.
  </p>
</div>

<div class="card-grid">
  <div class="card">
    <a href="/about/">👤 About Me</a>
    <p>Background, education, and my journey into AI</p>
  </div>
  <div class="card">
    <a href="/projects/">🧪 Research & Projects</a>
    <p>Speech synthesis, unlearning LLMs, real-world deployments</p>
  </div>
  <div class="card">
    <a href="/blog/">📝 Blog</a>
    <p>Thoughts on deep learning, generative models, and life</p>
  </div>
</div>
