---
layout: home
title: "Adam Oentoro | AI Researcher & ML Engineer"
description: "Professional portfolio of Adam Oentoro - AI Researcher and Machine Learning Engineer with expertise in reinforcement learning and GPU computing"
keywords: "Adam Oentoro, AI, Machine Learning, Portfolio, Research"
---

<!-- Hero Section -->
<section id="home" class="hero">
    <div class="hero-content">
        <div class="hero-text">
            <h1 class="hero-title">{{ site.title }}</h1>
            <p class="hero-subtitle">{{ site.description }}</p>
            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">View My Work</a>
                <a href="{{ '/blog' | relative_url }}" class="btn btn-outline">Read My Blog</a>
            </div>
        </div>
        <div class="hero-image">
            <div class="hero-avatar">
                <img src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="{{ site.author.name }}" onerror="this.style.display='none'">
            </div>
        </div>
    </div>
</section>

<!-- About Section -->
<section id="about" class="about-section">
    <div class="container">
        <h2 class="section-title">About Me</h2>
        <div class="about-content">
            <div class="about-text">
                <p>Recent MSc AI graduate from Vrije Universiteit Amsterdam with a passion for advancing the frontiers of artificial intelligence. My expertise spans reinforcement learning, knowledge-augmented systems, and GPU computing.</p>
                
                <p>With an international educational background and experience as a Teaching Assistant, I bring both technical depth and clear communication skills to complex AI challenges.</p>
                
                <div class="skills-grid">
                    <div class="skill-category">
                        <h3>Machine Learning</h3>
                        <ul>
                            <li>Reinforcement Learning</li>
                            <li>Deep Learning</li>
                            <li>Knowledge-Augmented AI</li>
                        </ul>
                    </div>
                    <div class="skill-category">
                        <h3>Technical Skills</h3>
                        <ul>
                            <li>Python, PyTorch, TensorFlow</li>
                            <li>CUDA Programming</li>
                            <li>GPU Computing</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Projects Section -->
<section id="projects" class="projects-section">
    <div class="container">
        <h2 class="section-title">Featured Projects</h2>
        <div class="projects-grid">
            <!-- Add your projects here -->
            <div class="project-card">
                <h3>Multi-Ontology LLM Augmentation</h3>
                <p>MSc thesis project exploring knowledge-augmented language models with multiple ontology integration.</p>
                <div class="project-tags">
                    <span class="tag">PyTorch</span>
                    <span class="tag">NLP</span>
                    <span class="tag">Research</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="contact-section">
    <div class="container">
        <h2 class="section-title">Let's Connect</h2>
        <p class="contact-description">Interested in AI research collaboration or have a project in mind? I'd love to hear from you.</p>
        <div class="contact-links">
            <a href="mailto:{{ site.email }}" class="contact-link">
                <span>Email</span>
            </a>
            {% if site.linkedin_username %}
            <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}" class="contact-link">
                <span>LinkedIn</span>
            </a>
            {% endif %}
            {% if site.github_username %}
            <a href="https://github.com/{{ site.github_username }}" class="contact-link">
                <span>GitHub</span>
            </a>
            {% endif %}
        </div>
    </div>
</section>