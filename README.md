<html>
<head>
	<title>자발적아싸</title>

<script> 
function view_layer(name){ 
  document.getElementById(name).style.display='block'; 
} 

function close_layer(name){ 
  document.getElementById(name).style.display='none'; 
} 
</script> 

<style type="text/css">
	html, body, div, a{margin: 0;padding: 0; border: 0; cursor: url(./img/cursor.cur); }

	.main{ width:1920px; height: 1273px;}
	.main img:last-child{display:none} 
	.main:hover img:first-child{display:none} 
	.main:hover img:last-child{display:inline-block}

	#layer1{position:absolute; left:86px; top:89px; width:600px; z-index:0; display:none;}
	#layer2{position:absolute; left:190px; top:380px; width:800px; z-index:0;display:none;}
	#layer3{position:absolute; left:840px; top:180px; width:400px; z-index:0;display:none;}
	#layer4{position:absolute; left:1050px; top:30px; width:600px; z-index:0;display:none;}
	#layer5{position:absolute; left:980px; top:560px; width:460px; z-index:0;display:none;}
	#layer6{position:absolute; left:550px; top:50px; width:400px; z-index:0;display:none;}
	#layer7{position:absolute; left:550px; top:50px; width:400px; z-index:0;display:none;}



</style>

</head>

<body> 

<!-- main 마우스오버 관련 -->
<div class="main">
<img src="./img/main.png">


	<a href="#" onclick="view_layer('layer1');">
		<img src="./img/1920_h.png" >
	</a> 

	

	<a href="#" onclick="view_layer('layer2');">
		<div id="layer1"> 
			<img src="./img2/1.png" onmouseover="this.src='./img2/1.gif';" onmouseout="this.src='./img2/1-2.png';"title="아싸_2명" style="width: 100%; height: auto;"><!-- 창1 이미지 -->

		<!--	<a href="#" onclick="close_layer('layer1');">X</a> -->
		</div> 
	</a> 


	<a href="#" onclick="view_layer('layer3');">
		<div id="layer2" > 
			<img src="./img2/2.png" onmouseover="this.src='./img2/2.gif';" onmouseout="this.src='./img2/2-2.png';"title="대외활동형 아싸_12명" style="width: 100%; height: auto;"><!-- 창2 이미지 -->
		<!--	<a href="#" onclick="close_layer('layer2');">X</a> -->
		</div> 
	</a> 


	<a href="#" onclick="view_layer('layer4');">
		<div id="layer3" > 
			<img src="./img2/3.png" onmouseover="this.src='./img2/3.gif';" onmouseout="this.src='./img2/3-2.png';"title="대외활동형 아싸_3명" style="width: 100%; height: auto;"><!-- 창3 이미지 -->
		<!--	<a href="#" onclick="close_layer('layer3');">X</a> -->
		</div> 
	</a> 
	

	<a href="#" onclick="view_layer('layer5');">
		<div id="layer4" > 
			<img src="./img2/4.png" onmouseover="this.src='./img2/4.gif';" onmouseout="this.src='./img2/4-2.png';"title="인간관계형 아싸_3명" style="width: 100%; height: auto;"><!-- 창4 이미지 --> 
		<!--	<a href="#" onclick="close_layer('layer4');">X</a> -->
		</div> 
	</a> 


	<a href="#" onclick="view_layer('layer6');">
		<div id="layer5" > 
			<img src="./img2/5.png" onmouseover="this.src='./img2/5.gif';" onmouseout="this.src='./img2/5-2.png';"title="대외활동형 아싸_6명" style="width: 100%; height: auto;"><!-- 창3 이미지 -->
		<!--	<a href="#" onclick="close_layer('layer3');">X</a> -->
		</div> 
	</a> 

	<a href="#" onclick="view_layer('layer7');">
		<div id="layer6" > 
			 <img src="./img/A_sticker_h.png" title="1주일간 만난 사람은?" style="width: 100%; height: auto;"><!-- 창3 이미지 -->
		<!--	<a href="#" onclick="close_layer('layer3');">X</a> -->
		</div> 
	</a> 

	<a href="#" onclick="close_layer('layer1');close_layer('layer2');close_layer('layer3');close_layer('layer4');close_layer('layer5'); close_layer('layer6'); close_layer('layer7');">
		<div id="layer7" > 
			<img src="./img/A_sticker_back.png" title="처음으로 돌아가려면 누르세요" style="width: 100%; height: auto;"><!-- 창3 이미지 -->
		<!--	<a href="#" onclick="close_layer('layer3');">X</a> -->
		</div> 
	</a> 
	


</div>


</body> 
</html>
