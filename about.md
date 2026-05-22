---
layout: home
title: About Me
---

<div style="max-width: 800px; margin: 50px auto; padding: 0 30px;">
    <style>
        .about-container {
            display: flex;
            flex-direction: column;
            gap: 40px;
        }
        .about-header {
            text-align: center;
            padding: 40px 0;
        }
        .about-header h1 {
            font-size: 3rem;
            background: linear-gradient(135deg, #ff6b6b, #feca57);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 20px;
        }
        .about-section {
            background: rgba(255,255,255,0.05);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            border: 1px solid rgba(255,255,255,0.1);
        }
        .about-section h2 {
            color: #ff6b6b;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }
        .about-section p {
            color: rgba(255,255,255,0.7);
            line-height: 1.8;
            font-size: 1.1rem;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .skill-tag {
            background: linear-gradient(135deg, rgba(255,107,107,0.2), rgba(254,202,87,0.2));
            padding: 15px 25px;
            border-radius: 30px;
            text-align: center;
            border: 1px solid rgba(255,107,107,0.3);
            transition: all 0.3s ease;
        }
        .skill-tag:hover {
            transform: scale(1.05);
            border-color: rgba(255,107,107,0.6);
        }
        .stats-row {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 20px;
        }
        .stat-card {
            text-align: center;
            padding: 25px;
            background: rgba(255,255,255,0.03);
            border-radius: 15px;
        }
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            background: linear-gradient(135deg, #ff6b6b, #feca57);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .stat-label {
            color: rgba(255,255,255,0.6);
            margin-top: 5px;
        }
    </style>
    
    <div class="about-container">
        <div class="about-header">
            <h1>About Ros258</h1>
            <p style="color: rgba(255,255,255,0.6); font-size: 1.2rem;">Digital Creator | Developer | Artist</p>
        </div>
        
        <div class="about-section">
            <h2>🎯 Who Am I?</h2>
            <p>I'm a passionate digital creator with a love for blending art and technology. With years of experience in web development and design, I create experiences that inspire, engage, and delight users across the digital landscape.</p>
        </div>
        
        <div class="about-section">
            <h2>💡 My Philosophy</h2>
            <p>Great design is not just about aesthetics—it's about creating meaningful connections. I believe in the power of simplicity, the beauty of minimalism, and the impact of thoughtful interactions.</p>
        </div>
        
        <div class="about-section">
            <h2>🛠️ Skills & Expertise</h2>
            <div class="skills-grid">
                <div class="skill-tag">HTML5</div>
                <div class="skill-tag">CSS3</div>
                <div class="skill-tag">JavaScript</div>
                <div class="skill-tag">React</div>
                <div class="skill-tag">Node.js</div>
                <div class="skill-tag">UI/UX Design</div>
                <div class="skill-tag">Jekyll</div>
                <div class="skill-tag">Git</div>
            </div>
        </div>
        
        <div class="about-section">
            <h2>📊 Highlights</h2>
            <div class="stats-row">
                <div class="stat-card">
                    <div class="stat-number">50+</div>
                    <div class="stat-label">Projects</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">3+</div>
                    <div class="stat-label">Years Experience</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">100%</div>
                    <div class="stat-label">Passion</div>
                </div>
            </div>
        </div>
    </div>
</div>
