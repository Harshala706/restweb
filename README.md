# Ex.07 Restaurant Website
## Date: 10-04-2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Delicious Eats | Colorful Style</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #e74c3c, #f39c12);
      padding: 20px;
      text-align: center;
      color: #fff;
    }

    nav a {
      color: #fff;
      margin: 0 12px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
    }

    section {
      margin-bottom: 50px;
    }

    h2 {
      color: #2c3e50;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }

    .menu-section {
      background-color: #ffebee;
      border-left: 6px solid #e53935;
      padding: 15px;
      margin: 15px 0;
      border-radius: 8px;
    }

    .menu-section h3 {
      color: #c62828;
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    .service-item {
      background-color: #e3f2fd;
      border-left: 6px solid #1e88e5;
      padding: 15px;
      margin: 15px 0;
      border-radius: 8px;
    }

    .service-item h3 {
      color: #1565c0;
    }

    .contact-info {
      background-color: #e8f5e9;
      border-left: 6px solid #43a047;
      padding: 15px;
      border-radius: 8px;
    }

    .contact-form {
      margin-top: 15px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .contact-form input,
    .contact-form textarea {
      padding: 10px;
      font-size: 16px;
      border: 2px solid #ddd;
      border-radius: 6px;
    }

    .contact-form button {
      background-color: #e74c3c;
      color: #fff;
      padding: 12px;
      font-size: 16px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .contact-form button:hover {
      background-color: #c0392b;
    }

    footer {
      background-color: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Delicious Eats</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#menu">Menu</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <!-- Home -->
    <section id="home">
      <h2>Welcome to Delicious Eats</h2>
      <p>We serve mouth-watering dishes with love and care. Experience the best taste in town.</p>
    </section>

    <!-- Menu -->
    <section id="menu">
      <h2>Our Menu</h2>

      <div class="menu-section">
        <h3>Starters</h3>
        <ul>
          <li>Tomato Soup - ₹99</li>
          <li>Chilli Paneer - ₹139</li>
          <li>Chicken Manchurian - ₹200</li>
          <li>Gobi Manchurian - ₹129</li>
        </ul>
      </div>

      <div class="menu-section">
        <h3>Main Course</h3>
        <ul>
          <li>Special Chicken Biryani - ₹189</li>
          <li>Mutton Biryani - ₹200</li>
          <li>Ragi Sangati with Natu Kodi - ₹240</li>
          <li>Ragi Sangati with Fish Curry - ₹260</li>
          <li>Butter Naan with Prawns Curry - ₹280</li>
        </ul>
      </div>

      <div class="menu-section">
        <h3>Desserts</h3>
        <ul>
          <li>Honey Cake - ₹150</li>
          <li>Chocolate Lava Cake - ₹200</li>
          <li>Red Velvet Cake - ₹189</li>
        </ul>
      </div>

      <div class="menu-section">
        <h3>Ice Creams</h3>
        <ul>
          <li>Vanilla Scoop - ₹60</li>
          <li>Chocolate Scoop - ₹70</li>
          <li>Strawberry Scoop - ₹60</li>
          <li>Fresh Mango Scoop - ₹70</li>
          <li>Pista Delight - ₹70</li>
        </ul>
      </div>

      <div class="menu-section">
        <h3>Drinks</h3>
        <ul>
          <li>Lemon Soda - ₹30</li>
          <li>Coke - ₹25</li>
          <li>Pepsi - ₹25</li>
        </ul>
      </div>
    </section>

    <!-- Services -->
    <section id="services">
      <h2>Our Services</h2>

      <div class="service-item">
        <h3>Dine-In</h3>
        <p>Relax and enjoy a great meal in our cozy dining space.</p>
      </div>

      <div class="service-item">
        <h3>Takeaway</h3>
        <p>Grab your favorites quickly with our fast takeaway service.</p>
      </div>

      <div class="service-item">
        <h3>Delivery</h3>
        <p>We deliver happiness hot and fresh to your doorstep.</p>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Contact Us</h2>

      <div class="contact-info">
        <p><strong>Address:</strong> Opp to 80 Feet Road, Ram Nagar, Anantapur, Andhra Pradesh, 515004</p>
        <p><strong>Phone:</strong> +91 85542 24004</p>
        <p><strong>Email:</strong> hello@deliciouseats.com</p>
      </div>

      <form class="contact-form">
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Delicious Eats. Designed with ❤️ in India.</p>
  </footer>

</body>
</html>
```
## OUTPUT:
![Screenshot 2025-05-16 234132](https://github.com/user-attachments/assets/76115353-50a7-4fbf-9328-38e69e53e773)
![Screenshot 2025-05-16 234152](https://github.com/user-attachments/assets/6dfcb38c-d8ca-409a-b71d-c40b6902d066)
![Screenshot 2025-05-16 234211](https://github.com/user-attachments/assets/ee4c6686-0935-4b3a-8ab3-b41dd68d5adc)
![Screenshot 2025-05-16 234228](https://github.com/user-attachments/assets/39e51426-e83e-494e-9b99-dda4aa6a12d1)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
