---
layout: page
title: Bildgallerie
permalink: /gallery/
---

Klicken Sie auf eine Abbildung, um dass nächste Bild zu sehen. Alternativ können Sie auf die schwarzen Punkte klicken, um vorwärts und zurück zu navigieren.

done

<details>
  <summary>Einleitung</summary>

<center><br>
<b onclick="currentDiv(1, 0)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2, 0)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(3, 0)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(4, 0)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(5, 0)">●</b> 
</center>
<figure class="dummieAbb0" >
<img src="/dummie/images/abb-dummies.001.png" onclick="plusDivs(+1, 0)">
<figcaption><b>Abb. 1: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb0" >
<img src="/dummie/images/abb-dummies.002.png" onclick="plusDivs(+1, 0)">
<figcaption><b>Abb. 2: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb0" >
<img src="/dummie/images/abb-dummies.003.png" onclick="plusDivs(+1, 0)">
<figcaption><b>Abb. 3: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb0" >
<img src="/dummie/images/abb-dummies.004.png" onclick="plusDivs(+1, 0)">
<figcaption><b>Abb. 4: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb0" >
<img src="/dummie/images/abb-dummies.005.png" onclick="plusDivs(+1, 0)">
<figcaption><b>Abb. 5: </b>Kapitel bla bla </figcaption>
</figure>
</details>

<details>
  <summary>Kapitel 1: text</summary>

<center><br>
<b onclick="currentDiv(1, 1)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2, 1)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(3, 1)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(4, 1)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(5, 1)">●</b> 
</center>
<figure class="dummieAbb1" >
<img src="/dummie/images/abb-dummies.001.png" onclick="plusDivs(+1, 1)">
<figcaption><b>Abb. 1: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb1" >
<img src="/dummie/images/abb-dummies.002.png" onclick="plusDivs(+1, 1)">
<figcaption><b>Abb. 2: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb1" >
<img src="/dummie/images/abb-dummies.003.png" onclick="plusDivs(+1, 1)">
<figcaption><b>Abb. 3: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb1" >
<img src="/dummie/images/abb-dummies.004.png" onclick="plusDivs(+1, 1)">
<figcaption><b>Abb. 4: </b>Kapitel bla bla </figcaption>
</figure>
<figure class="dummieAbb1" >
<img src="/dummie/images/abb-dummies.005.png" onclick="plusDivs(+1, 1)">
<figcaption><b>Abb. 5: </b>Kapitel bla bla </figcaption>
</figure>
</details>





<script>
var slideIndex = [1,1];
var slideId = ["dummieAbb0", "dummieAbb1"]
showDivs(1, 0);
showDivs(1, 1);

function currentDiv(n, no) {
  showDivs(slideIndex = n, no);
}

function plusDivs(n, no) {
  showDivs(slideIndex[no] += n, no);
}

function showDivs(n, no) {
  var i;
  var x = document.getElementsByClassName(slideId[no]);
  if (n > x.length) {slideIndex[no] = 1}
  if (n < 1) {slideIndex[no] = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex[no]-1].style.display = "block";  
}

</script>


