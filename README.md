# EXP_2
# Ex02 Commercial Website
## Date:2-11-26
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
STEP 1
Create an HTML file (index.html)

STEP 2
Create a CSS file (style.css)

STEP 3
Include a navigation bar with links to different sections.

STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

STEP 5
Include social media links at the footer with copyright information.

STEP 6
Define global styles for fonts, colors, and layout.

STEP 7
Style the header, navigation bar, and sections.

STEP 8
Use Flexbox for layout design.

STEP 9
Add hover effects and transitions for interactivity.

STEP 10
Add Images and Media.

STEP 11
Use optimized images for a professional look.

STEP 12
Open the HTML file in a browser to check layout and functionality.

STEP 13
Fix styling issues and refine content placement.

STEP 14
Deploy the website.

STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM : 
### HTML :
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOTORVAULT | Premium Automobiles</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- HEADER AND NAVIGATION -->
    <header>
        <div class="logo">MOTOR<span>VAULT</span></div>

        <nav>
            <a href="#home">Home</a>
            <a href="#collections">Collections</a>
            <a href="#parts">Spare Parts</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <a href="#account" class="login-link">Account</a>
        </nav>
    </header>


    <!-- HOME SECTION -->
    <section class="hero" id="home">

        <div class="hero-content">
            <p class="tagline">THE ART OF AUTOMOTIVE EXCELLENCE</p>

            <h1>DRIVE THE <span>LEGEND.</span></h1>

            <p>
                Discover rare automobiles, legendary superbikes
                and exclusive automotive parts.
            </p>

            <a href="#collections" class="btn">EXPLORE COLLECTIONS</a>
        </div>

    </section>


    <!-- INTRODUCTION -->
    <section class="intro">
        <p>MORE THAN MACHINES. THEY ARE MASTERPIECES.</p>

        <h2>Where Automotive History Meets Luxury</h2>

        <p>
            Explore a carefully selected collection of rare cars,
            iconic motorcycles and premium automobile components.
            Every machine has a story. Find yours at MotorVault.
        </p>
    </section>


    <!-- VEHICLE COLLECTIONS -->
    <section class="collections" id="collections">

        <div class="section-heading">
            <p>OUR EXCLUSIVE GARAGE</p>
            <h2>Rare Vehicle Collections</h2>
        </div>

        <div class="vehicle-container">

            <div class="vehicle-card">
                <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?w=700"
                     alt="Luxury sports car">

                <div class="card-content">
                    <p>CAR COLLECTION</p>
                    <h3>Porsche 911</h3>
                    <h4>₹1.85 Crore</h4>
                    <button>View Details</button>
                </div>
            </div>


            <div class="vehicle-card">
                <img src="https://images.unsplash.com/photo-1558981806-ec527fa84c39?w=700"
                     alt="Premium motorcycle">

                <div class="card-content">
                    <p>BIKE COLLECTION</p>
                    <h3>Classic Superbike</h3>
                    <h4>₹18.5 Lakh</h4>
                    <button>View Details</button>
                </div>
            </div>


            <div class="vehicle-card">
                <img src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?w=700"
                     alt="Luxury sports car">

                <div class="card-content">
                    <p>SPORTS CAR</p>
                    <h3>Premium Coupe</h3>
                    <h4>₹95 Lakh</h4>
                    <button>View Details</button>
                </div>
            </div>


            <div class="vehicle-card">
                <img src="https://images.unsplash.com/photo-1558981403-c5f9899a28bc?w=700"
                     alt="Vintage motorcycle">

                <div class="card-content">
                    <p>VINTAGE COLLECTION</p>
                    <h3>Vintage Motorcycle</h3>
                    <h4>₹12 Lakh</h4>
                    <button>View Details</button>
                </div>
            </div>

        </div>
    </section>


    <!-- SPARE PARTS SECTION -->
    <section class="parts" id="parts">

        <div class="section-heading">
            <p>BUILT FOR PERFORMANCE</p>
            <h2>Premium Spare Parts</h2>
        </div>

        <div class="parts-container">

            <div class="part-card">
                <img src="https://images.unsplash.com/photo-1486262715619-67b85e0b08d3?w=600"
                     alt="Automobile engine">

                <h3>Performance Engines</h3>
                <p>High-performance engine components.</p>
                <h4>From ₹45,000</h4>
                <button>Explore Parts</button>
            </div>


            <div class="part-card">
                <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?w=600"
                     alt="Car wheel and exterior">

                <h3>Premium Accessories</h3>
                <p>Exclusive accessories for your vehicle.</p>
                <h4>From ₹5,000</h4>
                <button>Explore Parts</button>
            </div>


            <div class="part-card">
                <img src="https://images.unsplash.com/photo-1558981806-ec527fa84c39?w=600"
                     alt="Motorcycle">

                <h3>Bike Components</h3>
                <p>Quality components for superbikes.</p>
                <h4>From ₹8,000</h4>
                <button>Explore Parts</button>
            </div>

        </div>
    </section>


    <!-- WHY CHOOSE US -->
    <section class="features">

        <div class="section-heading">
            <p>THE MOTORVAULT PROMISE</p>
            <h2>Why Choose Us?</h2>
        </div>

        <div class="feature-container">

            <div class="feature">
                <h3>✦ Rare Collections</h3>
                <p>Discover exclusive and hard-to-find automobiles.</p>
            </div>

            <div class="feature">
                <h3>✦ Quality Assurance</h3>
                <p>Carefully inspected vehicles and components.</p>
            </div>

            <div class="feature">
                <h3>✦ Expert Assistance</h3>
                <p>Get guidance from automotive enthusiasts.</p>
            </div>

            <div class="feature">
                <h3>✦ Premium Service</h3>
                <p>A personalized experience for every customer.</p>
            </div>

        </div>
    </section>


    <!-- ABOUT US -->
    <section class="about" id="about">

        <div class="about-image">
            <img src="https://images.unsplash.com/photo-1486262715619-67b85e0b08d3?w=800"
                 alt="Automotive workshop">
        </div>

        <div class="about-content">
            <p>OUR STORY</p>
            <h2>Driven By Passion. Defined By Excellence.</h2>

            <p>
                MotorVault is a premium automobile marketplace
                created for people who appreciate automotive
                engineering and timeless design.

                From legendary vintage cars to modern superbikes,
                we bring together exceptional vehicles and
                high-quality spare parts under one roof.
            </p>

            <a href="#contact" class="btn">KNOW MORE</a>
        </div>

    </section>


    <!-- USER ACCOUNT -->
    <section class="account" id="account">

        <div class="section-heading">
            <p>JOIN THE MOTORVAULT COMMUNITY</p>
            <h2>Customer Login</h2>
        </div>

        <form>
            <input type="email" placeholder="Enter your email" required>

            <input type="password" placeholder="Enter your password" required>

            <button type="submit">LOGIN</button>

            <p>New Customer? Create an account with us.</p>
        </form>

    </section>


    <!-- CONTACT -->
    <section class="contact" id="contact">

        <div class="section-heading">
            <p>GET IN TOUCH</p>
            <h2>Contact MotorVault</h2>
        </div>

        <div class="contact-container">

            <div>
                <h3>Address</h3>
                <p>Automotive Street, Chennai, India</p>
            </div>

            <div>
                <h3>Email</h3>
                <p>support@motorvault.com</p>
            </div>

            <div>
                <h3>Phone</h3>
                <p>+91 98765 43210</p>
            </div>

        </div>

    </section>


    <!-- FOOTER -->
    <footer>

        <div class="footer-logo">MOTOR<span>VAULT</span></div>

        <p>For Those Who Live and Breathe Automobiles.</p>

        <div class="social-links">
            <a href="https://www.instagram.com/">Instagram</a>
            <a href="https://www.facebook.com/">Facebook</a>
            <a href="https://www.youtube.com/">YouTube</a>
        </div>

        <p class="copyright">
            © 2026 MotorVault. All Rights Reserved.
        </p>

    </footer>

