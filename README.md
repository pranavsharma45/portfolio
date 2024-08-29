<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pranav Sharma | Creative Portfolio</title>
    <link rel="stylesheet" href="portfolio1.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav>
        <div class="logo">Your Logo</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Hello, I'm <span>Pranav Sharma</span></h1>
            <p>I'm a passionate <span>Developer/Designer</span> creating beautiful web experiences.</p>
            <a href="#projects" class="btn">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I am a creative developer with a passion for designing and building visually appealing and highly functional websites. With a keen eye for detail and a dedication to delivering quality, I enjoy solving complex problems with clean and efficient code.</p>
    <p>Currently pursuing BE, 3rd year,Information Technology Branch ,IET DAVV. </p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Qualifications</h2>
        <div class="project-card">
           
            <div class="card-content">
                <h3>10th</h3>
                <p>I scored 8.81 cgpa in diploma in computer science</p>
            </div>
        </div>
        <div class="project-card">
          
            <div class="card-content">
                <h3>12th</h3>
                <p>I scored 78% in class 10th from cbse. </p>
            </div>
        </div>
        <!-- Add more project cards as needed -->
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form action="https://formspree.io/your-email" method="POST">
            <div class="form-group">
                <input type="text" name="name" required>
                <label>Pranav Sharma</label>
            </div>
            <div class="form-group">
                <input type="email" name="_replyto" required>
                <label>pranavsh45@gmial.com</label>
            </div>
            <div class="form-group">
                <textarea name="message" required></textarea>
                <label>Hello world!</label>
            </div>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 Pranav Sharma.</p>
    </footer>

    <!-- Smooth Scrolling Script -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
