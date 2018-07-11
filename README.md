<html>
<head>
<meta charset="utf-8">
<title>Untitled Document</title>
</head>

<body onLoad="">
	
		<script>
	
	function mens(){
		
		document.getElementById("result").value = "100";
	}
		
		function womens(){
		
		document.getElementById("result").value = "100";
	}
	
		function kids(){
		
		document.getElementById("result").value = "100";
	}
	
	</script>
	
	<input id="mens" onClick="mens()" type="checkbox">Men's Newsletter<br><br>
	<input id="womens" onClick="womens()" type="checkbox">Women's Newsletter<br><br>
	<input id="kids" onClick="kids()" type="checkbox">Kid's Newsletter<br><br>
	Status ID <input id="result" type="text" value="100"><br><br>
	
	
</body>
</html>
