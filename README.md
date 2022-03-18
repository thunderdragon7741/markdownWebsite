# This is a markdown website example
## This is the second largest heading
###### This is the smallest heading


[This links to another page](anotherPage.md)

The following is an example **code block**. This is my __FizzBuzz__ solution from earlier in the semester.
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i <= 100; i++) 
	{
		
		if (i % 3 == 0 && i % 5 == 0)
		{
			displayHTML += "<p>FizzBuzz</p>";
		}
		else if (i % 3 == 0)
		{
			displayHTML += "<p>Fizz</p>";
		}
		else if (i % 5 == 0)
		{
			displayHTML += "<p>Buzz</p>";
		}
		else
		{
			displayHTML += "<p>" + i + "</p>";
		}
	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```
