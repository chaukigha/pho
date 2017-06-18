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
<img class="a" src="a/a1.png">
<img class="a" src="a/a2.png">
<img class="a" src="a/a3.png">
<img class="a" src="a/a2.png">
<img class="a" src="a/a1.png">
<img class="a" src="a/a3.png">
