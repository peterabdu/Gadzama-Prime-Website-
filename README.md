<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Gadzama Prime Digital World Limited | ICT, Digital Services & General Supplies</title>

<meta name="description" content="Gadzama Prime Digital World Limited provides ICT services, computer training, printing, photocopying, graphic design, procurement and general supplies in Karu Village, FCT Abuja, Nigeria.">

<meta name="keywords" content="Gadzama Prime Digital World Limited, ICT services Abuja, printing Karu, graphic design Abuja, computer training, general supplies, procurement Nigeria">

<meta name="author" content="Gadzama Prime Digital World Limited">

<meta name="theme-color" content="#071b3b">

<style>
        /* =========================
           GENERAL SETTINGS
        ========================== */

        :root {
            --primary: #071b3b;
            --secondary: #0b3673;
            --accent: #f4b400;
            --light: #f5f8fc;
            --white: #ffffff;
            --text: #273449;
            --muted: #64748b;
            --border: #e2e8f0;
            --shadow: 0 10px 30px rgba(7, 27, 59, 0.09);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            scroll-padding-top: 85px;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            color: var(--text);
            background: var(--white);
            line-height: 1.7;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        img {
            max-width: 100%;
            display: block;
        }

        button,
        input,
        textarea,
        select {
            font: inherit;
        }

        button,
        a {
            -webkit-tap-highlight-color: transparent;
        }

        .container {
            width: min(1140px, 92%);
            margin: auto;
        }

        .section {
            padding: 85px 0;
        }

        .section-heading {
            text-align: center;
            margin-bottom: 45px;
        }

        .section-heading .tag {
            color: var(--secondary);
            font-weight: 700;
            text-transform: uppercase;
            font-size: 13px;
            letter-spacing: 2px;
        }

        .section-heading h2 {
            color: var(--primary);
            font-size: clamp(28px, 4vw, 40px);
            line-height: 1.25;
            margin: 10px 0;
        }

        .section-heading p {
            max-width: 680px;
            margin: auto;
            color: var(--muted);
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            padding: 13px 22px;
            border-radius: 6px;
            font-weight: 700;
            border: 2px solid transparent;
            cursor: pointer;
            transition: 0.25s ease;
        }

        .btn-primary {
            background: var(--accent);
            color: var(--primary);
        }

        .btn-primary:hover {
            background: #ffd04a;
            transform: translateY(-2px);
        }

        .btn-outline {
            color: var(--white);
            border-color: rgba(255, 255, 255, 0.75);
        }

        .btn-outline:hover {
            background: var(--white);
            color: var(--primary);
        }

        /* =========================
           HEADER AND NAVIGATION
        ========================== */

        header {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: var(--white);
            box-shadow: 0 3px 18px rgba(0, 0, 0, 0.06);
        }

        .navbar {
            min-height: 78px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 20px;
        }

        .brand {
            display: flex;
            align-items: center;
            gap: 12px;
            min-width: 0;
        }

        .brand-logo {
            width: 49px;
            height: 49px;
            border-radius: 10px;
            background: var(--primary);
            color: var(--accent);
            display: grid;
            place-items: center;
            font-size: 19px;
            font-weight: 900;
            flex-shrink: 0;
            border: 2px solid var(--accent);
        }

        .brand-text {
            color: var(--primary);
            font-weight: 800;
            font-size: 14px;
            line-height: 1.3;
        }

        .brand-text small {
            display: block;
            font-size: 10px;
            font-weight: 600;
            color: var(--secondary);
            letter-spacing: 1px;
            margin-top: 4px;
        }

        .nav-links {
            display: flex;
            align-items: center;
            gap: 23px;
            list-style: none;
        }

        .nav-links a {
            font-size: 13px;
            font-weight: 700;
            color: var(--primary);
        }

        .nav-links a:hover,
        .nav-links a.active {
            color: #b78100;
        }

        .nav-cta {
            background: var(--primary);
            color: var(--white) !important;
            padding: 10px 15px;
            border-radius: 5px;
        }

        .menu-toggle {
            display: none;
            border: none;
            background: var(--primary);
            color: var(--white);
            border-radius: 5px;
            width: 43px;
            height: 43px;
            font-size: 25px;
            cursor: pointer;
        }

        /* =========================
           HERO SECTION
        ========================== */

        .hero {
            position: relative;
            overflow: hidden;
            color: var(--white);
            background:
                radial-gradient(circle at 85% 15%, rgba(244, 180, 0, 0.18), transparent 28%),
                linear-gradient(125deg, #06142d, #0b3673 75%, #10488d);
            padding: 105px 0 100px;
        }

        .hero::before {
            content: "";
            position: absolute;
            width: 400px;
            height: 400px;
            border: 1px solid rgba(255, 255, 255, 0.12);
            border-radius: 50%;
            right: -120px;
            bottom: -180px;
        }

        .hero-grid {
            position: relative;
            display: grid;
            grid-template-columns: 1.2fr 0.8fr;
            align-items: center;
            gap: 55px;
        }

        .hero-badge {
            display: inline-block;
            padding: 7px 13px;
            border: 1px solid rgba(255, 255, 255, 0.3);
            border-radius: 50px;
            font-size: 12px;
            color: #ffe18a;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-size: clamp(36px, 5vw, 58px);
            line-height: 1.13;
            margin-bottom: 22px;
        }

        .hero h1 span {
            color: var(--accent);
        }

        .hero p {
            color: #e0eaf8;
            max-width: 610px;
            font-size: 16px;
            margin-bottom: 30px;
        }

        .hero-actions {
            display: flex;
            flex-wrap: wrap;
            gap: 13px;
        }

        .hero-card {
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.18);
            backdrop-filter: blur(10px);
            border-radius: 18px;
            padding: 30px;
        }

        .hero-card h3 {
            font-size: 23px;
            margin-bottom: 20px;
        }

        .hero-feature {
            display: flex;
            gap: 14px;
            align-items: flex-start;
            padding: 14px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.15);
        }

        .hero-feature:last-child {
            border-bottom: none;
        }

        .feature-icon {
            width: 42px;
            height: 42px;
            flex-shrink: 0;
            display: grid;
            place-items: center;
            border-radius: 9px;
            background: rgba(244, 180, 0, 0.16);
            color: var(--accent);
            font-size: 21px;
        }

        .hero-feature strong {
            display: block;
            margin-bottom: 2px;
        }

        .hero-feature small {
            color: #d7e5f7;
        }

        /* =========================
           QUICK CONTACT STRIP
        ========================== */

        .quick-strip {
            background: var(--white);
            box-shadow: var(--shadow);
            position: relative;
            z-index: 2;
        }

        .quick-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            padding: 23px 0;
        }

        .quick-item {
            text-align: center;
            padding: 8px 15px;
            border-right: 1px solid var(--border);
        }

        .quick-item:last-child {
            border-right: none;
        }

        .quick-item strong {
            display: block;
            color: var(--primary);
        }

        .quick-item span {
            color: var(--muted);
            font-size: 13px;
        }

        /* =========================
           ABOUT SECTION
        ========================== */

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 55px;
            align-items: center;
        }

        .about-visual {
            min-height: 380px;
            border-radius: 16px;
            background:
                radial-gradient(circle at 80% 20%, rgba(244, 180, 0, 0.35), transparent 25%),
                linear-gradient(145deg, #0b3673, #071b3b);
            display: grid;
            place-items: center;
            padding: 35px;
            text-align: center;
            color: var(--white);
            position: relative;
            overflow: hidden;
        }

        .about-visual::after {
            content: "";
            position: absolute;
            inset: 18px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 12px;
        }

        .about-monogram {
            position: relative;
            z-index: 1;
        }

        .about-monogram strong {
            display: block;
            font-size: clamp(65px, 9vw, 100px);
            color: var(--accent);
            line-height: 1.1;
        }

        .about-monogram span {
            display: block;
            font-weight: 700;
            letter-spacing: 3px;
            margin-top: 15px;
        }

        .about-content h2 {
            color: var(--primary);
            font-size: 35px;
            line-height: 1.25;
            margin: 12px 0 18px;
        }

        .about-content p {
            color: var(--muted);
            margin-bottom: 15px;
        }

        .check-list {
            list-style: none;
            margin: 20px 0 27px;
        }

        .check-list li {
            margin: 10px 0;
            color: var(--text);
        }

        .check-list li::before {
            content: "✓";
            display: inline-grid;
            place-items: center;
            width: 23px;
            height: 23px;
            background: #e5f5e9;
            color: #16803c;
            border-radius: 50%;
            margin-right: 10px;
            font-weight: 800;
        }

        /* =========================
           SERVICES
        ========================== */

        .services-section {
            background: var(--light);
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 22px;
        }

        .service-card {
            background: var(--white);
            padding: 28px 25px;
            border: 1px solid var(--border);
            border-radius: 12px;
            transition: transform 0.25s, box-shadow 0.25s;
        }

        .service-card:hover {
            transform: translateY(-7px);
            box-shadow: var(--shadow);
        }

        .service-icon {
            width: 57px;
            height: 57px;
            display: grid;
            place-items: center;
            border-radius: 12px;
            background: #eaf1fc;
            font-size: 28px;
            margin-bottom: 19px;
        }

        .service-card h3 {
            color: var(--primary);
            font-size: 19px;
            margin-bottom: 10px;
        }

        .service-card p {
            color: var(--muted);
            font-size: 14px;
            margin-bottom: 18px;
        }

        .service-link {
            font-size: 13px;
            font-weight: 800;
            color: var(--secondary);
        }

        /* =========================
           WHY CHOOSE US
        ========================== */

        .why-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 22px;
        }

        .why-card {
            padding: 24px 18px;
            text-align: center;
            border: 1px solid var(--border);
            border-radius: 10px;
        }

        .why-card .why-icon {
            font-size: 34px;
            margin-bottom: 12px;
        }

        .why-card h3 {
            color: var(--primary);
            font-size: 16px;
            margin-bottom: 8px;
        }

        .why-card p {
            font-size: 13px;
            color: var(--muted);
        }

        /* =========================
           PRODUCTS AND SUPPLIES
        ========================== */

        .supplies-section {
            background: var(--light);
        }

        .supplies-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 22px;
        }

        .supply-card {
            background: var(--white);
            border: 1px solid var(--border);
            padding: 25px;
            border-radius: 12px;
        }

        .supply-card h3 {
            color: var(--primary);
            margin: 12px 0 8px;
        }

        .supply-card p {
            color: var(--muted);
            font-size: 14px;
        }

        .supply-icon {
            font-size: 38px;
        }

        /* =========================
           CALL TO ACTION
        ========================== */

        .cta-section {
            background: linear-gradient(120deg, var(--primary), var(--secondary));
            color: var(--white);
            text-align: center;
            padding: 75px 0;
        }

        .cta-section h2 {
            font-size: clamp(28px, 4vw, 40px);
            margin-bottom: 15px;
        }

        .cta-section p {
            max-width: 650px;
            margin: 0 auto 25px;
            color: #dbe7f7;
        }

        /* =========================
           CONTACT SECTION
        ========================== */

        .contact-grid {
            display: grid;
            grid-template-columns: 0.9fr 1.1fr;
            gap: 40px;
        }

        .contact-info {
            background: var(--primary);
            color: var(--white);
            padding: 32px;
            border-radius: 13px;
        }

        .contact-info h3 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .contact-info > p {
            color: #dbe7f7;
            margin-bottom: 25px;
        }

        .contact-detail {
            display: flex;
            gap: 14px;
            align-items: flex-start;
            margin: 20px 0;
        }

        .contact-detail .detail-icon {
            font-size: 22px;
            flex-shrink: 0;
        }

        .contact-detail strong {
            display: block;
            margin-bottom: 4px;
        }

        .contact-detail p,
        .contact-detail a {
            color: #dbe7f7;
            font-size: 14px;
            overflow-wrap: anywhere;
        }

        .contact-detail a:hover {
            color: var(--accent);
        }

        .contact-form {
            padding: 32px;
            background: var(--white);
            border: 1px solid var(--border);
            border-radius: 13px;
            box-shadow: var(--shadow);
        }

        .contact-form h3 {
            color: var(--primary);
            font-size: 24px;
            margin-bottom: 7px;
        }

        .contact-form > p {
            color: var(--muted);
            margin-bottom: 22px;
            font-size: 14px;
        }

        .form-group {
            margin-bottom: 17px;
        }

        .form-group label {
            display: block;
            font-size: 13px;
            font-weight: 700;
            margin-bottom: 7px;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 12px 14px;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            outline: none;
            background: var(--white);
            color: var(--text);
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            border-color: var(--secondary);
            box-shadow: 0 0 0 3px rgba(11, 54, 115, 0.1);
        }

        .form-group textarea {
            min-height: 125px;
            resize: vertical;
        }

        .contact-form .btn {
            width: 100%;
        }

        .form-note {
            font-size: 12px;
            color: var(--muted);
            margin-top: 12px;
        }

        /* =========================
           FOOTER
        ========================== */

        footer {
            background: #041126;
            color: var(--white);
            padding: 55px 0 20px;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: 1.4fr 1fr 1fr;
            gap: 35px;
            margin-bottom: 35px;
        }

        .footer-about p {
            color: #bdc9da;
            font-size: 14px;
            margin-top: 17px;
            max-width: 380px;
        }

        .footer-column h3 {
            font-size: 17px;
            margin-bottom: 15px;
            color: var(--accent);
        }

        .footer-column ul {
            list-style: none;
        }

        .footer-column li {
            margin: 9px 0;
            color: #bdc9da;
            font-size: 14px;
        }

        .footer-column a:hover {
            color: var(--accent);
        }

        .footer-bottom {
            border-top: 1px solid rgba(255, 255, 255, 0.13);
            padding-top: 20px;
            display: flex;
            justify-content: space-between;
            gap: 15px;
            flex-wrap: wrap;
            font-size: 12px;
            color: #bdc9da;
        }

        /* =========================
           FLOATING WHATSAPP BUTTON
        ========================== */

        .whatsapp-float {
            position: fixed;
            right: 20px;
            bottom: 22px;
            z-index: 999;
            background: #25d366;
            color: white;
            padding: 13px 17px;
            border-radius: 50px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.2);
            font-weight: 800;
            font-size: 14px;
            transition: transform 0.2s;
        }

        .whatsapp-float:hover {
            transform: translateY(-3px);
        }

        /* =========================
           BACK TO TOP
        ========================== */

        .back-to-top {
            position: fixed;
            left: 20px;
            bottom: 22px;
            z-index: 998;
            width: 43px;
            height: 43px;
            border: none;
            border-radius: 50%;
            background: var(--primary);
            color: var(--white);
            font-size: 22px;
            cursor: pointer;
            box-shadow: var(--shadow);
            display: none;
        }

        .back-to-top.visible {
            display: block;
        }

        /* =========================
           RESPONSIVE DESIGN
        ========================== */

        @media (max-width: 1000px) {
            .nav-links {
                gap: 13px;
            }

            .nav-links a {
                font-size: 12px;
            }

            .hero-grid {
                gap: 30px;
            }

            .services-grid,
            .supplies-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .why-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 780px) {
            .navbar {
                min-height: 72px;
            }

            .menu-toggle {
                display: block;
                flex-shrink: 0;
            }

            .nav-links {
                display: none;
                position: absolute;
                top: 72px;
                left: 0;
                right: 0;
                background: var(--white);
                padding: 20px 5%;
                flex-direction: column;
                align-items: stretch;
                gap: 0;
                box-shadow: var(--shadow);
                border-top: 1px solid var(--border);
            }

            .nav-links.open {
                display: flex;
            }

            .nav-links li {
                border-bottom: 1px solid var(--border);
            }

            .nav-links li:last-child {
                border-bottom: none;
                padding-top: 12px;
            }

            .nav-links a {
                display: block;
                padding: 12px 0;
                font-size: 14px;
            }

            .nav-links .nav-cta {
                text-align: center;
                padding: 12px;
            }

            .hero {
                padding: 75px 0;
            }

            .hero-grid,
            .about-grid,
            .contact-grid {
                grid-template-columns: 1fr;
            }

            .hero-card {
                margin-top: 10px;
            }

            .about-visual {
                min-height: 300px;
            }

            .quick-grid {
                grid-template-columns: 1fr;
                padding: 10px 0;
            }

            .quick-item {
                border-right: none;
                border-bottom: 1px solid var(--border);
                padding: 13px;
            }

            .quick-item:last-child {
                border-bottom: none;
            }

            .footer-grid {
                grid-template-columns: 1fr 1fr;
            }

            .footer-about {
                grid-column: 1 / -1;
            }

            .section {
                padding: 65px 0;
            }
        }

        @media (max-width: 520px) {
            .brand-logo {
                width: 42px;
                height: 42px;
                font-size: 16px;
            }

            .brand-text {
                font-size: 11px;
            }

            .brand-text small {
                font-size: 9px;
            }

            .hero h1 {
                font-size: 36px;
            }

            .hero-actions {
                flex-direction: column;
            }

            .hero-actions .btn {
                width: 100%;
            }

            .services-grid,
            .supplies-grid,
            .why-grid,
            .footer-grid {
                grid-template-columns: 1fr;
            }

            .footer-about {
                grid-column: auto;
            }

            .contact-info,
            .contact-form {
                padding: 23px;
            }

            .whatsapp-float {
                right: 12px;
                bottom: 12px;
                padding: 11px 14px;
            }

            .back-to-top {
                left: 12px;
                bottom: 12px;
            }

            .footer-bottom {
                flex-direction: column;
            }
        }

        /* Respect reduced-motion preferences */
        @media (prefers-reduced-motion: reduce) {
            html {
                scroll-behavior: auto;
            }

            *,
            *::before,
            *::after {
                transition-duration: 0.01ms !important;
                animation-duration: 0.01ms !important;
            }
        }
