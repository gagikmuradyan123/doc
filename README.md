# doc

<! DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Best klick</title>
<link rel="stylesheet" href="style14725.css">
</head>
<body>
<input type="text" id="myText" placeholder="Search">

<button onclick="myFunction()">test</button>
<p id="my"></p>

<script>
function myFunction()
{
var x =document.getElementById("myText").value;


if(x == "privet")
{
document.getElementById("my").innerHTML = "Hello My Friend";
}

else 
{
document.getElementById("my").innerHTML = "Ты написал неправильно";
}

}
</script>

	   


</body>
</html>












