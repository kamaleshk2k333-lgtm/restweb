# Ex.07 Restaurant Website
## Date:25/12/2025

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
add.css

body {
       font-family: Arial, sans-serif;
    background-color: #d0f70e;
    margin: 0;
    padding: 1;
    box-sizing: border-box;
}
h1
{
    padding-top: 2px;
    font-size: 10px;
    color:coral;
    letter-spacing: 20px;

}
nav {
    background-color: #333;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 8px;
    display: inline-block;
}
nav a:hover {
    background-color: #f2c57c; 
    color: #333;
}
section {
    padding: 40px;
    text-align: center;
}
h2 {
    color: #b33a3a;
    font-style:oblique;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.menu-grid{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 1000px;
    margin: 20px auto;
    text-align: center;
}
.card {
    background-color: white;
    display: flex;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    font-style: italic;
    color:#b33a3a;
    text-shadow:#f2c57c;
}
.card img {
    width: 80px;
    height: 100px;
    object-fit: cover;
    border-radius: 25px;
    align-items: center;
    border: #f2c57c;
    

yy  {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            padding: 20px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .yy h2 {
            text-align: center;
            color: #b33a3a;
        }
        .yy p {
            font-size: 18px;
            margin: 10px 0;
        }
        .yy b {
            color: #b33a3a;
        }
        }
footer {
    background-color:#333;
    color: white;
    
    text-align: center;
    padding: 15px;
}

home.html

<!DOCTYPE html>
<html>
<head>
    <title>EREN Restaurant</title>
    <link rel="stylesheet" href="add.css">
</head>
<body>
    <h1>EREN Restaurant</h1>
<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="BOOK.jpg" alt="Restaurant Banner" style="width:90%; max-width:800px; border-radius:9px;">
    
    <p>"Meat lovers, this one's for your bucket list."</p>
</section>

<footer>
    &copy Designed by KAMALESHKUMAR K(25012000) .
</footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html>
<head>
   
    <title>EREN Restaurant - Menu</title>
    <link rel="stylesheet" href="add.css">
</head>
<body>
    <h1>EREN Restaurant</h1>
<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <div class="card"><img src="dosa.png"><p> - rs-199</p></div>
        <div class="card"><img src="chicken.png"><p>Chicken 65 - rs-130</p></div>
        <div class="card"><img src="mutton.jpg"><p>Mutton Chukka  - rs-1150</p></div>
        <div class="card"><img src="briyani.png"><p>chicken Briyani - rs-2150</p></div>
        <div class="card"><img src="tea.jpg"><p>tea  - rs-2500</p></div>
        <div class="card"><img src="apple.jpg"><p>Apple Juice - rs-190</p></div>
    </div>
</section>

<footer>
    &copy Designed by KAMALESHKUMAR K(25012000) .
</footer>
</body>
</html>

admin.html

<!DOCTYPE html>
<html>
<head>
    <title>EREN Restaurant - Administration</title>
    <link rel="stylesheet" href="add.css">
</head>
<body>
    <h1>EREN Restaurant</h1>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Meet Our Team</h2>
    <div class="team">
        <div class="card"><img src="my  pho.jpeg" ><p>Person 1 - Manager</p></div>
        <div class="card"><img src="asta.jpg"><p>Person 2 - Head chef</p></div>
        <div class="card"><img src="die.jpg"><p>Person 3 - CEO</p></div>
        <div class="card"><img src="ling.jpg"><p>Person 4 - assistant manager</p></div>
        <div class="card"><img src="eee.jpg"><p>Person 5 - cashier </p></div>
    </div>
</section>

<footer>
   &copy Designed by KAMALESHKUMAR K(25012000) .
</footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>

    <title>EREN Restaurant - Contact Us</title>
    <link rel="stylesheet" href="add.css">
    
        
        
</head>
<body>
    <h1>EREN Restaurant</h1>
<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="yy">
        <h2>Contact Us</h2>
        <p>number-+91 9025874102</p>
        <p>Address-chennai royal next era end 600002</p>
        <p>Email-eren@gmail.com</p>
        <p>Opening Timing-MON-SUN: 10:00 AM - 1:00 PM</p>
    </div>
</section>

<footer>
    &copy Designed by KAMALESHKUMAR K(25012000) .
</footer>

</body>
</html>



```

## OUTPUT:
<img width="1444" height="785" alt="res 0" src="https://github.com/user-attachments/assets/301648b3-2119-4175-94da-86a91f5b250e" />
<img width="1102" height="730" alt="res 1" src="https://github.com/user-attachments/assets/47987446-b47c-432b-9801-6c83b548bcbf" />
<img width="1097" height="733" alt="res 2" src="https://github.com/user-attachments/assets/6fdbf4cf-a52c-4e48-88ce-aca7f86d4322" />
<img width="1104" height="734" alt="res 3" src="https://github.com/user-attachments/assets/9e4202ab-e7a8-4dfd-a74b-fadb3ab6b902" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
