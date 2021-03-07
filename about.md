---
layout: default
title: Vita
---


<!-- Hacky JS: https://stackoverflow.com/questions/18032220/css-change-image-src-on-imghover  -->

<script>
function hover(element) {
  element.setAttribute('src', '{{site.baseurl}}/{{site.hover-picture}}');
}

function unhover(element) {
  element.setAttribute('src', '{{site.baseurl}}/{{site.profile-picture}}');
}
</script>

<img class="profile-picture" src="{{site.baseurl}}/{{site.profile-picture}}" onmouseover="hover(this);" onmouseout="unhover(this);" float = "left" />

I am a PhD student and <a href="https://www.conflex.org">Marie Sklodowska-Curie Fellow</a> at the <a href="http://www.uam.es/UAM/Home.htm?language=es">Universidad Autónoma de Madrid</a> since July 2018, under the supervision of <a href="http://paginaspersonales.deusto.es/enrique.zuazua/">Enrique Zuazua</a>. 
I am scheduled to defend my PhD thesis in April or May of 2021. 
I am also affiliated with the <a href="https://cmc.deusto.eus">Chair of Computational Mathematics</a> at Fundación Deusto in Bilbao.

My current research is centered on the interplay of deep learning and control theory. I am also interested in other topics of applied mathematics, such as the  analysis, control and applications of partial differential equations with moving interfaces (free boundaries).

I obtained a BSc (2016, cum laude) in Applied Mathematics and Computer Science, as well as an MSc (2018, summa cum laude) in Applied Mathematics, from the <a href="https://www.u-bordeaux.fr">University of Bordeaux</a>.

My <b>curriculum vitae</b> can be found <a href="{{site.baseurl}}/{{site.cv}}">here</a>.

<section>
<h2>Contact</h2>
<b>Address:</b> Departamento de Matemáticas, Universidad Autónoma de Madrid, 28049 Madrid, Spain

<b>Email:</b> 
<span class="color-gray">myname.mysurname@uam.es</span> or <span class="color-gray">mysurnamemyname@gmail.com</span> 
</section>







