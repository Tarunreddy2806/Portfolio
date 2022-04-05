# Portfolio
<!DOCTYPE html> 
<html lang="en" dir="ltr">
  <head>
    <meta charset="UTF-8">
    <title> CSI WORK.html</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css"/>
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   </head>
<body>
  <div class="scroll-button">
    <a href="#home"><i class="fas fa-arrow-up"></i></a>
  </div>
  <nav>
    <div class="navbar">
      <div class="logo"><a href="#">My Portfolio.</a></div>
      <ul class="menu">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
        <div class="cancel-btn">
          <i class="fas fa-times"></i>
        </div>
      </ul>
      <div class="media-icons">
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
    <div class="menu-btn">
      <i class="fas fa-bars"></i>
    </div>
  </nav>
  <section class="home" id="home">
    <div class="home-content">
      <div class="text">
        <div class="text-one">Hello,</div>
        <div class="text-two">I'm Tarun Reddy</div>
      </div>
      <div class="right">
        <img src="portfolio.jpeg" alt="Portfolio" >
      </div>
     </div>
  </section>
  <section class="about" id="about">
    <div class="content">
      <div class="title"><span>About Me</span></div>
      <div class="about-details">
        <div class="left">
          <img src="My photo.jpeg" alt="Portfolio" width="500" height="200">
        </div>
        <div class="right">
          <div class="topic">who i am</div>
          <p>Hello, This is Tarun Reddy. I'm a student in VIT-AP.currently i am pursuing b.tech in ece. I'm a member of special mention for CSI Chapter. I am a person who loves to learn and explore new things  </p>
          </div>
      </div>
    </div
  </section>
  <section class="skills" id="skills">
    <div class="content">
      <div class="title"><span>My Skills</span></div>
      <div class="skills-details">
        <div class="text">
          <div class="topic">What i know</div>
          <p>As a fresher, I recently joined in CSI club with no skills. now i learned HTML,CSS,Java,Python. i am highly interested to learn more about technology.  </p>
          </div>
        <div class="boxes">
          <div class="box">
            <div class="topic">HTML</div>
            <div class="per">80%</div>
          </div>
          <div class="box">
            <div class="topic">CSS</div>
            <div class="per">90%</div>
          </div>
          <div class="box">
            <div class="topic">Python</div>
            <div class="per">60%</div>
          </div>
          <div class="box">
            <div class="topic">Java</div>
            <div class="per">20%</div>
          </div>
          </div>
      </div>
    </div>
  </section>
  <section class="contact" id="contact">
    <div class="content">
      <div class="title"><span>Contact Me</span></div>
      <div class="text">
        <div class="topic"></div>
        <div class="row">
          <i class="fas fa-envelope"></i>
          <div class="info">
              <div class="head">Email</div>
              <a href="mailto: tarun.21bec7015@vitapstudent.ac.in?subject = Feedback&body = Message">tarun.21bec7015@vitapstudent.ac.in</a>
          </div>
      </div>
  </ul>
  <div class="row">
      <a href="#"><i class="fab fa-instagram"></i></a>
          <i class="fas fa-instagram-logo"></i>
          <div class="info">
              <div class="head">Insta I'D</div>
              <a href="https://instagram.com/why_not_tarunn?utm_medium=copy_link">why_not_tarunn</a>
          </div>
      </div>
  </ul>
  <div class="row">
          <HI>phone</HI> <h5>7794849734</h5>
          </div>    
        </div>
    </div>
  </section>
 <script src="script.js"></script>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Ubuntu:wght@400;500;700&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  scroll-behavior: smooth;
}
:root{
    --primary-color:#ff8882;
    --black-color:#0E2431;
    --white-color:#fff;

}
body{
  font-family: 'Ubuntu', sans-serif;
}
::-webkit-scrollbar {
    width: 10px;
}
::-webkit-scrollbar-track {
    background: #f1f1f1;
}
::-webkit-scrollbar-thumb {
    background: var(--primary-color);
    border-radius: 12px;
    transition: all 0.3s ease;
}
::-webkit-scrollbar-thumb:hover {
    background: var(--primary-color);
}
nav{
  position:fixed;
  width:100%;
  padding:20px 0;
  z-index: 999;
  transition: all 0.3s ease;
}
nav.sticky{
  background:var(--primary-color);
  padding:13px 0;
}
nav .navbar{
  width:90%;
  display:flex;
  justify-content: space-between;
  align-items: center;
  margin:auto;
}
nav .navbar .logo a{
  font-weight: 500;
  font-size: 35px;
  color:var(--primary-color);
}

