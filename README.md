# ChinwiiX17-SiteWeb2
HADA SITE WEB JDID DYALI
[My SiteWeb.html](https://github.com/user-attachments/files/22351010/My.SiteWeb.html)

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHINWIX17 Gaming Shop</title>
    <style>
        * { margin:0; padding:0; box-sizing:border-box; font-family: 'Arial', sans-serif; scroll-behavior: smooth; }
        body { background-color: #0a0a0a; color: #fff; }
        nav { display:flex; justify-content:space-between; align-items:center; padding:20px 50px; background-color:#111; border-bottom:2px solid #00ffff; position:sticky; top:0; z-index:100; }
        nav a { color:#fff; text-decoration:none; margin-left:20px; transition:0.3s; }
        nav a:hover { color:#00ffff; text-shadow:0 0 10px #00ffff; }
        .hero { height:70vh; background:url('https://images.unsplash.com/photo-1612831455540-0c27f187f0a2?auto=format&fit=crop&w=1950&q=80') no-repeat center/cover; display:flex; justify-content:center; align-items:center; text-align:center; color:#00ffff; text-shadow:2px 2px 15px #000; }
        .hero h1 { font-size:3rem; margin-bottom:20px; text-shadow:0 0 10px #ff00ff,0 0 20px #00ffff; }
        .hero p { font-size:1.2rem; text-shadow:0 0 10px #00ffff; }
        .shop { padding:50px; display:flex; flex-wrap:wrap; justify-content:center; gap:20px; }
        .card { background-color:#111; border:2px solid #ff00ff; padding:20px; width:250px; text-align:center; border-radius:10px; transition:transform 0.3s, box-shadow 0.3s, border-color 0.3s; }
        .card:hover { transform:translateY(-10px); box-shadow:0 0 20px #ff00ff,0 0 40px #00ffff; border-color:#00ffff; }
        .card img { width:100%; border-radius:10px; margin-bottom:15px; }
        .card button { padding:10px 20px; border:none; background-color:#ff00ff; color:#fff; cursor:pointer; border-radius:5px; transition:0.3s; box-shadow:0 0 5px #ff00ff,0 0 10px #00ffff; }
        .card button:hover { background-color:#00ffff; box-shadow:0 0 20px #00ffff,0 0 40px #ff00ff; }
        footer { background-color:#111; text-align:center; padding:20px; border-top:2px solid #00ffff; text-shadow:0 0 10px #00ffff; }
        section h2 { margin-bottom:20px; }
        .about, .contact { padding:50px; text-align:center; }
        .about h2 { color:#ff00ff; text-shadow:0 0 10px #ff00ff; }
        .about p { max-width:600px; margin:20px auto; color:#fff; text-shadow:0 0 5px #00ffff; }
        .contact h2 { color:#00ffff; text-shadow:0 0 10px #00ffff; }
        .contact p { color:#fff; text-shadow:0 0 5px #ff00ff; }
        @media (max-width:768px){ nav{flex-direction:column;} .shop{flex-direction:column; align-items:center;} }
    </style>
</head>
<body>

<nav>
    <div class="logo">CHINWIX17</div>
    <div>
        <a href="#home">Home</a>
        <a href="#shop">Shop</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<section class="hero" id="home">
    <div>
        <h1>Welcome to CHINWIX17</h1>
        <p>Your ultimate gaming experience starts here!</p>
    </div>
</section>

<section class="shop" id="shop">
    <div class="card">
        <img src="https://images.unsplash.com/photo-1612832020415-87b30e70b3c2?auto=format&fit=crop&w=500&q=80" alt="Gaming Mouse">
        <h3>Gaming Mouse</h3>
        <p>$49.99</p>
        <button onclick="window.open('https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EXAMPLE1','_blank')">Buy Now</button>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1593642532973-d31b6557fa68?auto=format&fit=crop&w=500&q=80" alt="Mechanical Keyboard">
        <h3>Mechanical Keyboard</h3>
        <p>$89.99</p>
        <button onclick="window.open('https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EXAMPLE2','_blank')">Buy Now</button>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1615856438873-0ee5101cfb3b?auto=format&fit=crop&w=500&q=80" alt="Gaming Headset">
        <h3>Gaming Headset</h3>
        <p>$69.99</p>
        <button onclick="window.open('https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EXAMPLE3','_blank')">Buy Now</button>
    </div>
</section>

<section class="about" id="about">
    <h2>About CHINWIX17</h2>
    <p>
        CHINWIX17 is your go-to gaming shop for high-quality gear, peripherals, and accessories.
        Join our community and level up your gaming experience!
    </p>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: support@chinwix17.com</p>
</section>

<footer>
    &copy; 2025 CHINWIX17 | Follow us on social media!
</footer>

</body>
</html>
