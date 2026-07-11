<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aura Beauty Nepal | Organic Skincare & Cosmetics</title>
    <style>
        /* Modern Minimalist Styling for Beauty Brands */
        :root {
            --primary: #8d7060; /* Earthy, natural tone */
            --accent: #f4eae4;  /* Soft blush background */
            --dark: #2d2522;    /* Dark brown text for softer contrast than pure black */
            --white: #ffffff;
            --shadow: rgba(0, 0, 0, 0.05);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            color: var(--dark);
            background-color: var(--white);
            line-height: 1.6;
        }

        /* Navigation */
        header {
            background: var(--white);
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 1px solid var(--accent);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            letter-spacing: 2px;
            color: var(--primary);
            text-transform: uppercase;
        }

        nav a {
            text-decoration: none;
            color: var(--dark);
            margin-left: 20px;
            font-size: 0.95rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--primary);
        }

        /* Hero Section */
        .hero {
            background-color: var(--accent);
            padding: 5rem 5%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .hero-text {
            flex: 1;
            min-width: 300px;
            padding-right: 2rem;
        }

        .hero-text h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: var(--dark);
            line-height: 1.2;
        }

        .hero-text p {
            font-size: 1.1rem;
            margin-bottom: 2rem;
            color: #665a55;
        }

        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: var(--white);
            padding: 0.8rem 2rem;
            text-decoration: none;
            border-radius: 4px;
            font-weight: 600;
            transition: opacity 0.3s;
        }

        .btn:hover {
            opacity: 0.9;
        }

        .hero-image {
            flex: 1;
            min-width: 300px;
            display: flex;
            justify-content: center;
        }

        /* Placeholder image using a reliable public stock URL */
        .hero-image img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 10px 20px var(--shadow);
        }

        /* Products Grid Section */
        .products-section {
            padding: 5rem 5%;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 3rem;
            position: relative;
            letter-spacing: 1px;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .product-card {
            background: var(--white);
            border: 1px solid var(--accent);
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
        }

        .product-img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 6px;
            background-color: var(--accent);
            margin-bottom: 15px;
        }

        .product-card h3 {
            font-size: 1.2rem;
            margin-bottom: 8px;
        }

        .price {
            color: var(--primary);
            font-weight: bold;
            margin-bottom: 15px;
            font-size: 1.1rem;
        }

        /* Trust & Localization Flags */
        .features {
            background-color: #faf7f5;
            padding: 3rem 5%;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
            gap: 20px;
        }

        .feature-item {
            flex: 1;
            min-width: 200px;
        }

        .feature-item h4 {
            margin-bottom: 8px;
            color: var(--primary);
        }

        /* Payment Integration Info Banner */
        .payment-info {
            text-align: center;
            padding: 3rem 5%;
            border-top: 1px solid var(--accent);
        }

        .payment-info p {
            font-size: 0.9rem;
            color: #777;
            margin-bottom: 15px;
        }

        .payment-methods {
            font-weight: bold;
            color: var(--dark);
            letter-spacing: 1px;
        }

        /* Footer */
        footer {
            background-color: var(--dark);
            color: var(--white);
            text-align: center;
            padding: 2rem 5%;
            font-size: 0.9rem;
        }

        /* Responsive Design Rules */
        @media (max-width: 768px) {
            .hero { padding: 3rem 5%; }
            .hero-text h1 { font-size: 2.2rem; }
            header { flex-direction: column; gap: 10px; }
            nav a { margin: 0 10px; }
        }
    </style>
</head>
<body>

    <!-- Header Navigation -->
    <header>
        <div class="logo">Aura Beauty</div>
        <nav>
            <a href="#">Home</a>
            <a href="#shop">Shop</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Showcase Section -->
    <section class="hero">
        <div class="hero-text">
            <h1>Glow Naturally, <br>Every Day.</h1>
            <p>Premium, cruelty-free cosmetics and organic skincare tailored specifically for Nepali skin types. Discover your natural aura today.</p>
            <a href="#shop" class="btn">Shop Best Sellers</a>
        </div>
        <div class="hero-image">
            <!-- Sourced a universally available high-quality beauty stock photo -->
            <img src="https://images.unsplash.com/photo-1556228720-195a672e8a03?auto=format&fit=crop&w=500&q=80" alt="Natural Skincare Products Showcase">
        </div>
    </section>

    <!-- Core Business Features -->
    <section class="features">
        <div class="feature-item">
            <h4>🚚 Delivery Across Nepal</h4>
            <p>Inside Kathmandu valley & major cities out-of-valley</p>
        </div>
        <div class="feature-item">
            <h4>🌿 100% Organic & Safe</h4>
            <p>Formulated carefully for delicate skin types</p>
        </div>
        <div class="feature-item">
            <h4>💬 Nepali Support</h4>
            <p>Inquire directly on Instagram, TikTok, or WhatsApp</p>
        </div>
    </section>

    <!-- Product Showcase Grid -->
    <section class="products-section" id="shop">
        <h2 class="section-title">Our Best Sellers</h2>
        <div class="products-grid">
            
            <!-- Product 1 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1608248597481-496100c8c836?auto=format&fit=crop&w=300&q=80" alt="Vitamin C Serum" class="product-img">
                <h3>Hydrating Vitamin C Serum</h3>
                <p class="price">Rs. 1,450</p>
                <a href="#" class="btn" style="padding: 0.5rem 1.5rem; font-size: 0.9rem;">Add to Cart</a>
            </div>

            <!-- Product 2 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?auto=format&fit=crop&w=300&q=80" alt="Glow Moisturizer" class="product-img">
                <h3>Daily Mattifying Moisturizer</h3>
                <p class="price">Rs. 1,200</p>
                <a href="#" class="btn" style="padding: 0.5rem 1.5rem; font-size: 0.9rem;">Add to Cart</a>
            </div>

            <!-- Product 3 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1598440947619-2c35fc9aa908?auto=format&fit=crop&w=300&q=80" alt="Clay Mask" class="product-img">
                <h3>Himalayan Clay Detox Mask</h3>
                <p class="price">Rs. 950</p>
                <a href="#" class="btn" style="padding: 0.5rem 1.5rem; font-size: 0.9rem;">Add to Cart</a>
            </div>

        </div>
    </section>

    <!-- Localized Payment Section -->
    <section class="payment-info">
        <p>We accept local digital wallets and cash on delivery</p>
        <div class="payment-methods">
            eSewa | Khalti | Fonepay | Cash on Delivery (COD)
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Aura Beauty Nepal. All Rights Reserved.</p>
        <p style="font-size: 0.8rem; margin-top: 5px; opacity: 0.7;">Kathmandu, Nepal | Phone: +977-1XXXXXX</p>
    </footer>

</body>
</html>