nav.sticky .navbar .logo a{
  color:var(--white-color);
}

nav .navbar .menu{
  display:flex;
  position:relative;
}
nav .navbar .menu li{
  list-style: none;
  margin:0 8px;
}
nav .navbar .menu a{
  font-size: 18px;
  font-weight: 500;
  color:var(--black-color);
  padding:6px 0;
  transition: all 0.4s ease;
}
.navbar .menu a:hover{
  color:var(--primary-color);
}
nav.sticky .menu a{
  color:var(--white-color);
}
nav.sticky .menu a:hover{
  color:var(--black-color);
}
.navbar .media-icons a{
  color:var(--primary-color);
  font-size: 18px;
  margin:0 6px;
}
nav.sticky .media-icons a{
  color:var(--white-color);
}
nav .menu-btn,
.navbar .menu .cancel-btn{
  position:absolute;
  color:var(--white-color);
  right:30px;
  top:20px;
  font-size: 20px;
  cursor: pointer;
  transition: all 0.3s ease;
  display: none;
}
nav .menu-btn{
  color:var(--primary-color);
}
nav.sticky .menu-btn{
  color:var(--white-color);
}
.navbar .menu .menu-btn{
  color:var(--white-color);
}
.home{
  height:100vh;
  width:100%;
  background:url("Bg.jpeg") no-repeat;
  background-size: cover;
  background-position: center center;
  background-attachment: fixed;
}
.home .home-content{
  width:90%;
  height:100%;
  margin:auto;
  display:flex;
  flex-direction: column;
  justify-content: center;
}
.home .text-one{
  font-size:25px;
  color:var(--black-color);
}
.home .text-two{
  color:var(--black-color);
  font-size: 75px;
  font-weight: 600;
  margin-left: -3px;
}
section{
  padding-top:40px;
}
section .content{
  width:80%;
  margin:40px auto;
  font-family: 'Poppins', sans-serif;
}
section .title{
  display:flex;
  justify-content: center;
  margin-bottom: 40px;
}
section .title span{
  color:var(--black-color);
  font-size: 30px;
  font-weight: 600;
  position:relative;
  padding-bottom:8px;
}
section .title span::before,
section .title span::after{
  content:'';
  position:absolute;
  height:3px;
  width:100%;
  background:var(--primary-color);
  left:0;
  bottom:0;
}
section .title span::after{
  bottom:-7px;
  width:70%;
  left:50%;
  transform:translateX(-50%);
}
.about .about-details{
  display:flex;
  justify-content:space-between;
  align-items: center;
}
.about .about-details .left{
  width:45%;
}
.about .left img{
  height:400px;
  width:400px;
  object-fit: cover;
  border-radius: 12px;
}
.about .about-details .right{
  width:55%;
}
section .topic{
  color:var(--black-color);
  font-size:25px;
  font-weight: 500;
  margin-bottom: 10px;
}
.about-details .right p{
  text-align: justify;
  color:var(--black-color);
}
section .button{
  margin:16px 0;
}
section .button button{
  outline:none;
  padding:8px 16px;
  border-radius: 4px;
  font-size: 25px;
  font-weight: 400;
  background: var(--primary-color);
  color:var(--white-color);
  border:2px solid transparent;
  cursor: pointer;
  transition: all 0.4s ease;
}
section .button button:hover{
  border-color:var(--primary-color);
  background-color: var(--white-color);
  color:var(--primary-color);
}
.skills{
  background:#f0f8ff;
}
.skills .content{
  padding:40px 0;
}
.skills .skills-details{
  display:flex;
  justify-content: space-between;
  align-items: center;
}
.skills-details .text{
  width:50%;
}
.skills-details p{
  color:var(--black-color);
  text-align: justify;
}
.skills .skills-details .experience{
  display:flex;
  align-items: center;
  margin:0 10px;
}
.skills-details .experience .num{
  color:var(--black-color);
  font-size: 80px;
}
.skills-details .experience .exp{
  color:var(--black-color);
  margin-left: 20px;
  font-size: 18px;
  font-weight: 500;
  margin:0 6px;
}
.skills-details .boxes{
  width:45%;
  display:flex;
  flex-wrap: wrap;
  justify-content:space-between;
}
.skills-details .box{
  width:calc(100% / 2 - 20px);
  margin:20px 0;
}
.skills-details .boxes .topic{
  font-size: 20px;
  color:var(--primary-color);
}
.skills-details .boxes .per{
  font-size: 60px;
  color:var(--primary-color);
}
.contact{
  background: #f0f8ff;
}
.contact .content{
  margin:0 auto;
  padding:30px 0;
}
.contact .text{
  width:80%;
  text-align: center;
  margin:auto;
}
footer{
  background:var(--primary-color);
  padding:15px 0;
  text-align: center;
  font-family: 'Poppins', sans-serif;
}
footer .text span{
  font-size: 17px;
  font-weight: 400;
  color:var(--white-color);
}
footer .text span a{
  font-weight: 500;
  color:var(--white-color);
}
footer .text span a:hover{
  text-decoration: underline;
}
.scroll-button a{
  position:fixed;
  bottom:20px;
  right:20px;
  color:var(--white-color);
  background:var(--primary-color);
  padding:10px 12px;
  font-size: 18px;
  border-radius: 6px;
  box-shadow: rgba(0,0,0,0.15);
  display:none;
}
@media (max-width:1190px){
  section .content{
    width:85%;
  }
}
@media (max-width:1000px)
  .about .about-details{
    justify-content: center;
    flex-direction: column;
  }
  .about .about-details .left{
    display: flex;
    justify-content:center;
    width:100%;
  }
  .about .about-details .right{
    width:90%;
    margin:40px 0;
  }
  .services .boxes .box{
    margin:20px 0;
    width:calc(100% / 2 - 20px);
  }
