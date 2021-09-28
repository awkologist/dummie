---
layout: page
title: Bildgallerie
permalink: /gallery/
---

### Bildergallerie

<style>
.dummieAbb {display:none;}
</style>

<img class="dummieAbb" src="/dummie/images/abb-dummies.001.png">
<img class="dummieAbb" src="/dummie/images/abb-dummies.002.png">
<img class="dummieAbb" src="/dummie/images/abb-dummies.003.png">
<img class="dummieAbb" src="/dummie/images/abb-dummies.004.png">
<img class="dummieAbb" src="/dummie/images/abb-dummies.005.png">

<button class="w3-button w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
<button class="w3-button w3-display-right" onclick="plusDivs(+1)">&#10095;</button>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
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


