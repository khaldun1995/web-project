<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1500px;
  position: relative;
  margin: auto;
}

/* Heading 2 css style */
h4{
  color:#0ed8f0;
  text-align:none;
  padding:5px;
  margin:1px;
  font-size: 30px;
  }

#section{
  width:95%;
  height:100%;
  }

input{
  border-radius:10px;
  background-color:#15c9de;
  padding:5px;
  text-color:white;
  border:2px solid white;
  }


h3{
   color:#07b7dd;
   text-align:center;
   padding:5px;
   margin:1px;
   font-size:50px;
   font-family:MurrayHill Bd BT;
   }

h1{
   color:skyblue;
   text-align:center;
   padding:5px;
   margin:1px;
   font-size:35px;
   font-family:Estrangelo Edessa;
   }

h2{
   color:white;
   padding:10px;
   margin:20px;
   font-family:Arial;
   text-align:center;
   font-size:30px;
   }

.button{
   background-color:#78c8f2;
   font-family:Fritz;
   color:white;
   float:left;
   font-size:20px;
   border-radius:10px;
   }

#bolu{
  font-family:Fritz;
  border-radius:8px;
  color:#26afef;
  }
  


  p{
   color:black;
   text-align:none;
   padding:5px;
   margin:1px;
   font-family:Gabriola;
   font-size: 20px;
   }

#p01{
   color:coral;
   text-align:center;
   padding:10px;
   margin:1px;
   font-family:Bodoni MT;
   }

marquee {
   background-color: skyblue;
   color: white;
   font-family:DaunPenh;
   padding: 3px;
   font-size: 30px;
   border-radius: 10px;
   }

.topnav{
   background-color:skyblue;
   text-align:center;
   text-decoration:none;
   padding:5px;
   font-size:26px;
   margin:0.3px;
   color:white;
   width:1335px;
   border-radius:10px;
   }

.topnav a{
   text-decoration:none;
   padding:10px;
   font-size:20px;
   font-family:Flareserif821 BT;
   margin:2px;
   color:white;
   }

.topnav a.active{
   background-color:#05204d;
   color:white;
   }

.topnav a:hover{
   background-color:#1389b0;
   color:white;
   }

#event{
   border:none;
   color:skyblue;
   background-color:#78c8f2;
   text-align:left;
   padding:2px;
   height:30px;
   width:260px;
   margin:20px;
   }

#nav{
   background-color:#78c8f2;
   padding:10px;
   margin:2px;
   color:white;
   float:right;
   font-size:20px;
   }

#nav a{
   text-decoration:none;
   color:white;
   }

.mark{
   text-align:center;
   background-color:skyblue;
   font-family:NewsGoth Cn BT;
   color:white;
   }

.happy{
   text-align:center;
   font-family:Calibri;
   font-size:20px;
   }


#lady1{
   float:left;
   height:150px;
   border-radius:20px;
   }

.kjv{
   width:30px;
   }

.eze1{
   float:left;
   width:100%;
   }

.row {
   background-color: grey;
   }

#ade1{
   font-family:Gabriola;
   color: black;
   font-size: 29px;
   padding:5px;
   }

#ade2{
   font-family:Gabriola;
   color: black;
   font-size: 29px;
   padding:5px;
   }

.eze2{
   font-family:Gabriola;
   color: black;
   float:middle;
   font-size: 29px;
   padding:5px;
   }

.eze3{
   font-family:Gabriola;
   color: black;
   float:left;
   font-size: 25px;
   padding:0.5px;
   margin:1px 9px;
   width:1500px;
   position:relative;
   }

.eze4{
   margin:40px;
   float:left;
   border:5px solid #b6b5b5;
   }

.eze5{
   margin:60px;
   float:left;
   border:5px solid #b6b5b5;
   }

.eze6{
   margin:60px;
   float:left;
   border:5px solid #b6b5b5;
   }


.yomi{
   margin:70px;
   float:left;
   text-decoration:none;
   border:5px solid #b6b5b5;
   padding:5px;
   background-color:#4cb0de;
   color:#03356d;
   }

.hakeem a{
   text-decoration:none;
   padding:10px;
   font-size:17px;
   margin:2px;
   color:white;
   font-family:Calibri;
   }

.hakeem a.active{
   background-color:#05204d;
   color:white;
   }


.footer1{
   float:left;
   width:390px;
   padding:5px;
   height:150px;
   text-decoration:none;
   }


.mylove{
   height:200px;
   width:100%;
   }

#ade{
  color:black;
  }

.subscribe {
  color: #f2f2f2;
  font-size: 15px;
  padding:0.5;
  position:relative;
  bottom:8px;
  width:100%;
  bottom:100px;
  text-align:center;
  }

