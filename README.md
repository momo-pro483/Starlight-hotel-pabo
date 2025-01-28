<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starlight Hotel Pabo</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }

        /* Header */
        .header {
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }

        .header h1 {
            font-size: 2.5rem;
            margin: 0;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: center;
            background: #333;
            padding: 0.5rem 0;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .navbar a:hover {
            background: #ff7e5f;
        }

        /* About Section */
        .about, .services, .contact {
            padding: 2rem;
            text-align: center;
        }

        .about h2, .services h2, .contact h2 {
            color: #ff7e5f;
            margin-bottom: 1rem;
        }

        /* Services Section */
        .services {
            background: #f2f2f2;
        }

        .service-card {
            margin: 1rem auto;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 10px;
            max-width: 400px;
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .service-card h3 {
            color: #333;
            margin-bottom: 0.5rem;
        }

        /* Contact Section */
        .contact p {
            margin: 0.5rem 0;
        }

        /* Footer */
        .footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Starlight Hotel Pabo</h1>
        <p>Your comfort, our priority!</p>
    </header>

    <nav class="navbar">
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Welcome to Starlight Hotel Pabo, your home away from home. We offer luxurious accommodations, event decorations, and everything you need to make your stay memorable.</p>
    </section>

    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-card">
            <h3>Hotel Rooms</h3>
            <ul>
                <li>Single Rooms: <strong>12,000 UGX</strong> per night</li>
                <li>Self-Contained Rooms: <strong>20,000 UGX</strong> per night</li>
            </ul>
        </div>
        <div class="service-card">
            <h3>Event Items</h3>
            <ul>
                <li>Tents</li>
                <li>Decorations for Weddings</li>
                <li>Party Decorations</li>
            </ul>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>📍 Location: Pabo, Uganda</p>
        <p>📞 Phone 1: +256 778 754 632</p>
        <p>📞 Phone 2: +256 740 460 544</p>
        <p>📧 Email: info@starlighthotelpabo.com</p>
    </section>

    <footer class="footer">
        <p>&copy; 2025 Starlight Hotel Pabo. All rights reserved.</p>
    </footer>
</body>
</html>
