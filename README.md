# Ex.07 Restaurant Website
## Date:22-12-2024

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

html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Little Lemon Restaurant</title>
    <meta name="description" content="Enjoy delicious dishes at Little Lemon.">
    <meta name="author" content="Little Lemon Team">

    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header section -->
    <header>
        <div class="logo">
           
        </div>
        <nav>
            <ul class="nav-menu">
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main content section -->
    <main>
        <!-- Promotional Banner -->
        <section class="promo">
            <h1>Welcome to Little Lemon</h1>
            <p>Your favorite place for unforgettable flavors!</p>
            <p>Explore a fusion of delightful vegetarian and non-vegetarian dishes crafted to satisfy every palate. Discover starters and snacks bursting with flavor and enjoy a dining experience like no other!</p>
        </section>

        <!-- Three columns section -->
        <section class="three-columns">
            <article class="column">
                <h2>Starters & Snacks</h2>
                <img src="73.jpg" alt="Starters and Snacks">
                <p>Begin your culinary journey with our irresistible appetizers, perfect for every occasion.</p>
            </article>
            <article class="column">
                <h2>Vegetarian Delights</h2>
                <img src="74.jpg" alt="Vegetarian Dishes">
                <p>Celebrate nature's best with vibrant, plant-based meals that nourish and satisfy.</p>
            </article>
            <article class="column">
                <h2>Non-Vegetarian Treats</h2>
                <img src="75.jpg" alt="Non-Vegetarian Dishes">
                <p>Enjoy bold, savory flavors with our expertly crafted non-vegetarian dishes.</p>
            </article>
        </section>
    </main>

    <!-- Footer section -->
    <footer>
        <div class="footer-left">
            
        </div>
        <div class="footer-right">
            <p>Designed and Developed by Jawahar</p>
        </div>
    </footer>

</body>
</html>

styles.css

 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    line-height: 1.6;
    background-color: #f9f9f9;
}

/* Header Section */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #ffcc00;
    padding: 10px 20px;
}

.logo img {
    max-height: 60px;
}

.nav-menu {
    list-style: none;
    display: flex;
    gap: 15px;
}

.nav-menu li {
    display: inline;
}

.nav-menu a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
    transition: color 0.3s;
}

.nav-menu a:hover {
    color: #0073e6;
}

/* Main Section */
main {
    padding: 20px;
    background-color: #ffffff;
}

/* Promo Section */
.promo {
    text-align: center;
    margin-bottom: 20px;
}

.promo img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-top: 10px;
}

.promo h1 {
    font-size: 2.5em;
    color: #444;
}

.promo p {
    margin-top: 10px;
    color: #666;
}

/* Three Columns Section */
.three-columns {
    display: flex;
    justify-content: space-between;
    gap: 20px;
}

.column {
    flex: 1;
    padding: 15px;
    background-color: #f3f3f3;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.column img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 10px;
}

.column h2 {
    font-size: 1.5em;
    color: #555;
    margin-bottom: 10px;
}

.column p {
    color: #777;
    margin-top: 10px;
}

/* Footer Section */
footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #444;
    color: #fff;
    padding: 10px 20px;
}

.footer-left img {
    max-height: 40px;
}

.footer-right p {
    margin: 0;
    font-size: 0.9em;
}


```

## OUTPUT:
![Screenshot (4)](https://github.com/user-attachments/assets/4b0a6dc6-ded1-4824-b9c6-dc19ce3ea696)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