</style>
</head>

<body>

<!-- HEADER -->
<header>
<div class="container navbar">

<a href="#home" class="brand" aria-label="Gadzama Prime Digital World Limited homepage">
<div class="brand-logo">GP</div>

<div class="brand-text">
                    GADZAMA PRIME
<small>DIGITAL WORLD LIMITED</small>
</div>
</a>

<button
                class="menu-toggle"
                id="menuToggle"
                aria-label="Open navigation menu"
                aria-expanded="false"
                aria-controls="navLinks"
>
                ☰
</button>

<nav aria-label="Main navigation">
<ul class="nav-links" id="navLinks">
<li><a href="#home">Home</a></li>
<li><a href="#about">About Us</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#supplies">Supplies</a></li>
<li><a href="#contact">Contact</a></li>
<li>
<a href="#contact" class="nav-cta">Get a Quote</a>
</li>
</ul>
</nav>

</div>
</header>


<main>

<!-- HERO SECTION -->
<section class="hero" id="home">
<div class="container hero-grid">

<div class="hero-content">

<span class="hero-badge">
                        YOUR PARTNER IN DIGITAL SOLUTIONS
</span>

<h1>
                        Smart Digital Solutions.
<span>Reliable Services.</span>
</h1>

<p>
                        Welcome to Gadzama Prime Digital World Limited.
                        We provide ICT services, computer training,
                        printing, graphic design, procurement and general
                        supplies to individuals, businesses and organisations.
