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
                <a class="buttonType1" href="{{ site.baseurl }}/aikido">WAS IST AIKIDO</a><br/><br />
                <a class="buttonType1" href="#wasDichErwartet">WAS DICH ERWARTET</a>
            </div>
            <div class="col">
                <a class="buttonType2" href="{{ site.baseurl }}/ueberUns">WER WIR SIND</a><br /><br />
                <a class="buttonType2" href="{{ site.baseurl }}/training#erstesTraining">ERSTES TRAINING</a>
            </div>
        </div>
    </div>
</div>
<br/>

<div class="container" id="wasDichErwartet">
<div class="row text-center">
<div class="col" markdown="1">
# Aikido
Was dich erwartet
</div>
</div>
<div class="row">
<div class="col" markdown="1">
# Kampfkunst
**Aikido** ist eine traditionelle japanische Kampfkunst, die von O-Sensei Morihei Ueshiba zu Beginn des 20. Jahrhunderts aus älteren Kampfkünsten entwickelt wurde. Das Ziel dieser Kampfkunst ist jedoch nicht der Sieg über oder die Zerstörung eines Gegeners, sondern vielmehr eine friedliche Lösung für eine Konfliktsituation zu finden. Der Aspekt den Angreifer nicht zu verletzen ist ebenso wichtig, wie der Aspekt der Selbstverteidigung. Aikido ist kein Sport, es gibt daher auch keinen sportlichen Wettkampf – ein Aspekt der in der heutigen Zeit, in der man z. B. im Berufsleben oft gezwungen ist immer schneller und besser zu werden, zur Entschleunigung beiträgt.
</div>
<div class="col" markdown="1">
# Technik
Die Bewegungen im Aikido sind oft kreis- bzw. spiralförmig. Im Aikido lernt man, nicht gegen die Angriffsenergie, sondern mit der Angriffsenergie zu arbeiten und diese in eine kreisförmige Bewegung umzuwandeln. Man lernt Hebel, Fixierungen und Würfe um Angriffe zu neutralisieren, ohne den Angreifer dabei zu verletzen. In der selben Weise wie man die Techniken lernt, lernt man auch die Fallschule, die es ermöglicht geworfen zu werden ohne sich dabei zu verletzen. Durch kontinuierliches und kooperatives Training **verbessert** man seine Technik, ohne dass es dabei einen Sieger oder einen Verlierer gibt: die persönliche Entwicklung steht im Vordergrund!
</div>
<div class="col" markdown="1">
# Essenz
Aikido ist aber mehr als das Erlernen von Techniken: **Selbstvertrauen**, Präsenz, Mut, Aufrichtigkeit, Glaubwürdigkeit aber auch Güte und Höflichkeit werden durch das regelmäßige Üben der Kampfkunst  Aikido verinnerlicht.  Auch im Alltag werden sich diese Tugenden ganz automatisch etablieren: es ist erstaunlich, wie viele Konflikte man durch Aufmerksamkeit und Selbstvertrauen bereits im Vorfeld vermeiden oder durch Höflichkeit, Respekt und eine Prise Humor gewaltlos lösen kann. Als traditionelle japanische Kampfkunst verbindet Aikido einen aufmerksamen Geist und eine effektive Technik mit Respekt und Höflichkeit bei einem fürsorglichen Umgang miteinander.
</div>
</div>
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