</body>
</html>
```
### CSS :
```

/* GLOBAL STYLING */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
    scroll-behavior: smooth;
}

body {
    background-color: #101010;
    color: white;
}

html {
    scroll-behavior: smooth;
}

/* HEADER */
header {
    background-color: #080808;
    padding: 22px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    border-bottom: 1px solid #333;
}

.logo, .footer-logo {
    font-size: 27px;
    font-weight: bold;
    letter-spacing: 2px;
}

.logo span, .footer-logo span {
    color: #d6a84f;
}

/* NAVIGATION BAR */
nav {
    display: flex;
    gap: 25px;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    font-size: 14px;
    transition: 0.3s;
}

nav a:hover {
    color: #d6a84f;
}

.login-link {
    border: 1px solid #d6a84f;
    padding: 8px 15px;
}

/* HERO SECTION */
.hero {
    min-height: 550px;

    background:
    linear-gradient(rgba(0,0,0,0.55),
                    rgba(0,0,0,0.7)),
    url("https://images.unsplash.com/photo-1503376780353-7e6692767b70?w=1600")
    center/cover no-repeat;

    display: flex;
    align-items: center;
    padding: 50px 10%;
}

.hero-content {
    max-width: 650px;
}

.tagline, .section-heading p {
    color: #d6a84f;
    letter-spacing: 3px;
    font-size: 13px;
    margin-bottom: 18px;
}

