# <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Minimalist Website</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2; /* Updated background color to grey */
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
        }

        .hero {
            text-align: center;
        }

        .hero img {
            max-width: 100%;
            height: auto;
        }

        .about {
            text-align: center;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            text-align: center;
        }

        .services img {
            max-width: 100%;
            height: auto;
        }

        .testimonials {
            text-align: center;
        }

        .contact {
            text-align: center;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Your Company Name</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Portfolio</a>
        <a href="#">Contact</a>
    </nav>

    <section class="hero">
        <img src="hero-image.jpg" alt="Hero Image">
        <h2>Welcome to Our Minimalist Website</h2>
    </section>

    <section class="about">
        <h2>About Us</h2>
        <p>Your brief introduction goes here...</p>
    </section>

    <section class="services">
        <div>
            <img src="service1-icon.png" alt="Service 1">
            <h3>Service 1</h3>
            <p>Description of Service 1.</p>
        </div>
        <div>
            <img src="service2-icon.png" alt="Service 2">
            <h3>Service 2</h3>
            <p>Description of Service 2.</p>
        </div>
        <!-- Add more service items as needed -->
    </section>

    <section class="testimonials">
        <h2>What Our Clients Say</h2>
        <!-- Testimonial slider or grid goes here -->
    </section>

    <section class="contact">
        <h2>Contact Us</h2>
        <!-- Contact form goes here -->
    </section>

    <footer>
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </footer>

</body>

</html>
