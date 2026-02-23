<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thanusha Portfolio 2026</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #5d3c64;
            --accent: black;
        }

        * { margin: 0;
             padding: 0; 
             box-sizing: border-box; 
             font-family: 'Poppins', sans-serif; 
             scroll-behavior: smooth; }

        body { 
            /* IMAGE 1: BACKGROUND */
            background-image: linear-gradient(rgba(255,255,255,0.8), rgba(255,255,255,0.8)), url("backgrd.jpeg"); 
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            color: #333; 
            overflow-x: hidden; 
            background-image: no-repeat;
            image-rendering: crisp-edges;
        }

        nav {
            display: flex;
            justify-content: space-between; 
            align-items: center;
            padding: 15px 8%; 
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(12px); 
            position: fixed;
             width: 100%; 
             top: 0; 
             z-index: 1000;
        }
        .logo { font-size: 1.6rem;
             font-weight: 800;
              color: var(--primary); }
        .nav-links a { text-decoration: none; 
                       color:#5d3c64;
                        margin-left: 25px;
                         font-weight: 500;
                          transition: 0.3s; }

        .nav-links a:hover { color: var(--accent); }

        .hire-btn { background: var(--primary); 
            color: white !important; 
            padding: 10px 25px;
             border-radius: 50px; }

        .hero {
            display: flex;
             align-items: center; 
            justify-content: center;
            height: 100vh;
             padding: 0 10%; gap: 60px;
        }
        .profile-img {
            width: 320px; 
            height: 320px;
             border-radius: 30px;
            background: #fff;
            border: 10px solid white;
            box-shadow: 20px 20px 50px rgba(0,0,0,0.1);
            object-fit: cover;
        }

        .text-side h1 { font-size: 3.2rem;
             margin-bottom: 15px; }
        #typing-text { color: var(--primary); border-right: 3px solid var(--accent); padding-right: 8px; }

        section { padding: 100px 10% 20px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; margin-top: 40px; }
        
        .v-box {
            background: rgba(138, 139, 139, 0.9); padding: 45px; border-radius: 24px;
            text-align: center; transition: 0.4s;
            border-bottom: 5px solid transparent;
            
        }
    
        .v-box:hover { transform: translateY(-12px); border-bottom: 5px solid var(--accent); background: whitesmoke; }

        /* IMAGE 2: UNIVERSITY LOGO IN CORNER */
        .edu-card { position: relative; display: flex; align-items: center; gap: 20px; }
        .univ-logo {
            width: 60px; height: 60px; object-fit: contain;
        }

        .code-display {
            background: #282a36; color: #f8f8f2; padding: 30px;
            border-radius: 20px; font-family: monospace; font-size: 1.1rem; height: 120px;
            display: flex; align-items: center; border-left: 5px solid #50fa7b;
        }

        /* SOCIAL ICON STYLING (Images 3, 4, 5) */
        .social-container { display: flex; flex-direction: column; gap: 15px; margin-top: 20px; }
        .social-item { display: flex; align-items: center; gap: 15px; text-decoration: none; color: inherit; }
        .social-icon { width: 40px; height: 40px; transition: 0.3s; }
        .social-icon:hover { transform: scale(1.2); }

        footer { text-align: center;
             padding: 30px; 
             background: rgb(149, 146, 146);
              margin-top: 100px; }
    </style>
