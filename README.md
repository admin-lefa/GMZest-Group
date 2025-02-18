<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="GMZEST Group offers AI-powered digital marketing and tech solutions to transform your brand. Innovate. Inspire. Impact.">
    <meta name="keywords" content="digital marketing, AI solutions, branding, web design, app development">
    <title>GMZEST Group | Innovate. Inspire. Impact.</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Open+Sans&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary: #2A2D5D;
            --accent: #FF6B35;
        }
        body {
            font-family: 'Open Sans', sans-serif;
            scroll-behavior: smooth;
            line-height: 1.6;
        }
        .navbar {
            background-color: var(--primary) !important;
            padding: 0.5rem 1rem;
        }
        h1, h2, h3 {
            font-family: 'Montserrat', sans-serif;
            margin-bottom: 1rem;
        }
        .hero {
            background: linear-gradient(rgba(42, 45, 93, 0.6), rgba(42, 45, 93, 0.6)), url('https://images.pexels.com/photos/3183197/pexels-photo-3183197.jpeg');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 50px 0;
            margin-top: 56px;
            min-height: 80vh;
            display: flex;
            align-items: center;
        }
        .about-section {
            background: linear-gradient(rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8)), url('https://images.pexels.com/photos/3184292/pexels-photo-3184292.jpeg');
            background-size: cover;
            background-position: center;
            padding: 2rem 0;
            min-height: 100vh;
            display: flex;
            align-items: center;
        }
        .vision-mission {
            background: linear-gradient(rgba(248, 249, 250, 0.8), rgba(248, 249, 250, 0.8)), url('https://images.pexels.com/photos/669615/pexels-photo-669615.jpeg');
            background-size: cover;
            background-position: center;
            padding: 2rem 0;
            min-height: 80vh;
            display: flex;
            align-items: center;
        }
        .services-section {
            background: linear-gradient(rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8)), url('https://images.pexels.com/photos/590041/pexels-photo-590041.jpeg');
            background-size: cover;
            background-position: center;
            padding: 2rem 0;
            min-height: 100vh;
            display: flex;
            align-items: center;
        }
        .contact-section {
            background: linear-gradient(rgba(248, 249, 250, 0.8), rgba(248, 249, 250, 0.8)), url('https://images.pexels.com/photos/380769/pexels-photo-380769.jpeg');
            background-size: cover;
            background-position: center;
            padding: 2rem 0;
            min-height: 80vh;
            display: flex;
            align-items: center;
        }
        .service-card {
            background: #fff;
            border-radius: 10px;
            padding: 1.5rem;
            margin: 0.5rem;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            height: 100%;
        }
        .service-card img {
            max-width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }
        .owl-nav button {
            background: var(--accent) !important;
            color: white !important;
            width: 35px;
            height: 35px;
            border-radius: 50% !important;
        }
        .btn-accent {
            background-color: var(--accent);
            color: white;
            padding: 0.5rem 1.5rem;
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            .hero {
                min-height: 60vh;
                padding: 30px 0;
            }
            .about-section, .services-section {
                min-height: auto;
                padding: 2rem 0;
            }
            .service-card {
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <!-- Fixed Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <h3>GMZEST GROUP</h3>
                <small>Innovate. Inspire. Impact.</small>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero text-center" id="home">
        <div class="container">
            <h1 class="display-5">Transform Your Brand with Innovation</h1>
            <p class="lead mb-4">AI-Powered Digital Marketing & Tech Solutions</p>
            <a href="#contact" class="btn btn-accent btn-lg">Get Started</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section py-5">
        <div class="container">
            <h2 class="text-center mb-4">ABOUT</h2>
            <h3 class="text-center mb-3">GM ZEST GROUP</h3>
            <p class="lead text-center mb-5">Innovate.Inspire.Impact</p>
            <div class="row">
                <div class="col-md-8 mx-auto">
                    <p class="text-muted">
                        At GM ZEST GROUP, we are redefining the future of marketing by blending innovation, technology and creativity. As a forward-thinking company, we leverage the power of AI and emerging technologies to deliver impactful, tailor-made solutions that drive brand growth and engagement.
                    </p>
                    <img src="https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg" alt="Our Team" class="img-fluid rounded shadow-lg mt-4" loading="lazy">
                </div>
            </div>
        </div>
    </section>

    <!-- Vision & Mission Section -->
    <section class="vision-mission">
        <div class="container">
            <div class="row g-4">
                <div class="col-md-6">
                    <div class="p-4 bg-white rounded shadow">
                        <h3 class="text-accent">Vision</h3>
                        <p>To be the leader in transforming the marketing landscape through cutting-edge technology, unyielding innovation, and an energetic approach. Setting the benchmark for how brands connect with their audiences in the digital age.</p>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="p-4 bg-white rounded shadow">
                        <h3 class="text-accent">Mission</h3>
                        <ul class="list-unstyled">
                            <li>Transform brands through innovative marketing solutions</li>
                            <li>Deliver AI-powered technologies to clients</li>
                            <li>Create impactful solutions for brand growth</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Carousel Section -->
    <section id="services" class="services-section py-5">
        <div class="container">
            <h2 class="text-center mb-5">Our Services</h2>
            <div class="owl-carousel owl-theme">
                <!-- Service Card 1 -->
                <div class="service-card">
                    <img src="https://images.pexels.com/photos/546819/pexels-photo-546819.jpeg" alt="Design and Development Services" loading="lazy">
                    <h5 class="text-primary mt-3">Design & Development</h5>
                    <ul class="mt-3">
                        <li>Graphic Design</li>
                        <li>Web Design</li>
                        <li>App Development</li>
                        <li>Software Design</li>
                        <li>Branding & Signage</li>
                    </ul>
                </div>
                <!-- Service Card 2 -->
                <div class="service-card">
                    <img src="https://images.pexels.com/photos/267350/pexels-photo-267350.jpeg" alt="Digital Marketing Services" loading="lazy">
                    <h5 class="text-primary mt-3">Digital Marketing</h5>
                    <ul class="mt-3">
                        <li>Social Media Management</li>
                        <li>SEO Optimization</li>
                        <li>Content Creation</li>
                        <li>Copywriting</li>
                        <li>Web Analytics</li>
                    </ul>
                </div>
                <!-- Service Card 3 -->
                <div class="service-card">
                    <img src="https://images.pexels.com/photos/669615/pexels-photo-669615.jpeg" alt="Strategy and Management Services" loading="lazy">
                    <h5 class="text-primary mt-3">Strategy & Management</h5>
                    <ul class="mt-3">
                        <li>Strategy Development</li>
                        <li>Events Management</li>
                        <li>Publication Services</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section py-5 bg-light">
        <div class="container">
            <div class="row g-4">
                <div class="col-md-6">
                    <h2>Contact Us</h2>
                    <div class="mt-4">
                        <p>Phuthaditjhaba, 9866</p>
                        <p>060 976 7066</p>
                        <p>info@gmzestgroup.com</p>
                    </div>
                    <div class="mt-4">
                        <h5>Core Values</h5>
                        <div class="d-flex gap-2">
                            <span class="badge bg-accent">Innovation</span>
                            <span class="badge bg-accent">Agility</span>
                            <span class="badge bg-accent">Speed</span>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <form>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Your Name" required>
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Email Address" required>
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="4" placeholder="Your Message" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-accent btn-lg w-100">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h5>GMZEST Group</h5>
                    <p>Innovate. Inspire. Impact.</p>
                </div>
                <div class="col-md-4">
                    <h5>Quick Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="#home" class="text-white">Home</a></li>
                        <li><a href="#about" class="text-white">About</a></li>
                        <li><a href="#services" class="text-white">Services</a></li>
                        <li><a href="#contact" class="text-white">Contact</a></li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h5>Follow Us</h5>
                    <a href="#" class="text-white me-2"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="text-white me-2"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="text-white me-2"><i class="fab fa-linkedin"></i></a>
                </div>
            </div>
            <div class="text-center mt-3">
                <p>&copy; 2025 GMZEST Group. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Scroll-to-top Button -->
    <button id="scrollToTop" title="Go to top" style="display: none; position: fixed; bottom: 20px; right: 20px; z-index: 1000;">
        ↑
    </button>

    <!-- Scripts -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <script>
        $(document).ready(function(){
            // Initialize auto-sliding carousel
            $('.owl-carousel').owlCarousel({
                loop: true,
                margin: 20,
                nav: true,
                dots: false,
                autoplay: true,
                autoplayTimeout: 3000,
                autoplayHoverPause: true,
                responsive: {
                    0: { items: 1 },
                    768: { items: 2 },
                    992: { items: 3 }
                }
            });

            // Smooth scrolling for anchor links
            $('a[href^="#"]').on('click', function(event) {
                event.preventDefault();
                $('html, body').animate({
                    scrollTop: $($(this).attr('href')).offset().top
                }, 800);
            });

            // Scroll-to-top button
            $(window).scroll(function() {
                if ($(this).scrollTop() > 100) {
                    $('#scrollToTop').fadeIn();
                } else {
                    $('#scrollToTop').fadeOut();
                }
            });

            $('#scrollToTop').click(function() {
                $('html, body').animate({ scrollTop: 0 }, 800);
                return false;
            });
        });
    </script>
</body>
</html>
