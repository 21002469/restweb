# Ex.07 Restaurant Website
## Date:11-11-2024

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
index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Restaurant</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Discover Delicious Meals!</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="Dhokla.jpg" alt="Gujarat special">
                    <h4>Dhokla</h4>
                    <p>Dhokla is an authentic snack which has originated from the state of Gujarat.</p>
                </div>
                <div class="food-item">
                    <img src="kosha mangsho.jpg" alt="West bengal special">
                    <h4>kosha mangsho</h4>
                    <p>Kosha Mangsho is a traditional dish prepared of Mutton (Goat meat) in every Bengali house.</p>
                </div>
                <div class="food-item">
                    <img src="Litti_chokha_.webp" alt="Bihar special">
                    <h4>Litti chokha</h4>
                    <p>The lip-smacking taste of Litti Chokha, savoured by one and all, needs no introduction.</p>
                </div>
                <div class="food-item">
                    <img src="pongal.jpg" alt="Tamil Nadu special">
                    <h4>sweet pongal</h4>
                    <p>This is a staple meal during every auspicious festival of Tamil Nadu.</p>
                </div>
            </section>
        </main>
        
        
        <footer>
            <p>Narendra</p>
            <p>212221040117</p>
        </footer>
    </div>
</body>
</html>
```
menu.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Menu</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Delicious Food Items</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="Hyderabadi biryani.jpg" alt="Hyderabadi biryani">
                    <h4>Hyderabadi biryani</h4>
                </div>
                <div class="food-item">
                    <img src="Kafuli.jpg" alt="Kafuli">
                    <h4>Kafuli</h4>
                </div>
                <div class="food-item">
                    <img src="PoothaRekulu.jpg" alt="PoothaRekulu">
                    <h4>PoothaRekulu</h4>
                </div>
                <div class="food-item">
                    <img src="Goa fish curry.jpg" alt="Gao fish curry">
                    <h4>Goa fish curry</h4>
                </div>
                <div class="food-item">
                    <img src="Dhaam.jpg" alt="Dhaam">
                    <h4>Dhaam</h4>
                </div>
                <div class="food-item">
                    <img src="Dhokla.jpg" alt="Dhokla">
                    <h4>Dhokla</h4>
                </div>
                <div class="food-item">
                    <img src="rugra.jpg" alt="Rugra">
                    <h4>Rugra</h4>
                </div>
                <div class="food-item">
                    <img src="Rogan-Josh.jpg" alt="Rogan-Josh">
                    <h4>Rogan-Josh</h4>
                </div>
                <div class="food-item">
                    <img src="pongal.jpg" alt="pongal">
                    <h4>pongal</h4>
                </div>
                <div class="food-item">
                    <img src="kosha mangsho.jpg" alt="kosha mangsho">
                    <h4>kosha mangsho</h4>
                </div>
                <div class="food-item">
                    <img src="Litti_chokha_.webp" alt="Litti chokha">
                    <h4>Litti chokha</h4>
                </div>
                <div class="food-item">
                    <img src="Appam.jpg" alt="Appam">
                    <h4>Appam</h4>
                </div>
            </section>
        </main>
        
        <footer>
            <p>Narendra</p>
            <p>212221040117</p>
        </footer>
    <div>
    
</body>
</html>
```
contact.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Contact Us</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Get in Touch</h2>
            <p>Address: 123 Delicious St, Food City, Chennai</p>
            <p>Phone: 456-7890</p>
            <p>Email: landelight@restaurant.com</p>
        </main>
        <footer>
            <p>Narendra</p>
            <p>212221040117</p>
        </footer>

    </div>
    
</body>
</html>
```
administration.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Administration</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Meet Our Team</h2>
            <div class="team">
                <div class="member">
                    <img src="Narendra.jpg" alt="Admin 1">
                    <p>Narendra - Manager</p>
                </div>
                <div class="member">
                    <img src="varun.jpg" alt="Admin 2">
                    <p>Varun - Chef</p>
                </div>
                <div class="member">
                    <img src="maheswar.jpg" alt="Admin 3">
                    <p>Maheswar - Waiter</p>
                </div>
                <div class="member">
                    <img src="mothish.jpg" alt="Admin 4">
                    <p>Mothish - Bartender</p>
                </div>
                <div class="member">
                    <img src="sai vinay.jpg" alt="Admin 5">
                    <p>sai vinay - Host</p>
                </div>
                <div class="member">
                    <img src="wasim.jpg" alt="Admin 6">
                    <p>wasim - Accountant</p>
                </div>
            </div>
        </main>
        <footer>
            <p>Narendra</p>
            <p>212221040117</p>
        </footer>

    </div>
    
</body>
</html>
```
styles.css:
```
/* General Reset */
* {
    box-sizing: border-box;
}

html, body {
    height: 100%;
    margin: 0;
    font-family: 'Helvetica Neue', sans-serif;
    color: #333333;
}

/* Container Setup */
.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

/* Header Styling */
header {
    background-color: #34495e; /* Dark slate blue */
    color: #f8f9fa; /* Light text color */
    padding: 20px;
    text-align: center;
    font-size: 1.8em;
    font-weight: bold;
}

/* Navigation Styling */
nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    color: #f8f9fa;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #3498db; /* Light blue hover color */
}

/* Typography */
h1, h2 {
    margin: 10px 0;
    color: #2c3e50; /* Dark slate */
}

/* Main Content Styling */
main {
    flex: 1;
    padding: 30px;
    background-color: #ecf0f1; /* Light gray for contrast */
}

/* Team Section */
.team {
    display: flex;
    flex-wrap: wrap;
    gap: 20px; /* Spacing between items */
    justify-content: center;
    margin-top: 20px;
}

.member {
    width: 10%;
    margin: 10px;
    text-align: center;
    background-color: #ffffff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    border-radius: 15px;
    padding: 15px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 10px;
}

/* Footer Styling */
footer {
    text-align: center;
    padding: 20px;
    background-color: #34495e; /* Same as header */
    color: #f8f9fa;
}

/* Menu Section */
.menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly; /* Space out items evenly */
    margin: 30px 0;

}

.food-item {
    width: 10%;
    margin: 10px;
    text-align: center;
    background-color: #ffffff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    border-radius: 8px;
    padding: 15px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.food-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
}

.food-item img {
    width: 80%; /* Scale image within container */
    height: auto;
    border-radius: 8px;
    margin-bottom: 10px;
}

/* Responsive Design */
@media (max-width: 768px) {
    .member, .food-item {
        width: 90%; /* Full width on smaller screens */
        margin: 10px auto;
    }
}

```

## OUTPUT:
![Screenshot (33)](https://github.com/user-attachments/assets/97871ecb-94e9-4c29-a63e-c5595a13a61d)
![Screenshot (34)](https://github.com/user-attachments/assets/29420ed3-e4f8-4dd0-85cf-af01f2c7fc5b)
![Screenshot (35)](https://github.com/user-attachments/assets/85a1195b-2d10-42d6-bdeb-eebd2a5ced23)
![Screenshot (36)](https://github.com/user-attachments/assets/2f34dd98-fe5f-4b68-8686-912c0b25d232)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
