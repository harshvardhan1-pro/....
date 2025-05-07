<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Chandra Prakash Cloth Store</title>
    <link rel="stylesheet" href="cp.css">
    <link href="https://fonts.googleapis.com/css2?family=Tangerine&family=Lato&display=swap" rel="stylesheet">
</head>
<body>

<header>
    <div class="logo">CP</div>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#register">Register</a></li>
        </ul>
    </nav>
</header>

<section id="home" class="hero">
    <h1>Welcome to Chandra Prakash Cloth Store</h1>
    <p>Suiting • Shirting • Lehenga • Chunri</p>
</section>

<section id="about" class="about">
    <h2>About Us</h2>
    <p>Chandra Prakash Cloth Store is your destination for premium handmade and ready-made traditional clothing. We offer a stunning range of suiting, shirting, fancy lehengas, and colorful chunris, celebrating the rich heritage of Rajasthan. With a passion for craftsmanship, we bring you the finest in ethnic wear for every occasion.</p>
</section>

<section class="search-filter">
    <input type="text" placeholder="Search products..." id="search">
    <select id="age">
        <option value="">Age</option>
        <option>Kids</option>
        <option>Teens</option>
        <option>Adults</option>
    </select>
    <select id="size">
        <option value="">Size</option>
        <option>S</option>
        <option>M</option>
        <option>L</option>
        <option>XL</option>
    </select>
    <select id="price">
        <option value="">Budget</option>
        <option>Under ₹500</option>
        <option>₹500-₹1000</option>
        <option>Above ₹1000</option>
    </select>
    <button>Filter</button>
</section>

<section id="products" class="products">
    <h2>Our Collections</h2>
    <div class="product-grid">
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\Screenshots\Screenshot 2025-05-07 122731.png" alt="Suits">
            <h3>Suits</h3>
        </div>
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\Screenshots\Screenshot 2025-05-07 140403.png" alt="Shirts">
            <h3>Shirts</h3>
            </div>
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\Screenshots\Screenshot 2025-05-07 144324.png" alt="Chunri">
            
            <h3>Chunri</h3>

         </div>
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\Screenshots\Screenshot 2025-05-07 150017.png"alt="Saree">
            <h3>Saree</h3>

        </div>
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\Screenshots\Screenshot 2025-05-07 145558.png" alt="Lehenga">
            <h3>Leheng</h3>
               </div>
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\Screenshots\Screenshot 2025-05-07 122609.png" alt="Rajasthani">
            <h3>Rajasthani Special</h3>
            </div>
        <div class="product-card">
            <img src="C:\Users\HP\Documents\suittt.jpg" alt="Suit">
            <h3>Suit</h3>
             </div>
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\ritika kurti 2.jpg" alt="Cord set">
            <h3>Cord set</h3>
 </div>
        <div class="product-card">
            <img src="C:\Users\HP\Pictures\short kurta 2.jpg" alt="Short kurta">
            
            <h3>Short Kurta</h3>

             </div>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: vardhan.harsh.singh1@gmail.com | Phone: +91-6376774289</p>
    <p>Address: Near Hawa Mahal, Jaipur, Rajasthan</p>
</section>

<section id="register" class="register">
    <h2>Book or Register</h2>
    <form>
        <input type="text" placeholder="Full Name" required>
        <input type="email" placeholder="Email" required>
        <input type="tel" placeholder="Phone Number" required>
        <textarea placeholder="Message or Booking Details" required></textarea>
        <button type="submit">Submit</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Chandra Prakash Cloth Store. All rights reserved.</p>
</footer>

<script>
    document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            document.querySelector(this.getAttribute('href')).scrollIntoView({
                behavior: 'smooth'
            });
        });
    });
</script>

</body>
</html>
body {
    margin: 0;
    font-family: 'Lato', sans-serif;
    background: url('https://www.shutterstock.com/image-illustration/traditional-indian-rajasthani-wall-painting-260nw-397679494.jpg') center center / cover no-repeat fixed;
    background-blend-mode: lighten;
    color: #333;
}

/* Updated Header Styling */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
   
    color: purple;
    padding: 30px 60px; /* Increased height */
    box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.3);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

/* Enhanced Logo Styling */
.logo {
    font-family: 'Tangerine', cursive;
    font-size: 48px; /* Larger logo text */
    font-weight: bold;
    animation: slideIn 2s ease;
    text-shadow: 2px 2px 8px rgba(255, 255, 255, 0.6); /* Glowing text */
    border-bottom: 2px solid white;
    padding-bottom: 5px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    color: white ;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav a:hover {
    color: #ffcc70;
}

.hero {
    background: url('https://source.unsplash.com/1200x500/?rajasthan,textile') center/cover no-repeat;
    color: white;
    text-align: center;
    padding: 100px 20px;
    animation: fadeIn 2s ease;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
}

@keyframes slideIn {
    from { transform: translateX(-100%); }
    to { transform: translateX(0); }
}

.search-filter {
    display: flex;
    justify-content: center;
    gap: 10px;
    padding: 20px;
    background: rgba(255, 250, 240, 0.8);
}

.search-filter input,
.search-filter select,
.search-filter button {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.products {
    padding: 40px 20px;
    background: rgba(253, 245, 230, 0.9);
}

.products h2 {
    text-align: center;
    margin-bottom: 20px;
    font-family: 'Tangerine', cursive;
    font-size: 36px;
    animation: starryGlow 3s infinite alternate;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.product-card {
    text-align: center;
    background: white;
    padding: 10px;
    border-radius: 10px;
    transition: transform 0.3s;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.product-card:hover {
    transform: scale(1.05) rotate(-1deg);
}

.product-card img {
    width: 100%;
    border-radius: 10px;
}

.about, .contact, .register {
    padding: 40px 20px;
    text-align: center;
    background: rgba(255, 255, 255, 0.8);
    margin-bottom: 20px;
}

.register form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}

.register input,
.register textarea,
.register button {
    width: 80%;
    max-width: 400px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

}

@keyframes starryGlow {
    from { text-shadow: 0 0 10px #ffcc70; }
    to { text-shadow: 0 0 20px #ffcc70, 0 0 30px #ffcc70; }
}

@media (max-width: 600px) {
    .search-filter {
        flex-direction: column;
        align-items: center;
    }
}
