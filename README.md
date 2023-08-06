<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
</head>
  <style>
    /* Reset some default styles for better consistency */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

.hero {
    background-image: url('hero-image.jpg'); /* Replace with your hero image */
    background-size: cover;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-content {
    text-align: center;
}

h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

p {
    font-size: 18px;
    margin-bottom: 20px;
}

.btn {
    display: inline-block;
    padding: 12px 24px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

.features {
    padding: 40px;
}

.features h2 {
    font-size: 30px;
    margin-bottom: 20px;
}

.feature {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 30px;
}

.icon {
    font-size: 40px;
    margin-bottom: 10px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}

/* Add responsive styles as needed */

  </style>
    <header>
        <h1>Welcome to Our Landing Page</h1>
    </header>
    <section class="hero">
        <div class="hero-content">
            <h2>Discover Amazing Products</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed luctus ex eget malesuada dictum.</p>
            <a href="#" class="btn">Explore Now</a>
        </div>
    </section>
    <section class="features">
        <h2>Our Features</h2>
        <div class="feature">
            <i class="icon">Icon 1</i>
            <h3>Feature 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div class="feature">
            <i class="icon">Icon 2</i>
            <h3>Feature 2</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <!-- Add more features here -->
    </section>
    <footer>
        <p>&copy; 2023 ULTRA WEB. All rights reserved.</p>
    </footer>
</body>
</html>

