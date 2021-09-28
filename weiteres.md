---
layout: page
title: Bildgallerie
permalink: /gallery/
---

### Bildergallerie

<style>
.dummieAbb {display:none;}
</style>

<img class="dummieAbb" src="/dummie/images/abb-dummies.001.png" onclick="plusDivs(+1)">
<img class="dummieAbb" src="/dummie/images/abb-dummies.002.png" onclick="plusDivs(+1)">
<img class="dummieAbb" src="/dummie/images/abb-dummies.003.png" onclick="plusDivs(+1)">
<img class="dummieAbb" src="/dummie/images/abb-dummies.004.png" onclick="plusDivs(+1)">
<img class="dummieAbb" src="/dummie/images/abb-dummies.005.png" onclick="plusDivs(+1)">

<center>
<b onclick="currentDiv(1)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(3)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(4)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(5)">●</b> 

<button onclick="currentDiv(1)">⦿</button> 
<button onclick="currentDiv(2)">⦿</button> 
<button onclick="currentDiv(3)">⦿</button> 
<button onclick="currentDiv(4)">⦿</button> 
<button onclick="currentDiv(5)">⦿</button> 
</center>

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


