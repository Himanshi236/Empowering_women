<!-- HTML CODE -->
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <!--It will help us to make our website responsive-->
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Document</title>
   <!-- *********** -->

<!-- ********* -->
   <link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
   <link rel="stylesheet" href="style.css">
   <link rel="preconnect" href="https://fonts.googleapis.com"> 
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css">

</head>
<body>
   <section class="header">
      <nav>
         <a href="index.html"><img src="logo.jpeg"></a>
         <div class="nav-links" id="navLinks">
            <ul>
               <li><a href="">HOME</a></li>
               <li><a href="#about1">ABOUT US</a></li>
               <li><a href="">SCHOLARSHIP</a></li>
               <li><a href="">HEALTH</a></li>
               <li><a href="">BLOG </a></li>
               <li><a href="#contact">CONTACT US</a></li>
            </ul>
         </div>

        

      </nav>

      <div class="text-box">
         <h1>We are Helping</h1>
         <p>A woman is a full circle. Within her is the power to create,nuture and transform
            -- Diane mariechild
         </p>
         <!-- ************ -->
         <a href="" class="hero-btn">Login</a>
         <!-- *********************** -->
            
         <!-- ************* -->
      </div>
   </section>


<!--Our Programs-->

<section class="about">
   <h1 id="about1" class="headings">About Us</h1>
   <p class="quote">"Women Empowerment isn't about making women stronger. <br>Women are already strong, it's about changing the way the world perceives that strength."<br>
      G.D. Anderson</p>

   <p><br>The women we serve are strong and resilient. All too often they are limited by a lack of resources, opportunity, and safety. We are on a mission to change that with economic empowerment tools to thrive and overcome the obstacles in their way.</p><br><br>



   </section>

<section class="program">
   <h1 class="headings">Our Initiatives</h1>
   <p>Our mission is to empower women with tools to work their way out of poverty, society barriers
      and stand out as the strong independent individuals</p>
   <br>
   <div class="row ">
      <div class="program-col">
      <img  class="image" src="health.jpg" alt="">
         <h3>Women's Health</h3>
      </div>

      <div class="program-col">
         <img class="image" src="edu.jpg" alt="">
            <h3>Women's Education</h3>
         </div>

         <div class="program-col">
            <img class="image" src="help.jpg" alt="">
               <h3>Women's Empowerment</h3>
            </div>
   </div>
</section>

<br>
<br>
<br>
<section id="contact">
    <h1 id="contact" class="h-primary center">Contact Us</h1>
<div id="contact-box">
    <form action="">
        <div class="form-group">
        <label for="name">Name: </label>
        <input type="text"name="name"id="name"
        placeholder="Enter your Name">
        </div>
        <div class="form-group">
            <label for="name">Email: </label>
            <input type="text"name="e-mail"id="e-mail"
            placeholder="Enter your Email">
        </div>
        <div class="form-group">
            <label for="name">Phone Number: </label>
            <input type="text"name="name"id="phone"
            placeholder="Enter your Phone Number">
        </div>
        <div class="form-group">
            <label for="name">Message: </label>
            <textarea name="message"id="message"cols="30" rows="10"></textarea>
        </div>
    </form>
</div>
</section>
<button>submit</button>



</body>
</html>


<!-- CSS CODE -->

@import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&display=swap');
*{
    font-family: 'Bree Serif',serif;
    margin: 0px;
    padding: 0px;
}
body{
   margin:0;
   overflow-x: hidden;
}
 .header{
    min-height: 100vh;
    width: 100%;
    background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url(./banner1.jpg);
    background-position: center;
    background-size: cover;
    position: relative;
 }
 nav{
    background-color: black;
    display: flex;
    padding: 2% 6%;
    justify-content: space space-between;
    align-items: center;
 }
 nav img{
    width: 50px;
    height: 50px;
 }
 .nav-links{
    flex: 1;
    text-align: right;
 }
 .nav-links ul li{
    font-family: 'Bree Serif',serif;
    list-style: none;
    display: inline-block;
    padding: 8px 12px;
    position: relative;
 }
 .nav-links ul li a{
    font-family: 'Bree Serif',serif;
    color:white;
    text-decoration: none;
    font-size: 13px;
 }

 .nav-links ul li::after{
    content: '';
    width: 0%;
    height: 2px;
    background: rgb(51, 150, 64);
    display: block;
    border-radius: 12px;
    margin: auto;
    transition: 0.5s;
 }
 .nav-links ul li:hover::after{
    width: 100%;
 }
 .text-box{
    width: 90%;
    color: white;
    position:absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,50%);
    text-align: center;
 }
 .text-box h1{
    font-size: 62px;
    font-family: 'Bree Serif',serif;
 }
 .text-box p{
    margin: 10px 0 40px;
    font-size: 24px;
    font-family: 'Bree Serif',serif;
    color: white;
 }
 .hero-btn{
    font-family: 'Bree Serif',serif;
    display: inline-block;
    text-decoration: none;
    color: white;
    border: 1px solid white;
    padding: 12px 34px;
    background: transparent;
    position: relative;
    cursor: pointer;
 }
 .hero-btn:hover{
    border: 1px solid rgb(51, 150, 64);
    background: rgb(51, 150, 64);
    transition: 1s;
 }
 nav .fa-solid{
    display: none;
 }

 
 
 /*----------Program----------------*/
 
/* .program{
   text-align: center;
   margin-left: 100px;
   display: inline-block;
   justify-content: space-between;
   padding: 12px 12px;
   position: relative;
   z-index: -1;
 } */
.program img{
   width: 250px;
   height: 250px;
}
 .program-col{
   display: inline-block;
   padding: 10px 10px;
   border: 4px solid black;
   border-radius: 10px;
 }


 


 /*Contact Section*/
#contact{
    position: relative;
}
#contact::before{
    content:"";
    position: absolute;
    width:100%;
    height: 100%;
    z-index:-1;
    opacity: 1.7;
    background: url('cont.webp')
    /*image-repeat:no-repeat center center/cover ;*/
}
#contact-box{
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 34px;
}
#contact-box input,
#contact-box textarea{
    width: 100%;
    padding: 0.5rem;
    border-radius: 9px;
    font-size:1.1rem;
}
#contact-box form{
    width: 40%;
}
#contact-box label{
    font-size: 1.3rem;
    font-family: 'Bree Serif',serif;
}
footer{
    background: black;
    color: white;
    padding: 9px 20px;
}
/*Utility Class*/
.h-primary{
    font-family:'Bree Serif',serif ;
    font-size:3.0rem;
    padding:12px;
}
.h-secondary{
    font-family: 'Bree Serif',serif;
    font-size: 2.0rem;
    padding: 12px;
}
.btn{
    padding: 6px 20px;
    border: 2px solid white;
    background-color: brown;
    color: white;
    margin: 17px;
    font-size: 1.5rem;
    border-radius: 10px;
    cursor: pointer;
}
.center{
    text-align: center;
}


/* changes */
.about{
  
   margin-top: 10px;
   text-align: center;
   margin-left: 100px;
   display: inline-block;
   justify-content: space-between;

   
   padding: 12px 12px;
   position: relative;
   z-index: -1;
   
}
.program{
   display:inline-block;
   text-align: center;
   margin-left:230px;
}
.headings{
   font-size: 60px;
}
.quote{
   font-size: 40px;
   font-family: Georgia, 'Times New Roman', Times, serif;
}

.program-col{
   position: relative;
   background-color:rgb(51, 150, 64);
}


<!-- Images -->


