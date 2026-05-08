# WorldEats_Public
<a href="https://edenchisvo.github.io/WorldEats_Public/PrivacyPolicy.md">Privacy Policy</a> <strong>|</strong>
<a href="https://edenchisvo.github.io/WorldEats_Public/TermsOfService.md">Terms Of Service</a> <strong>|</strong>
<a href="https://edenchisvo.github.io/WorldEats_Public/DataDeletion.md">Data Deletion Process</a>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WorldEats | Every Cuisine. Every Culture.</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #FF9A00; /* Saffron */
            --secondary: #CC5500; /* Terracotta */
            --dark: #1A0A00;
            --light: #FFF8F0;
            --gray: #666;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Outfit', sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
        }

        header {
            background: linear-gradient(135deg, var(--dark) 0%, #3d1c0b 100%);
            color: white;
            padding: 100px 20px;
            text-align: center;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .logo {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 10px;
            color: var(--primary);
        }

        .tagline {
            font-size: 1.5rem;
            opacity: 0.9;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: white;
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.3s ease, background 0.3s ease;
        }

        .btn:hover {
            transform: scale(1.05);
            background-color: var(--secondary);
        }

        section {
            padding: 80px 0;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .feature-card {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            text-align: center;
        }

        .feature-icon {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .feature-card h3 {
            margin-bottom: 15px;
            color: var(--secondary);
        }

        .legal-links {
            background-color: #eee;
            padding: 40px 0;
            text-align: center;
        }

        .legal-links a {
            color: var(--gray);
            margin: 0 15px;
            text-decoration: none;
            font-size: 0.9rem;
        }

        footer {
            background-color: var(--dark);
            color: rgba(255,255,255,0.6);
            padding: 40px 0;
            text-align: center;
            font-size: 0.8rem;
        }

        .mockup {
            max-width: 300px;
            margin: 50px auto 0;
            border: 10px solid #333;
            border-radius: 40px;
            background: #000;
            aspect-ratio: 9/19;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #333;
        }
        .rounded {
        border-radius: 20px;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="logo">WorldEats</div>
            <p class="tagline">Every Cuisine. Every Culture. Right in your pocket.</p>
            <a href="#" class="btn">Available on Google Play</a>

            <div class="mockup">
                <!-- Replace with an actual screenshot later -->
                <span><img src="Screenshot_20260508_145911.png" width="275" height="650" class="rounded"></span>
            </div>
        </div>
    </header>

    <section class="container">
        <h2 style="text-align: center; margin-bottom: 50px;">Why WorldEats?</h2>
        <div class="features">
            <div class="feature-card">
                <div class="feature-icon">🔍</div>
                <h3>AI Pantry Scanner</h3>
                <p>Don't know what to cook? Snap a photo of your ingredients and let our AI suggest the perfect global recipe.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🎙️</div>
                <h3>Hands-Free Cooking</h3>
                <p>Messy hands? No problem. Use voice commands to navigate steps, repeat instructions, or set timers without touching your screen.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🌍</div>
                <h3>Global Flavors</h3>
                <p>Explore thousands of authentic recipes from every corner of the world. Filter by diet, mood, or occasion.</p>
            </div>
        </div>
    </section>

    <div class="legal-links">
        <div class="container">
            <a href="https://edenchisvo.github.io/WorldEats_Public/PrivacyPolicy.md">Privacy Policy</a>
            <a href="https://edenchisvo.github.io/WorldEats_Public/TermsOfService.md">Terms of Service</a>
            <a href="https://edenchisvo.github.io/WorldEats_Public/DataDeletion.md">Data Deletion</a>
        </div>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2023 WorldEats. All rights reserved.</p>
            <p>Designed for foodies, by foodies.</p>
        </div>
    </footer>

</body>
</html>
