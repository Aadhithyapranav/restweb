# Ex.07 Restaurant Website
## Date:24-12-2024

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
index.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to teriyaki</title>
    <style>
        body {
            font-family: 'Georgia', serif; /* Changed font */
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f0f4f8; /* New background color */
        }
        .banner {
            background-color: rgba(244, 162, 97, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #264653;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Welcome to Teriyaki</h1>
        <p>Experience the taste of excellence!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>About Us</h2>
        <p>At teriyaki, we are committed to serving delicious, fresh, and delightful meals to tantalize your taste buds. Join us for an unforgettable dining experience.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>Authentic and fresh ingredients.</li>
            <li>Friendly and professional staff.</li>
            <li>A warm and inviting atmosphere.</li>
        </ul>
    </div>

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="f1.jpg" alt="Delicious Food 1">
        <img src="f2.jpg" alt="Delicious Food 2">
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: Aadhithya Pranav</p>
    </footer>
</body>
</html>

administration.html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Teriyaki</title>
    <style>
        /* Importing Google font 'Roboto' */
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;600&display=swap');

        body {
            font-family: 'Roboto', sans-serif; /* Updated font */
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f6f8; /* Changed background color */
        }
        .banner {
            background-color: #FF7043; /* Banner background color */
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .admin-section {
            padding: 20px;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .admin-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .admin-card h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .admin-card p {
            font-size: 14px;
            color: #555;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Meet Our Administration</h1>
        <p>The team behind Teriyaki's success</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Administration Section -->
    <div class="admin-section">
        <h2>Our Dedicated Team</h2>
        <div class="admin-grid">
            <div class="admin-card">
                <img src="admin1.jpg" alt="Admin 1">
                <h3>VIJAY</h3>
                <p>C.E.O</p>
                <p>EMAIL:vijay@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="admin2.jpg" alt="Admin 2">
                <h3>GORDON RAMSAY</h3>
                <p>Head Chef</p>
                <p>EMAIL:GR@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="admin3.jpg" alt="Admin 3">
                <h3>TOM CRUISE</h3>
                <p>MENU CURATOR</p>
                <p>EMAIL:TOM@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="admin4.jpg" alt="Admin 4">
                <h3>THOMAS SHELBY</h3>
                <p>MARKETING MANAGER</p>
                <p>TOMMYSHELBY@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="admin5.jpg" alt="Admin 5">
                <h3>PEP GUARDIOLA</h3>
                <p>FINANCE MANAGER</p>
                <p>EMAIL:PEP@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="admin6.jpg" alt="Admin 6">
                <h3>LIONEL MESSI</h3>
                <p>PUBLIC RELATIONS OFFICER</p>
                <p>EMAIL:LEO@gmail.com</p>
            </div>
        </div>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: Aadhithya Pranav</p>
    </footer>
</body>
</html>
  
menu.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Our Specialties</title>
    <style>
        /* Adding Google font 'Roboto' */
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif; /* Updated font */
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f0f4f8; /* Changed background color */
        }
        h2 {
            background-color: #2a9d8f;
            color: white;
            padding: 20px;
        }
        table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        img {
            width: 100px;
            height: auto;
            border-radius: 8px;
        }
        caption {
            font-size: 1.5em;
            margin: 10px 0;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <h2>Our Specialties</h2>
    <table>
        <caption>Delicious Indian Cuisine</caption>
        <tr>
            <td><img src="f1.jpg" alt="Food Item 1"></td>
            <td>
                <h3>1. BUTTER CHICKEN</h3>
                <p>Creamy and flavorful chicken cooked in a rich tomato-based gravy.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f2.jpg" alt="Food Item 2"></td>
            <td>
                <h3>2. CHOLE BHATURE</h3>
                <p>Spicy chickpeas served with a fluffy, deep-fried bread.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f3.jpg" alt="Food Item 3"></td>
            <td>
                <h3>3. BIRYANI</h3>
                <p>Fragrant rice dish with a mix of aromatic spices and marinated meat.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f4.jpg" alt="Food Item 4"></td>
            <td>
                <h3>4. PALAK PANEER</h3>
                <p>Paneer cubes cooked in a smooth, spiced spinach gravy.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f5.jpg" alt="Food Item 5"></td>
            <td>
                <h3>5. ALOO PARATHA</h3>
                <p>Stuffed flatbread made with spiced mashed potatoes, served with yogurt and pickle.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f6.jpg" alt="Food Item 6"></td>
            <td>
                <h3>6. TANDOORI CHICKEN</h3>
                <p>Juicy, marinated chicken cooked in a traditional tandoor oven.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f7.jpg" alt="Food Item 7"></td>
            <td>
                <h3>7. SAMOSA</h3>
                <p>Deep-fried pastry pockets filled with spiced potatoes and peas.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f8.jpg" alt="Food Item 8"></td>
            <td>
                <h3>8. DOSA</h3>
                <p>Crispy, thin rice crepes served with coconut chutney and sambar.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f9.jpg" alt="Food Item 9"></td>
            <td>
                <h3>9. PAV BHAJI</h3>
                <p>Spicy mashed vegetables served with buttered pav (bread rolls).</p>
            </td>
        </tr>
        <tr>
            <td><img src="f10.jpg" alt="Food Item 10"></td>
            <td>
                <h3>10. MALAI KOFTA</h3>
                <p>Deep-fried vegetable balls in a creamy, flavorful gravy.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f11.jpg" alt="Food Item 11"></td>
            <td>
                <h3>11. GULAB JAMUN</h3>
                <p>Sweet, syrup-soaked dumplings made of milk solids and flour.</p>
            </td>
        </tr>
        <tr>
            <td><img src="f12.jpg" alt="Food Item 12"></td>
            <td>
                <h3>12. MANGO LASSI</h3>
                <p>A refreshing yogurt-based drink with the sweet flavor of ripe mangoes.</p>
            </td>
        </tr>
    </table>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: Aadhithya Pranav</p>
    </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Teriyaki</title>
    <style>
        /* Importing Google font 'Poppins' */
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

        body {
            font-family: 'Poppins', sans-serif; /* Updated font */
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #e3f2fd; /* Changed background color */
        }
        .banner {
            background-color: #1e88e5; /* Banner background color */
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .contact-section {
            padding: 20px;
        }
        .contact-details {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 500px;
            text-align: left;
        }
        .contact-details h2 {
            font-size: 20px;
            margin-bottom: 15px;
        }
        .contact-details p {
            font-size: 16px;
            margin: 5px 0;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Contact Us</h1>
        <p>We would love to hear from you!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Contact Section -->
    <div class="contact-section">
        <h2>Get in Touch</h2>
        <div class="contact-details">
            <h2>Our Address</h2>
            <p>valasaravakkam</p>
            <p>CHENNAI</p>

            <h2>Phone</h2>
            <p>7892067842</p>

            <h2>Email</h2>
            <p><a href="mailto:info@teriyaki.com">info@teriyaki.com</a></p>
        </div>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: Aadhithya Pranav</p>
    </footer>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-25 130312.png>)
![alt text](<Screenshot 2024-12-25 130342.png>)
![alt text](<Screenshot 2024-12-25 130355.png>)
![alt text](<Screenshot 2024-12-25 130408.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
