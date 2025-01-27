<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <img src="logo.png" alt="Logo" class="logo">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#introduction">Home</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#about-me">About Me</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Introduction Section -->
    <section id="introduction" class="section intro">
        <div class="container">
            <h2>Welcome to My Portfolio</h2>
            <p>Hello! My name is Amrita Singh. Explore my projects and learn more about me!</p>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="section">
        <div class="container">
            <h2>My Portfolio</h2>
            <div class="portfolio-grid">
                <div class="card">
                    <h3>Project 1</h3>
                    <p>Taken part in a case study "CHANAKYANEETI".</p>
                </div>
                <div class="card">
                    <h3>Project 2</h3>
                    <p>Designer in the CINESTOX post.</p>
                </div>
                <div class="card">
                    <h3>Project 3</h3>
                    <p>Part of 7th newsletter edition.</p>
                </div>
                <div class="card">
                    <h3>Project 4</h3>
                    <p>Designer in Amazon project.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about-me" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>
                I'm a learner.
            </p>
            <ul>
                <li><strong>Skills:</strong> Web Development, UI/UX Design, Problem Solving</li>
                <li><strong>Education:</strong> Bachelor's in Computer Science</li>
                <li><strong>Achievements:</strong> Hackathon Winner, Open-Source Contributor</li>
                <li><strong>Interests:</strong> Coding, Design, and Photography</li>
            </ul>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="#">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2025 My Portfolio | Follow me on 
                <a href="#">LinkedIn</a>, <a href="#">GitHub</a>, and <a href="#">Twitter</a>.
            </p>
        </div>
    </footer>
</body>
</html>