</p>

<div class="hero-actions">

<a href="#services" class="btn btn-primary">
                            Explore Our Services →
</a>

<a
                            href="https://wa.me/2348164015705"
                            class="btn btn-outline"
                            target="_blank"
                            rel="noopener noreferrer"
>
                            Chat on WhatsApp
</a>

</div>

</div>


<div class="hero-card">

<h3>How We Can Help You</h3>

<div class="hero-feature">
<div class="feature-icon">💻</div>
<div>
<strong>ICT & Digital Services</strong>
<small>Computer services, training and online support.</small>
</div>
</div>

<div class="hero-feature">
<div class="feature-icon">🖨️</div>
<div>
<strong>Printing & Business Centre</strong>
<small>Printing, photocopying, scanning and typing.</small>
</div>
</div>

<div class="hero-feature">
<div class="feature-icon">🎨</div>
<div>
<strong>Graphics & Branding</strong>
<small>Creative designs and business branding.</small>
</div>
</div>

<div class="hero-feature">
<div class="feature-icon">📦</div>
<div>
<strong>Procurement & Supplies</strong>
<small>Office equipment and general supplies.</small>
</div>
</div>

</div>

</div>
</section>


<!-- QUICK CONTACT -->
<section class="quick-strip">
<div class="container quick-grid">

