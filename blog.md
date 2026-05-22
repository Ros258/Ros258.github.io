---
layout: home
title: Blog
---

<div style="max-width: 1000px; margin: 50px auto; padding: 0 30px;">
    <style>
        .blog-header {
            text-align: center;
            margin-bottom: 50px;
        }
        .blog-header h1 {
            font-size: 3rem;
            background: linear-gradient(135deg, #ff6b6b, #feca57);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 15px;
        }
        .blog-header p {
            color: rgba(255,255,255,0.6);
            font-size: 1.2rem;
        }
        .blog-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        .blog-card {
            background: rgba(255,255,255,0.05);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            overflow: hidden;
            border: 1px solid rgba(255,255,255,0.1);
            transition: all 0.3s ease;
        }
        .blog-card:hover {
            transform: translateY(-10px);
            border-color: rgba(255,107,107,0.5);
        }
        .blog-image {
            height: 200px;
            background: linear-gradient(135deg, #ff6b6b, #feca57);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
        }
        .blog-content {
            padding: 25px;
        }
        .blog-category {
            display: inline-block;
            background: rgba(255,107,107,0.2);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.85rem;
            color: #ff6b6b;
            margin-bottom: 10px;
        }
        .blog-title {
            font-size: 1.4rem;
            color: #fff;
            margin-bottom: 10px;
            transition: color 0.3s ease;
        }
        .blog-card:hover .blog-title {
            color: #ff6b6b;
        }
        .blog-excerpt {
            color: rgba(255,255,255,0.6);
            font-size: 0.95rem;
            line-height: 1.6;
            margin-bottom: 15px;
        }
        .blog-meta {
            display: flex;
            justify-content: space-between;
            color: rgba(255,255,255,0.4);
            font-size: 0.85rem;
        }
        .read-more {
            color: #feca57;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-top: 15px;
            transition: color 0.3s ease;
        }
        .read-more:hover {
            color: #ff6b6b;
        }
    </style>
    
    <div class="blog-header">
        <h1>My Blog</h1>
        <p>Thoughts, tutorials, and creative insights</p>
    </div>
    
    <div class="blog-grid">
        <div class="blog-card">
            <div class="blog-image">🎨</div>
            <div class="blog-content">
                <span class="blog-category">Design</span>
                <h3 class="blog-title">The Art of Minimalist Design</h3>
                <p class="blog-excerpt">Exploring how less can indeed be more in modern web design...</p>
                <div class="blog-meta">
                    <span>Jan 15, 2024</span>
                    <span>5 min read</span>
                </div>
                <a href="#" class="read-more">Read More →</a>
            </div>
        </div>
        
        <div class="blog-card">
            <div class="blog-image">💻</div>
            <div class="blog-content">
                <span class="blog-category">Development</span>
                <h3 class="blog-title">Getting Started with Jekyll</h3>
                <p class="blog-excerpt">A beginner's guide to building static sites with Jekyll...</p>
                <div class="blog-meta">
                    <span>Jan 10, 2024</span>
                    <span>8 min read</span>
                </div>
                <a href="#" class="read-more">Read More →</a>
            </div>
        </div>
        
        <div class="blog-card">
            <div class="blog-image">✨</div>
            <div class="blog-content">
                <span class="blog-category">Tech</span>
                <h3 class="blog-title">The Future of Web Development</h3>
                <p class="blog-excerpt">What's next in the world of web technologies...</p>
                <div class="blog-meta">
                    <span>Jan 5, 2024</span>
                    <span>6 min read</span>
                </div>
                <a href="#" class="read-more">Read More →</a>
            </div>
        </div>
        
        <div class="blog-card">
            <div class="blog-image">🎯</div>
            <div class="blog-content">
                <span class="blog-category">Productivity</span>
                <h3 class="blog-title">Mastering Your Workflow</h3>
                <p class="blog-excerpt">Tips and tricks to boost your productivity as a developer...</p>
                <div class="blog-meta">
                    <span>Dec 28, 2023</span>
                    <span>4 min read</span>
                </div>
                <a href="#" class="read-more">Read More →</a>
            </div>
        </div>
        
        <div class="blog-card">
            <div class="blog-image">🎵</div>
            <div class="blog-content">
                <span class="blog-category">Creative</span>
                <h3 class="blog-title">Music and Creativity</h3>
                <p class="blog-excerpt">How music influences the creative process...</p>
                <div class="blog-meta">
                    <span>Dec 20, 2023</span>
                    <span>5 min read</span>
                </div>
                <a href="#" class="read-more">Read More →</a>
            </div>
        </div>
        
        <div class="blog-card">
            <div class="blog-image">🚀</div>
            <div class="blog-content">
                <span class="blog-category">Career</span>
                <h3 class="blog-title">Building a Portfolio</h3>
                <p class="blog-excerpt">Tips for creating an impressive developer portfolio...</p>
                <div class="blog-meta">
                    <span>Dec 15, 2023</span>
                    <span>7 min read</span>
                </div>
                <a href="#" class="read-more">Read More →</a>
            </div>
        </div>
    </div>
</div>