#logo{
 text-align:center;
}

.subscribe1 {
  color: #f2f2f2;
  font-size: 20px;
  padding:0.5;
  position:relative;
  bottom:8px;
  width:95%;

  bottom:120px;
  text-align:center;
  }

.ranch1{
  font-family:Gabriola;
  text-align:center;
  }

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}

</style>

<title>Janeze International Hospital</title>

</head>

<body onload="Pl()">

<h1>Janeze International Hospital</h1>

<div id="logo">
<img src="images/khaldun1.png">
</div>

<div class="date">

  <p>Date/Time:<span id="datetime"></span></p>

  <script>

  var dt=new Date();
  
  document.getElementById("datetime").innerHTML=(("0"+(dt.getMonth()+1)).slice(-2)
  +"/"+(("0"+dt.getDate())).slice(-2))+"/"+(dt.getFullYear())+""+((""+dt.getHours
  ()).slice(-2))+":"+(("0"+dt.getMinutes()).slice(-2));

  </script>

  </div>

<div class="topnav">

<ui><a  class="active" href="index.html">Home</a><ui>

<ui><a href="aboutus.html">About Us</a><ui>

<ui><a href="services.html">Our Testimonies</a><ui>

<ui><a href="form.html">Register for Services</a><ui>

<ui><a href="index.html">Health Records</a><ui>

<ui><a href="register.html">Training</a><ui>

<ui><a href="testimony.html">Newsfeed</a></ui>

<a href="contact.html">Contact Us</a>

</div>

<div class="slideshow-container">
<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/ope.jpg" style="width:100%">
  </div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/cat.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/employee training.jpg" style="width:100%">
  </div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/operate.jpg" style="width:100%">
  </div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/hosp.jpg" style="width:100%">
  </div>

  <div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/like.jpg" style="width:100%">
  </div>

  <div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/took.jpg" style="width:100%">
  </div>

  <div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/doc.jpg" style="width:100%">
  </div>

  <div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/hospital.jpg" style="width:100%">
  </div>


<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="images/care.jpg" style="width:100%">
  </div>

  <br>

  <div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span> 
  </div>



<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 5000); // Change image every 2 seconds
}

</script>

<br>



<div id="section">


<h3>You Are Welcome To Our Official Webpage</h3>




<!-- Here is upcoming event -->


<div id="nav">

  <h2>Upcoming Events</h2>

<div id="nife">

<button id="bolu">May<br>8</button>

<button id="event">
<a href="index.html">Janeze Medical Center Board of Director
<br>
9:30am-12:30am</a>
</button>

</div>


<div id="nife">

<button id="bolu">Jun<br>10</button>


<button id="event">
<a href="index.html">Janeze Corporation Board of Directors Meeting
<br>
12:300am-1:00pm</a>
</button>

</div>


<div id="nife">


<button id="bolu">July<br>10</button>

<button id="event">
<a href="index.html">Nurse and Staff Meeting
<br>
1:00pm-3:00pm</a>
</button>

</div>

</div>

<!-- Upcoming event end here -->

<br>

<!-- president speech at the section -->

<div class="lady">

<h4>President Speech On Schizophrenia</h4>

<p id="ade2">

Schizophrenia is a chronic and severe mental disorder that affects
how a person thinks feels and behaves. It is a mental disorder that
affects how a person thinks feels and behaves. It is a mental disorder
coined by Eugen Bleuler to mean "split psyche or mind". A concept used
not only to mean a split from social reality but also a split between thoughts
and emotions. Schizophrenia is a serious mental disorder that affects how a person
thinks what they think, feels and behaves in the society.

<a href=#newsfeed>Read more on this</a>

</div>


<br>



<div id="eze">

<h4>Doctor William Analysis on Child Sexual Abuse</h4>

<p id="ade1">

Child sexual abuse has emerged has one of the serious social problems in Nigeria 
to the extent that if appropriate measure is not taken into consideration to curb 
this menace, it will not only harmper societal order but also disrupt the growth 
and development of Nigerian society. Although, various societies have had to live 
with it, all through the ages, its sudden increase in Nigeria is spreading fears 
across the land, that citizen especially the women are now in state of pandemonium 
as their female child fall victims of this act everyday of their lives. The sudden 
increase in this phenomenon is attributed to breakdown of the traditional culture, 
due to rapid and radical social change in the traditional African society which is 
fostered by the sociological concept of the extended family as a system which provides 
profound love, protection, security and care to the child within the cultural milieu.

<a href=#newsfeed>Read more on this</a>

</p>

</div>


<br>

