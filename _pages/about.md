---
permalink: /
title: " "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p style="font-family:Arial"> I am a S.V. Ciriacy-Wantrup postdoctoral fellow at UC Berkeley ARE. Starting fall of 2025, I will be an assistant professor at the Frank Batten School of Leadership and Public Policy at the University of Virginia.</p>

<p style="font-family:Arial"> I received my PhD in economics from Harvard in 2024, and my B.A. in economics and environmental studies from Brown University in 2016.</p>

<p style="font-family:Arial"> My research interests are in public economics and environmental economics. I'm particularly interested in regulation and social and environmental programs.</p>

<p style="font-family:Arial"> My CV can be found <a href="http://jenna-anders.github.io/files/Anders_CV_2024.pdf" target="_blank">here</a>.

</p>

<br>

<div id="slideshow-wrapper" style="position: relative; width: 300px; height: 400px; margin: 100px auto; text-align: center;">
  <img class="slide" src="images/fortwitter.jpeg" style="width:100%; height:auto; position:absolute; top:0; left:0; opacity:1; transition: opacity 1s;">
  <img class="slide" src="images/bird.jpeg" style="width:100%; height:auto; position:absolute; top:0; left:0; opacity:0; transition: opacity 1s;">
  <img class="slide" src="images/yosemite.jpeg" style="width:100%; height:auto; position:absolute; top:0; left:0; opacity:0; transition: opacity 1s;">
</div>

<script>
  const slides = document.querySelectorAll('#slideshow-wrapper .slide');
  let current = 0;

  setInterval(() => {
    slides[current].style.opacity = 0;
    current = (current + 1) % slides.length;
    slides[current].style.opacity = 1;
  }, 5000);
</script>


<br>

