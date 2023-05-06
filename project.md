---
layout: page
title: 3-1-1 Cases in San Francisco
permalink: /project/
---

<h1 class="page-heading">{{ page.title }}</h1>

Empty about right now blaaaaah blah blah tesitng hteah adsadsakfhsakfh sadhsahd shdjhsdj hsajdh sadj ahd asjd hasfa  dhsadkjasidu asdjakdha sdhakdn akfb ajdhasndhadhakd asldh asd aknd jkad asdhsadalkdh ashd ad a

<div>
    <h4 style="text-align:center">Time Series</h4>
    <embed 
        type="text/html" 
        src="/SocialDataFinalProject/assets/images/timeSeriesPlot.html"
        width="1100"
        height="600"
        >
</div>

<div>
    <h4 style="text-align:center">Map Yearly</h4>
    <embed 
        type="text/html" 
        src="/SocialDataFinalProject/assets/images/SF_mapYearly.html"
        width="1100"
        height="600"
        >
</div>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  max-height: 600px;
  position: relative;
  margin: auto;
}

.slideshow-container div { 
    margin: 0px auto;
    width: 100%;
    height: 100%;
    text-align: center;
}

.slideshow-container img {
  object-fit: cover;
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
  <img src="/SocialDataFinalProject/assets/SF_images/Human_or_Animal_Waste_34819.0_South_of_Market_lat37.776082_lng-122.41386.jpg" style="align:center">
  <div class="text">Human or Animal Waste - Closed after 34819 hours ~ 4 years - South of Market</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="/SocialDataFinalProject/assets/SF_images/Liquids_-_Oil_Paint_Other_34816.0_Downtown___Union_Square_lat37.78697032485_lng-122.404836053143.jpg" style="align:center">
  <div class="text">Liquids - Closed after 34816 hours ~ 4 years - Downtown Union Square</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="/SocialDataFinalProject/assets/SF_images/Loose_Garbage_and_Debris_65408.0_Crocker_Amazon_lat37.709297204486_lng-122.431679157206.jpg" style="align:center">
  <div class="text">Garbage and Debris - Closed after 65408 hours ~ 7.5 years - Crocker Amazon</div>
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
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
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
</script>

</body>