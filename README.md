<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adebayo Olabisi - Shopify Expert</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
        body { background: #f4f4f4; color: #333; text-align: center; padding: 50px; }
        .container { max-width: 800px; margin: auto; background: #fff; padding: 30px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        h1 { color: #222; font-size: 32px; margin-bottom: 10px; }
        p { font-size: 18px; margin-bottom: 10px; }
        nav { margin-bottom: 20px; }
        nav a { text-decoration: none; color: #333; margin: 0 15px; font-weight: 600; }
        .profile-pic { width: 120px; height: 120px; border-radius: 50%; margin-bottom: 15px; }
        .btn { display: inline-block; padding: 10px 20px; background: #0073e6; color: #fff; text-decoration: none; border-radius: 5px; margin-top: 10px; }
        .btn:hover { background: #005bb5; }
        .socials a { text-decoration: none; margin: 0 10px; font-size: 24px; color: #0073e6; }
        .contact-form input, .contact-form textarea { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; }
        .contact-form button { padding: 10px 15px; background: #0073e6; color: white; border: none; cursor: pointer; border-radius: 5px; }
        .contact-form button:hover { background: #005bb5; }
    </style>
</head>
<body>

    <div class="container">
        <nav>
            <a href="#">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>

        <img src="https://via.placeholder.com/120" alt="Profile Picture" class="profile-pic">  

        <h1>Adebayo Olabisi</h1>
        <p>Shopify Expert & eCommerce Professional</p>
        <p>Helping businesses grow with powerful online stores.</p>

        <a href="https://merchantola.com" class="btn">Visit Merchant Ola</a>

        <div class="socials">
            <a href="https://www.instagram.com/MerchantOla" target="_blank">📸</a>
            <a href="https://www.facebook.com/MerchantOla" target="_blank">📘</a>
            <a href="https://www.linkedin.com/in/yourprofile" target="_blank">🔗</a>
        </div>

        <h2 id="about">About Me</h2>
        <p>I specialize in Shopify store design, eCommerce optimization, and helping businesses scale. Let's build something amazing together!</p>

        <h2 id="contact">Contact Me</h2>
        <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>

</body>
</html>
