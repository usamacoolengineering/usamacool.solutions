<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Usama Cool Engineering (SMC-Pvt) Ltd</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2d3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header img {
            width: 100px;
        }
        nav {
            text-align: center;
            background-color: #1d2d3f;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        section {
            padding: 40px 20px;
        }
        footer {
            background-color: #2d3e50;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h2 {
            color: #2d3e50;
        }
        .services, .contact-form {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service, .contact {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            width: 30%;
            margin: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #2d3e50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/100" alt="Logo">
        <h1>Usama Cool Engineering (SMC-Pvt) Ltd</h1>
        <p>Your Trusted HVAC Solutions Partner</p>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We specialize in providing top-notch HVAC services, focusing on industrial-grade cooling systems for commercial and industrial spaces. Our team ensures high-quality performance and long-lasting solutions.</p>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service">
                    <h3>HVAC Systems</h3>
                    <p>Installation and maintenance of HVAC systems for industrial and commercial applications.</p>
                </div>
                <div class="service">
                    <h3>Chillers & Freezers</h3>
                    <p>Providing installation and repair services for industrial chillers and freezers.</p>
                </div>
                <div class="service">
                    <h3>Industrial Cooling Solutions</h3>
                    <p>Customized cooling solutions tailored for large-scale industrial setups.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <div class="contact-form">
                <form>
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                    <button type="submit">Send Message</button>
                </form>
            </div>
            <div class="contact">
                <h3>Contact Details:</h3>
                <p><strong>Phone:</strong> +923142924589</p>
                <p><strong>Email:</strong> <a href="mailto:usamacoolengineering@gmail.com">usamacoolengineering@gmail.com</a></p>
                <p><strong>Location:</strong> Karachi, Pakistan</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 Usama Cool Engineering | All Rights Reserved</p>
    </footer>
</body>
</html>
