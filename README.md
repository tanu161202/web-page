<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Development</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h1>Web Development</h1>
            <p>Building innovative and responsive websites for the digital world.</p>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <h2>Why Choose Web Development?</h2>
        <div class="feature-box">
            <div class="feature">
                <h3>Frontend Development</h3>
                <p>Creating visually appealing interfaces using HTML, CSS, and JavaScript.</p>
            </div>
            <div class="feature">
                <h3>Backend Development</h3>
                <p>Developing robust server-side logic with Node.js, Python, and PHP.</p>
            </div>
            <div class="feature">
                <h3>Full-Stack Development</h3>
                <p>Combining frontend and backend to build complete web solutions.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <h2>Register Now</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>

            <label for="email">Email Id:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>

            <button type="submit">Submit</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Web Development | All Rights Reserved</p>
    </footer>

</body>
</html>