<div class="quick-item">
<strong>📍 Our Location</strong>
<span>Karu Village, FCT Abuja</span>
</div>

<div class="quick-item">
<strong>☎️ Call Us</strong>
<span>08164015705</span>
</div>

<div class="quick-item">
<strong>✉️ Email Us</strong>
<span>gadzamaprimedigitalworld@gmail.com</span>
</div>

</div>
</section>


<!-- ABOUT US -->
<section class="section" id="about">
<div class="container about-grid">

<div class="about-visual">
<div class="about-monogram">
<strong>GP</strong>
<span>GADZAMA PRIME</span>
<p>Digital World Limited</p>
</div>
</div>

<div class="about-content">

<span class="tag">ABOUT OUR COMPANY</span>

<h2>Committed to Quality, Service and Innovation</h2>

<p>
                        Gadzama Prime Digital World Limited is a Nigerian
                        company focused on delivering digital solutions,
                        ICT-related services and general supplies.
</p>

<p>
                        Our aim is to support individuals, entrepreneurs,
                        businesses and organisations with practical,
                        dependable and accessible services.
</p>

<p>
                        Based at Zumunta Road, Karu Village, FCT Abuja,
                        we welcome enquiries about our services, supply
                        capabilities and potential business partnerships.
</p>

<ul class="check-list">
<li>Customer-focused service delivery</li>
<li>Digital and business support solutions</li>
<li>Printing, graphics and computer services</li>
<li>Procurement and general supply enquiries</li>
</ul>

