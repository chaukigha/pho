<style>
  img{height:600px;
</style>
<body onload="document.getElementById('b1').click()">
<a id="b1" onclick="aa(1)"/>
<a id="b2" onclick="aa(-1)"/>
<script>
var a=1;b(a);
function aa(c){b(a+=c);}
function b(c) {
var d;
var e = document.getElementsByClassName("a");
if(c>e.length){a=1;}
if(c<1){a=e.length;}
for(d=0;d<e.length;d++){
e[d].style.display="none";
e[a-1].style.display="block";
}}
setInterval(function(){
document.getElementById("b2").click();},1000);
</script>
</body>
<img class="a" src="https://static.pexels.com/photos/23049/pexels-photo.jpg">
<img class="a" src="https://image.freepik.com/free-photo/mountain-with-clouds_1161-18.jpg">
<img class="a" src="https://previews.123rf.com/images/janpietruszk/janpietruszk1011/janpietruszk101100302/8314883-Cima-della-montagna-sotto-il-cielo-azzurro-con-nuvole-Archivio-Fotografico.jpg">
<img class="a" src="http://www.travelettes.net/wp-content/uploads/2012/02/trav_anzere-clouds-between-mountains.jpg">
<img class="a" src="http://www.timashov.com/wp-content/uploads/2011/03/DSC-0104.jpg">
<img class="a" src="http://1.bp.blogspot.com/-p81m8gUyA40/TlMlQIK7cMI/AAAAAAAADk4/FxCXNk758cE/s1600/5.jpg">
