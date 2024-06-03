# Codesoft_WD_task2
Personal portfolio website
<!DOCTYPE html>
<html lang="en">
<head>
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta charset="UTF-8" />
  <title>Personal Portfolio Website</title>
  
  <style>
   @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap"); 

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  background-color:#93B1A6 ;
}
a {
  text-decoration: none;
}
.hero {
  width: 100%;
  height: 100vh;
  background: url(img/bg.png);
  background-size: cover;
}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 30px 100px;
}
.logo {
  max-height: 60px;
}
nav ul li {
  list-style: none;
  display: inline-block;
  padding: 10px 20px;
}
nav ul li a {
  color: #183D3D;
  position: relative;
  padding: 5px 0;
}
nav ul li a:hover {
  color: #183D3D;
}
nav ul li a:after {
  content: "";
  position: absolute;
  left: 0;
  width: 0;
  height: 3px;
  background: #183D3D;
  transition: 0.3s;
  bottom: 0;
}
nav ul li a:hover:after {
  width: 100%;
}
.btn {
  color: #fff;
  font-size: 16px;
  text-transform: uppercase;
  letter-spacing: 2px;
  padding: 16px 40px;
  border-radius: 500px;
  display: inline-block;
  font-weight: 500;
  transition: all 0.4s ease-in-out;
  background-size: 152% 100%;
  background: #5C8374;
  border: 2px solid #5C8374;
}
.btn:hover {
  background: transparent;
  border-color: #5C8374;
  color: #5C8374;
}
.content {
  position: absolute;
  top: 35%;
  left: 8%;
}
.content h1 {
  color:black;
  font-size: 75px;
  font-weight: 900;
  line-height: 90px;
  text-transform: inherit;
  width: 70%;
}
.content h1 span {
  color: rgb(36, 75, 75);
}
.content p {
  width: 55%;
  color: #202020;
  margin-top: 25px;
  margin-bottom: 30px; }

  </style>


</head>

<body>
  <div class="hero">
    <nav>
      <img src="circlephoto.png" class="logo" />
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Service</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <a href="#" class="btn">Resume</a>
    </nav>

    <div class="content">
      <span class="title"> Web Developer</span>
      <h1>Hello, I'm <span>Deepak</span></h1>
      <p>
        I'm working on a professional, visually sophisticated and
        technologically proficient, responsive and multi-functional React
        Components.
      </p>
      <a href="#" class="btn">Download CV</a>
    </div>
  </div>
  
  </div>


</body>

</html>
