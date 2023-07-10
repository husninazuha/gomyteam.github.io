<!DOCTYPE html>
<html>
<head>
<title>GoMyTeam Website</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<style>

	.header{
		margin-top: 10px;
	}

	.logo{
		
		width:90px;
		height:45px;
		margin-left:700px;
		margin-right:60px;

	}

	.box{
		font-size:15px;
		padding:20px;
		text-decoration:none;
		font-family:New Century Schoolbook, serif;
		color:black;
	}

	/*slideshow*/

	.mySlides {
		display:none;
		height:700px;
		background: linear-gradient(#00FFFF, #9198e5);

	}
.w3-tag, .fa {cursor:pointer}
.w3-tag {height:15px;width:15px;padding:0;margin-top:6px}

.images{
	opacity:40%;
}

.centered {
	
  text-align:center;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.centered1{
	font-family:'Montserrat', sans-serif;
	font-weight:300;
	margin-bottom:0px;
	font-size:30px;
	color:white;

}

.centered2{
	font-size:50px;
	line-height:0.9;
	font-weight:600;
	font-family:'Montserrat', sans-serif;
	color:white;
	text-align:center;
}

.newsletter:hover{
	cursor:pointer;

}

.newsletter{
	text-decoration:none;
	margin-left: 5%;
}

footer{
	margin-top:50px;
}

h1{
  	font-weight:600;
  	font-size:20px;
  	color:#00FFFF;
  }

  a{text-decoration:none;}
  a:hover{cursor:pointer;}

/*end slideshow*/

</style>
</head>

<body>
<div class="header">
	
	<div class="w3-white w3-top w3-padding-large">
	  <a href="gomyteam.html" class="box w3-button">Home</a>
	  <a href="candidate.html" class="box w3-button">Candidates</a>
	  <div class="w3-dropdown-hover w3-hide-small">
      <button class="w3-button box" title="Notifications">Product <i class="fa fa-caret-down"></i></button>     
      <div class="w3-dropdown-content w3-card-4 w3-bar-block">
      <a href="payroll.html" class="w3-bar-item w3-button">E Payroll</a>
      <a href="attendance.html" class="w3-bar-item w3-button">E Attendance</a>
      <a href="performance.html" class="w3-bar-item w3-button">E Performance</a>
      </div>
      <a href="pricing.html" class="box w3-button">Pricing</a>
	</div>
	<img class ="logo" src="image/logo.png" alt="logo">

</div>
</div>

<!-- Slideshow -->
  <div class="w3-container " id="home">
    <div class="w3-display-container mySlides">
      <img class="images" src="image/image1.jpg" style="width:100%; height:700px">
      <div class="w3-display-middle w3-container w3-padding-32 centered">
  		<p class="centered1">Keep in touch & stay updated</p>
  		<p class="centered2">ANYWHERE </p>
  		<p class="centered2">ANYTIME</p>
        <a href="attendance.html" class="w3-white w3-padding-large w3-animate-bottom newsletter" style="white-space:nowrap"> E Attendance</a>
        
      </div>
    </div>
    <div class="w3-display-container mySlides">
      <img class="images" src="image/image2.jpg" style="width:100%; height:700px">
      <div class="w3-display-middle w3-container w3-padding-32 centered">
  		<p class="centered1">Stuck in a career?</p>
  		<p class="centered2">LET US HELP YOU</p>
  		<p class="centered2">MATCH YOUR ROLE</p>
        <a href="candidate.html" class="w3-white w3-padding-large w3-animate-bottom newsletter">Upload Your CV</a>
        
      </div>
    </div>
    <div class="w3-display-container mySlides">
      <img class="images" src="image/image3.jpg" style="width:100%; height:700px">
      <div class="w3-display-middle w3-container w3-padding-32 centered">
  		<p class="centered1">Scale Better with the Right Plan</p>
  		<p class="centered2">ESTIMATE TOTAL COST</p>

        <a href="payroll.html" class="w3-white w3-padding-large w3-animate-bottom newsletter">E Payroll</a>
        
      </div>
    </div>

    <!-- Slideshow next/previous buttons -->
    <div class="w3-container w3-dark-grey w3-padding w3-xlarge">
      <div class="w3-left" onclick="plusDivs(-1)"><i class="fa fa-arrow-circle-left w3-hover-text-teal"></i></div>
      <div class="w3-right" onclick="plusDivs(1)"><i class="fa fa-arrow-circle-right w3-hover-text-teal"></i></div>
    
      <div class="w3-center">
        <span class="w3-tag demodots w3-border w3-transparent w3-hover-white" onclick="currentDiv(1)"></span>
        <span class="w3-tag demodots w3-border w3-transparent w3-hover-white" onclick="currentDiv(2)"></span>
        <span class="w3-tag demodots w3-border w3-transparent w3-hover-white" onclick="currentDiv(3)"></span>
      </div>
    </div>
  </div>

  <!-- Footer section -->
  
  <footer class="w3-row-padding w3-padding-54 w3-black">

    <div class="w3-third  m6 w3-padding-large">
      <h1>EXPLORE</h1>
      <p>
        <a href="gomyteam.html" class=" w3-large w3-margin-bottom">Home</a><br> <a href="candidate.html" class=" w3-margin-bottom w3-large">Candidates</a><br><a href="attendance.html" class=" w3-large w3-margin-bottom">E Attendance</a><br> <a href="payroll.html" class=" w3-large w3-margin-bottom">E Payroll</a><br> <a href="performance.html" class=" w3-large w3-margin-bottom">E Performance</a><br>  
        <a href="pricing.html" class=" w3-large w3-margin-bottom">Pricing</a> 
      </p>
    </div>
  
    <div class="w3-third m6 w3-padding-large">
      <h1>GoMyTeam Sdn Bhd</h1>
      <ul class="w3-ul w3-hoverable">
        <li class="w3-padding-16">
          <img src="image/location.jpg" class="w3-left w3-margin-right" style="width:30px">
          <span class="">Changkat Bukit Utama PJU 6, Bandar Utama, 47800 Petaling Jaya, Selangor</span><br>
          
        </li>
        <li class="w3-padding-16">
          <img src="image/phone.jpg" class="w3-left w3-margin-right" style="width:30px">
          <span class="w3-large">+601 234 5678</span><br>
          
        </li>
          <li class="w3-padding-16">
          <img src="image/email.png" class="w3-left w3-margin-right" style="width:30px">
          <span class="w3-large">gomyteam@gmail.com</span><br>
          
        </li> 
      </ul>
    </div>

    <div class="w3-third m6 w3-padding-large">
      <h1>GoMyTeam Group</h1>
      <p>We focus on providing the world class employee engangement applications. As one of the leading entities in Malaysia's HR industry, we take pride in ensuring our clients' highest level of satisfaction and service.</p>
      
    </div>
  </footer>

  <script>
// Slideshow
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function currentDiv(n) {
  showDivs(slideIndex = n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demodots");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" w3-white", "");
  }
  x[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " w3-white";
}
</script>


</body>
</html>
