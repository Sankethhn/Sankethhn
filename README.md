## Hi there 👋

<!--
**Sankethhn/Sankethhn** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanketh H N | AI & Python Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        :root {
            --primary: #6C63FF;
            --secondary: #4D44DB;
            --dark: #2F2E41;
            --light: #F8F9FA;
            --accent: #FF6584;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.7;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            text-align: center;
            padding: 4rem 0 6rem;
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path fill="rgba(255,255,255,0.05)" d="M0,0 L100,0 L100,100 L0,100 Z" /></svg>');
            background-size: cover;
        }
        
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 0 2rem;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            font-weight: 700;
            position: relative;
            display: inline-block;
        }
        
        h1::after {
            content: "";
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 50px;
            height: 4px;
            background: var(--accent);
            border-radius: 2px;
        }
        
        h2 {
            font-size: 2.2rem;
            margin-bottom: 2rem;
            color: var(--dark);
            position: relative;
            display: inline-block;
        }
        
        h2::after {
            content: "";
            position: absolute;
            bottom: -8px;
            left: 0;
            width: 40px;
            height: 3px;
            background: var(--primary);
            border-radius: 2px;
        }
        
        h3 {
            font-size: 1.4rem;
            margin-bottom: 1rem;
            color: var(--secondary);
        }
        
        .lead {
            font-size: 1.3rem;
            max-width: 700px;
            margin: 0 auto 2rem;
            opacity: 0.9;
        }
        
        .section {
            padding: 5rem 0;
        }
        
        .section-light {
            background-color: white;
        }
        
        .about-content {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 3rem;
        }
        
        .about-text {
            flex: 1;
            min-width: 300px;
        }
        
        .profile-img {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        
        .profile-img img {
            width: 100%;
            max-width: 350px;
            border-radius: 20px;
            box-shadow: 0 20px 30px rgba(108, 99, 255, 0.2);
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .skill-category {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .skill-category:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
        }
        
        .skill-item {
            margin-bottom: 1rem;
        }
        
        .skill-name {
            display: flex;
            justify-content: space-between;
            margin-bottom: 0.5rem;
        }
        
        .skill-bar {
            height: 8px;
            background: #e9ecef;
            border-radius: 4px;
            overflow: hidden;
        }
        
        .skill-progress {
            height: 100%;
            background: linear-gradient(90deg, var(--primary), var(--accent));
            border-radius: 4px;
        }
        
        .contact-card {
            background: white;
            padding: 3rem;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(108, 99, 255, 0.1);
            max-width: 600px;
            margin: 0 auto;
            text-align: center;
        }
        
        .contact-info {
            margin-bottom: 2rem;
        }
        
        .contact-info p {
            margin-bottom: 1rem;
            font-size: 1.1rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 2rem;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            border-radius: 50%;
            font-size: 1.5rem;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .social-links a:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(108, 99, 255, 0.3);
        }
        
        .fun-fact {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 2rem;
            border-radius: 15px;
            margin-top: 3rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .fun-fact::before {
            content: "";
            position: absolute;
            top: -20px;
            right: -20px;
            width: 100px;
            height: 100px;
            background: rgba(255,255,255,0.1);
            border-radius: 50%;
        }
        
        .fun-fact i {
            font-size: 2rem;
            margin-bottom: 1rem;
            color: var(--accent);
        }
        
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            h2 {
                font-size: 2rem;
            }
            
            .about-content {
                flex-direction: column;
            }
            
            .profile-img {
                order: -1;
            }
            
            .section {
                padding: 3rem 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Sanketh H N</h1>
            <p class="lead">Passionate AI & Python Developer crafting intelligent solutions</p>
        </div>
    </header>

    <!-- About Section -->
    <section class="section section-light">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>Hello! I'm Sanketh, a passionate developer with a strong interest in artificial intelligence and machine learning. I specialize in Python development and enjoy creating innovative solutions to complex problems.</p>
                    <p>With a curious mind and a love for technology, I'm constantly exploring new frameworks and methodologies to enhance my skills and contribute to meaningful projects.</p>
                    
                    <div class="fun-fact">
                        <i class="fas fa-lightbulb"></i>
                        <p>Fun fact: I think I'm funny! (And I promise my code is better than my jokes)</p>
                    </div>
                </div>
                <div class="profile-img">
                    <!-- Replace with your actual image -->
                    <img src="https://via.placeholder.com/350x450/6C63FF/FFFFFF?text=Sanketh+H+N" alt="Sanketh H N">
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="section">
        <div class="container">
            <h2>My Skills</h2>
            <p>Here are the technologies and tools I work with:</p>
            
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Programming</h3>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Python</span>
                            <span>90%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Java</span>
                            <span>75%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 75%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>C</span>
                            <span>80%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%"></div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>AI & ML</h3>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Machine Learning</span>
                            <span>85%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Computer Vision</span>
                            <span>80%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Deep Learning</span>
                            <span>70%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 70%"></div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Development</h3>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Flutter</span>
                            <span>65%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 65%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Frontend</span>
                            <span>75%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 75%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Git</span>
                            <span>80%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Current Focus Section -->
    <section class="section section-light">
        <div class="container">
            <h2>Current Focus</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <i class="fas fa-code" style="font-size: 2rem; color: var(--primary); margin-bottom: 1rem;"></i>
                    <h3>Working On</h3>
                    <p>Developing Python applications and exploring AI solutions to real-world problems.</p>
                </div>
                <div class="skill-category">
                    <i class="fas fa-graduation-cap" style="font-size: 2rem; color: var(--primary); margin-bottom: 1rem;"></i>
                    <h3>Learning</h3>
                    <p>Flutter for cross-platform development, advanced Python concepts, and Java programming.</p>
                </div>
                <div class="skill-category">
                    <i class="fas fa-users" style="font-size: 2rem; color: var(--primary); margin-bottom: 1rem;"></i>
                    <h3>Collaboration</h3>
                    <p>Looking to collaborate on Computer Vision projects and open-source initiatives.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section">
        <div class="container">
            <h2>Let's Connect</h2>
            <p>I'm always open to discussing new opportunities, collaborations, or just chatting about technology!</p>
            
            <div class="contact-card">
                <div class="contact-info">
                    <p><i class="fas fa-envelope"></i> sankethsanketh96396@gmail.com</p>
                    <p><i class="fas fa-map-marker-alt"></i> Based in India</p>
                </div>
                
                <div class="social-links">
                    <a href="https://instagram.com/_sanketh_shaiva_" target="_blank"><i class="fab fa-instagram"></i></a>
                    <a href="https://github.com/sankethhn" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="mailto:sankethsanketh96396@gmail.com"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2023 Sanketh H N. All rights reserved.</p>
            <p>Built with passion and <i class="fas fa-heart" style="color: var(--accent);"></i></p>
        </div>
    </footer>
</body>
</html>