<br>

<marquee behavior="scroll" direction="right">

The Number One Health Care Facility in Nigeria...

Towards Ensuring Wellness and Wellbeing of Individual...

</marquee>


<!-- The three middle image section start from here-->


<div class="eze4">
<img src="images/world health.jpeg" alt="health" style="width:320px; height:250px">

<h4>APPLE DECIDES</h4>

<p id="ade">

Apple has acquired Tueo Health, a small start-up<br> company
that was developing a system to help <br> parents monitor
asthma symptoms in sleeping <br>children, according to a
person familiar with the<br> deal.
It's unclear how much Apple paid for Tueo<br> Health
-The start-up raised a small seed round<br>$1.1million
in funding in 2017.</p>

<button class="button">Read More</button>

</div>


<div class="eze5">
<img src="images/apple.jpeg" alt="health" style="width:320px; height:250px">

<h4>(WHO)Health</h4>

<p id="ade">

Apple has acquired Tueo Health, a small start-up<br> company
that was developing a system to help <br> parents monitor
asthma symptoms in sleeping <br>children, according to a
person familiar with the<br> deal.
It's unclear how much Apple paid for Tueo<br> Health
-The start-up raised a small seed round<br>$1.1million
in funding in 2017.</p>

<button class="button">Read More</button>

</div>

</div>


<div class="eze6">
<img src="images/work.jpg" alt="health" style="width:320px; height:250px">

<h4>Workplace Health</h4>

<p id="ade">

Apple has acquired Tueo Health, a small start-up<br> company
that was developing a system to help <br> parents monitor
asthma symptoms in sleeping <br>children, according to a
person familiar with the<br> deal.
It's unclear how much Apple paid for Tueo<br> Health
-The start-up raised a small seed round<br>$1.1million
in funding in 2017.</p>

<button class="button">Read More</button>

</div>

</div>


<!-- The get notified image together with prior footer start from here-->


<div>
<img src="images/koko.jpg" class="mylove">
<div class="subscribe1">
Get Notified
</div>

<div class="subscribe">
<input type="text" name="email" placeholder="email">
<input type="Submit" value="Submit">
</div>


<div class="joyce">

<h3>Get Real Health Expert At your Door Step</h3>

</div>


 <div class="ranch1">

    <p id="ade">

    "The power of community to create health is far greater than<br>
     any physician, clinic or hospital"

     --Mark Hyman
     
     <br>

    "Never walk into a hospital crying. Have an attitude that you<br>
     will make someone else's life better"

     --Jim Kelly

     </p>

 </div>

<div class="health">

<p id="ade">

With our health system, we guarantee maximum health protection, health
counselling and proper health supervision. Our health system cut across
pivotal health sector of human system that aimed at ensuring human body
system is at equlibrum all time all day.
With our health system, we guarantee maximum health protection, health
counselling and proper health supervision. Our health system cut across
pivotal health sector of human system that aimed at ensuring human body
system is at equlibrum all time all day.pivotal health sector of human 
system that aimed at ensuring human body that aimed at ensuring human body

</p>

</div>
     

<!-- The get to know us footer start from here-->


<div class="yomi">

  <div class="footer1">

  <h5>Learn About</h5>
   
  <div class="hakeem">
  <a href=#aboutus>What Janeze is all about</a>
  <br>
  <a href=#aboutus>Plan & Piorities</a>
  <br>
  <a href=#newsfeed>Frequently Asked Question (FAQ)</a>
  </div>

  </div>




  <div class="footer1">

  <h5>Get Involved</h5>

  <div class="hakeem">
  <a href=#newsfeed>Janeze Corporation</a>
  <br>
  <a href=#newsfeed>Janeze Board of Directors</a>
  <br>
  <a href=#training>Janeze Training</a>
  </div>

  </div>


  <div class="footer1">

  <h5>Subscribe</h5>

  <br>

  <input type="Email" name="Email" placeholder="Email">

  <input type="Submit" value="Submit">

  </div>

</div>


<!-- The get connected footer start from here-->

<div class="happy">
Get Connected To Us Via:
<br>
<br>
<img src="images/unnamed1.png" class="kjv">
<img src="images/unnamed.png" class="kjv">
<img src="images/unnamed2.png" class="kjv">
</div>


<!-- The main footer start from here-->



<div class="mark">
   2019 | Janeze Hospital | A Corporate Body.<br>
   All Rights Reserved. Accredited by the Higher Learning Commision.
   All Trademarks Are Registered Property of Janeze International Hospital.<br>
   Used By Permission only.<br>
   Powered By Khaldun Jr.

</div>



</div>




</body>

</html>















                                     
