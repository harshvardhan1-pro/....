
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
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/Screenshot%202025-05-07%20150017.png" alt="Saree">
            <h3>Saree</h3>

  </div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/Screenshot%202025-05-07%20145558.png" alt="Lehengha">
            <h3>Lehengha</h3>
   </div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/Screenshot%202025-05-26%20174913.png" alt="Lehengha">
            <h3>Lehengha</h3>              
 </div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/Screenshot%202025-05-07%20122609.png" alt="Rajasthani">
            <h3>Rajasthani Special</h3>
       
 </div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/suittt.jpg" alt="Suit">
            <h3>Suit</h3>
      
</div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/ritika%20kurti%202.jpg" alt="Cord set">
            <h3>Cord set</h3>
 </div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/short%20kurta%202.jpg" alt="Short kurta">
             <h3>Short Kurta</h3>
 </div>
             <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/Screenshot%202025-05-07%20122731.png" alt="Suits">
            <h3>Suits</h3>
 </div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/Screenshot%202025-05-07%20140403.png" alt="Shirts">
            <h3>Shirts</h3>
 </div>
        <div class="product-card">
            <img src="https://raw.githubusercontent.com/harshvardhan1-pro/..../main/Screenshot%202025-05-07%20144324.png" alt="Chunri">
            <h3>Chunri</h3>

   
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

   
  


 

@media (max-width: 600px) {
    .search-filter {
        flex-direction: column;
        align-items: center;
    }
}
