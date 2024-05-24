# pratankvardhan.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
   <style>
     *{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sams-serif;
    box-sizing: border-box;    
}
body{
    background: #080808;
    color: #fff;
}
#header{
    width: 100%;
    height: 100vh;
    background-image: url(./images/bg.png);
    background-size: cover;
    background-position: center;
}
.container {
    padding: 10px 10%;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}

#logo{
    width: 140px;
}

nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}

nav ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    position: relative;
}

nav ul li a::after{
    content: '';
    width: 0;
    height:3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition:0.5s;
}
nav ul li a:hover::after{
    width:100%;
}
.header-text{
    margin-top: 20%;
    font-size: 30px;

}

.header-text h1{
    font-size: 60px;
    margin-top: 20px;
}

.header-text h1 span{
    color: #ff004f;
}

/*----------about-------*/

#about{
    padding: 80px 0;
    color: #ababab;
}

.row{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.about-col-1{
    flex-basis: 35%;

}

.about-col-1 img{
    width: 100%;
    border-radius: 15px;
}

.about-col-2{
    
}
   </style>
</head>
<body>
    <div id="header">
       <div class="container">
        <nav>
            <img src="./images/logo5.png" alt="logo" class="logo">
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Services</a></li>
                <li><a href="">Portfolio</a></li>
                <li><a href="">Contact</a></li>
            </ul>
        </nav>
        <div class="header-text">
            <p>UI/UX Designer</p>
            <h1>Hi, I am <span> Pratank Vardhan</span> from India</h1>
        </div>
       </div>
    </div>
    <!-- --------about------- -->  
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="./images/user.png" alt="user">
                </div>
                <div class="about_col-2">
                    <h1>
                        About Me
                    </h1>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
