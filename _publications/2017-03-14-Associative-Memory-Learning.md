---
title: "Associative Memory Learning"
collection: Talks
type: "single"
permalink: /research/2017-03-14-Associative-Memory-Learning
venue: ""
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
  <img src="https://an-hongyu.github.io/vt/images/photo/associative_memory/motivation.PNG" style="width:100%">
  <div class="text">Two-layer Memristor</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/associative_memory/associative_memory_learning.PNG" style="width:100%">
  <div class="text">Oak Ridge National Laboratory</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/associative_memory/associative_memory_learning2.PNG" style="width:100%">
  <div class="text">Paul E. Torgersen Researrch Excellence Award</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/associative_memory/associative_memory_learning3.PNG" style="width:100%">
  <div class="text">Paul E. Torgersen Researrch Excellence Award</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://an-hongyu.github.io/vt/images/photo/associative_memory/conclusion.PNG" style="width:100%">
  <div class="text">Paul E. Torgersen Researrch Excellence Award</div>
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

Associative memory is a ubiquitous self-learning method of animals, which enables their neural system to memorize the relationship between two concurrent events. The significance of rebuilding associative is not only to reveal a way of designing a brain-like self-learning neuromorphic system but also to explore a method of comprehending the learning mechanism of a nervous system. The investigations on associative memory reveal that two critical features play important roles: synaptic connecting strength modification and distributed data processing. In nervous systems, the different captured signals, e.g., image and sound, are preprocessed at the different regions of the brain. During the learning process, the synaptic connection strength between the sensory and response neurons increases, consequently to increase the received signal at response neurons. 
In my work, I design a brain-like associative memory learning system that can memorize the relationship of concurrent visual and auditory information by correlating the probabilistic output scores of ANNs together. The hybrid information is associated together through two procedures: preprocessing phase and association phase. In the preprocessing phase, the auditory signal and the visual signal are separately preprocessed by the ANNs. Then the prediction scores are represented by a sequence of spikes. In this way, the information carried by the original data (visual and auditory information) is abstracted into the spiking signals. Then, these spiking signals are coupled together by our so-called associative memory network (AMNs). 


Related Articles:
•	H. An, Qiyuan An, Y. Yi, “[Realizing Behavior Level Associative Memory Learning through Three-dimensional Memristor-based Neuromorphic Circuits](https://ieeexplore.ieee.org/abstract/document/8753741/)”, IEEE Transactions on Emerging Topics in Computational Intelligence, 2019;
•	H. An, Z. Zhou, and Y. Yi, “[Memristor-based 3D neuromorphic computing system and its application to associative memory learning](https://ieeexplore.ieee.org/abstract/document/8117459),” in IEEE 17th International Conference on Nanotechnology (IEEE-NANO), 2017, pp. 555-560.
•	H. An, K. Bai, and Y. Yi, [The Roadmap to Realize Memristive Three-Dimensional Neuromorphic Computing System](https://www.intechopen.com/books/advances-in-memristor-neural-networks-modeling-and-applications/the-roadmap-to-realize-memristive-three-dimensional-neuromorphic-computing-system),” in Advances in Memristor Neural Networks-Modeling and Applications: IntechOpen, 2018.
•	H. An, Z. Zhou, and Y. Yi, “[Opportunities and challenges on nanoscale 3D neuromorphic computing system](https://ieeexplore.ieee.org/abstract/document/8077906),” in Electromagnetic Compatibility & Signal/Power Integrity (EMCSI), 2017 IEEE International Symposium on, 2017, pp. 416-421.
   


