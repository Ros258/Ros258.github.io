---
layout: home
---

<div class="hero">
    <h1>Welcome to My World</h1>
    <p>Exploring the intersection of art, technology, and creativity. Join me on this journey of discovery.</p>
    <button class="btn" onclick="scrollToFeatures()">Discover More</button>
</div>

<div id="features" class="features">
    <div class="card">
        <div class="card-icon">🎨</div>
        <h3>Creative Design</h3>
        <p>Beautiful, modern designs that capture attention and inspire emotion. Every pixel tells a story.</p>
    </div>
    <div class="card">
        <div class="card-icon">💻</div>
        <h3>Web Development</h3>
        <p>Clean, efficient code that powers seamless digital experiences across all devices.</p>
    </div>
    <div class="card">
        <div class="card-icon">✨</div>
        <h3>Innovation</h3>
        <p>Pushing boundaries and exploring new possibilities in the digital landscape.</p>
    </div>
</div>

<script>
    function scrollToFeatures() {
        document.getElementById('features').scrollIntoView({ behavior: 'smooth' });
    }
</script>
