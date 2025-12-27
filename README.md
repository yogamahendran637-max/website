# Ex.06 Restaurant Website
# Date:09/12/25
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Foodie's Delight</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #F5F5F5;
      color: #333;
    }

    header {
      background-image: url('banner.jpg'); 
      background-size: cover;
      background-position: center;
      height: 250px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 36px;
      font-weight: bold;
      text-shadow: 2px 2px 5px #000;
    }

    nav {
      background-color: #2E8B57;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 15px 25px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      background-color: #FFD700;
      color: #2E8B57;
    }

    section {
      padding: 40px;
      text-align: center;
    }

    .menu-grid, .admin-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
      margin-top: 30px;
    }

    .menu-item, .admin-card {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .menu-item img, .admin-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
    }

    .admin-card h3 {
      margin: 10px 0 5px;
    }

    .admin-card p {
      margin: 0;
      font-style: italic;
    }

    footer {
      background-color: #2E8B57;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>Welcome to Foodie's Delight</header>

  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#admin">Administration</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <section id="home">
    <h2>Home</h2>
    <h2>Experience the Taste of Tradition</h2>
    <p>Welcome to Food's Delight — where flavor meets tradition. Nestled in the heart of Chennai, our restaurant offers a warm, inviting atmosphere and a menu inspired by the rich culinary heritage of India. From sizzling tandoori platters to aromatic biryanis and handcrafted desserts, every dish is prepared with passion and the finest ingredients. Whether you're joining us for a family dinner, a festive celebration, or a quiet meal for two, Food's Delight promises an unforgettable dining experience that delights every sense.
</p>

    <p>Discover delicious dishes and meet the team behind your favorite flavors.</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
      <div class="menu-item"><img src="food1.jpg"><p>Margherita Pizza</p></div>
      <div class="menu-item"><img src="food2.jpg"><p>Paneer Tikka</p></div>
      <div class="menu-item"><img src="food3.jpg"><p>Veg Biryani</p></div>
      <div class="menu-item"><img src="food4.png"><p>Butter Chicken</p></div>
      <div class="menu-item"><img src="food5.jpg"><p>Idli Sambar</p></div>
      <div class="menu-item"><img src="food6.jpg"><p>Fish Curry</p></div>
      <div class="menu-item"><img src="food7.jpg"><p>Masala Dosa</p></div>
      <div class="menu-item"><img src="food8.jpg"><p>Chicken Tandoori</p></div>
      <div class="menu-item"><img src="food9.jpg"><p>Rasgulla</p></div>
      <div class="menu-item"><img src="food10.jpg"><p>Fruit Salad</p></div>
    </div>
  </section>

  <section id="admin">
    <h2>Administration</h2>
    <div class="admin-grid">
      <div class="admin-card"><img src="person1.jpg"><h3>Catherine</h3><p>Manager</p></div>
      <div class="admin-card"><img src="person2.jpg"><h3>Aravind</h3><p>Chef</p></div>
      <div class="admin-card"><img src="person3.jpg"><h3>Arun Das</h3><p>Marketing Head</p></div>
      <div class="admin-card"><img src="person4.jpg"><h3>Neha</h3><p>HR Executive</p></div>
      <div class="admin-card"><img src="person5.jpg"><h3>Lavanya</h3><p>Finance Officer</p></div>
      <div class="admin-card"><img src="person6.jpg"><h3>Karthik</h3><p>Operations Lead</p></div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Thank You for Visiting Food's Delight
Thank you for taking the time to visit our website. We're truly honored to have you here. At Food's Delight, we believe that great food is more than just a meal — it's an experience, a celebration of flavor, culture, and connection. Whether you're browsing our menu, learning about our team, or planning your next visit, we hope you've felt the warmth and passion that drives everything we do.
Your interest and support mean the world to us. We look forward to welcoming you in person and serving you the finest dishes crafted with care and tradition. Until then, stay connected, stay hungry, and remember — at Food's Delight, every bite tells a story.
Warm regards,
The Food's Delight Team
</p>
    <p>📍 123 Food Street, Mambalam, Chennai, Tamil Nadu</p>
    <p>📞 +91 1234567890</p>
    <p>📧 contact@foodiesdelight.in</p>
  </section>

  <footer>
    Designed by PriyaRithanya
  </footer>

</body>
</html>
```
# OUTPUT:
<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/008f5135-2d8a-4d54-813c-2deff7f783e6" />
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/77b1953d-94b2-48ff-a708-4c97b5b662d4" />
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/4ff0898d-bfcd-4e12-acb9-eefac3d9d8b1" />
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/d80947e8-54c0-4664-a3ce-f9961485a3d5" />




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
