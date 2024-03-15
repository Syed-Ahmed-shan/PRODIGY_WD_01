# PRODIGY_WD_01
I make the responsible web page with html CSS and javascript 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation</title>
    <style>
        
    </style>
</head>
<body>
    <link rel="stylesheet" href="styles.css">
   <header>
        <nav class="navbar">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Portfolio </a></li>
                <div class="search"> 
                    <input type="text" name="search" id="search" placeholder="Search">
                </div>
            </ul>
        </nav>
        <HR>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius error molestias facilis in iure id excepturi dicta totam maxime! Consequuntur consectetur impedit saepe! Labore numquam eum dolorem porro error quam.</p>
        <HR>
            <big>This is the just sample basic of web page  </big>
            <hr>

        
    </header>
    <h1><font color="#8EE4AF" hight="100">Resgistration from</font></h1> 
        <from action="/action.php">
            <input type="username" placeholder="username">
           <br><br>
            <input type="password" placeholder="Password">
           <br><br>
           <a href="details.html">
        <input type="submit" value="submit">
        </a>
        <br>
    <footer><h3>
        contact me 
     </h3>
     </footer>
     <!--this is the linked in url profile with image-->
     <a href="https://www.linkedin.com/in/ahmed-syed-31a60a271/" ><img src="https://static.vecteezy.com/system/resources/previews/018/930/587/non_2x/linkedin-logo-linkedin-icon-transparent-free-png.png" alt="LinkedIn" height="100" >
      
</body>
</html>
CSS CODE FROM HERE

body{
  background-color: #DFF5FF;
  color: black;
}
.navbar{
  background-color: #3a4664;
  border-radius: 36px;

}
.navbar ul{
  overflow: auto;
}
.navbar li{
  float: left;
  list-style: none;
  padding: 3px 3px;
  margin: 13px 20px;

}
.navbar li a{
  padding: 3px 3px;
  text-decoration: none;
  color: white;
  transition: .3s;
  
}
.navbar li a:hover{
  background-color: rgb(88, 86, 86);
  color: aquamarine;
}
.search{
  float: right;
  color: rgb(190, 239, 239);
  padding: 12px 17px;
}
.navbar input{
  border: white;
  border-radius: 14px;
  padding: 3px 17px;
  width: 129px;
}
JAVA CODE FROM HERE FOR THE SMALL ACTION IN THE WEB PAGE 
window.addEventListener('scroll', function() {
    const navbar = document.getElementById('navbar');
    if (window.scrollY > 8) {
      navbar.classList.add('scrolled');
    } else {
      navbar.classList.remove('scrolled');
    }
});
  
