<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="style.css">
	<title>Make a Clock</title>
</head>
<body>
	<style type="text/css">
	    #Clock {margin-left: 350px;
	    	    margin-top: 250px;
	    	    color: #49fb35;
	            font-size: 150px;
	            font-family: "impact",  Charcoal, sans-serif;}
	    body {background-color: #000000;}
	</style>
	<div>
        <p id="Clock"></p>
<script>
var myVar = setInterval(myTimer, 1000);

function myTimer() {
    var d = new Date();
    document.getElementById("Clock").innerHTML = d.toLocaleTimeString();
}
</script>
    </div>
</body>
</html>