</head>
<body>

    <nav>
        <div class="logo">Thanusha S</div>
        <div class="nav-links">
            <a href="#about">About</a><a href="#skills">Skills</a><a href="#projects">Projects</a><a href="#contact">Contact</a>
            <a href="mailto:sthanusha60@gmail.com" class="hire-btn">Hire Me</a>
        </div>
        
    </nav>
    

    <header class="hero">
        <div class="profile-side">
            <img src="me.jpeg" alt="Thanusha" class="profile-img">
        </div>
        <div class="text-side">
            <h1>Excited for learning <br><span id="typing-text"></span></h1>
            <p>I am dedicated student passionate about building functional and aesthetic digital solutions.you should hire me because i blend technical logic with creative problem solving and am always ready to adapt to new technologies.</p>
        </div>
    </header>

    <section id="about">
        <div class="v-box edu-card">
            <img src="bcu.jpeg" alt="BCU" class="univ-logo">
            <div>
                <h2 style="color: var(--primary);">Education</h2>
                <p>Currently studying in Bengaluru City University</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2 style="text-align: center;">Technical Expertise</h2>
        <div class="grid">
            <div class="v-box"><h3>HTML & CSS</h3></div>
            <div class="v-box"><h3>PYTHON</h3></div>
            <div class="v-box"><h3>JAVASCRIPT</h3></div>
        </div>
    </section>
    <section id="projects">
        <h2 style="text-align: center;">Projects</h2>
        <div class="grid">
            <div class="v-box"><h3>Studywiththanu</h3><p>build for uploading a notes ,model paper ,textbooks <br> specially for SEP students
            </p></div>
            <div class="v-box"><h3>Weather App</h3><p>A Python application that fetches real-time weather data using an API.</p></div>
            <div class="v-box"><h3>To-Do List</h3><p>FKCCI Business plan competition </p></div>
        </div>

    <section id="contact">
        <div style="display: flex; gap: 50px; align-items: center; flex-wrap: wrap;">
            <div id="code-flipper" class="code-display" style="flex: 1; min-width: 300px;"></div>
            <div style="flex: 1; min-width: 300px;">
                <h2 style="margin-bottom: 20px;">Let's Connect</h2>
                <div class="social-container">
                    <a href="#" class="social-item">
                        <img src="github.jpeg" class="social-icon" alt="GitHub">
                        <a href="https://github.com/thanusha-20" style="text-decoration: none; color: inherit;"><span>GitHub Profile</span></a>
                    </a>
                    <a href="#" class="social-item">
                        <img src="linkedin.jpeg" class="social-icon" alt="LinkedIn">
                       <a href="https://www.linkedin.com/in/thanusha-s-765555361?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app "style="text-decoration: none; color: inherit;"> <span>LinkedIn Profile</span>
                    </a>
                    <a href="#" class="social-item">
                        <img src="email.jpeg" class="social-icon" alt="Email">
                        <a href="mailto:sthanusha60@gmail.com" style="text-decoration: none; color: inherit;"><span>Email me</span>
                    </a>
                </div>
                <p style="margin-top: 15px;"></p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2026 Thanusha | All Rights Reserved</p>
        <p>Follow me on <a href="#" style="color: var(--primary); text-decoration: none;">GitHub</a> and <a href="#" style="color: var(--primary); text-decoration: none;">LinkedIn</a></p>
        <p>Designed with ❤️ by Thanusha S</p>
    </footer>

    <script>
        // TYPING EFFECT
        const techList = ["New Skills", "Advance Technologies", "New Tools"];
        let techIndex = 0; let charIndex = 0; let isDeleting = false;
        const typingTextElement = document.getElementById("typing-text");

        function type() {
            const currentTech = techList[techIndex];
            typingTextElement.innerText = isDeleting ? currentTech.substring(0, charIndex--) : currentTech.substring(0, charIndex++);
            let typeSpeed = isDeleting ? 50 : 100;
            if (!isDeleting && charIndex > currentTech.length) { isDeleting = true; typeSpeed = 600; }
            else if (isDeleting && charIndex < 0) { isDeleting = false; techIndex = (techIndex + 1) % techList.length; charIndex = 0; typeSpeed = 200; }
            setTimeout(type, typeSpeed);
        }

        // CODE FLIPPER (0.5s)
        const codes = ["print('Success')", "git push", "npm start", "const dev = 'Thanusha'", "plt.show()"];
        let codeIdx = 0;
        setInterval(() => {
            document.getElementById("code-flipper").innerText = codes[codeIdx];
            codeIdx = (codeIdx + 1) % codes.length;
        }, 500);

        window.onload = type;
    </script>
</body>
</html>
