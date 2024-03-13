<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cheese Burger Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .topnav {
            overflow: hidden;
            background-color: white;
            height: 50px;
            display: flex;
            justify-content: space-between; /* Adjusts the position of elements */
            align-items: center; /* Vertically center items */
            padding: 0 20px; /* Add padding to separate items from edges */
        }

        .topnav a {
            color: black;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
        }

        .topnav a.active {
            background-color: black;
            color: white;
            background-position: center;
        }

        .container {
            position: relative;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        h1 {
            color: black;
        }

        p {
            color: black;
        }

        .banner {
            height: 50vh; 
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative; /* Ensure relative positioning for absolute elements */
        }

        .banner img {
            width: 100%; 
            max-height: 100%;         
        }

        .cta-button {
            position: absolute;
            bottom: 20px;
            background-color: #ff9900;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            z-index: 1; 
        }

        .overlay {
            color: black;
            width: 100%; /* Make it take full width */
            margin-top: 20px;
            display: flex;
            justify-content: center; /* Center the image horizontally */
        }

        .overlay img {
            max-width: 100%; /* Ensure the image doesn't overflow its container */
            height: auto; /* Maintain aspect ratio */
        }
        .deals {
            position: absolute;
            top: 20px; /* Adjust the top position as needed */
            left: 20px; /* Adjust the left position as needed */
        }

        .burger-img {
            width: 150%;
            margin: 0; 
            margin-top: 80px;
            background-size: cover;
        }

        .b3 {
            margin-top: auto; /* Places this div at the bottom */
        }

        /* New CSS for grid layout */
        .scroll-container {
            width: 100%; /* Adjust the width as needed */
            overflow-x: auto; /* Enable horizontal scrolling */
        }

        .row {
            display: flex;
            justify-content: flex-start; /* Start from the left */
            align-items: center;
        }

        .column {
            flex: 0 0 auto;
            margin: 10px; /* Adjust the margin as needed */
        }

        .column img {
            width: 180px; /* Adjust the width as needed */
            height: auto; /* Maintain aspect ratio */
            padding: 70px;
        }
    </style>
</head>
<body>
    <div class="topnav">
        <a class="active" href="#home">Home</a>
        <a href="#Dine-in">Dine-in</a>
        <a href="#Take-out">Take-out</a>
        <a href="#Specials">Specials!!!</a>
        <a href="Contact Us">Contact Us</a>
        <a href="About Us">About Us</a>
        <a href="# Sign in/Register" style="margin-left: auto;">Sign-in/Register</a> <!-- This button will be on the extreme right -->   
    </div>

    <div class="banner">
        <img src="https://th.bing.com/th/id/R.3e0c8b8a1a0bf706510e8a654318d7f2?rik=zxl81MuEW4ZqOw&riu=http%3a%2f%2fwww.mrcapetown.co.za%2fwp-content%2fuploads%2f2019%2f01%2fBurgers.png&ehk=0omFCksbjdO%2bocmD4AY%2beHpJ0u%2bDpAf9JWTqYwePjJ4%3d&risl=&pid=ImgRaw&r=0">
    </div>
    

    <div class="container">
        <h1>Welcome to <i>Cheesy juicy Burger</i>!!!</h1>
        <p><b><u>An escape to Burger Haven, where every bite is a journey through flavor paradise....</u></b></p>
        <a href="Order Now" class="cta-button">Order-Now</a> <!-- Moved after the text -->
        <div class="social-icons">
            <i class="ri-instagram-line"></i>
            <i class="ri-twitter-line"></i>
            <i class="ri-facebook-box-fill"></i>
        </div>
        
        <div class="scroll-container">
            <div class="row">
                <div class="column">
                    <img src="https://th.bing.com/th/id/OIP.rqD6Qz5Jb_ehBov5akE6-QDSEp?rs=1&pid=ImgDetMain" alt="Snow">
                </div>
                <div class="column">
                    <img src="https://i.pinimg.com/564x/50/f6/1a/50f61a63f1e618d27bf1f240fcacc6a2.jpg">
                </div>
                <div class="column">
                    <img src="https://i.pinimg.com/564x/e0/c9/b8/e0c9b81eb1e365a320af11d48f9fb52d.jpg" alt="Mountains">
                </div>
                <div class="column">
                    <img src="https://i.pinimg.com/736x/25/8c/bd/258cbd8da4af4bc4f69a9d3e42092d7d.jpg">
                </div>
               
            </div>
        </div>
        <img class="burger-img" src="https://www.dsmenu.com/user-folder/menu/basic/4/big_t_13248-.png">
    </div>

    <div class="b3">
        <div class="overlay">
            
            <p>Terms and Conditions Applied</p>
            
        </div>
    </div>
</body>
</html>

