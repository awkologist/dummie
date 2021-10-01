---
layout: page
title: Bildgallerie
permalink: /gallery/
---

Klicken Sie auf eine Abbildung, um dass nächste Bild zu sehen. Alternativ können Sie auf die schwarzen Punkte klicken, um vorwärts und zurück zu navigieren.

done4

<details>
  <summary>Einleitung</summary>

<center><br>
<b onclick="currentDiv(1, 0)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2, 0)">●</b> 
</center>
<figure class="dummieChapter_0" >
<img src="/dummie/images/biodummie.001.png" onclick="plusDivs(+1, 0)">
<figcaption>Kunst am Buch – von Kerstin Zentner.</figcaption>
</figure>
<figure class="dummieChapter_0" >
<img src="/dummie/images/biodummie.002.png" onclick="plusDivs(+1, 0)">
<figcaption><b>Abb. 1: </b>Schematische Illustration des Cas9-Proteins der Genschere.</figcaption>
</figure>
<br>
</details>

<details>
  <summary>Kapitel 1: Die Welt der Gene</summary>

<center><br>
<b onclick="currentDiv(1, 1)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2, 1)">●</b> 
</center>
<figure class="dummieChapter_1" >
<img src="/dummie/images/biodummie.006.png" onclick="plusDivs(+1, 1)">
<figcaption>Kunst am Buch – von Kerstin Zentner.</figcaption>
</figure>
<figure class="dummieChapter_1" >
<img src="/dummie/images/biodummie.007.png" onclick="plusDivs(+1, 1)">
<figcaption><b>Abb. 1.1: </b>Modell der DNA-Doppelhelix. Diese Zeichnung aus der Veröffentlichung von <i>James Watson</i> und <i>Francis Crick</i> hat Cricks Frau <i>Odile Crick</i> gezeichnet. Sie verwendete dabei mutmaßlich die Proportionen des Goldenen Schnitts. Die der Struktur zugrundeliegenden Daten wurden von <i>Rosalind Franklin</i> per Röntgenstrukturanalyse gewonnen. Sie starb, bevor der Nobelpreis 1962 für die Strukturaufklärung vergeben wurde.</figcaption>
</figure>
<br>
</details>


<details>
  <summary>Kapitel 2: Von der Vererbung zur quantitativen Genetik</summary>

<center><br>
<b onclick="currentDiv(1, 2)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2, 2)">●</b> 
</center>
<figure class="dummieChapter_2" >
<img src="/dummie/images/biodummie.024.png" onclick="plusDivs(+1, 2)">
<figcaption>Kunst am Buch – von Kerstin Zentner.</figcaption>
</figure>
<figure class="dummieChapter_2" >
<img src="/dummie/images/biodummie.025.png" onclick="plusDivs(+1, 2)">
<figcaption><b>Abb. 2.1: </b>Die Mendelschen Regeln gelten für Merkmale, die von genau einem Gen codiert werden, das in zwei Kopien – also als mütterliches und väterliches Allel – vorliegt. Die erste und zweite Mendelsche Regel beschreiben die Weitergabe der Gene und die Merkmalsausprägung in der ersten und zweiten Tochtergeneration. Das <i>Punnett</i>-Quadrat, benannt nach dem britischen Genetiker <i>Reginald Punnett</i>, beschreibt die möglichen diploiden Genotypen, die aus den haploiden Keimzellen (Allel <i>F</i> und Allel <i>f</i>) entstehen können.</figcaption>
</figure>
<figure class="dummieChapter_2" >
<img src="/dummie/images/biodummie.026.png" onclick="plusDivs(+1, 2)">
<figcaption><b>Abb. 2.2: </b>Die dritte Mendelsche Regel beschreibt die unabhängige Vererbung mehrerer Merkmale, wenn diese nicht gekoppelt sind, das heißt, wenn sie auf unterschiedlichen Chromosomen liegen oder auf einem Chromosom weit voneinander entfernt sind. In diesem Beispiel folgen die Merkmale Farbe (<i>F</i>) und Beschaffenheit (<i>B</i>) der Erbsenhülle einem dominat-rezessiven Erbgang. Die <i>Punnett</i>-Quadrate zeigen die aus der Fusion der haploiden Keimzellen möglichen diploiden Genotypen. Die eingerahmten Merkmalskombinationen der F2-Generation kommen nicht in der Elterngeneration vor. Sie sind reinerbige neue Kombinationen.</figcaption>
</figure>
<br>
</details>


<details>
  <summary>Kapitel 3: Vom Gen über's Genom zum Ich</summary>

<center><br>
<b onclick="currentDiv(1, 3)">●&nbsp;&nbsp;&nbsp;&nbsp;</b> 
<b onclick="currentDiv(2, 3)">●</b> 
</center>
<figure class="dummieChapter_3" >
<img src="/dummie/images/biodummie.033.png" onclick="plusDivs(+1, 3)">
<figcaption>Kunst am Buch – von Kerstin Zentner.</figcaption>
</figure>
<figure class="dummieChapter_3" >
<img src="/dummie/images/biodummie.034.png" onclick="plusDivs(+1, 3)">
<figcaption><b>Abb. 3.1: </b>Grad der Übereinstimmung der Genome verschiedener Organismen. Auf der Ebene der Proteine ist die Identität noch viel größer. Der Mensch ganz rechts ist der Neanderthaler. Der Maus, Zebrafisch und Fruchtfliege sind beliebte Modellorganisimen für Krankheiten beim Menschen, da sie sich gut züchten und halten lassen. Schon gemerkt?: Die Größenverhältnisse stimmen nicht.</figcaption>
</figure>

<br>
</details>



<script>
var slideIndex = [1,1,1,1];
var slideId = ["dummieChapter_0", "dummieChapter_1", "dummieChapter_2", "dummieChapter_3"];
showDivs(1, 0);
showDivs(1, 1);
showDivs(1, 2);
showDivs(1, 3);

function currentDiv(n, no) {
  showDivs(slideIndex[no] = n, no);
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


