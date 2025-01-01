<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beautiful Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="container">
                <a href="#" class="logo">NUR.Web</a>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
        <div class="hero" id="home">
            <h1>Welcome to My Website</h1>
            <p>Creating beautiful designs with simplicity and elegance.</p>
            <a href="#services" class="btn">Learn More</a>
        </div>
    </header>

    <main>
        <section id="services" class="services">
            <div class="container">
                <h2>Our Services</h2>
                <div class="service-items">
                    <div class="service-item">
                        <h3>Web Design</h3>
                        <p>We create modern and responsive web designs tailored to your needs.</p>
                    </div>
                    <div class="service-item">
                        <h3>Development</h3>
                        <p>Our team develops websites that are fast, secure, and scalable.</p>
                    </div>
                    <div class="service-item">
                        <h3>SEO Optimization</h3>
                        <p>We optimize your site to rank higher on search engines.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="about" class="about">
            <div class="container">
                <h2>About Us</h2>
                <p>We are passionate about delivering creative and innovative solutions for our clients.</p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 NUR.Web. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>




/* Reset styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

/* Navbar */
.navbar {
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

.navbar .logo {
    font-size: 1.5rem;
    font-weight: bold;
    text-transform: uppercase;
    color: #fff;
    text-decoration: none;
}

.navbar .nav-links {
    list-style: none;
    display: flex;
    gap: 1.5rem;
}

.navbar .nav-links li a {
    color: #fff;
    text-decoration: none;
}

.navbar .nav-links li a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    background: linear-gradient(to right, #6a11cb, #2575fc);
    color: #fff;
    text-align: center;
    padding: 4rem 1rem;
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.hero .btn {
    background: #fff;
    color: #333;
    padding: 0.8rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    text-transform: uppercase;
}

.hero .btn:hover {
    background: #f4f4f4;
}

/* Services Section */
.services {
    padding: 4rem 1rem;
    background: #f9f9f9;
    text-align: center;
}

.services h2 {
    font-size: 2rem;
    margin-bottom: 2rem;
}

.service-items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.service-item {
    background: #fff;
    padding: 1.5rem;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.service-item h3 {
    margin-bottom: 1rem;
    color: #6a11cb;
}

/* About Section */
.about {
    padding: 4rem 1rem;
}

.about h2 {
    font-size: 2rem;
    text-align: center;
    margin-bottom: 2rem;
}

.about p {
    text-align: center;
    max-width: 700px;
    margin: 0 auto;
    font-size: 1.1rem;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}