.hero h1 {
    font-size: 65px;
    margin-bottom: 20px;
}

.hero h1 span {
    color: #d6a84f;
}

.hero-content p {
    line-height: 1.8;
    margin-bottom: 30px;
    font-size: 17px;
}

.btn {
    display: inline-block;
    background-color: #d6a84f;
    color: black;
    text-decoration: none;
    padding: 14px 25px;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    background-color: white;
    transform: translateY(-3px);
}

/* INTRODUCTION */
.intro {
    text-align: center;
    padding: 65px 10%;
}

.intro > p:first-child {
    color: #d6a84f;
    letter-spacing: 2px;
    margin-bottom: 15px;
}

.intro h2 {
    font-size: 32px;
    margin-bottom: 20px;
}

.intro > p:last-child {
    color: #aaa;
    line-height: 1.8;
    max-width: 750px;
    margin: auto;
}

/* COMMON SECTION HEADING */
section {
    padding: 65px 7%;
}

.section-heading {
    text-align: center;
    margin-bottom: 40px;
}

.section-heading h2 {
    font-size: 34px;
}

/* VEHICLE COLLECTIONS */
.collections {
    background-color: #181818;
}

.vehicle-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 25px;
}

.vehicle-card {
    background-color: #222;
    width: 250px;
    border: 1px solid #333;
    transition: 0.3s;
}

.vehicle-card:hover {
    transform: translateY(-10px);
    border-color: #d6a84f;
}

.vehicle-card img {
    width: 100%;
    height: 190px;
    object-fit: cover;
}

.card-content {
    padding: 20px;
}

.card-content p {
    color: #d6a84f;
    font-size: 11px;
    letter-spacing: 2px;
    margin-bottom: 12px;
}

.card-content h3 {
    margin-bottom: 12px;
}

.card-content h4 {
    color: #d6a84f;
    margin-bottom: 18px;
}

button {
    background-color: #d6a84f;
    color: black;
    padding: 11px 18px;
    border: none;
    cursor: pointer;
    font-weight: bold;
    transition: 0.3s;
}

button:hover {
    background-color: white;
}

/* SPARE PARTS */
.parts {
    background-color: #101010;
}

