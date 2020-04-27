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
  <img src="https://an-hongyu.github.io/vt/images/photo/20191111_two_layer_memristor/IMG_3975_2.JPG" style="width:100%">
  <div class="text">Caption Text</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/2019_ornl/IMG_3537.JPG" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/20190510_Torgersen_award/DSC_0185_2.jpg" style="width:100%">
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
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

</body>
</html> 




About Me
------
I am a researcher on Neuromorphic Computing, Neuromorphic Electronic Circuits Design using Emerging Devices, and Artificial Intelligence. I am a doctoral candidate in the [Bradley Department of Electrical and Computer Engineering (ECE)](https://ece.vt.edu/) at [Virginia Tech](https://vt.edu/) (VT). At VT, I am a research assistant under supervision of [Prof. Yang (Cindy) Yi](https://www.yangyi.ece.vt.edu/) in the [Multifunctional Integrated Circuits and Systems Group (MICS)](https://www.mics.ece.vt.edu/). Prior to joining VT, I obtained a master’s degree in the [Electrical and Computer Engineering Department](https://ece.mst.edu/) at [Missouri University of Science and Technology](https://www.mst.edu/) (MST). At MST, I worked with [Prof. Jun Fan](https://emclab.mst.edu/members/faculty/jun-fan/) on the High-speed Design and Signal Integrity projects from Apple and Sony.  During my doctoral period, I worked with [Dr. Zhen Zhou](https://www.linkedin.com/in/zhen-zhou-06484610/) (Intel Labs) on three-dimensional neuromorphic circuit design combining with traditional CMOS technology and memristors. In 2019, I worked with [Dr. Katie Schuman](https://www.ornl.gov/staff-profile/catherine-d-schuman) (Oak Ridge National Laboratory) on developing a new training method for Spiking Neural Networks.  I was born in Shenyang, a small town in the northeast of China. I spent all my childhood in Shenyang, mostly in public library reading popular science books, like One, Two, Three...Infinity, The Feynman Lectures on Physics, etc. Although I did not fully understand what they are talking about then. I also read a lot of science fiction books, such as I, robot, Twenty Thousand Leagues Under the Seas. The dramatic stories and interesting knowledge in these books ignited my interest in science and technology, and eventually leads me to here, a Ph.D. candidate in electrical engineering at Virginia Tech. In my spare time, I’d like to watch movies, read books, do exercises, and sleep.   

Student Recruiting 
------
I will be joining the ECE department of [Michigan Tech](https://www.mtu.edu/ece/) in Fall 2020, serving as an assistant professor. 

Multiple Master and Ph.D. positions with full RA/TA support are available in Hongyu An's research group starting from Fall 2020 or Spring 2021.
Neuromorphic computing is an emerging research topic that realizes artificial intelligence by mimicking and recreating the human brain, including neurons, synapse, and neural networks. This approach involves both hardware design and algorithm developing, such as circuit design, FPGA, neural network algorithms. 
The candidates are expected with either excellent programming capability or hardware design experience. The projects will be assigned based on your background. Two directions can be considered with different responsibilities: 
1.	Software direction: help the PI to develop training algorithm on Spiking Neural Networks and Associative Memory Learning 
2.	Hardware direction: assist the PI to design the corresponding circuits (CMOS, emerging devices) and architecture simulators for Spiking Neural Networks and Associative Memory Learning

Basic Qualifications:

 •	Basic understanding of deep learning, neural networks
 
 •	Relevant research experience in machine learning, deep learning, artificial intelligence
 
 •	Hands-on experience with the latest artificial intelligence and machine learning libraries
 
 •	Programming experience in one or more of the following languages: Python, C++, Java, etc. 
 
 •	Programming experience on deep learning platforms: Pytorch, TensorFlow, etc. 
 
 •	Circuit design experience with Virtuoso, Cadence, SPICE, etc. 


Preferred Qualifications:

 •	Relevant research experience in neuromorphic computing, brain-inspired computing
 
 •	Relevant research experience on Spiking Neural Networks
 
 •	Experience with high-performance computing and novel computing architectures.
 
Desired Skills:

 •	Programming experience with Python, Pytorch, TensorFlow, Java, C++, etc. 
 
 •	Experience with Circuit design, Virtuoso, Cadence, HSPICE, Verilog-A, etc. 
 
 •	Good writing and communication skills 

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

