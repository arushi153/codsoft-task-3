<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VivahVastra - Celebrate Every Wedding With Elegance</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #fdf7f9;
        }
        header {
            background: url('https://www.example.com/elegant-wedding-background.jpg') no-repeat center center/cover;
            height: 50vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            position: relative;
        }
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
        }
        header h1 {
            font-size: 3.2rem;
            z-index: 1;
            animation: fadeInDown 2s ease;
        }
        header p {
            font-size: 1.5rem;
            margin: 1rem 0;
            z-index: 1;
            animation: fadeInUp 2s ease;
        }
        header a {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            background-color: #f28e90;
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 8px;
            transition: background-color 0.3s ease;
            z-index: 1;
        }
        header a:hover {
            background-color: #ff6e71;
        }
        @keyframes fadeInDown {
            0% { opacity: 0; transform: translateY(-50px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(50px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        section h2 {
            font-size: 2.5rem;
            color: #333;
            margin-bottom: 1rem;
        }
        section p {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 1.5rem;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }
        .product-card {
            background-color: white;
            border-radius: 15px;
            box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-10px);
        }
        .product-card img {
            width: 100%;
            height: auto;
        }
        .product-card h3 {
            font-size: 1.8rem;
            color: #444;
            padding: 1rem;
        }
        .product-card p {
            font-size: 1rem;
            color: #666;
            padding: 0 1rem 1.5rem;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }
        .service-card {
            background-color: #f7e7e7;
            border-radius: 15px;
            padding: 2rem;
            text-align: center;
            box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-10px);
        }
        .service-card h3 {
            font-size: 1.8rem;
            color: #444;
            margin-bottom: 1rem;
        }
        .service-card p {
            font-size: 1rem;
            color: #666;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 2rem 1rem;
            text-align: center;
        }
        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
        .customer-reviews {
            background-color: #f28e90;
            padding: 3rem 1rem;
            color: white;
            text-align: center;
        }
        .review-box {
            background-color: white;
            color: #333;
            margin: 1rem;
            padding: 1.5rem;
            border-radius: 10px;
            display: inline-block;
            width: 250px;
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .review-box:hover {
            transform: translateY(-10px);
        }
        .review-box h4 {
            font-size: 1.4rem;
            margin-bottom: 0.5rem;
        }
        .review-box p {
            font-size: 1rem;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>VivahVastra</h1>
        <p>Elegance and Tradition for Every Wedding</p>
        <a href="#shop-now">Shop Now</a>
    </header>
    <section>
        <h2>Our Collections</h2>
        <p>Explore our exclusive range of wedding attire for every celebration.</p>
        <div class="products">
            <div class="product-card">
                <img src="bride dress.jpg" alt="Bridal Lehenga">
                <h3>Bridal Lehenga</h3>
                <p>Intricately designed lehengas to make your wedding day unforgettable.</p>
            </div>
            <div class="product-card">
                <img src="groom dress.jpg" alt="Groom Sherwani">
                <h3>Groom Sherwani</h3>
                <p>Elegant sherwanis with traditional craftsmanship for a royal look.</p>
            </div>
            <div class="product-card">
                <img src="familyy.jpg" alt="Family Attire">
                <h3>Family Attire</h3>
                <p>Beautiful outfits for the entire family to celebrate in style.</p>
            </div>
        </div>
    </section>
    <section>
        <h2>Our Services</h2>
        <p>We offer a range of services to make your wedding shopping experience effortless and special.</p>
        <div class="services">
            <div class="service-card">
                <h3>Customization</h3>
                <p>Get your dream outfit custom-made with our tailored services for the perfect fit and design.</p>
            </div>
            <div class="service-card">
                <h3>On-Time Delivery</h3>
                <p>We ensure timely delivery, so you can enjoy a stress-free wedding shopping experience.</p>
            </div>
            <div class="service-card">
                <h3>Styling Assistance</h3>
                <p>Our expert stylists are here to guide you in selecting the perfect ensemble for your big day.</p>
            </div>
        </div>
    </section>
    <section class="customer-reviews">
        <h2>What Our Customers Say</h2>
        <div class="review-box">
            <h4>Radhika S.</h4>
            <p>“The lehenga was absolutely stunning. I felt like a queen on my big day!”</p>
        </div>
        <div class="review-box">
            <h4>Aditya M.</h4>
            <p>“VivahVastra’s sherwani collection is unmatched. The fit and design were perfect!”</p>
        </div>
        <div class="review-box">
            <h4>Neha K.</h4>
            <p>“I bought outfits for my family, and we received so many compliments!”</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 VivahVastra - All Rights Reserved</p>
    </footer>
</body>
</html>
# codsoft-task-3
