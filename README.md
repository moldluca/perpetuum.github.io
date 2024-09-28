<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Perpetuum Mobile</title>
    <link rel="icon" href="logo.png" type="image/icon type">
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation -->
    <header>
        <nav class="navbar">
            <div class="logo">
                <img src="images/logo.png" alt="Team Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#team">Team</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#sponsors">Sponsors</a></li>
                <li><a href="#news">News</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>



    <section class="hero">
        <div class="overlay"></div>
        <div class="hero-content">
            <h1>Perpetuum Mobile</h1>
            <p>We keep on moving!</p>
            <a href="#about" class="btn">Discover More</a>
        </div>
    </section>
    
    <script>
        // Array of image URLs
        const heroImages = [
            'images/hero1.jpg',
            'images/hero2.jpg',
            'images/hero3.jpg',
            'images/hero4.jpg',
            'images/hero5.jpg',
            'images/hero6.jpg',
            'images/hero7.jpg',
            
        ];
    
        // Select the hero section
        const heroSection = document.querySelector('.hero');
    
        // Randomly choose an image
        const randomImage = heroImages[Math.floor(Math.random() * heroImages.length)];
    
        // Set the background image of the hero section
        heroSection.style.backgroundImage = `url(${randomImage})`;
    </script>
    

    <!-- About Section -->
    <section id="about" class="about-section">
        <div class="about-content">
            <div class="about-text">
                    <h2>About Us</h2>
                    <p>In order to encourage technical innovation and growth among the youth of Colegiul Național „Mihai Eminescu" in Satu Mare, Romania, Perpetuum Mobile, squad 17870, was established in 2017. We have developed into a well-known and tenacious organisation thanks to a passion spurred by the STEAM initiative and a desire to change the world by instructing people about robotics. We qualified twice for nationals and placed second in the Design Award in 2019 and among the top 15 in 2023 as a result of our participation in the BRD FIRST Tech Challenge in Romania. Beyond rivalry, we are proud of the community-based projects we've started and sponsored that have improved lives and shown how technology advances society.</p>
                </div>
                <div class="about-image">
                    <img src="images/about.jpg" alt="Grup picture">
                </div>
            </div>
        </div>
    </section>

   <!-- Team Section -->
<section id="team" class="section dark-section">
    <div class="container">
        <h2>Meet the Team</h2>
        <div class="team-members grid">
            <!-- Existing Members -->
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 1">
                <h3>Vlad</h3>
                <p>Team Leader, CAD</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 2">
                <h3>Luca</h3>
                <p>Engineering</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 3">
                <h3>Alex</h3>
                <p>Programming, Engineering</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 4">
                <h3>Mold</h3>
                <p>CAD</p>
            </div>
            
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 5">
                <h3>Member 5</h3>
                <p>Member Role</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 6">
                <h3>Member 6</h3>
                <p>Member Role</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 7">
                <h3>Member 7</h3>
                <p>Member Role</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 8">
                <h3>Member 8</h3>
                <p>Member Role</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 9">
                <h3>Member 9</h3>
                <p>Member Role</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 10">
                <h3>Member 10</h3>
                <p>Member Role</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 11">
                <h3>Member 11</h3>
                <p>Member Role</p>
            </div>
            <div class="team-member">
                <img src="images/_.jpeg" alt="Team Member 12">
                <h3>Member 12</h3>
                <p>Member Role</p>
            </div>
        </div>
    </div>
</section>


    <!-- Projects Section -->
    <section id="projects" class="section light-section">
        <div class="container">
            <h2>Our Projects</h2>
            <div class="projects-grid grid">
                <div class="project-card grid-item">
                    <img src="images/project1.jpg" alt="Project 1">
                    <h3>Project 1</h3>
                    <p>Description of the project.</p>
                </div>
                <!-- More projects -->
            </div>
        </div>
    </section>

    <!-- Sponsors Section -->
    <section id="sponsors" class="section dark-section">
        <div class="container">
            <h2>Our Sponsors</h2>
            <div class="sponsor-logos">
                <img src="images/sponsor1.jpg" alt="Sponsor 1">
                <!-- More sponsor logos -->
            </div>
        </div>
    </section>

    <!-- News Section -->
    <section id="news" class="section light-section">
        <div class="container">
            <h2>Latest News</h2>
            <div class="news-grid grid">
                <div class="news-item grid-item">
                    <img src="images/news1.jpg" alt="News 1">
                    <h3>News Title 1</h3>
                    <p>Brief description of the news item.</p>
                </div>
                <!-- More news items -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section dark-section">
        <div class="container">
            <h2>Contact Us</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>© 2024 Your Robotics Team | All Rights Reserved</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </footer>

    <script src="scripts.js"></script>
    
</body>
</html>

