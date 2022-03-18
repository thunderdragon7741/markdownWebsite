# This is a markdown website example
## This is the second largest heading
###### This is the smallest heading


[This links to another page](anotherPage.md)

[This links to an external website](www.uwa.edu.au)

This is an image hosted on this repo:

![This is an image hosted on this repo](dragon.jpg)

This is an image hosted on wikipedia:

![This is an image hosted on wikipedia](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d8/Friedrich-Johann-Justin-Bertuch_Mythical-Creature-Dragon_1806.jpg/1024px-Friedrich-Johann-Justin-Bertuch_Mythical-Creature-Dragon_1806.jpg)

This is a **list**:
* *First* item;
* *Second* item;
* *Last* item.

The following is an example **code block**. This is my *FizzBuzz* solution from earlier in the semester.
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
