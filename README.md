# Ex.06 Restaurant Website
## Date:26/12/2025

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
Home.html

<html>
<head>
    <title>Restaurant Special Menu</title>
    <link rel="stylesheet" href="Home.css">

</head>
<body>

<div class="border-box">

<header>
    <div class="logo">Ruchis Restaurant</div>
    <nav>
        <a href="Home.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="Admin.html">ADMIN</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="container">
    <div class="text-section">
        <h1>Today's<br>Special Menu</h1>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Phasellus ac varius sem. Fusce posuere risus arcu,
            nec porttitor lorem viverra id.
        </p>
        

    </div>

    <div class="image-section">
        <img src="6.png" alt="Food Image">
    </div>
</section>

</div>

 <footer>
         E.Vamsi Krishna - (25005454)
 </footer>


</body>
</html>
 
 Home.css
 body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: rgb(6, 6, 6);
            color: rgb(245, 245, 245);
        }

        /* HEADER */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 80px;
        }

        .logo {
            font-size: 24px;
            color: rgb(255, 255, 2);
            font-weight: bold;
        }
        
       /* Navbar */
        nav a {
            margin-left: 40px;
            text-decoration: none;
            color: rgb(0, 0, 0);
            font-size: 16px;
            background-color: rgb(243, 249, 255);
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* MAIN SECTION */
        .container {
            display: flex;
            align-items: center;
            padding: 60px 80px;
        }

        .text-section {
            width: 45%;
        }

        .text-section h1 {
            font-size: 46px;
            color: rgb(242, 242, 9);
            font-family: cursive;
            margin-bottom: 20px;
        }

        .text-section p {
            color: rgb(230, 227, 227);
            line-height: 1.6;
            margin-bottom: 30px;
        }

        .image-section {
            width: 55%;
            position: relative;
            padding-left: 40px;
        }

        .image-section img {
            width: 100%;
            border-radius: 10px;
            border: 3px solid rgb(255, 255, 6);
        }

        
        .border-box {
            border: 2px solid rgb(250, 250, 5);
            margin: 60px;
            padding: 20px;
        }
        

        footer {
            text-align: center;
            background: rgba(47, 46, 46, 0);
            padding: 5px;
            font-size: 12px;
            position: fixed;
            bottom: 0;
            width: 100%;
        
        }    

Menu.html

<html>
<head>
    <title>Restaurant Menu</title>
    <link rel="stylesheet" href="Menu.css">
</head>
<body>

    
    <div class="navbar">
        <a href="Home.html">HOME</a>
        <a href="Menu.html">MENU</a>
        <a href="Admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    
    <div class="menu-title">MENU</div>

    
    <div class="menu-container">

        <div class="card">
            <img src="img 1.png" alt="Chicken Biryani">
            <h3>Chicken Biryani</h3>
            <p>Rs. 200</p>
        </div>

        <div class="card">
            <img src="img 2.png" alt="Dum Biryani">
            <h3>Dum Biryani</h3>
            <p>Rs. 250</p>
        </div>

        <div class="card">
            <img src="img 3.png" alt="chicken kurma">
            <h3>chicken kurma</h3>
            <p>Rs. 200</p>
        </div>

        <div class="card">
            <img src="img 4.png" alt="Mutton Biryani">
            <h3>Mutton Biryani</h3>
            <p>Rs. 300</p>
        </div>

        <div class="card">
            <img src="img 5.png" alt="Kundu Biryani">
            <h3>Kundu Biryani</h3>
            <p>Rs. 230</p>
        </div>

    </div>


    <footer>
         E.vamsi krishna (25005454)
    </footer>

</body>
</html>

Menu.css
body {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Segoe UI", sans-serif;
        }

        body {
            background: url("2.png") no-repeat center/cover;
            min-height: 100vh;
        }

        /* Navbar */
        .navbar {
            background: rgb(255, 255, 255);
            padding: 10px 20px;
            width: fit-content;
            margin: 20px auto;
            border-radius: 4px;
        }

        .navbar a {
            text-decoration: none;
            color: rgb(122, 0, 122);
            margin: 0 15px;
            font-weight: 600;
        }

        /* Menu Heading */
        .menu-title {
            color: rgb(255, 255, 255);
            font-size: 60px;
            font-weight: bold;
            margin: 20px 40px;
        }

        /* Menu Container */
        .menu-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px 40px;
            flex-wrap: wrap;
        }

        /* Menu Card */
        .card {
            background: rgb(255, 255, 255);
            width: 180px;
            border-radius: 15px;
            text-align: center;
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        .card img {
            width: 100%;
            height: 120px;
            object-fit: cover;
            border-radius: 10px;
        }

        .card h3 {
            margin: 10px 0 5px;
        }

        .card p {
            font-size: 14px;
            color: rgb(7, 7, 7);
        }


        footer {
            text-align: center;
            background: rgb(20, 19, 19);
            padding: 5px;
            font-size: 12px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
ADMIN.html
<html>
<head>
    <title>Administration Team</title>
     <link rel="stylesheet" href="Admin.css">
    
</head>

<body>


    <div class="navbar">
        <a href="Home.html">HOME</a>
        <a href="Menu.html">MENU</a>
        <a href="Admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    
    <div class="header">
        <h1>ADMINISTRATION TEAM</h1>
    </div>

    
    <section class="team">

        <div class="card">
            <img src="1 ph.jpeg">
            <h3>E.Vamsi krishna</h3>
            <p>CEO</p>
        </div>

        <div class="card">
            <img src="2 ph.png">
            <h3>Ram Charan</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="card">
            <img src="3 ph.png">
            <h3>Bala Krishan</h3>
            <p>Operations Manager</p>
        </div>

        <div class="card">
            <img src="4 ph.png">
            <h3>Anupama</h3>
            <p>HR Manager</p>
        </div>

        <div class="card">
            <img src="5 ph.png">
            <h3>Ananya</h3>
            <p>Executive Chef</p>
        </div>

    </section>


    <footer>
         E.Vamsi Krishna - (25005454)
    </footer>

</body>
</html>

Admin.css

 body { 
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background: rgb(255, 255, 255);
             min-height: 100vh;
        }

        /* NAVBAR */
        .navbar {
            position: absolute;
            top: 20px;
            right: 40px;
            background: rgb(243, 241, 241);
            padding: 10px 20px;
            border-radius: 5px;
        }

        .navbar a {
            text-decoration: none;
            margin: 0 15px;
            color: purple;
            font-weight: bold;
        }

        /* HEADER */
        .header {
            background: url("3.png") no-repeat center/cover;
            padding: 80px;
            color: rgb(255, 255, 255);
            text-align: left;
        }

        .header h1 {
            font-size: 60px;
            font-weight: bold;
            letter-spacing: 3px;
        }

        /* TEAM SECTION */
        .team {
            display: flex;
            justify-content: space-around;
            padding: 50px 20px;
            background: url("3.png") no-repeat center/cover;
            flex-wrap: wrap;
        }

        .card {
            background: rgb(255, 255, 255);
            width: 180px;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            margin: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .card img {
            width: 120px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .card h3 {
            font-size: 18px;
            margin-bottom: 5px;
        }

        .card p {
            font-size: 14px;
            color:rgb(109, 109, 109);
        }
        
    
        footer {
            text-align: center;
            background: rgb(0, 0, 0);
            padding: 5px;
            font-size: 12px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

contact.html

<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>

    
    <nav class="navbar">
        <a href="Home.html">HOME</a>
        <a href="Menu.html">MENU</a>
        <a href="Admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>


    <div class="contact-container">
        <h1>CONTACT</h1>

        <div class="contact-details">
            <h3>Visit us at:</h3>
            <p>
                Ruchis restaurent<br>
                123, Mankonda Street,<br>
                Back Street, Anantapur<br>
                India
            </p>

            <h3>Phone:</h3>
            <p>+91 7993893864</p>

            <h3>Email ID:</h3>
            <p>vamsikrishna123@gmail.com</p>
        </div>
    </div>

    <footer>
           E.Vamsi Krishna - (25005454)
    </footer>

</body>
</html>

contact.css
 body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background: url('1.png') no-repeat center center/cover;
    height: 100vh;
    color: rgb(249, 246, 246);
}

/* Navbar */
.navbar {   
    background: rgba(255, 255, 255, 0.9);
    padding: 10px 20px;
    position: absolute;
    top: 15px;
    right: 20px;
    border-radius: 5px;
}

.navbar a {
    text-decoration: none;
    margin: 0 15px;
    color: rgb(5, 6, 6);
    font-weight: bold;
}

/* Contact Section */
.contact-container {
    padding: 80px 60px;
    max-width: 500px;
}

.contact-container h1 {
    font-size: 60px;
    color: rgb(234, 215, 228);
    margin-bottom: 20px;
}

.contact-details h3 {
    margin-top: 20px;
    font-size: 18px;
}

.contact-details p {
    font-size: 14px;
    line-height: 1.6;
}


footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    background: rgba(0, 0, 0, 0.6);
    text-align: center;
    padding: 8px;
    font-size: 12px;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-26 095812.png>)
![alt text](<Screenshot 2025-12-26 095838.png>)
![alt text](<Screenshot 2025-12-26 100151.png>)
![alt text](<Screenshot 2025-12-26 100042.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