@media (max-width:900px){
  .about .left img{
    height:350px;
    width:350px;
  }
}
@media (max-width:750px){
   nav .navbar{
     width:90%;
   }
   nav .navbar .menu{
     position:fixed;
     left:-100%;
     top:0;
     background:var(--primary-color);
     height:100vh;
     max-width: 400px;
     width:100%;
     padding-top:60px;
     flex-direction: column;
     align-items:center;
     transition: all 0.5s ease;
   }
   .navbar.active .menu{
     left:0;
   }
   nav .navbar .menu a{
     font-size:23px;
     display:block;
     color:var(--white-color);
     margin:10px 0;
   }
   nav.sticky .menu a:hover{
     color:var(--primary-color);
   }
   nav .navbar .media-icons{
     display:none;
   }
   nav .menu-btn,
   .navbar .menu .cancel-btn{
     display:block;
   }

   .home .text-two{
     font-size: 65px;
   }
.home .text-three{
    font-size: 35px;
  }
.skills .skills-details{
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .skills-details .text{
    width:100%;
    margin-bottom:50px;
  }
  .skills-details .boxes{
    justify-content:center;
    align-items: center;
    width:100%;
  }
.services .boxes .box{
    margin:20px 0; 
    width:100%;
  }
.contact .text{
    width:100%;
  }
}
