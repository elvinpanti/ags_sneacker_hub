<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AGS Sneaker Hub - Your Ultimate Sneaker Destination</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            background-color: #f4f4f4; 
            color: #333; 
            line-height: 1.6;
        }

        /* Navigation */
        nav {
            background-color: #1a1a1a;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            text-transform: uppercase;
            font-size: 0.9rem;
            letter-spacing: 1px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ff6b35;
        }

        /* Header */
        header { 
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white; 
            text-align: center; 
            padding: 80px 20px; 
            box-shadow: 0 4px 20px rgba(0,0,0,0.2);
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        header p {
            font-size: 1.3rem;
            opacity: 0.95;
        }

        .container { 
            max-width: 1200px; 
            margin: 0 auto; 
            padding: 20px; 
        }

        .section { 
            margin-bottom: 60px; 
            animation: fadeInUp 0.6s ease;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Hero Section */
        .hero { 
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),<header>
    <a href="#home">
        <img src="YOUR_LOGO_URL" alt="AG Sneaker Hub Logo" style="max-width: 200px;">
    </a>
</header>
    </a>
    <h1>Welcome to AGS Sneaker Hub</h1>
</header>
            background-size: cover; 
            background-position: center;
            height: 500px; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            color: white; 
            text-shadow: 2px 2px 8px rgba(0,0,0,0.7);
            margin-bottom: 40px;
        }

        .hero h1 { 
            font-size: 4rem;
            animation: slideIn 1s ease;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            color: #333;
            text-align: center;
            position: relative;
            padding-bottom: 15px;
        }

        .section h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            border-radius: 2px;
        }

        .section p {
            font-size: 1.1rem;
            line-height: 1.8;
            text-align: center;
            max-width: 900px;
            margin: 0 auto 2rem;
        }

        /* Features Section */
        .features { 
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .feature { 
            background: white; 
            padding: 2.5rem 2rem; 
            border-radius: 15px; 
            box-shadow: 0 5px 20px rgba(0,0,0,0.1); 
            text-align: center;
            transition: all 0.3s ease;
        }

        .feature:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .feature h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #667eea;
        }

        .feature p {
            font-size: 1rem;
            color: #666;
        }

        /* Featured Sneakers */
        .sneaker-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .sneaker-item {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
        }

        .sneaker-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .sneaker-item strong {
            font-size: 1.3rem;
            color: #333;
            display: block;
            margin-bottom: 0.5rem;
        }

        .sneaker-item p {
            color: #666;
            text-align: left;
        }

        .shop-btn {
            display: inline-block;
            margin-top: 2rem;
            padding: 1rem 3rem;
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2rem;
            transition: all 0.3s ease;
            box-shadow: 0 5px 20px rgba(102, 126, 234, 0.4);
        }

        .shop-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 30px rgba(102, 126, 234, 0.6);
        }

        /* Contact Section */
        .contact-section {
            background: white;
            padding: 3rem;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            text-align: center;
        }

        .contact-section p {
            font-size: 1.1rem;
            margin: 1rem 0;
        }

        .contact-section a {
            color: #667eea;
            text-decoration: none;
            font-weight: 600;
        }

        .contact-section a:hover {
            color: #764ba2;
        }

        /* Footer */
        footer { 
            background-color: #1a1a1a; 
            color: white; 
            text-align: center; 
            padding: 30px 20px;
            margin-top: 60px;
        }

        footer a {
            color: #ff6b35;
            text-decoration: none;
            margin: 0 10px;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            .hero h1 {
                font-size: 2.5rem;
            }

            .section h2 {
                font-size: 2rem;
            }

            nav ul {
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#why-choose">Why Us</a></li>
            <li><a href="#featured">Featured</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header id="home">
        <h1>Welcome to AGS Sneaker Hub</h1>
        <p>Discover the latest trends in sneakers for every style and occasion.</p>
    </header>

    <div class="hero">
        <h1>Step Into Style</h1>
    </div>

    <div class="container">
        <section class="section" id="about">
            <h2>About AGS Sneaker Hub</h2>
            <p>AGS Sneaker Hub is your go-to spot for premium sneakers from top brands like Nike, Adidas, Jordan, and more. Whether you're a casual walker, a fitness enthusiast, or a streetwear fan, we have the perfect pair to elevate your game. Enjoy exclusive deals, fast shipping, and expert advice from our sneaker experts.</p>
        </section>

        <section class="section" id="why-choose">
            <h2>Why Choose Us?</h2>
            <div class="features">
                <div class="feature">
                    <h3>🎯 Wide Selection</h3>
                    <p>Over 500+ styles from iconic brands, updated weekly with the newest drops.</p>
                </div>
                <div class="feature">
                    <h3>✓ Authentic Quality</h3>
                    <p>100% genuine sneakers with authenticity guarantees and warranties.</p>
                </div>
                <div class="feature">
                    <h3>💰 Exclusive Deals</h3>
                    <p>Member discounts, flash sales, and bundle offers to save big.</p>
                </div>
                <div class="feature">
                    <h3>🚀 Fast Delivery</h3>
                    <p>Free shipping on orders, with express options available.</p>
                </div>
            </div>
        </section>

        <section class="section" id="featured">
            <h2>Featured Sneakers</h2>
            <p>Check out our top picks:</p>
            <div class="sneaker-list">
                <div class="sneaker-item">
                    <strong>Nike Air Max 270</strong>
                    <p>Comfort meets style for all-day wear. Perfect for casual outings and light exercise.</p>
                </div>
                <div class="sneaker-item">
                    <strong>Adidas Ultraboost 22</strong>
                    <p>Ultimate energy return for runners. Experience cloud-like cushioning with every step.</p>
                </div>
                <div class="sneaker-item">
                    <strong>Jordan 1 Retro High</strong>
                    <p>Iconic design for collectors and fans. A timeless classic that never goes out of style.</p>
                </div>
            </div>
            <p><a href="#shop" class="shop-btn">Shop Now</a></p>
        </section>

        <section class="section" id="contact">
            <div class="contact-section">
                <h2>Contact Us</h2>
                <p>Have questions? Reach out to our team!</p>
                <p><strong>Email:</strong> <a href="mailto:info@agssneakerhub.com">info@agssneakerhub.com</a></p>
                <p><strong>Phone:</strong> (501) 6379693</p>
                <p style="margin-top: 1.5rem;">Follow us on social media for the latest updates and giveaways.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 AGS Sneaker Hub. All rights reserved.</p>
        <p>
            <a href="#privacy">Privacy Policy</a> | 
            <a href="#terms">Terms of Service</a>
        </p>
    </footer>

    <script>
        // Smooth scrolling for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add scroll animation
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        document.querySelectorAll('.section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(30px)';
            section.style.transition = 'all 0.6s ease';
            observer.observe(section);
        });
    </script>
</body>
</html># ags_sneacker_hub
