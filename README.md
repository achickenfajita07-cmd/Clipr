[webtest6.html](https://github.com/user-attachments/files/23966234/webtest6.html)<img width="1920" height="1425" alt="purpletool" src="https://github.com/user-attachments/assets/9dfec03d-7e8a-4eeb-9e08-aaff5c9f2206" />
<img width="1920" height="1425" alt="bluecar" src="https://github.com/user-attachments/assets/238f28eb-1b21-4d1a-96ea-1d45bdd6c8f5" />
<img width="1920" height="1425" alt="orangecar" src="https://github.com/user-attachments/assets/a79a644c-6711-4b42-b6ef-1e745c924ee6" />
<img width="1920" height="1425" alt="purplecar" src="https://github.com/user-attachments/assets/e419422b-e83e-49e8-86f9-f71d3643976b" />
<img width="728" height="487" alt="Renderss1" src="https://github.com/user-attachments/assets/06a9f20b-f5bc-4431-bd71-e1750250bc21" />
<img width="1920" height="1380" alt="Doublesell" src="https://github.com/user-attachments/assets/5ebbe266-05e0-45c6-9206-9df57b556838" />
<img width="2158" height="3840" alt="topdown" src="https://github.com/user-attachments/assets/866a5d5f-2d63-493a-96a7-de66872be651" />
<img width="1920" height="1425" alt="bluetool" src="https://github.com/user-attachments/assets/01c33d52-b234-4d66-a6f9-d123f97f1a8a" />
<img width="1920" height="1425" alt="orangetool" src="https://github.com/user-attachments/assets/481b5099-9f94-4398-88c8-60c64e05a2ef" />

[Uploading webtest6.html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Tool Carabiner</title>
    <link href="https://db.onlinewebfonts.com/c/5106d68e104769a524b10bb049340f26?family=Litera+Bold"  rel="stylesheet" type="text/css"/>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'litera bold', sans-serif;
            background: #1a1a1a;
            color: #ffffff;
            overflow-x: hidden;
        }

        /* Header */
        header {
            position: fixed;
            width: 100%;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            background: rgba(26, 26, 26, 0.85);
            backdrop-filter: blur(30px);
            border-bottom: 0 4px 20px rgba(255, 255, 255, 0.1);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3)
        }

        .logo {
            font-size: 30px;
            font-weight: bold;
            color: #ff6b35;
            cursor: pointer;
        }

        nav {
            display: flex;
            align-items: center;
            gap: 30px;
        }

        nav a {
            color: #ffffff;
            text-decoration: none;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ff6b35;
        }

        /* Dropdown Menu */
        .nav-dropdown {
            position: relative;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            top: 100%;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(26, 26, 26, 0.98);
            backdrop-filter: blur(30px);
            min-width: 200px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            padding: 10px 0;
            margin-top: 5px;
            z-index: 1001;
        }

        .nav-dropdown:hover .dropdown-content {
            display: block;
        }

        /* Add invisible bridge between menu and dropdown */
        .dropdown-content::before {
            content: '';
            position: absolute;
            top: -10px;
            left: 0;
            right: 0;
            height: 10px;
            background: transparent;
        }

        .dropdown-content a {
            display: block;
            padding: 12px 25px;
            color: #ffffff;
            text-decoration: none;
            transition: all 0.3s;
        }

        .dropdown-content a:hover {
            background: #ff6b35;
            color: #ffffff;
        }

        .basket-icon {
            position: relative;
            cursor: pointer;
            font-size: 24px;
        }

        .basket-count {
            position: absolute;
            top: -8px;
            right: -8px;
            background: #ff6b35;
            color: white;
            border-radius: 50%;
            width: 20px;
            height: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            font-weight: bold;
        }

        /* Pages */
        .page {
            display: none;
            min-height: 100vh;
        }

        .page.active {
            display: block;
        }

        /* Hero */
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            background: linear-gradient(135deg, #2a2a2a 0%, #1a1a1a 100%);
        }

        .hero-content {
            text-align: center;
            z-index: 2;
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 72px;
            margin-bottom: 20px;
            color: #ffffff;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        .hero h1 span {
            color: #ff6b35;
        }

        .hero p {
            font-size: 24px;
            color: #b0b0b0;
            margin-bottom: 40px;
        }

        .cta-button {
            display: inline-block;
            padding: 18px 45px;
            background: #ff6b35;
            color: #ffffff;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            border-radius: 50px;
            transition: all 0.3s;
            box-shadow: 0 10px 30px rgba(255, 107, 53, 0.3);
            border: none;
            cursor: pointer;
        }

        .cta-button:hover {
            background: #ff8555;
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(255, 107, 53, 0.4);
        }

        /* Features */
        .features {
            padding: 100px 50px;
            background: #ffffff;
            color: #1a1a1a;
        }

        .features h2 {
            text-align: center;
            font-size: 48px;
            margin-bottom: 60px;
            color: #1a1a1a;
        }

        .features h2 span {
            color: #ff6b35;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .feature-card {
            background: #f5f5f5;
            padding: 40px 30px;
            border-radius: 15px;
            text-align: center;
            transition: all 0.3s;
            border: 3px solid transparent;
        }

        .feature-card:hover {
            transform: translateY(-10px);
            border-color: #ff6b35;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
        }

        .feature-icon {
            width: 80px;
            height: 80px;
            background: #ff6b35;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 25px;
            font-size: 36px;
        }

        .feature-card h3 {
            font-size: 24px;
            margin-bottom: 15px;
            color: #1a1a1a;
        }

        .feature-card p {
            color: #666;
            line-height: 1.6;
        }

        /* Showcase/Carousel */
        .showcase {
            padding: 100px 50px;
            background: #2a2a2a;
            text-align: center;
        }

        .showcase h2 {
            font-size: 48px;
            margin-bottom: 30px;
        }

        .showcase h2 span {
            color: #ff6b35;
        }

        .carousel-container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 0 50px;
            position: relative;
        }

        .carousel-wrapper {
            background: linear-gradient(135deg, #3a3a3a 0%, #2a2a2a 100%);
            border-radius: 20px;
            padding: 80px 20px;
            min-height: 600px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .carousel {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            perspective: 1000px;
        }

        .carousel-arrow {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background: rgba(255, 107, 53, 0.8);
            color: white;
            border: none;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            font-size: 24px;
            cursor: pointer;
            transition: all 0.3s;
            z-index: 100;
        }

        .carousel-arrow:hover {
            background: #ff6b35;
            transform: translateY(-50%) scale(1.1);
        }

        .carousel-arrow.left {
            left: 20px;
        }

        .carousel-arrow.right {
            right: 20px;
        }

        .carousel-item {
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            border-radius: 15px;
            overflow: hidden;
            position: relative;
        }

        .carousel-item img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            display: block;
            transition: opacity 0.3s;
        }

        .carousel-item.side {
            width: 150px;
            height: 150px;
            opacity: 0.6;
            transform: scale(0.8);
            filter: grayscale(30%);
        }

        .carousel-item.center {
            width: 450px;
            height: 450px;
            opacity: 1;
            transform: scale(1);
            border: 4px solid #ff6b35;
            box-shadow: 0 20px 60px rgba(255, 107, 53, 0.4);
            z-index: 10;
            cursor: pointer;
        }

        .carousel-item.center:hover img {
            opacity: 0.85;
        }

        .carousel-item.center:hover .buy-button-overlay {
            opacity: 1;
        }

        .buy-button-overlay {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            opacity: 0;
            transition: opacity 0.3s;
            pointer-events: none;
        }

        .carousel-item.center:hover .buy-button-overlay {
            pointer-events: all;
        }

        .buy-button-overlay button {
            padding: 15px 40px;
            background: #ff6b35;
            color: white;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 10px 30px rgba(255, 107, 53, 0.5);
            transition: all 0.3s;
        }

        .buy-button-overlay button:hover {
            background: #ff8555;
            transform: scale(1.05);
        }

        .carousel-item.hidden {
            display: none;
        }

        /* Product Page */
        .product-page {
            padding: 120px 50px 50px;
            min-height: 100vh;
        }

        .back-button {
            display: inline-block;
            padding: 10px 25px;
            background: #3a3a3a;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            margin-bottom: 30px;
            transition: all 0.3s;
        }

        .back-button:hover {
            background: #4a4a4a;
        }

        .product-container {
            max-width: 1400px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1fr 300px;
            gap: 50px;
            align-items: start;
        }

        .product-image-section {
            background: linear-gradient(135deg, #3a3a3a 0%, #2a2a2a 100%);
            border-radius: 20px;
            padding: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 500px;
            max-height: 500px;
            position: sticky;
            top: 120px;
        }

        .product-image-section img {
            max-width: 100%;
            max-height: 500px;
            object-fit: contain;
        }

        .product-details {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }

        .product-details h1 {
            font-size: 42px;
            color: #ff6b35;
            margin-bottom: 10px;
        }

        .product-price {
            font-size: 32px;
            color: #ffffff;
            font-weight: bold;
        }

        .product-description {
            color: #b0b0b0;
            line-height: 1.8;
            font-size: 16px;
        }

        .color-selector {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .color-selector h3 {
            font-size: 18px;
            color: #ffffff;
        }

        .color-options {
            display: flex;
            gap: 15px;
        }

        .color-option {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            cursor: pointer;
            border: 3px solid transparent;
            transition: all 0.3s;
        }

        .color-option:hover {
            transform: scale(1.1);
        }

        .color-option.selected {
            border-color: #ff6b35;
            box-shadow: 0 0 20px rgba(255, 107, 53, 0.5);
        }

        .add-to-basket-btn {
            padding: 18px 45px;
            background: #ff6b35;
            color: white;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: 0 10px 30px rgba(255, 107, 53, 0.3);
        }

        .add-to-basket-btn:hover {
            background: #ff8555;
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(255, 107, 53, 0.4);
        }

        /* Specs Sidebar */
        .specs-sidebar {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .spec-section {
            background: #2a2a2a;
            border-radius: 10px;
            overflow: hidden;
            transition: all 0.3s;
        }

        .spec-header {
            padding: 20px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #2a2a2a;
            transition: all 0.3s;
        }

        .spec-header:hover {
            background: #3a3a3a;
        }

        .spec-header h3 {
            font-size: 16px;
            color: #ffffff;
        }

        .spec-arrow {
            transition: transform 0.3s;
        }

        .spec-section.open .spec-arrow {
            transform: rotate(180deg);
        }

        .spec-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
            background: #1a1a1a;
        }

        .spec-section.open .spec-content {
            max-height: 500px;
        }

        .spec-content-inner {
            padding: 20px;
            color: #b0b0b0;
            line-height: 1.8;
        }

        .spec-content-inner ul {
            list-style: none;
            padding: 0;
        }

        .spec-content-inner li {
            padding: 8px 0;
            border-bottom: 1px solid #2a2a2a;
        }

        .spec-content-inner li:last-child {
            border-bottom: none;
        }

        /* All Products Page */
        .all-products-page {
            padding: 120px 50px 50px;
            min-height: 100vh;
        }

        .all-products-container {
            max-width: 1400px;
            margin: 0 auto;
        }

        .all-products-container h1 {
            font-size: 48px;
            color: #ff6b35;
            margin-bottom: 20px;
            text-align: center;
        }

        .all-products-container p {
            text-align: center;
            color: #b0b0b0;
            font-size: 18px;
            margin-bottom: 50px;
        }

        .all-products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .product-card {
            background: linear-gradient(135deg, #3a3a3a 0%, #2a2a2a 100%);
            border-radius: 20px;
            padding: 30px;
            text-align: center;
            transition: all 0.3s;
            cursor: pointer;
            border: 3px solid transparent;
        }

        .product-card:hover {
            transform: translateY(-10px);
            border-color: #ff6b35;
            box-shadow: 0 20px 60px rgba(255, 107, 53, 0.4);
        }

        .product-card-image {
            width: 100%;
            height: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
            background: rgba(26, 26, 26, 0.5);
            border-radius: 15px;
            padding: 20px;
        }

        .product-card-image img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
        }

        .product-card h3 {
            font-size: 24px;
            color: #ffffff;
            margin-bottom: 15px;
        }

        .product-card-price {
            font-size: 28px;
            color: #ff6b35;
            font-weight: bold;
            margin-bottom: 15px;
        }

        .product-card-description {
            color: #b0b0b0;
            font-size: 14px;
            line-height: 1.6;
            margin-bottom: 20px;
            display: -webkit-box;
            -webkit-line-clamp: 3;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }

        .product-card-button {
            padding: 12px 35px;
            background: #ff6b35;
            color: white;
            border: none;
            border-radius: 50px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
        }

        .product-card-button:hover {
            background: #ff8555;
            transform: scale(1.05);
        }

        /* Checkout Page */
        .checkout-page {
            padding: 120px 50px 50px;
            min-height: 100vh;
        }

        .checkout-container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .checkout-container h1 {
            font-size: 42px;
            color: #ff6b35;
            margin-bottom: 40px;
        }

        .basket-items {
            background: #2a2a2a;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
        }

        .basket-item {
            display: grid;
            grid-template-columns: 100px 1fr auto auto;
            gap: 20px;
            padding: 20px;
            background: #1a1a1a;
            border-radius: 10px;
            margin-bottom: 15px;
            align-items: center;
        }

        .basket-item-image {
            width: 100px;
            height: 100px;
            background: #3a3a3a;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }

        .basket-item-image img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
        }

        .basket-item-details h3 {
            color: #ffffff;
            margin-bottom: 10px;
        }

        .basket-item-color {
            display: flex;
            align-items: center;
            gap: 10px;
            color: #b0b0b0;
        }

        .basket-item-color-circle {
            width: 20px;
            height: 20px;
            border-radius: 50%;
            border: 2px solid #4a4a4a;
        }

        .basket-item-price {
            font-size: 24px;
            color: #ff6b35;
            font-weight: bold;
        }

        .remove-item-btn {
            padding: 10px 20px;
            background: #4a4a4a;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .remove-item-btn:hover {
            background: #ff6b35;
        }

        .empty-basket {
            text-align: center;
            padding: 60px;
            color: #b0b0b0;
        }

        .basket-summary {
            background: #2a2a2a;
            border-radius: 15px;
            padding: 30px;
        }

        .summary-row {
            display: flex;
            justify-content: space-between;
            padding: 15px 0;
            border-bottom: 1px solid #3a3a3a;
        }

        .summary-row.total {
            border-bottom: none;
            font-size: 24px;
            font-weight: bold;
            color: #ff6b35;
            margin-top: 15px;
        }

        .checkout-button {
            width: 100%;
            padding: 18px;
            background: #ff6b35;
            color: white;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            margin-top: 20px;
            transition: all 0.3s;
        }

        .checkout-button:hover {
            background: #ff8555;
            transform: translateY(-3px);
        }

        footer {
            background: #1a1a1a;
            padding: 40px 50px;
            text-align: center;
            color: #b0b0b0;
            border-top: 2px solid #ff6b35;
        }

        @media (max-width: 1200px) {
            .product-container {
                grid-template-columns: 1fr;
            }
            
            .specs-sidebar {
                flex-direction: row;
                flex-wrap: wrap;
            }
            
            .spec-section {
                flex: 1;
                min-width: 200px;
            }
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 42px;
            }

            .carousel-item.center {
                width: 300px;
                height: 300px;
            }

            .carousel-item.side {
                width: 100px;
                height: 100px;
            }

            .basket-item {
                grid-template-columns: 80px 1fr;
                gap: 15px;
            }

            .basket-item-price,
            .remove-item-btn {
                grid-column: 2;
            }

            .all-products-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo" onclick="showPage('home')">CLIPR</div>
        <nav>
            <a href="#" onclick="showPage('home')">Home</a>
            <a href="#features">Features</a>
            <div class="nav-dropdown">
                <a href="#" onclick="event.preventDefault()">Shop</a>
                <div class="dropdown-content">
                    <a href="#products">Best Sellers</a>
                    <a href="#" onclick="showPage('allProducts'); return false;">All Products</a>
                </div>
            </div>
            <div class="basket-icon" onclick="showPage('checkout')">
                🛒
                <span class="basket-count" id="basketCount">0</span>
            </div>
        </nav>
    </header>

    <!-- HOME PAGE -->
    <div id="homePage" class="page active">
        <section class="hero" id="home">
            <div class="hero-content">
                <h1>The Ultimate <span>Multi-Tool</span></h1>
                <p>Engineered for adventure. Built to last.</p>
                <a href="#features" class="cta-button">Discover More</a>
            </div>
        </section>

        <section class="features" id="features">
            <h2>Why Choose <span>CLIPR?</span></h2>
            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">🔧</div>
                    <h3>Multi-Functional</h3>
                    <p>Combines essential tools in one compact design for maximum versatility on the go.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">💪</div>
                    <h3>Durable Build</h3>
                    <p>Premium materials engineered to withstand extreme conditions and heavy use.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">⚡</div>
                    <h3>Lightweight</h3>
                    <p>Compact and portable design that won't weigh you down during any adventure.</p>
                </div>
            </div>
        </section>

        <section class="showcase" id="products">
            <h2>Best <span>Sellers</span></h2>
            <p style="color: #b0b0b0; font-size: 18px; margin-bottom: 20px;">Shop the products everyone can't get enough of</p>
            <div class="carousel-container">
                <button class="carousel-arrow left" onclick="moveCarousel(-1)">‹</button>
                <button class="carousel-arrow right" onclick="moveCarousel(1)">›</button>
                <div class="carousel-wrapper">
                    <div class="carousel" id="carousel"></div>
                </div>
            </div>
        </section>

        <footer id="contact">
            <p>CLIPR</p>
            <p style="margin-top: 10px; color: #ff6b35;">Multi-Clip Carabiner Multi-Tool</p>
        </footer>
    </div>

    <!-- PRODUCT PAGES -->
    <div id="productPage" class="page product-page"></div>

    <!-- ALL PRODUCTS PAGE -->
    <div id="allProductsPage" class="page all-products-page">
        <button class="back-button" onclick="showPage('home')">← Back to Home</button>
        <div class="all-products-container">
            <h1>All Products</h1>
            <p>Explore our complete collection of multi-tool carabiners</p>
            <div class="all-products-grid" id="allProductsGrid"></div>
        </div>
    </div>

    <!-- CHECKOUT PAGE -->
    <div id="checkoutPage" class="page checkout-page">
        <button class="back-button" onclick="showPage('home')">← Back to Shop</button>
        <div class="checkout-container">
            <h1>Your Basket</h1>
            <div class="basket-items" id="basketItems"></div>
            <div class="basket-summary" id="basketSummary"></div>
        </div>
    </div>

    <script>
        const products = [
            {
                id: 1,
                name: 'CLIPR1',
                price: 25.00,
                description: 'Our best seller and latest carabina the CLIPR1 is the first stepping stone you need to an easier day to day life.',
                colors: [
                    { name: 'Midnight Black', hex: '#1a1a1a', image: 'topdown.png' },
                    { name: 'Steel Blue', hex: '#4a7c9e', image: 'topdown.png' },
                    { name: 'Forest Green', hex: '#2d5016', image: 'topdown.png' }
                ],
                specs: {
                    materials: ['Aircraft-grade aluminum', 'Stainless steel components', 'Anodized finish'],
                    dimensions: ['Length: 3.5 inches', 'Width: 1.8 inches', 'Weight: 2.1 oz'],
                    features: ['Bottle opener', '4mm-10mm hex wrench set', 'Phillips/flathead screwdriver', 'Key ring attachment', 'Carabiner gate (not for climbing)']
                }
            },
            {
                id: 2,
                name: 'CLIPR-DUAL',
                price: 34.99,
                description: 'The CLIPR-DUAL contains our original CLIPR1 as well as a second set of tools of you choosing.',
                colors: [
                    { name: 'Matte Black', hex: '#2a2a2a', image: 'Doublesell.png' },
                    { name: 'Titanium Gray', hex: '#6a6a6a', image: 'Doublesell.png' },
                    { name: 'Copper Bronze', hex: '#b87333', image: 'Doublesell.png' }
                ],
                specs: {
                    materials: ['Titanium-coated steel', 'Ceramic blade insert', 'Powder-coated finish'],
                    dimensions: ['Length: 2.8 inches', 'Width: 1.2 inches', 'Weight: 1.3 oz'],
                    features: ['Integrated box cutter', 'Bottle opener', 'Metric hex keys (3mm-8mm)', 'Phone stand', 'Compact carabiner clip']
                }
            },
            {
                id: 3,
                name: 'CLIPR-ADD1',
                price: 12.99,
                description: 'The CLIPR-ADD1, is the primary add-on for any clipr user. Showcasing all of your basic tools for daily use, choose from a selection of colours to mix and match with your CLIPR1.',
                colors: [
                    { name: 'Metallic Blue', hex: '#0f4560', image: 'bluetool.png' },
                    { name: 'Metallic Orange', hex: '#754200', image: 'orangetool.png' },
                    { name: 'Metallic Purple', hex: '#4d325c', image: 'purpletool.png' }
                ],
                specs: {
                    materials: ['Aerospace Grade Aluminium', 'Recycled Rubber'],
                    dimensions: ['Length: 4.2 inches', 'Width: 2.1 inches', 'Weight: 3.2 oz'],
                    features: ['Fire starter rod', 'Emergency whistle', 'Integrated compass', 'Bottle opener', 'Hex wrench set', 'Wire stripper', 'Ruler markings', 'Glass breaker tip']
                }
            },
            {
                id: 4,
                name: 'CLIPR2',
                price: 25.00,
                description: 'The CLIPR2 offers a differnt look if thats what your about still offering the same multi-tool system that the CLIPR1 has.',
                colors: [
                    { name: 'Metallic Blue', hex: '#0f4560', image: 'bluecar.png' },
                    { name: 'Metallic Orange', hex: '#754200', image: 'orangecar.png' },
                    { name: 'Metallic purple', hex: '#4d325c', image: 'purplecar.png' }
                ],
                specs: {
                    materials: ['Hardened steel', 'Rubber grip coating', 'Rustproof finish'],
                    dimensions: ['Length: 2.3 inches', 'Width: 1.0 inches', 'Weight: 0.9 oz'],
                    features: ['Bottle opener', 'Screwdriver bits (Phillips/flat)', 'Key ring loop', 'Lightweight carabiner', 'Measurement markings']
                }
            },
            {
                id: 5,
                name: 'CLIPR5',
                price: 89.99,
                description: 'Our most advanced multi-tool yet. Crafted from aerospace titanium, this lightweight marvel includes 12 precision tools, a magnetic bit holder, and a lifetime guarantee. The ultimate statement piece for tool enthusiasts.',
                colors: [
                    { name: 'Raw Titanium', hex: '#8a8d8f', image: 'carab5.png' },
                    { name: 'Anodized Blue', hex: '#4169e1', image: 'carab5.png' },
                    { name: 'Gold PVD', hex: '#d4af37', image: 'carab5.png' }
                ],
                specs: {
                    materials: ['Grade 5 titanium alloy', 'Magnetic N52 neodymium', 'Sapphire crystal accents'],
                    dimensions: ['Length: 3.8 inches', 'Width: 1.9 inches', 'Weight: 1.8 oz'],
                    features: ['Magnetic bit holder', 'Bottle opener', 'Pry bar', 'Hex wrench set', 'Screwdriver bits', 'Wire stripper', 'Ruler markings', 'Lifetime warranty', 'Premium carrying case']
                }
            }
        ];

        let basket = [];
        let currentCarouselIndex = 2;

        function createCarousel() {
            const carousel = document.getElementById('carousel');
            carousel.innerHTML = '';
            
            products.forEach((product, i) => {
                const item = document.createElement('div');
                item.className = 'carousel-item';
                
                const img = document.createElement('img');
                img.src = product.colors[0].image;
                img.alt = product.name;
                
                const overlay = document.createElement('div');
                overlay.className = 'buy-button-overlay';
                overlay.innerHTML = `<button onclick="showProduct(${product.id})">BUY NOW</button>`;
                
                item.appendChild(img);
                item.appendChild(overlay);
                carousel.appendChild(item);
            });
            
            updateCarousel();
        }

        function updateCarousel() {
            const items = document.querySelectorAll('.carousel-item');
            
            items.forEach((item, index) => {
                item.classList.remove('center', 'side', 'hidden');
                
                if (index === currentCarouselIndex) {
                    item.classList.add('center');
                } else if (index === currentCarouselIndex - 1 || index === currentCarouselIndex + 1) {
                    item.classList.add('side');
                } else {
                    item.classList.add('hidden');
                }
            });
        }

        function moveCarousel(direction) {
            currentCarouselIndex += direction;
            if (currentCarouselIndex < 0) currentCarouselIndex = products.length - 1;
            if (currentCarouselIndex >= products.length) currentCarouselIndex = 0;
            updateCarousel();
        }

        function showPage(pageName) {
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });
            
            if (pageName === 'home') {
                document.getElementById('homePage').classList.add('active');
            } else if (pageName === 'checkout') {
                document.getElementById('checkoutPage').classList.add('active');
                renderCheckout();
            } else if (pageName === 'allProducts') {
                document.getElementById('allProductsPage').classList.add('active');
                renderAllProducts();
            }
        }

        function showProduct(productId) {
            const product = products.find(p => p.id === productId);
            if (!product) return;
            
            const productPage = document.getElementById('productPage');
            productPage.innerHTML = `
                <button class="back-button" onclick="showPage('home')">← Back to Shop</button>
                <div class="product-container">
                    <div class="product-image-section">
                        <img id="productImage" src="${product.colors[0].image}" alt="${product.name}">
                    </div>
                    
                    <div class="product-details">
                        <h1>${product.name}</h1>
                        <div class="product-price">${product.price}</div>
                        <div class="product-description">${product.description}</div>
                        
                        <div class="color-selector">
                            <h3>Select Color:</h3>
                            <div class="color-options" id="colorOptions">
                                ${product.colors.map((color, i) => `
                                    <div class="color-option ${i === 0 ? 'selected' : ''}" 
                                         style="background: ${color.hex}"
                                         data-color-index="${i}"
                                         onclick="selectColor(${productId}, ${i})"
                                         title="${color.name}">
                                    </div>
                                `).join('')}
                            </div>
                        </div>
                        
                        <button class="add-to-basket-btn" onclick="addToBasket(${productId})">
                            Add to Basket
                        </button>
                    </div>
                    
                    <div class="specs-sidebar">
                        <div class="spec-section" onclick="toggleSpec(this)">
                            <div class="spec-header">
                                <h3>Materials</h3>
                                <span class="spec-arrow">▼</span>
                            </div>
                            <div class="spec-content">
                                <div class="spec-content-inner">
                                    <ul>
                                        ${product.specs.materials.map(m => `<li>${m}</li>`).join('')}
                                    </ul>
                                </div>
                            </div>
                        </div>
                        
                        <div class="spec-section" onclick="toggleSpec(this)">
                            <div class="spec-header">
                                <h3>Dimensions</h3>
                                <span class="spec-arrow">▼</span>
                            </div>
                            <div class="spec-content">
                                <div class="spec-content-inner">
                                    <ul>
                                        ${product.specs.dimensions.map(d => `<li>${d}</li>`).join('')}
                                    </ul>
                                </div>
                            </div>
                        </div>
                        
                        <div class="spec-section" onclick="toggleSpec(this)">
                            <div class="spec-header">
                                <h3>Features</h3>
                                <span class="spec-arrow">▼</span>
                            </div>
                            <div class="spec-content">
                                <div class="spec-content-inner">
                                    <ul>
                                        ${product.specs.features.map(f => `<li>${f}</li>`).join('')}
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            `;
            
            showPage('product');
            document.getElementById('productPage').classList.add('active');
        }

        let selectedColorIndex = 0;

        function selectColor(productId, colorIndex) {
            const product = products.find(p => p.id === productId);
            selectedColorIndex = colorIndex;
            
            document.getElementById('productImage').src = product.colors[colorIndex].image;
            
            document.querySelectorAll('.color-option').forEach((opt, i) => {
                opt.classList.toggle('selected', i === colorIndex);
            });
        }

        function toggleSpec(element) {
            element.classList.toggle('open');
        }

        function addToBasket(productId) {
            const product = products.find(p => p.id === productId);
            const selectedColor = product.colors[selectedColorIndex];
            
            basket.push({
                product: product,
                color: selectedColor
            });
            
            updateBasketCount();
            alert(`${product.name} (${selectedColor.name}) added to basket!`);
        }

        function updateBasketCount() {
            document.getElementById('basketCount').textContent = basket.length;
        }

        function renderCheckout() {
            const basketItems = document.getElementById('basketItems');
            const basketSummary = document.getElementById('basketSummary');
            
            if (basket.length === 0) {
                basketItems.innerHTML = '<div class="empty-basket"><h2>Your basket is empty</h2><p>Add some items to get started!</p></div>';
                basketSummary.innerHTML = '';
                return;
            }
            
            basketItems.innerHTML = basket.map((item, index) => `
                <div class="basket-item">
                    <div class="basket-item-image">
                        <img src="${item.color.image}" alt="${item.product.name}">
                    </div>
                    <div class="basket-item-details">
                        <h3>${item.product.name}</h3>
                        <div class="basket-item-color">
                            <span>Color:</span>
                            <div class="basket-item-color-circle" style="background: ${item.color.hex}"></div>
                            <span>${item.color.name}</span>
                        </div>
                    </div>
                    <div class="basket-item-price">${item.product.price}</div>
                    <button class="remove-item-btn" onclick="removeFromBasket(${index})">Remove</button>
                </div>
            `).join('');
            
            const subtotal = basket.reduce((sum, item) => sum + item.product.price, 0);
            const tax = subtotal * 0.1;
            const total = subtotal + tax;
            
            basketSummary.innerHTML = `
                <div class="summary-row">
                    <span>Subtotal:</span>
                    <span>${subtotal.toFixed(2)}</span>
                </div>
                <div class="summary-row">
                    <span>Tax (10%):</span>
                    <span>${tax.toFixed(2)}</span>
                </div>
                <div class="summary-row total">
                    <span>Total:</span>
                    <span>${total.toFixed(2)}</span>
                </div>
                <button class="checkout-button" onclick="processCheckout()">Proceed to Checkout</button>
            `;
        }

        function removeFromBasket(index) {
            basket.splice(index, 1);
            updateBasketCount();
            renderCheckout();
        }

        function processCheckout() {
            alert('Thank you for your order! This would normally process payment.');
            basket = [];
            updateBasketCount();
            showPage('home');
        }

        function renderAllProducts() {
            const grid = document.getElementById('allProductsGrid');
            grid.innerHTML = products.map(product => `
                <div class="product-card" onclick="showProduct(${product.id})">
                    <div class="product-card-image">
                        <img src="${product.colors[0].image}" alt="${product.name}">
                    </div>
                    <h3>${product.name}</h3>
                    <div class="product-card-price">${product.price}</div>
                    <div class="product-card-description">${product.description}</div>
                    <button class="product-card-button" onclick="event.stopPropagation(); showProduct(${product.id})">
                        View Details
                    </button>
                </div>
            `).join('');
        }

        window.onload = function() {
            createCarousel();
        };
    </script>
</body>
</html>…]()