<a href="#contact" class="btn btn-primary">
                        Contact Our Team →
</a>

</div>

</div>
</section>


<!-- SERVICES -->
<section class="section services-section" id="services">

<div class="container">

<div class="section-heading">
<span class="tag">WHAT WE DO</span>
<h2>Our Professional Services</h2>
<p>
                        Discover our range of digital, administrative and
                        business support services.
</p>
</div>


<div class="services-grid">

<article class="service-card">
<div class="service-icon">💻</div>
<h3>ICT Services</h3>
<p>
                            Computer-related services, digital support,
                            software assistance and technology solutions
                            for individuals and businesses.
</p>
<a href="#contact" class="service-link"
                           data-service="ICT Services">
                            Enquire About This Service →
</a>
</article>


<article class="service-card">
<div class="service-icon">🎓</div>
<h3>Computer Training</h3>
<p>
                            Practical computer lessons covering Microsoft
                            Word, Excel, file management and other
                            essential digital skills.
</p>
<a href="#contact" class="service-link"
                           data-service="Computer Training">
                            Enquire About This Service →
</a>
</article>


<article class="service-card">
<div class="service-icon">🖨️</div>
<h3>Printing & Photocopying</h3>
<p>
                            Document printing, photocopying, scanning,
                            typing, document formatting and related
                            business centre services.
</p>
<a href="#contact" class="service-link"
                           data-service="Printing and Photocopying">
                            Enquire About This Service →
