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
            <h1 class="hero-title">
                <span class="greeting">Hello, I'm</span>
                <span class="name">Adam Oentoro</span>
            </h1>
            <p class="hero-subtitle">{{ site.description }}</p>
            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">View My Work</a>
                <a href="{{ '/blog' | relative_url }}" class="btn btn-outline">Read My Blog</a>
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
            <div class="project-card">
                <h3>Multi-Ontology Augmentation for LLM-Based Cooking Instruction</h3>
                <p>MSc thesis project developing a multi-agent system integrating FoodOn ontology and USDA nutritional databases to improve reliability and educational effectiveness of LLM-based cooking instruction.</p>
                <div class="project-tags">
                    <span class="tag">PyTorch</span>
                    <span class="tag">NLP</span>
                    <span class="tag">Multi-Agent Systems</span>
                    <span class="tag">Research</span>
                </div>
            </div>
            
            <div class="project-card">
                <h3>Reinforcement Learning for Simulation and Hardware Robotics</h3>
                <p>Designed and implemented advanced reinforcement learning algorithms (DQL, PPO, DDPG) in CoppeliaSim, enabling autonomous robot navigation and object interaction in enclosed environments.</p>
                <div class="project-tags">
                    <span class="tag">Python</span>
                    <span class="tag">Reinforcement Learning</span>
                    <span class="tag">CoppeliaSim</span>
                    <span class="tag">Robotics</span>
                </div>
            </div>
            
            <div class="project-card">
                <h3>Reinforcement Learning for Self-Adaptive Systems</h3>
                <p>Bachelor's thesis enhancing adaptive decision-making in Self-Adaptive Systems using DingNet and MockSAS Python library, contributing to SAS research opportunities.</p>
                <div class="project-tags">
                    <span class="tag">Python</span>
                    <span class="tag">Reinforcement Learning</span>
                    <span class="tag">Self-Adaptive Systems</span>
                    <span class="tag">Research</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Experience Section -->
<section id="experience" class="experience-section">
    <div class="container">
        <h2 class="section-title">Experience</h2>
        <div class="experience-content">
            <div class="experience-item">
                <div class="experience-header">
                    <h3>Teaching Assistant</h3>
                    <span class="experience-date">June 2022 - June 2025</span>
                </div>
                <div class="experience-company">Vrije Universiteit Amsterdam</div>
                <div class="courses-grid">
                    <div class="course-item">
                        <h4>Information Management (for CS and AI)</h4>
                        <p>Hosted homework and project seminars, provided one-on-one tutoring, and graded assignments. Assisted students in understanding database state transition diagrams and Petri Nets.</p>
                    </div>
                    <div class="course-item">
                        <h4>Machine Learning</h4>
                        <p>Led practical sessions on implementing machine learning algorithms, offered guidance on project development, and provided feedback on students' code. Helped clarify complex concepts such as Deep Reinforcement Learning.</p>
                    </div>
                    <div class="course-item">
                        <h4>Digitalization and Sustainability</h4>
                        <p>Facilitated discussions on the intersection of technology and sustainability, guided students through case studies, and assisted in the development of sustainable IT solutions.</p>
                    </div>
                    <div class="course-item">
                        <h4>Learning Machines</h4>
                        <p>Provided technical assistance and guidance in this robotics course, focusing on deep reinforcement learning concepts and implementation techniques. Supported students in applying theoretical knowledge to practical robotics projects.</p>
                    </div>
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