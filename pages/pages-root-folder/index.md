---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
header:
    # image_fullwidth: "genvis-dna-bg_optimized_v1a.png"
---      
<div class="row">

  <div class="small-6 columns" >
    <img src="/assets/img/SJTU-photo4.jpg">
  </div>
    
  <div class="small-6 columns">
    <img src="/assets/img/group-photo.jpg">
  </div>
    

</div>

<!-- <div class="row">
  
</div> -->

## Research Overview
The Intelligent Imaging & Computational Vision (IICV) Laboratory investigates artificial intelligence and machine learning (AI/ML) for imaging science and vision science. 

Our current projects include:
1. Deep generative model-produced virtual population for conducting virtual imaging trials.
2. Machine learning-based numerical observers for calculating task-based measures of image quality.
3. Visual search and biologically plausible computer vision.
4. Deep learning for task-driven computational imaging.

Research in the IICV Lab is conducted within the Global Institute of Future Technology (GIFT) at Shanghai Jiao Tong University (SJTU). Students in the IICV Lab come from various institutes including GIFT and UM-SJTU JI. The IICV Lab is directed by Prof. Weimin Zhou.
<div class="row">
  
</div>


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
  animation-name: fade;
  animation-duration: 1.5s;
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
  <img src="/assets/img/research/VS.png" style="width:100%">
    <caption class = "caption"> Bayesian Ideal Searcher with Inter-Saccade Response Correlations </caption>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="/assets/img/research/mcmc_gan.jpg" style="width:100%">
  <p class = "caption"> MCMC-GAN for Ideal Observer Computation </p>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="/assets/img/research/AmGAN.png" style="width:100%">
  <p class = "caption"> AmbientGAN for Establishing Stochastic Object Models </p>
</div>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>


let slideIndex = 0;
showSlides();
    
function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none"; 
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1} 
  slides[slideIndex-1].style.display = "block"; 
  setTimeout(showSlides, 5000); 
}

function showSlides_(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
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

function plusSlides(n) {
  showSlides_(slideIndex += n);
}
    
</script>

</body>
