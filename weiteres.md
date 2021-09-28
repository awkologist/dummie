---
layout: page
title: Bildgallerie
permalink: /gallery/
---

Klicken Sie auf eine Abbildung, um dass nächste Bild zu sehen. Alternativ können Sie auf die schwarzen Punkte klicken, um vorwärts und zurück zu navigieren.

done

<center>
<b onclick="currentDiv(1)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(3)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(4)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(5)">●</b> 
</center>
<figure class="dummieAbb" >
<img src="/dummie/images/abb-dummies.001.png" onclick="plusDivs(+1)">
<figcaption><b>Abb. 1: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb" >
<img src="/dummie/images/abb-dummies.002.png" onclick="plusDivs(+1)">
<figcaption><b>Abb. 2: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb" >
<img src="/dummie/images/abb-dummies.003.png" onclick="plusDivs(+1)">
<figcaption><b>Abb. 3: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb" >
<img src="/dummie/images/abb-dummies.004.png" onclick="plusDivs(+1)">
<figcaption><b>Abb. 4: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb" >
<img src="/dummie/images/abb-dummies.005.png" onclick="plusDivs(+1)">
<figcaption><b>Abb. 5: </b>Kapitel bla bla </figcaption>
</figure>



<script>
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
  var x = document.getElementsByClassName("dummieAbb");
  if (n > x.length) {slideIndex = 1} 
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none"; 
  }
  x[slideIndex-1].style.display = "block"; 
}
</script>