.parts-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 25px;
}

.part-card {
    width: 300px;
    background-color: #202020;
    padding-bottom: 25px;
    text-align: center;
    border: 1px solid #333;
    transition: 0.3s;
}

.part-card:hover {
    border-color: #d6a84f;
    transform: translateY(-7px);
}

.part-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.part-card h3 {
    margin: 20px 0 12px;
}

.part-card p {
    color: #aaa;
    margin: 0 10px 15px;
}

.part-card h4 {
    color: #d6a84f;
    margin-bottom: 18px;
}

/* FEATURES */
.features {
    background-color: #1c1c1c;
}

.feature-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.feature {
    flex: 1;
    min-width: 200px;
    padding: 25px;
    background-color: #292929;
    border-bottom: 2px solid #d6a84f;
}

.feature h3 {
    color: #d6a84f;
    margin-bottom: 15px;
}

.feature p {
    color: #bbb;
    line-height: 1.6;
}

/* ABOUT US */
.about {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 50px;
    flex-wrap: wrap;
    background-color: #101010;
}

.about-image {
    flex: 1;
    min-width: 280px;
}

.about-image img {
    width: 100%;
    height: 350px;
    object-fit: cover;
}

.about-content {
    flex: 1;
    min-width: 280px;
}

.about-content > p:first-child {
    color: #d6a84f;
    letter-spacing: 3px;
    margin-bottom: 18px;
}

.about-content h2 {
    font-size: 35px;
    margin-bottom: 20px;
}

.about-content > p {
    color: #aaa;
    line-height: 1.8;
    margin-bottom: 25px;
}

/* USER ACCOUNT */
.account {
    background-color: #1c1c1c;
}

.account form {
    max-width: 400px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap: 18px;
}

.account input {
    padding: 15px;
    background-color: #292929;
    border: 1px solid #555;
    color: white;
    outline: none;
}

.account input:focus {
    border-color: #d6a84f;
}

.account form p {
    text-align: center;
    color: #aaa;
    font-size: 13px;
}

/* CONTACT */
.contact {
    background-color: #101010;
}

.contact-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 30px;
    text-align: center;
}

.contact-container h3 {
    color: #d6a84f;
    margin-bottom: 12px;
}

.contact-container p {
    color: #aaa;
}

/* FOOTER */
footer {
    background-color: #080808;
    padding: 40px 20px;
    text-align: center;
    border-top: 1px solid #333;
}

.footer-logo {
    margin-bottom: 15px;
}

footer > p {
    color: #aaa;
    margin: 15px 0;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin: 25px 0;
    flex-wrap: wrap;
}

.social-links a {
    color: #d6a84f;
    text-decoration: none;
    transition: 0.3s;
}

.social-links a:hover {
    color: white;
}

.copyright {
    border-top: 1px solid #333;
    padding-top: 20px;
    font-size: 13px;
}

/* RESPONSIVE DESIGN */
@media (max-width: 768px) {

    header {
        flex-direction: column;
        gap: 20px;
    }

    nav {
        justify-content: center;
        gap: 15px;
    }

    .hero {
        min-height: 450px;
        text-align: center;
        justify-content: center;
    }

    .hero h1 {
        font-size: 40px;
    }

    .section-heading h2 {
        font-size: 27px;
    }

    .vehicle-card {
        width: 100%;
        max-width: 350px;
    }

    .part-card {
        width: 100%;
        max-width: 350px;
    }

    .about {
        text-align: center;
    }

    .contact-container {
        flex-direction: column;
    }
}
```

## OUTPUT
<img width="1832" height="971" alt="image" src="https://github.com/user-attachments/assets/7ea87406-28d1-49ae-b7d9-bcf55fbefcdb" />
<img width="1422" height="767" alt="image" src="https://github.com/user-attachments/assets/e73059ef-2b1c-4043-8861-a3db288696c8" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
