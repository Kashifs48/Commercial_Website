# Ex02 Commercial Website
## Date:16.02.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Elite Cars Showroom</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <div class="logo">Elite Cars</div>
        <nav>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Cars</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account">Account</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="section home">
        <h1>Welcome to Elite Cars</h1>
        <p>Your Dream Car Awaits You</p>
    </section>

    <!-- Products Section -->
    <section id="products" class="section">
        <h2>Our Cars</h2>
        <div class="product-container">

            <div class="product-card">
                <img src="download (1).jpg" alt="Sedan">
                <h3>Luxury SUV</h3>
                <p>₹2.5CR</p>
                <button>Book Now</button>
            </div>

            <div class="product-card">
                <img src="download (2).jpg" alt="SUV">
                <h3>Power SUV</h3>
                <p>₹55LAKH</p>
                <button>Book Now</button>
            </div>

            <div class="product-card">
                <img src="download (3).jpg" alt="Sports Car">
                <h3>Comfort SUV</h3>
                <p>₹35LAKH</p>
                <button>Book Now</button>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>Elite Cars is one of the leading car dealers providing premium quality vehicles with best customer service.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: syedkashif4062@gmail.com</p>
        <p>Phone: +91 0443201121</p>
    </section>

    <!-- Account Section -->
    <section id="account" class="section">
        <h2>User Account</h2>
        <button>Login</button>
        <button>Register</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow Us:</p>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
        <p>© 2026 Elite Cars. All Rights Reserved.</p>
    </footer>

</body>
</html>

style.css

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Header */
header {
    background: #111;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 50px;
}

.logo {
    font-size: 22px;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

.nav-links a:hover {
    color: #ff4c29;
}

/* Sections */
.section {
    padding: 60px 50px;
    text-align: center;
}

.home {
    background: url('images/car-banner.jpg') no-repeat center center/cover;
    color: white;
    padding: 120px 20px;
}

/* Products Flexbox */
.product-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-top: 30px;
}

.product-card {
    background: white;
    width: 250px;
    margin: 15px;
    padding: 20px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s;
    border-radius: 8px;
}

.product-card:hover {
    transform: scale(1.05);
}

.product-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 8px;
}

/* Buttons */
button {
    padding: 10px 20px;
    border: none;
    background: #ff4c29;
    color: white;
    cursor: pointer;
    margin-top: 10px;
    transition: 0.3s;
    border-radius: 5px;
}

button:hover {
    background: #e63e1e;
}

/* Footer */
footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 20px;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin: 10px 0;
}

.social-links a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

.social-links a:hover {
    color: #ff4c29;
}

/* Responsive */
@media (max-width: 768px) {
    .product-container {
        flex-direction: column;
        align-items: center;
    }

    header {
        flex-direction: column;
    }

    .nav-links {
        flex-direction: column;
        margin-top: 10px;
    }

    .nav-links li {
        margin: 10px 0;
    }
} 

```
## OUTPUT
![alt text](<../Screenshot 2026-02-16 162349.png>)
![alt text](<../Screenshot 2026-02-16 162402.png>)
## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
