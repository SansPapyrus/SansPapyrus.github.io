``` html
<!DOCTYPE html>
<html style="width: 100%; height: 100%;">
<head>
	<meta charset="UTF8">
	<!--如果要修改刷新时间，修改下一行的content（秒数）-->
	<meta http-equiv="refresh" content="5">
</head>
<body style="width: 100%; height: 100%;">
	<!--
		如果要修改一个页面内出现的图片个数，将以下
		从<iframe>到</iframe>代码的重复次数改一下（默认1次）
	-->
	<div style="width: 100%; height: 100%;">

	<iframe	src			= "https://api.yimian.xyz/img?type=wallpaper"
		name			= 图片
		width			= 100%
		height			= 100%
		frameborder		= 0
		scrolling		= no
		allowtransparency	= true
	>
	</iframe>
	
</body>
</html>
```
