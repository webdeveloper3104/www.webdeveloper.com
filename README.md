
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web developer Portfolio</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="webdesigner.css">
</head>

<body>
    <nav class="navbar navbar-light navbar-expand-lg py-3 bg-light sticky-top shadow-lg p-3 mb-5 rounded">
        <a class="navbar-brand text-dark font-weight-bold" href="#">Webdeveloper3104</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link text-dark font-weight-bold h5" href="#hero">Home <span
                            class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-dark font-weight-bold h5" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-dark font-weight-bold h5" href="#skills">Skills</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-dark font-weight-bold h5" href="#projects">Projects</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-dark font-weight-bold h5" href="#education">Education</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-dark font-weight-bold h5" href="#experience">Experience</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-dark font-weight-bold h5" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="hero-section ">
        <video class="video-background" autoplay loop muted>
            <source src="stock.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <div class="hero-content text-start">
                        <h2 class="font-weight-bold">I'm</h2>
                        <h1 class="h1 display-3 font-weight-bold name">Shiva<span>-Desinger</span></h1>
                        <h2><span id="typed"></span></h2>
                        <i class="fab fa-youtube"></i>
                        <i class="fab fa-github"></i>
                        <i class="fab fa-linkedin"></i>
                    </div>
                </div>
                <div class="col-md-6 profile-img">
                    <div class="hero-image text-center ">
                        <img src="profile 3104.jpg" alt="Your Name" >
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <div class="about-image text-center">
                        <img src="about3104.jpg" alt="About Image">
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="about-content">
                        <h2 class="font-weight-bold">About Me</h2>
                        <p class="font-weight-bold">I am a dedicated software engineer with a passion for creating innovative and efficient software solutions. With expertise in various programming languages and frameworks, I specialize in designing, developing, and maintaining robust applications. My strong problem-solving skills and attention to detail ensure high-quality, reliable software. I thrive in collaborative environments and continuously seek to enhance my skills and knowledge in the ever-evolving field of technology.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills-section bg-light">
        <div class="container">
            <h2 class="text-center font-weight-bold mb-4">Skills</h2>
            <div class="d-flex flex-wrap justify-content-center">
                <div class="skills-item">
                    <div class="skills-icon">
                        <i class="fab fa-html5"></i>
                    </div>
                    <div class="skills-details">
                        <h3>HTML5</h3>
                        <p>Proficient in creating semantic HTML markup.</p>
                    </div>
                </div>
                <div class="skills-item">
                    <div class="skills-icon">
                        <i class="fab fa-css3"></i>
                    </div>
                    <div class="skills-details">
                        <h3>CSS3</h3>
                        <p>Skilled in CSS for styling and layout.</p>
                    </div>
                </div>
                <div class="skills-item">
                    <div class="skills-icon">
                        <i class="fab fa-js"></i>
                    </div>
                    <div class="skills-details">
                        <h3>JavaScript</h3>
                        <p>Experience in client-side scripting and DOM manipulation.</p>
                    </div>
                </div>
                <div class="skills-item">
                    <div class="skills-icon">
                        <i class="fab fa-python"></i>
                    </div>
                    <div class="skills-details">
                        <h3>Python</h3>
                        <p>Experienced in Python programming.</p>
                    </div>
                </div>
                <div class="skills-item">
                    <div class="skills-icon">
                        <i class="fab fa-react"></i>
                    </div>
                    <div class="skills-details">
                        <h3>React</h3>
                        <p>Developing dynamic user interfaces with React.</p>
                    </div>
                </div>
                <!-- Add more skills as needed -->
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects-section ">
        <div class="container">
            <h2 class="text-center font-weight-bold mb-4">Projects</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card project-card my-2">
                        <img src="project.jpg" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">Project 1</h5>
                            <p class="card-text">Brief description of Project 1.</p>
                            <a href="#" class="btn btn-primary">View Details</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card project-card my-2">
                        <img src="project.jpg" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title">Project 2</h5>
                            <p class="card-text">Brief description of Project 2.</p>
                            <a href="#" class="btn btn-primary">View Details</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card project-card my-2">
                        <img src="project.jpg" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title">Project 3</h5>
                            <p class="card-text">Brief description of Project 3.</p>
                            <a href="#" class="btn btn-primary">View Details</a>
                        </div>
                    </div>
                </div>
                <!-- Add more project cards as needed -->
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="education-section bg-light">
        <div class="container">
            <h2 class="text-center mb-4 font-weight-bold">Education</h2>
            <div class="d-flex flex-wrap justify-content-center">
                <div class="education-item">
                    <div class="education-icon">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <div class="education-details">
                        <h3>Bachelor's Degree</h3>
                        <p>University Name, Year</p>
                    </div>
                </div>
                <div class="education-item">
                    <div class="education-icon">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <div class="education-details">
                        <h3>Master's Degree</h3>
                        <p>University Name, Year</p>
                    </div>
                </div>
                <!-- Add more education items as needed -->
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="experience-section ">
        <div class="container">
            <h2 class="text-center mb-4 font-weight-bold">Experience</h2>
            <ul class="timeline">
                <li class="timeline-item">
                    <div class="timeline-icon">
                        <i class="fas fa-briefcase"></i>
                    </div>
                    <div class="timeline-item-left">
                        <h3>Software Engineer</h3>
                        <p>Company Name, Year - Year</p>
                        <p>Brief description of your role and responsibilities.</p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-icon">
                        <i class="fas fa-briefcase"></i>
                    </div>
                    <div class="timeline-item-right">
                        <h3>Senior Developer</h3>
                        <p>Company Name, Year - Year</p>
                        <p>Brief description of your role and responsibilities.</p>
                    </div>
                </li>
                <!-- Add more timeline items as needed -->
            </ul>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section bg-light">
        <div class="container py-3">
            <h2 class="text-center mb-4 font-weight-bold">Contact Me</h2>
            <div class="row justify-content-center">
                <div class="col-md-6">
                    <div class="">
                        <img src="contact.png"/>
                    </div>
                </div>
                <div class="col-md-6">
                    <form action="send_email.php" method="POST">
                        <div class="form-group">
                            <label for="name">Your Name</label>
                            <input type="text" class="form-control" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Your Email</label>
                            <input type="email" class="form-control" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea class="form-control" id="message" name="message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer-section bg-dark text-white py-3">
        <div class="container text-center">
            <p>&copy; 2024 Your Name. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <!-- Typewriter Effect JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>
    <!-- Font Awesome Icons -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/js/all.min.js"></script>
    <!-- Custom JavaScript -->
    <script>
        var typed = new Typed('#typed', {
            strings: ['Web Developer'],
            typeSpeed: 80,
            backSpeed: 40,
            loop: true
        });
    </script>
</body>

</html>ch
