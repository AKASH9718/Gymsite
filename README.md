# Gymsite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GYM FITNESS</title>
</head>
<link rel="font" href="https://fonts.google.com/specimen/Nerko+One">
<link rel="stylesheet" href="css/style.css">
<style>
    body {
        /*Css reset*/
        font-family: Nerko One;
        margin: 10px;
        padding: 0px ;
        color: whitesmoke;
        background: url("img1/go.jpeg");
        background-repeat: no-repeat;
        background-size: 100%;
    }
    .left {
        position: absolute;
        left: 34px;
        top: 20px;
    }
    .mid {
        display: block;
        width: 50%;
        margin: 20px auto;
        height: 40px;
    }
    .right {
        position: absolute;
        right: 15px;
        top: 20px;
        display: inline-block;

    }
    .navbar {
        display: inline-block;
        padding-left: 0%;
        padding-right: 0%;
        margin-top: 5px;
        margin-bottom: 5px;
        margin-right: 5px;
    }
    .navbar li {
        display: inline;
        font-size: 20px;
    }
    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 4px 13px;
    }
    .navbar li a:hover, .navbar li a:active {
        color: grey;
        text-decoration: underline;
        
    }
    .left img {
        width: 81px;
        background-color: black;
        filter:opacity(50%);
    }
    .left div {
        text-align: center;
        line-height: 6px;
    }
    .btn {
        margin: 4px 3px;
        color: white;
        background-color: black;
        padding: 3px 3px;
        border: 2px solid grey;
        border-radius: 14px;
        font-size: 20px;
        cursor: pionter;
        font-family: Nerko One;
    }
    .btn:hover {
        background-color: grey;
    }
    .container {
        border: 2px solid white;
        text-align: center;
        margin: 100px 100px;
        padding: 33px;
        width: 39%;
        border-radius: 8px;
        font-size: small;
    }
    .form-group input {
        text-align: center;
        display: block;
        width: 188px;
        padding: 5px;
        border: 2px solid black;
        margin: 11px auto;
        border-radius: 23px;
        font-size: 14px;
    }
    .container button {
        display:block;
        width: 196px;
        margin: 25px auto;
    }
</style>
<body>
    <header class="header">
        <div class="left">
            <img src="img1/gym.png" alt="">
            <div>Gym Fitness</div>
        </div>
        <div class="mid">
            <ul class="navbar">
                <li><a href="#">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
        <div class="right">
            <button class="btn">call us</button>
            <button class="btn">email us</button>
        </div>
    </header>
    <div class="container">
        <h1>Join the best gym of the world</h1>
        <form action="no-action.php">
            <div class="form-group">
                <input type="text" placeholder="Enter your name">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your age">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your gender">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your location">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your phone-number">
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
