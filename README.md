
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Green Earth | Environmental Awareness</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #f5f8f2;
            color: #26382b;
            line-height: 1.6;
        }

        header {
            background: #123d2b;
            color: white;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        .logo {
            font-size: 25px;
            font-weight: bold;
        }

        .logo span {
            color: #a8dc76;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
            font-weight: bold;
        }

        nav a:hover {
            color: #a8dc76;
        }

        .hero {
            min-height: 550px;
            display: flex;
            align-items: center;
            padding: 70px 10%;
            color: white;
            background:
                linear-gradient(rgba(5, 35, 20, 0.65),
                rgba(5, 35, 20, 0.65)),
                url("https://images.unsplash.com/photo-1441974231531-c6227db76b6e")
                center/cover no-repeat;
        }

        .hero-content {
            max-width: 650px;
        }

        .hero h1 {
            font-size: 55px;
            line-height: 1.15;
            margin-bottom: 20px;
        }

        .hero h1 span {
            color: #b5ed83;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background: #a8dc76;
            color: #173b27;
            padding: 13px 25px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: white;
            transform: translateY(-3px);
        }

        section {
            padding: 75px 10%;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
        }

        .section-title h2 {
            color: #205b39;
            font-size: 34px;
            margin-bottom: 10px;
        }

        .section-title p {
            color: #68766a;
        }

        .about {
            display: flex;
            align-items: center;
            gap: 45px;
            flex-wrap: wrap;
        }

        .about-image {
            flex: 1 1 300px;
        }

        .about-image img {
            width: 100%;
            height: 330px;
            object-fit: cover;
            border-radius: 15px;
        }

        .about-text {
            flex: 1 1 300px;
        }

        .about-text h2 {
            color: #205b39;
            font-size: 32px;
            margin-bottom: 15px;
        }

        .about-text p {
            margin-bottom: 15px;
            color: #58665b;
        }

        .issues {
            background: #eaf2e5;
        }

        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 25px;
        }

        .card {
            background: white;
            border-radius: 14px;
            overflow: hidden;
            box-shadow: 0 5px 18px rgba(0,0,0,0.07);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-7px);
        }

        .card img {
            width: 100%;
            height: 190px;
            object-fit: cover;
        }

        .card-content {
            padding: 22px;
        }

        .card-content h3 {
            color: #28613d;
            margin-bottom: 10px;
        }

        .card-content p {
            color: #667168;
            font-size: 14px;
        }

        .tips {
            background: #17452f;
            color: white;
        }

        .tips .section-title h2 {
            color: #b5ed83;
        }

        .tips .section-title p {
            color: #d5e4d6;
        }

        .tip-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .tip {
            background: rgba(255,255,255,0.09);
            padding: 25px;
            border-radius: 12px;
            text-align: center;
        }

        .tip .icon {
            font-size: 40px;
            margin-bottom: 12px;
        }

        .tip h3 {
            color: #b5ed83;
            margin-bottom: 10px;
        }

        .call-to-action {
            text-align: center;
            background: #dceccf;
        }

        .call-to-action h2 {
            color: #205b39;
            font-size: 32px;
            margin-bottom: 15px;
        }

        .call-to-action p {
            max-width: 650px;
            margin: 0 auto 25px;
            color: #58665b;
        }

        footer {
            background: #102f21;
            color: white;
            text-align: center;
            padding: 25px;
        }

        footer span {
            color: #a8dc76;
        }

        @media (max-width: 700px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav {
                text-align: center;
            }

            nav a {
                display: inline-block;
                margin: 5px 8px;
            }

            .hero {
                min-height: 450px;
                padding: 60px 7%;
            }

            .hero h1 {
                font-size: 39px;
            }

            section {
                padding: 55px 7%;
            }
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <div class="logo">🌿 GREEN<span>EARTH</span></div>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#issues">Environmental Issues</a>
            <a href="#tips">Take Action</a>
        </nav>
    </header>

    <!-- HOME SECTION -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Protect Nature, <span>Protect Our Future.</span></h1>

            <p>
                A healthy planet starts with responsible choices.
                Together, we can reduce pollution, protect wildlife,
                and create a cleaner and greener environment.
            </p>

            <a href="#about" class="btn">Explore More</a>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about">
        <div class="about">
            <div class="about-image">
                <img
                    src="https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05"
                    alt="Beautiful green mountain landscape">
            </div>

            <div class="about-text">
                <h2>Why Environmental Awareness Matters</h2>

                <p>
                    Environmental awareness helps people understand
                    the importance of protecting our natural resources.
                    It teaches us how our daily activities affect the
                    environment.
                </p>

                <p>
                    By practicing sustainability, reducing waste,
                    conserving water, and planting trees, we can help
                    build a healthier world for future generations.
                </p>

                <a href="#tips" class="btn">Learn How to Help</a>
            </div>
        </div>
    </section>

    <!-- ENVIRONMENTAL ISSUES -->
    <section class="issues" id="issues">
        <div class="section-title">
            <h2>Environmental Issues</h2>
            <p>Understand the problems that affect our planet.</p>
        </div>

        <div class="card-container">

            <div class="card">
                <img
                    src="https://images.unsplash.com/photo-1532601224476-15c79f2f7a51"
                    alt="Air pollution from industrial activities">

                <div class="card-content">
                    <h3>Air Pollution</h3>
                    <p>
                        Smoke from vehicles and factories can pollute
                        the air and affect human health and the environment.
                    </p>
                </div>
            </div>

            <div class="card">
                <img
                    src="https://images.unsplash.com/photo-1530053969600-caed2596d242"
                    alt="Plastic waste and water pollution">

                <div class="card-content">
                    <h3>Water Pollution</h3>
                    <p>
                        Improper waste disposal and chemicals can
                        contaminate rivers, oceans, and other water sources.
                    </p>
                </div>
            </div>

            <div class="card">
                <img
                    src="https://images.unsplash.com/photo-1448375240586-882707db888b"
                    alt="Forest trees">

                <div class="card-content">
                    <h3>Deforestation</h3>
                    <p>
                        Cutting down too many trees destroys habitats,
                        reduces forest cover, and harms wildlife.
                    </p>
                </div>
            </div>

            <div class="card">
                <img
                    src="https://images.unsplash.com/photo-1473448912268-2022ce9509d8"
                    alt="Green forest affected by environmental changes">

                <div class="card-content">
                    <h3>Climate Change</h3>
                    <p>
                        Rising global temperatures affect weather
                        patterns, ecosystems, and communities.
                    </p>
                </div>
            </div>

        </div>
    </section>

    <!-- ACTION TIPS -->
    <section class="tips" id="tips">
        <div class="section-title">
            <h2>Small Actions, Big Impact</h2>
            <p>Simple ways to help protect our environment every day.</p>
        </div>

        <div class="tip-grid">

            <div class="tip">
                <div class="icon">♻️</div>
                <h3>Recycle</h3>
                <p>Separate recyclable materials and reuse items whenever possible.</p>
            </div>

            <div class="tip">
                <div class="icon">🌳</div>
                <h3>Plant Trees</h3>
                <p>Help restore green spaces and protect natural habitats.</p>
            </div>

            <div class="tip">
                <div class="icon">💧</div>
                <h3>Save Water</h3>
                <p>Turn off taps when not in use and avoid wasting clean water.</p>
            </div>

            <div class="tip">
                <div class="icon">💡</div>
                <h3>Save Energy</h3>
                <p>Switch off lights and appliances when they are not needed.</p>
            </div>

        </div>
    </section>

    <!-- CALL TO ACTION -->
    <section class="call-to-action">
        <h2>Be Part of the Change!</h2>

        <p>
            Protecting the environment is everyone's responsibility.
            Start with small actions today and encourage others to
            make sustainable choices. Together, we can make a difference.
        </p>

        <a href="#home" class="btn">Go Back to Top ↑</a>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>🌿 <span>GREEN EARTH</span> | Environmental Awareness</p>
        <p>Protect Nature. Preserve Life. Secure the Future.</p>
        <p>&copy; 2026 Green Earth. All Rights Reserved.</p>
    </footer>

</body>
</html>
