<!doctype html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>送李莹</title>
  <link href="style/main.css" rel="stylesheet" >
  <script src="js/wc-3.0.6.min.js"></script>
</head>
<style>
	
</style>
<body>
	<div class="box" align="center">
		<p>我观察你很久了</p>
		<h1>李莹做我对象好不好?</h1>
		<img src="images/1.jpg">
		<div class="bottom">
			<div class="left" id="hao">好</div>
			<div class="right" id="buhao">不好</div>
		</div>
	</div>
    <audio autoplay="autoplay" loop>  
      <source src="music/douyin.mp3" type="audio/mpeg">
    </audio>
</body>
	<script type="text/javascript" src="js/yiqi.js"></script>
   <script>

let p = document.querySelector("p")
let str = "我从遥远的地方来看你，要说许多的故事给你听。我最喜欢看你胡乱说话的模样。我是那深深的大海，你是那自海的另一边升起的曙光，永远照亮我的人生。见过无数鲸落，看过漫天星辰。唯守一片寂静，最终只念那人。我喜欢你，喜欢到以爱你为圆心，以保护你为半径，就连圆周率都变成了520"

let i = 0

setInterval(function(){
      if(i >= str.length){
         return
      }
      p.innerText += str[i]
    i += 1
    },100)
</script>
</html>

