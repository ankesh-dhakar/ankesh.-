<!DOCTYPE html>

<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Responsive Navbar</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
 
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bitter:ital,wght@0,200;0,300;1,900&family=Play:wght@700&display=swap" rel="stylesheet">


    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
    

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/2.0.1/css/ionicons.min.css">
    <link rel="stylesheet" href="assets/css/style.css">

<style>
*{
  padding: 0;
  margin: 0;
  text-decoration: none;
  list-style: none;
  box-sizing: border-box;
  
}
body{
  
  font-family: 'Bitter', serif;
font-family: 'Play', sans-serif;
}

nav{
  background: orange;
  height: 65px;
  width: 100%;

}
label.logo{
  color: white;
  font-size: 35px;
  line-height: 80px;
  padding: 0 100px;
  font-weight: bold;
}

 .outer-div{padding: 50px;
background-color: greenyellow;
height: 300px;
width: 185vh;
margin-left: 100px;
margin-top: 30px;
}

nav  li{
  margin-top:10px;
  color:white;
  margin-left:50px;
  font-size:15px;
}



nav li label.logo{font-size: 80px; }

label.log{
  color: white;
  font-size: 10px;
  line-height: 80px;
  padding: 0 100px;
  font-weight: bold;
  margin-right: 10px;
}
nav ul{
  float: right;
 margin-top: 50px; 
  margin-right: 350px;
  
}
nav ul li{
  display: inline-block;
  line-height: 80px;
  margin: 0 5px;
}
nav ul li a{
  color: black ;
  font-size: 20px;
  margin-top:50px;
  padding: 7px 13px;
  border-radius: 30px;
  text-transform: uppercase;
}
a.active,a:hover{
  background: orange;
  transition: .5s;
}
.checkbtn{
  font-size: 35px;
  color: green ;
  float: right;
  line-height: 80px;
  margin-left: 100px;
  margin-top: 10px; 
  cursor: pointer;
  display: none;
}
#check{
  display: none;
}
@media (max-width: 952px){
  label.logo{
    font-size: 30px;
    padding-right: 50px;
  }
  nav ul li a{
    font-size: 16px;
  }
}
@media (max-width: 858px){
  .checkbtn{
    display: block;
  }

  



  ul{
    position: fixed;
    width: 100%;
    height: 100vh;
    background: navajowhite;
    top: 80px;
    left: -100%;
    text-align: center;
    transition: all .5s;
    text-bo
  }
  nav ul li{
    display: block;
    margin: 50px 0;
    line-height: 30px;
  }
  nav ul li a{
    font-size: 20px;
  }
  a:hover,a.active{
    background: none;
    color: #0082e6;
  }
  #check:checked ~ ul{
    left: 0;
  }
}

section{
  background-color: black ;
  background: url(C:\Users\AS Computer\Desktop\R.L\img/12345.jpg) no-repeat;
  background-size: cover;
  height: calc(100vh - 80px);
}

@media only screen and (min-width:100px){
.checkbox{
  margin-top: 100px;
  font-family: "Arial Black", Gadget, sans-serif;
font-size: 20px;
letter-spacing: -0.6px;
word-spacing: 4.4px;
color: #000000;
font-weight: 700;
text-decoration: underline solid rgb(68, 68, 68);
font-style: normal;
font-variant: normal;
text-transform: capitalize;
text-align: center;
}

.box2{ color: white; margin-left: 100px;}
.box3

@media only screen and (min-width:100px){.logo{margin-top: -75px}}


@media only screen and (min-width:100px){.box{height: 80%;
width: 70%;
  margin: 0 auto; border: 7px solid whitesmoke;
  font-size: 30px;
}
 }


 .footer-basic {
  padding:40px 0;
  background-color:brown;
  color:white;
}

.footer-basic ul {
  padding:0;
  list-style:none;
  text-align:center;
  font-size:18px;
  line-height:1.6;
  margin-bottom:0;
}

.footer-basic li {
  padding:0 10px;
}

.footer-basic ul a {
  color:inherit;
  text-decoration:none;
  opacity:0.8;
}

.footer-basic ul a:hover {
  opacity:1;
}

.footer-basic .social {
  text-align:center;
  padding-bottom:25px;
}

.footer-basic .social > a {
  font-size:24px;
  width:40px;
  height:40px;
  line-height:40px;
  display:inline-block;
  text-align:center;
  border-radius:50%;
  border:1px solid #ccc;
  margin:0 8px;
  color:inherit;
  opacity:0.75;
}

.footer-basic .social > a:hover {
  opacity:0.9;
}

.footer-basic .copyright {
  margin-top:15px;
  text-align:center;
  font-size:13px;
  color:#aaa;
  margin-bottom:0;


</style>
  </head>
  <body>
    
    
    <nav>

     <li class="fas fa-phone" >+917999516733</li>

       <li class="fas fa-envelope" ><a href="https://mail.google.com/mail/u/0/?tab=cm#inbox" > rlcomputer04@gmail.com</a></li>



     

<input type="checkbox" id="check">
    
      <label class="log"> <label for="check" class="checkbtn">
        <i class="fas fa-bars"></i>
      </label></label> 

<label class="logo"></label>
      <ul>
        <li><a class="active" href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Feedback</a></li>
      </ul>
    </nav>
    
   
<div class="logo">
<img src="C:\Users\AS Computer\Desktop\R.L\img/12345.jpg"height="90px"width="110px">
    </div>
    

<div class="checkbox"><p>LATEST UPDATES</p> </div>
  
<br><br>

<div class="box">

  
<marquee behavior="scroll" width="100%" direction="left" height="20%" scrollamount="2"><a href="">
    https://www.sarkariresult.com/.
</marquee><br>
<marquee  behavior="scroll" width="100%" direction="left" height="20%" scrollamount="3" ><a href="">
  https://www.mponline.gov.in/portal/
</marquee>  <br>

<marquee behavior="scroll" width="100%" direction="left" height="20%" scrollamount="4"><a href=""> https://www1.incometaxindiaefiling.gov.in/home
   
</marquee><br>

</div><br><br>


    <div class="footer-basic">
        <footer>
            <div class="social"><a href="#"><i class="icon ion-social-instagram"></i></a><a href="#"><i class="icon ion-social-snapchat"></i></a><a href="#"><i class="icon ion-social-twitter"></i></a><a href="#"><i class="icon ion-social-facebook"></i></a></div>
          <hr style="height:2px;border-width:0;color:gray;background-color:white">
            <ul class="list-inline">
                <li class="list-inline-item"><a href="#">Home</a></li>
                <li class="list-inline-item"><a href="#">Services</a></li>
                <li class="list-inline-item"><a href="#">About</a></li>
                <li class="list-inline-item"><a href="#">Sitemap</a></li>
                <li class="list-inline-item"><a href="#">Privacy Notice</a></li>
            </ul>
            <p class="copyright">Company Name © DeepAI 2021</p>
        </footer>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/js/bootstrap.bundle.min.js"></script>



  
  </body>
</html>








