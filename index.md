---
layout: default
---
 <!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <img src="{{ site.baseurl }}/images/SliderOne.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <img src="{{ site.baseurl }}/images/SliderTwo.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <img src="{{ site.baseurl }}/images/SliderThree.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <img src="{{ site.baseurl }}/images/SliderFour.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <img src="{{ site.baseurl }}/images/SliderFive.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <img src="{{ site.baseurl }}/images/SliderSix.jpg" style="width:100%">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <div class="centered">
        <h1>Aikinomichi Linz</h1>
        <p>Persönliche Entwicklung durch Kampfkunst</p>
        <div class="row">
            <div class="col">
                <button class="buttonType1">WAS IST AIKIDO</button><br/><br />
                <button class="buttonType1">WAS DICH ERWARTET</button>
            </div>
            <div class="col">
                <button class="buttonType2">WER WIR SIND</button><br /><br />
                <button class="buttonType2">ERSTES TRAINING</button>
            </div>
        </div>
    </div>
</div>
<br/>

<div class="container">
<div class="row text-center">
<div class="col" markdown="1">
# Aikido
Was dich erwartet
</div>
</div>
<div class="row">
<div class="col" markdown="1">
# Kampfkunst
Aikido ist eine traditionelle japanische Kampfkunst, die von O-Sensei Morihei Ueshiba zu Beginn des 20. Jahrhunderts aus älteren Kampfkünsten entwickelt wurde. Das Ziel dieser Kampfkunst ist jedoch nicht der Sieg über oder die Zerstörung eines Gegeners sondern vielmehr eine friedliche Lösung einer Konfliktsituation. Der Aspekt den Angreifer nicht zu verletzen ist ebensowichtig wie der Aspekt der Selbstverteidigung.
</div>
<div class="col" markdown="1">
# Technik
Die Basisbewegungen sind kreis- bzw. spiralförmig. Der Aikidoka lernt nicht gegen eine Angriffsenergie zu arbeiten sondern mit der Angriffsenergie zu arbeiten und diese in eine kreisförmige Bewegung umzuwandeln. Man lernt Hebel, Fixierungen und Würfe um Angreifer zu neutralisieren, ohne diese ernsthaft zu verletzen. In der selben Weise wie man die Techniken lernt, lernt man auch die Fallschule, die es ermöglicht geworfen zu werden ohne sich dabei zu verletzen. 
</div>
<div class="col" markdown="1">
# Essenz
Aikido ist aber mehr als nur das Erlernen von Techniken. Etikette und Höflichkeit sind ein ebenso wichtiger Teil in Aikido. Aikido ist auch kein Sport, es gibt daher auch keinen sportlichen Wettkampf. Durch kontinuierliches und kooperatives Training verbessert man seine Technik, ohne dass es dabei einen Sieger oder einen Verlierer gibt. Als traditionelle japanische Kampfkunst verbindet Aikido einen aufmerksamen Geist und eine effektive Technik mit Respekt und Etikette bei einem fürsorglichen Umgang miteinander.
</div>
</div>
<!--
<div class="container" >
<div class="row">
<div class="col text-danger" markdown="1">
# helloooooooo
## Hello 2
### hello 3
This is a test
* 1
* 2
</div>
</div>
</div>
-->
<script>
var slideIndex = 0;
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
  setTimeout(showSlides, 8000); // Change image every 2 seconds
}
</script>