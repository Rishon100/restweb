# Ex.07 Restaurant Website
## Date:

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
home.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>WELCOME TO NEON RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to neon restaurant, where we serve the finest dishes made from the freshest ingredients. Our chefs are dedicated to providing you with an unforgettable dining experience.</p>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-container">
            <div class="menu-left">
                <ul>
                    <li>
                        <img src="sandwich.png" width="300">
                        <b>chicken Sandwich - 149 Rs</b>
                    </li>
                    <li>
                        <img src="soup.png" width="300">
                        <b>Tomato Soup - 99 Rs</b>
                    </li>
                    <li>
                        <img src="sushi.png" width="300">
                        <b>Sushi - 399 Rs</b>
                        </li> 
                    </li>
                </ul>
            </div>
            <div class="menu-right">
                <ul>
                    <li>
                        <img src="burger.png"  width="400" height="240">
                        <b>cheese burger- 299 Rs</b>
                    </li>
                    <li>
                        <img src="pizza.png"  width="400">
                       <b> Pizza - 499 Rs</b>
                    </li>
                    <li>
                        <img src="fries.png"  width="400">
                         <b>French Fries - 199 Rs</b>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: neonrestaurant@gmail.com</p>
        <p>Phone: (123) 456-7890</p>
        <p>Address: 12345, chennai </p>
    </section>

    <footer>
        <p>&copy; 2024 Neon Restaurant. All rights reserved.</p>
    </footer>
</body>
</html>

styles.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    font-size: large;
    background-image: url('purple.png');
    background-size: cover; 
    background-position: center; 
    background-repeat: no-repeat; 
    padding: 20px;
    color: white;
}

header {
    background: #ff6347; 
    color: rgb(246, 240, 245);
    padding: 10px 0;
    text-align: center;
    font-style: oblique;
    border-radius: 20px;
}



nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: rgb(15, 14, 14);
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 10px;
}

h2 {
    color: #f552e2; 
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #88bc19;
    color: rgb(240, 240, 230);
    position: relative;
    bottom: 0;
    width: 100%;
}
.menu-container {
    display: flex;
    justify-content: space-between;
}

.menu-left, .menu-right {
    width: 48%; 
}

.menu-left ul, .menu-right ul {
    list-style: none;
    padding: 0;
    font-size: large;
}

.menu-left li, .menu-right li {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
}

.menu-left li img, .menu-right li img {
    margin-right: 10px;
    border-radius: 45px;
}

```


## OUTPUT:
![alt text](<Screenshot 2024-12-12 200338.png>)
![alt text](<Screenshot 2024-12-12 200445.png>)
![alt text](<Screenshot 2024-12-12 200406.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
