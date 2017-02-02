<!DOCTYPE html>
<html>
<head> 
	 <script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
	 <script src="script.js"></script>
</head>
<body>


<style type="text/css">
 @keyframes dildo{

0% {
    transform: rotate(0deg);
}


20% {

     transform: rotate(-20deg);

}

40% {

    position: relative;
    bottom:10px; 
    left:10px;
}


80%{

position: relative;
    bottom:0px; 
    left:0px;

}




 }
	
 body { 
     background: url(images/bg.jpg) no-repeat center center fixed; 
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     font-family: sans-serif;
     padding: auto;
      cursor:crosshair;
   }
 
#overlay {
   width:30%;

   height:400px;
    
    background:red;
 
     float:center;
    position: relative;
    
    margin:auto;
    padding-bottom:10px; 
}

#like {
 

animation:dildo 4s ease-in-out 0s infinite;


}


#like2 {
	opacity: 0;

}

#ho {


width:200px;
height:100px;




}


#like3 {
opacity: 0;
transform: rotate(180deg);
}

#like3:hover {
width: 150px;
height: 70px;
}
#like2:hover {
width: 150px;
height: 70px;
}




</style>




<div id="overlay">

 
<br><br><br><br><br><br><br><br>
<center><div id="ho">
<img src="images/like.png" width="50" height="50" id="like"><br><br>
<img src="images/like2.png" width="100" height="50" id="like2" onclick="call()">
<img src="images/like2.png" width="100" height="50" id="like3" onclick="call2()">
<div>LIKE:</div>
<div id="raodenoba"></div>
<div>DISLIKE:</div>
<div id="raodenoba2"></div>
</div>

</div>

 
<script type="text/javascript">

var  v = 0;


function  call(){
    // body...
 
   v += 1;
   var pasuxi = document.getElementById("raodenoba");

   pasuxi.innerHTML = v;
}


var k = 0;

function  call2(){
    // body...
 
   k += 1;
   var pasuxi2 = document.getElementById("raodenoba2");

   pasuxi2.innerHTML = k;
}

</script>


<script type="text/javascript">
    

$(document).ready(function(){

$("#ho").hover(function(){
    $("#like3").animate({
      

      "opacity" : 1.5
     


    },500);



},function(){
    $("#like3").animate({

  'opacity':0

    },500);






});



});


</script>












</body>
</html>
