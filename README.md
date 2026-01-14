# Bella-vista-ristorante
Price 8000 best restaurant website contact  me 9302291202 email akash2005gunour@gmai.com
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bella Vista Ristorante - Authentic Italian Cuisine</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        /* Header */
        header {
            background-color: #2c3e50;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #e74c3c;
        }
        /* Hero Section */
        .hero {
            background-image: url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80'); /* Beautiful restaurant interior */
            background-size: cover;
            background-position: center;
            height: 70vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
        }
        .hero-content {
            position: relative;
            z-index: 1;
        }
        .hero h2 {
            font-size: 3em;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        .btn {
            background-color: #e74c3c;
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #c0392b;
        }
        /* Sections */
        section {
            padding: 60px 0;
        }
        section h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #2c3e50;
        }
        .about, .menu, .gallery, .contact {
            margin-bottom: 60px;
        }
        .about p {
            font-size: 1.1em;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }
        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .menu-item {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }
        .gallery-slider {
            display: flex;
            overflow-x: auto;
            gap: 20px;
            padding: 20px;
            scroll-snap-type: x mandatory;
        }
        .gallery-slider img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            scroll-snap-align: start;
        }
        .contact form {
            max-width: 600px;
            margin: 0 auto;
            display: grid;
            gap: 20px;
        }
        .contact input, .contact textarea {
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1em;
        }
        .contact button {
            background-color: #e74c3c;
            color: #fff;
            padding: 15px;
            border: none;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
            transition: background 0.3s;
        }
        .contact button:hover {
            background-color: #c0392b;
        }
        /* Footer */
        footer {
            background-color: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        /* Responsive */
        @media (max-width: 768px) {
            .hero h2 {
                font-size: 2em;
            }
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Bella Vista Ristorante</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h2>Welcome to Bella Vista</h2>
            <p>Experience the flavors of Italy in a cozy, elegant setting. Authentic pasta, wood-fired pizzas, and exquisite wines await.</p>
            <a href="#menu" class="btn">View Our Menu</a>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Located at 123 Main St, Anytown, USA, Bella Vista Ristorante has been serving authentic Italian cuisine since 2010. Our chefs use fresh, local ingredients to create dishes that transport you straight to the heart of Italy. Whether you're here for a romantic dinner or a family gathering, our warm ambiance and exceptional service make every visit memorable.</p>
        </div>
    </section>

    <section id="menu" class="menu">
        <div class="container">
            <h2>Our Menu</h2>
            <div class="menu-grid">
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ca4b?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Margherita Pizza">
                    <h3>Margherita Pizza</h3>
                    <p>Fresh mozzarella, tomato sauce, basil. $18</p>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1621996346565-e3dbc353d2e5?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Pasta Carbonara">
                    <h3>Pasta Carbonara</h3>
                    <p>Creamy sauce with pancetta and eggs. $22</p>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1546833999-b9f581a1996d?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Tiramisu">
                    <h3>Tiramisu</h3>
                    <p>Classic Italian dessert with coffee and mascarpone. $10</p>
                </div>
            </div>
        </div>
    </section>

    <section id="gallery" class="gallery">
        <div class="container">
            <h2>Gallery</h2>
            <div class="gallery-slider">
                <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Restaurant Interior">
                <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Delicious Pasta">
                <img src="https://images.unsplash.com/photo-1574484284002-952d92456975?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Wine Selection">
                <img src="https://images.unsplash.com/photo-1551782450-17144efb5723?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Outdoor Seating">
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
            <p style="text-align: center; margin-top: 20px;">Address: 123 Main St, Anytown, USA | Phone: (123) 456-7890 | Email: info@bellavista.com</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Bella Vista Ristorante. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Simple gallery slider scroll behavior
        const slider = document.querySelector('.gallery-slider');
        slider.addEventListener('wheel', (e) => {
            e.preventDefault();
            slider.scrollLeft += e.deltaY;
        });
    </script>
</body>
</html>
