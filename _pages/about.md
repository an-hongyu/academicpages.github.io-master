---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
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
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
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
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/20190510_Torgersen_award/DSC_0185_2.jpg" style="width:100%">
  <div class="text">Caption Text</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/2019_ornl/IMG_3537.JPG" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/20191111_two_layer_memristor/IMG_3975_2.JPG" style="width:100%">
  <div class="text">Caption Three</div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>

</body>
</html> 




About Me
------
I am a researcher on Neuromorphic Computing, Neuromorphic Electronic Circuits Design using Emerging Devices, and Artificial Intelligence. I was born in Shenyang, a small town in the northeast of China. I spent all my childhood in Shenyang, mostly in public library reading popular science books, like One, Two, Three...Infinity, The Feynman Lectures on Physics, etc. Although I did not fully understand what they are talking about then. I also read a lot of science fiction books, such as I, robot, Twenty Thousand Leagues Under the Seas. The dramatic stories and interesting knowledge in these books ignited my interest in science and technology, and eventually leads me to here, a Ph.D. candidate in electrical engineering at Virginia Tech. In my spare time, I’d like to watch movies, read books, do exercises, and sleep.   

Resaerch Interest: 
------
 •	Neuromorphic Engineering/Computing
 
 •	Energy-Efficient Neuromorphic Electronic Circuits Design
 
 •	Emerging Nanoscale Device Design (Memristor)
 
 •	Machine Learning, Deep Learning, Spiking Neural Networks, Binarized Neural Networks, Reservoir Computing
 
 •	Artificial Intelligence

Education:
------
•	MS, Electrical Engineering, Missouri University of Science and Technology, Rolla, MO, USA

•	BS, Electrical Engineering, Shenyang University of Technology, Shenyang, Liaoning, China

Work Experiences:
------
•	Neuromorphic Algorithms Intern at Oak Ridge National Laboratory, Oak Ridge, summer 2019

Awards and Honors:
------
•	Paul E. Torgersen Graduate Student Research Excellence Award: honored by the work of "Realizing Associative Memory Learning through Neuromorphic Circuits" in 2019

•	Fellowship from the Oak Ridge National Laboratory Advanced Short-Term Research Opportunity Program (ASTRO) in 2019

•	NSF Student Travel Fellowship Reward on IEEE International Conference on Nanotechnology (IEEE NANO 2017)

•	Best Paper Nomination in 18th IEEE International Symposium on Quality Electronic Design (ISQED), 2017

Journal/Conference Reviewer:
------
•	IEEE Transactions on Neural Networks and Learning Systems (TNNLS)

•	IEEE Transactions on Circuits and System I: Regular Papers (TCAS)

•	IEEE International Conference on Nanotechnology (TNANO)

•	Neurocomputing

•	Integration, the VLSI Journal

•	Design Automation Conference (DAC)

•	Design, Automation and Test in Europe Conference and Exhibition (DATE)

•	IEEE International Symposium on Circuits and Systems (ISCAS)

•	IEEE/ACM International Conference On Computer-Aided Design (ICCAD)

•	ACM Great Lakes Symposium on VLSI (GLSVLSI)

•	IEEE International Symposium on Quality Electronic Design (ISQED)

•	IEEE International Symposium on Electromagnetic Compatibility, Signal and Power Integrity (EMC-SIPI)


Skills:
------
•	Programming: MATLAB, C/C++, LabView, PHP, Python, Java

•	Software: HFSS, CST, PSPICE, ADS, Hyperlynx, Q3D, Q2D, HSPICE, Altium

•	Instruments: Network Analyzer, TDR, Spectrum Analyzer, Oscilloscope, Signal generator

