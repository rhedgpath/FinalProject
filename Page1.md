[README.md](https://github.com/rhedgpath/FinalProject/blob/master/README.md)
# Header1
## Header2

<pre><code>
	<html>
	<html>
	<head>
	<meta charset="UTF-8">
	<title>Fizz Buzz</title>    
	
	<script>
	
	function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {    
			displayHTML+="< p > " + i + "< /p >";     
	   }   
	display.innerHTML = displayHTML;
	   }

		</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>
</code></pre>
