---
permalink: /
title: " "
excerpt: "About me"
author_profile: true
---

<p style="font-family:Arial"> I am a S.V. Ciriacy-Wantrup postdoctoral fellow at UC Berkeley ARE. Starting fall of 2025, I will be an assistant professor at the Frank Batten School of Leadership and Public Policy at the University of Virginia.</p>

<p style="font-family:Arial"> I received my PhD in economics from Harvard in 2024, and my B.A. in economics and environmental studies from Brown University in 2016.</p>

<p style="font-family:Arial"> My research interests are in public economics and environmental economics. I'm particularly interested in regulation and social and environmental programs.</p>

<p style="font-family:Arial"> My CV can be found <a href="http://jenna-anders.github.io/files/Anders_CV_2023.pdf" target="_blank">here</a>.

</p>

<br>

<p style="text-align:center; margin-top:100px"><img src="images/fortwitter.jpeg" alt="Test" width="300" height="auto"> </p>

<br>

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>

<!-- <h2>Automatic Slideshow</h2> 
<p>Change image every 2 seconds:</p> -->

<div class="slideshow-container">

<div class="mySlides fade">
  <img src="images/fortwitter.jpeg" style="width:30%">
  <div class="text">Andover, MA</div>
</div>

<div class="mySlides fade">
  <img src="images/bird.jpeg" style="width:30%">
  <div class="text">Upland Sandpiper</div>
</div>

<div class="mySlides fade">
  <img src="images/yosemite.jpg" style="width:30%">
  <div class="text">Yosemite National Park</div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
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
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>

</body>
</html> 