</a>
</article>


<article class="service-card">
<div class="service-icon">🎨</div>
<h3>Graphics & Branding</h3>
<p>
                            Flyers, business cards, logos, stamps,
                            promotional materials and other graphic
                            design services.
</p>
<a href="#contact" class="service-link"
                           data-service="Graphics and Branding">
                            Enquire About This Service →
</a>
</article>


<article class="service-card">
<div class="service-icon">🌐</div>
<h3>Online Registration Services</h3>
<p>
                            Assistance with online applications,
                            registrations, document preparation and
                            other authorised digital processes.
</p>
<a href="#contact" class="service-link"
                           data-service="Online Registration Services">
                            Enquire About This Service →
</a>
</article>


<article class="service-card">
<div class="service-icon">📋</div>
<h3>Business Support</h3>
<p>
                            Administrative support, business document
                            preparation, company profile design and
                            general digital business services.
</p>
<a href="#contact" class="service-link"
                           data-service="Business Support">
                            Enquire About This Service →
</a>
</article>

</div>

</div>
</section>


<!-- WHY CHOOSE US -->
<section class="section" id="why-us">

<div class="container">

<div class="section-heading">
<span class="tag">WHY WORK WITH US</span>
<h2>A Business Partner You Can Contact With Confidence</h2>
<p>
                        We aim to make business support and digital
                        services more accessible to our customers.
</p>
</div>


<div class="why-grid">

<div class="why-card">
<div class="why-icon">🤝</div>
<h3>Customer Focus</h3>
<p>
                            We listen to your requirements and work
                            towards meeting your needs.
</p>
</div>

<div class="why-card">
<div class="why-icon">💡</div>
<h3>Practical Solutions</h3>
<p>
                            Services designed to address everyday
                            digital and business needs.
</p>
</div>

<div class="why-card">
<div class="why-icon">📞</div>
<h3>Easy Communication</h3>
<p>
                            Contact us by telephone, email or WhatsApp
                            to discuss your requirements.
</p>
</div>

<div class="why-card">
<div class="why-icon">📦</div>
<h3>Multiple Services</h3>
<p>
                            ICT, business centre operations, graphics
                            and general supply enquiries in one place.
</p>
</div>

</div>

</div>
</section>


<!-- SUPPLIES -->
<section class="section supplies-section" id="supplies">

<div class="container">

<div class="section-heading">
<span class="tag">PROCUREMENT & GENERAL SUPPLIES</span>
<h2>Products and Supply Capabilities</h2>
<p>
                        Contact us with your requirements for availability,
                        specifications, pricing and quotations.
</p>
</div>


<div class="supplies-grid">

<article class="supply-card">
<div class="supply-icon">🖥️</div>
<h3>Computer & ICT Equipment</h3>
<p>
                            Enquiries for computers, printers, accessories
                            and other ICT-related equipment.
</p>
</article>


<article class="supply-card">
<div class="supply-icon">🗄️</div>
<h3>Office Equipment & Materials</h3>
<p>
                            Office equipment, stationery and other
                            administrative materials.
</p>
</article>


<article class="supply-card">
<div class="supply-icon">🌾</div>
<h3>Agricultural Supplies</h3>
<p>
                            Enquiries about farm inputs, agricultural
                            materials and related supplies.
</p>
</article>


<article class="supply-card">
<div class="supply-icon">🪑</div>
<h3>Furniture & General Goods</h3>
<p>
                            Supply enquiries for furniture and other
                            general goods based on customer requirements.
</p>
</article>


<article class="supply-card">
<div class="supply-icon">📄</div>
<h3>Printing & Office Materials</h3>
<p>
                            Printed materials, paper products and
                            related office consumables.
</p>
</article>


<article class="supply-card">
<div class="supply-icon">🏢</div>
<h3>Organisational Supply Requests</h3>
<p>
                            Businesses and organisations can contact us
                            to discuss supply requirements and quotations.
</p>
</article>

</div>

</div>
</section>


<!-- CALL TO ACTION -->
<section class="cta-section">

<div class="container">

<h2>Have a Project or Supply Request?</h2>

<p>
                    Tell us what you need. We welcome enquiries from
                    individuals, businesses, institutions and organisations.
</p>

<a href="#contact" class="btn btn-primary">
                    Request a Quotation →
</a>

</div>

</section>


<!-- CONTACT -->
<section class="section" id="contact">

<div class="container">

<div class="section-heading">
<span class="tag">GET IN TOUCH</span>
<h2>Contact Gadzama Prime Digital World Limited</h2>
<p>
                        Contact us for enquiries, service requests,
                        quotations, procurement and business partnerships.
</p>
</div>


<div class="contact-grid">

<div class="contact-info">

<h3>Let's Talk Business</h3>

<p>
                            We would be pleased to hear from you.
                            Reach us through any of the channels below.
