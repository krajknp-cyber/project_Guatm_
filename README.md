# project_Guatm_
 <!DOCTYPE html>
<html lang="end">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Proposal at Taj Mahal</title>

<style>
*{
margin:0;
padding:0;
box-sizing: border-box;
font-family: Arial, Helvetica, sans-serif;
}

body{
overflow: hidden;
height:100vh;
display: flex;
justify-content: center;
align-items: center;
background: linear-gradient(to top,#8fd3ff,#dff5ff);
}

/* Taj Mahal */
.taj{
position: absolute;
bottom:90px;
width:500px;
height:260px;
}

.dome{
position: absolute;
left:150px;
top:10px;
width:200px;
height:140px;
background: white;
border-radius:100px 0 0;
}

.base{
position: absolute;
bottom:0;
width:500px;
height:120px;
background: white;
}

.tower{
position:absolute;
bottom:0;
width:35px;
height:210px;
background: white;
}

.t1{left:0;}
.t2{left:465px;}

.spike{
position: absolute;
top:-20px;
left:13px;
width:8px;
height:20px;
background: gold;
}

/* Crowd */

.crowd{
position: absolute;
bottom:0;
width:100%;
height:130px;
display: flex;
justify-content: space-evenly;
align-items: flex-end;
}

.person{
width:22px;
height:70px;
background:#222;
border-radius:20px;
position: relative;
animation: move 2s infinite alternate;
}

.person: before{
content:'';
position: absolute;
width:26px;
height:26px;
background:#222;
border-radius:50%;
top:-18px;
left:-2px;
}

@keyframes move{
from{transform: translate(0);}
to{transform: translate(-6px);}
}

/* Characters */

.scene{
position: absolute;
bottom:120px;
display: flex;
align-items: flex-end;
gap:100px;
}

.char{
text-align: center;
color:#000;
font-weight: bold;
}

.head{
width:45px;
height:45px;
border-radius:50%;
background:#ff dab;
margin: auto;
}

.body{
width:50px;
height:80px;
margin:auto;
background:#3b82f6;
border-radius:10px;
}

.girl .body{
background:#ff4fa5;
}

.kneel{
transform: rotate(20deg);
}

.ring{
font-size:35px;
animation: ring 1s infinite;
}

@keyframes ring{
50%{
transform: scale(1.3);
}
}

/* Heart */

.heart{
position: absolute;
top:70px;
font-size:180px;
color: red;
animation: beat .8s infinite;
}

@keyframes beat{
50%{
transform: scale(1.2);
}
}

/* Text */

#text{
position: absolute;
top:20px;
font-size:30px;
font-weight: bold;
color:#b30000;
text-align: center;
padding:10px;
}

/* Broken Heart */

#broken{
position: absolute;
font-size:170px;
display: none;
top:80px;
animation: fall 2s forwards;
}

@keyframes fall{
0%{
opacity:1;
transform: translate(0) rotate(0deg);
}
100%{
opacity:0;
transform: translate(260px) rotate(180deg);
}
}

.reject{
position: absolute;
bottom:280px;
font-size:45px;
display: none;
font-weight: bold;
color: red;
animation: pop .8s infinite;
}

@keyframes pop{
50%{
transform: scale(1.15);
}
}

</style>

</head>

<body>

<div id="text">
❤️ Gautam Loves Riya Rani ❤️
</div>

<div class="heart" id="heart">❤️</div>

<div id="broken">💔</div>

<div class="reject" id="reject">
NO
</div>

<div class="taj">

<div class="tower t1">
<div class="spike"></div>
</div>

<div class="tower t2">
<div class="spike"></div>
</div>

<div class="dome"></div>
<div class="base"></div>

</div>

<div class="scene">

<div class="char">
<div class="head"></div>
<div class="body kneel"></div>
<div class="ring">💍</div>
<div>Gautam</div>
</div>

<div class="char girl">
<div class="head"></div>
<div class="body"></div>
<div>Riya Rani</div>
</div>

</div>

<div class="crowd">
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
<div class="person"></div>
</div>

<script>

set Timeout(function(){

document. telemetry Id("text").inner HTML=
"💔 Riya Rani Rejected Gautam's Proposal";

document. telemetry Id("heart").style. Display="none";

document. telemetry Id("broken").style. Display="block";

document. telemetry Id("reject").style. Display="block";

},5000);

</script>

</body>
</html>

