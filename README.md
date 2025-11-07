# Clipr
Carabiner multi tool
[index.html.html](https://github.com/user-attachments/files/23422482/index.html.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Tool Carabiner</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: #1a1a1a;
            color: #ffffff;
            overflow-x: hidden;
        }<img width="1479" height="960" alt="Adobe Express - file (9)" src="https://github.com/user-attachments/assets/849a112b-4de7-4c6d-b71c-74862f4385e8" />


        header {
            position: fixed;
            width: 100%;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            background: rgba(26, 26, 26, 0.95);
            backdrop-filter: blur(10px);
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ff6b35;
        }

        nav a {
            color: #ffffff;
            text-decoration: none;
            margin-left: 30px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ff6b35;
        }

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
        }

        .cta-button:hover {
            background: #ff8555;
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(255, 107, 53, 0.4);
        }

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

        .product-display {
            max-width: 800px;
            height: 500px;
            margin: 50px auto;
            background: linear-gradient(135deg, #3a3a3a 0%, #2a2a2a 100%);
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 3px solid #ff6b35;
            font-size: 24px;
            color: #b0b0b0;
        }

        footer {
            background: #1a1a1a;
            padding: 40px 50px;
            text-align: center;
            color: #b0b0b0;
            border-top: 2px solid #ff6b35;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 42px;
            }

            .hero p {
                font-size: 18px;
            }

            header {
                padding: 20px 30px;
            }

            nav a {
                margin-left: 15px;
                font-size: 14px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">CLIPR</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#features">Features</a>
            <a href="#products">Products</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

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

    <section class="showcase" id="#design">
        <h2>Innovative <span>Design</span></h2>
        <p style="color: #b0b0b0; font-size: 18px; margin-bottom: 20px;">Form meets function in perfect harmony</p>
        <div class="product-display">
            <img src="Adobe Express - file (9).png" alt="Carabiner Multi-Tool" style="max-width: 90%; max-height: 90%; object-fit: contain; border-radius: 10px;">
        </div>
    </section>

    <footer id="contact">
        <p>CLIPR</p>
        <p style="margin-top: 10px; color: #ff6b35;">Multi-Clip Carabiner Multi-Tool</p>
    </footer>
</body>
</html>