</p>


<div class="contact-detail">
<div class="detail-icon">📍</div>
<div>
<strong>Office Address</strong>
<p>
                                    Zumunta Road, Karu Village,
                                    FCT-Abuja, Nigeria
</p>
</div>
</div>


<div class="contact-detail">
<div class="detail-icon">☎️</div>
<div>
<strong>Telephone Numbers</strong>
<p>
<a href="tel:+2348164015705">
                                        08164015705
</a>
<br>
<a href="tel:+2348154968439">
                                        08154968439
</a>
<br>
<a href="tel:+2348024741262">
                                        08024741262
</a>
</p>
</div>
</div>


<div class="contact-detail">
<div class="detail-icon">✉️</div>
<div>
<strong>Email Address</strong>
<p>
<a href="mailto:gadzamaprimedigitalworld@gmail.com">
                                        gadzamaprimedigitalworld@gmail.com
</a>
</p>
</div>
</div>


<div class="contact-detail">
<div class="detail-icon">💬</div>
<div>
<strong>WhatsApp</strong>
<p>
<a
                                        href="https://wa.me/2348164015705"
                                        target="_blank"
                                        rel="noopener noreferrer"
>
                                        Chat with us on WhatsApp
</a>
</p>
</div>
</div>

</div>


<!-- CONTACT FORM -->
<form class="contact-form" id="contactForm">

<h3>Send an Enquiry</h3>

<p>
                            Complete the form below to prepare your
                            enquiry for WhatsApp.
</p>


<div class="form-group">
<label for="name">Your Full Name *</label>
<input
                                type="text"
                                id="name"
                                name="name"
                                placeholder="Enter your name"
                                autocomplete="name"
                                maxlength="100"
                                required
>
</div>


<div class="form-group">
<label for="phone">Your Phone Number *</label>
<input
                                type="tel"
                                id="phone"
                                name="phone"
                                placeholder="Enter your phone number"
                                autocomplete="tel"
                                maxlength="25"
                                required
>
</div>


<div class="form-group">
<label for="service">Service Required *</label>

<select id="service" name="service" required>
<option value="">Select a service</option>
<option>ICT Services</option>
<option>Computer Training</option>
<option>Printing and Photocopying</option>
<option>Graphics and Branding</option>
<option>Online Registration Services</option>
<option>Business Support</option>
<option>Computer and ICT Equipment</option>
<option>Office Equipment and Materials</option>
<option>Agricultural Supplies</option>
<option>Furniture and General Goods</option>
<option>Government Procurement Enquiry</option>
<option>Other Enquiry</option>
</select>

</div>


<div class="form-group">
<label for="message">Your Message *</label>

<textarea
                                id="message"
                                name="message"
                                placeholder="Please describe what you need..."
                                maxlength="2000"
                                required
></textarea>

</div>


<button type="submit" class="btn btn-primary">
                            Send Enquiry via WhatsApp →
</button>

<p class="form-note" id="formStatus" role="status">
                            Your message will open in WhatsApp for you
                            to review and send.
</p>

</form>

</div>

</div>
</section>

</main>


<!-- FOOTER -->
<footer>

<div class="container">

<div class="footer-grid">

<div class="footer-about">

<a href="#home" class="brand">
<div class="brand-logo">GP</div>

<div class="brand-text" style="color:white;">
                            GADZAMA PRIME
<small style="color:#f4b400;">
                                DIGITAL WORLD LIMITED
</small>
</div>
</a>

<p>
                        Providing ICT services, digital solutions,
                        printing, graphic design, procurement and
                        general supply services in Nigeria.
</p>

</div>


<div class="footer-column">

<h3>Quick Links</h3>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About Us</a></li>
<li><a href="#services">Our Services</a></li>
<li><a href="#supplies">Supplies</a></li>
<li><a href="#contact">Contact Us</a></li>
</ul>

</div>


<div class="footer-column">

<h3>Contact Details</h3>

<ul>
<li>
<a href="tel:+2348164015705">
                                08164015705
</a>
</li>

<li>
<a href="tel:+2348154968439">
                                08154968439
</a>
</li>

<li>
<a href="tel:+2348024741262">
                                08024741262
</a>
</li>

<li>
<a href="mailto:gadzamaprimedigitalworld@gmail.com">
                                Send Us an Email
</a>
</li>

<li>Zumunta Road, Karu Village, FCT Abuja</li>
</ul>

</div>

</div>


<div class="footer-bottom">

<p>
&copy; <span id="year"></span>
                    Gadzama Prime Digital World Limited.
                    All rights reserved.
</p>

<p>Designed for digital growth and business success.</p>

</div>

</div>

</footer>


<!-- FLOATING WHATSAPP BUTTON -->
<a
        href="https://wa.me/2348164015705"
        class="whatsapp-float"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Chat with Gadzama Prime Digital World Limited on WhatsApp"
>
        ☎ WhatsApp Us
</a>


<!-- BACK TO TOP BUTTON -->
<button
        class="back-to-top"
        id="backToTop"
        aria-label="Back to top"
        title="Back to top"
>
        ↑
</button>


<script>
"use strict";

        // ==============================
        // MOBILE NAVIGATION
        // ==============================

        const menuToggle = document.getElementById("menuToggle");
        const navLinks = document.getElementById("navLinks");

        function closeMenu() {
            navLinks.classList.remove("open");
            menuToggle.setAttribute("aria-expanded", "false");
            menuToggle.setAttribute("aria-label", "Open navigation menu");
            menuToggle.textContent = "☰";
        }

        menuToggle.addEventListener("click", function () {
            const isOpen = navLinks.classList.toggle("open");

            menuToggle.setAttribute("aria-expanded", String(isOpen));
            menuToggle.setAttribute(
"aria-label",
                isOpen ? "Close navigation menu" : "Open navigation menu"
            );

            menuToggle.textContent = isOpen ? "✕" : "☰";
        });

        navLinks.querySelectorAll("a").forEach(function (link) {
            link.addEventListener("click", closeMenu);
        });


        // ==============================
        // AUTOMATIC COPYRIGHT YEAR
        // ==============================

        document.getElementById("year").textContent =
            new Date().getFullYear();


        // ==============================
        // BACK TO TOP BUTTON
        // ==============================

        const backToTop = document.getElementById("backToTop");

        window.addEventListener("scroll", function () {
            if (window.scrollY > 350) {
                backToTop.classList.add("visible");
            } else {
                backToTop.classList.remove("visible");
            }
        });

        backToTop.addEventListener("click", function () {
            window.scrollTo({
                top: 0,
                behavior: "smooth"
            });
        });


        // ==============================
        // SERVICE ENQUIRY SHORTCUTS
        // ==============================

        document.querySelectorAll("[data-service]").forEach(function (link) {
            link.addEventListener("click", function () {
                const serviceName = this.getAttribute("data-service");
                const serviceSelect = document.getElementById("service");

                const matchingOption = Array.from(
                    serviceSelect.options
                ).find(function (option) {
                    return option.text.trim() === serviceName.trim();
                });

                if (matchingOption) {
                    serviceSelect.value = matchingOption.value ||
                        matchingOption.text;
                }
            });
        });


        // ==============================
        // CONTACT FORM
        // Opens WhatsApp with the enquiry
        // ==============================

        const contactForm = document.getElementById("contactForm");
        const formStatus = document.getElementById("formStatus");

        contactForm.addEventListener("submit", function (event) {
            event.preventDefault();

            if (!contactForm.reportValidity()) {
                return;
            }

            const name = document.getElementById("name").value.trim();
            const phone = document.getElementById("phone").value.trim();
            const service = document.getElementById("service").value;
            const message = document.getElementById("message").value.trim();

            if (!name || !phone || !service || !message) {
                formStatus.textContent =
"Please complete all required fields.";

                return;
            }

            const whatsappNumber = "2348164015705";

            const whatsappMessage =
"Hello Gadzama Prime Digital World Limited," +
"\n\nI would like to make an enquiry." +
"\n\nName: " + name +
"\nPhone: " + phone +
"\nService Required: " + service +
"\nMessage: " + message +
"\n\nThank you.";

            const whatsappURL =
"https://wa.me/" +
                whatsappNumber +
"?text=" +
                encodeURIComponent(whatsappMessage);

            formStatus.textContent =
"Opening WhatsApp. Please review your enquiry and press Send.";

            const whatsappWindow = window.open(
                whatsappURL,
"_blank",
"noopener,noreferrer"
            );

            // Some browsers block new tabs. Provide a direct fallback.
            if (!whatsappWindow) {
                window.location.href = whatsappURL;
            }
        });


        // ==============================
        // BASIC ACTIVE NAVIGATION
        // ==============================

        const pageSections = document.querySelectorAll("main section[id]");
        const pageNavLinks = document.querySelectorAll(
'.nav-links a[href^="#"]'
        );

        if ("IntersectionObserver" in window) {
            const sectionObserver = new IntersectionObserver(
                function (entries) {
                    entries.forEach(function (entry) {
                        if (!entry.isIntersecting) {
                            return;
                        }

                        pageNavLinks.forEach(function (link) {
                            link.classList.toggle(
"active",
                                link.getAttribute("href") ===
"#" + entry.target.id
                            );
                        });
                    });
                },
                {
                    rootMargin: "-25% 0px -60% 0px"
                }
            );

            pageSections.forEach(function (section) {
                sectionObserver.observe(section);
            });
        }

</script>

</body>
</html>
