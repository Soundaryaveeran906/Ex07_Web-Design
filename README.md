# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```
## OUTPUT

![calcul sc-1](https://github.com/Soundaryaveeran906/Ex07_Web-Design/assets/127818071/540de868-d0b6-480b-a2cc-daa9bb5e8474)
![calcul sc-2](https://github.com/Soundaryaveeran906/Ex07_Web-Design/assets/127818071/629ddb4f-11dd-4129-a238-16c4ab697e5e)
![calcul sc-3](https://github.com/Soundaryaveeran906/Ex07_Web-Design/assets/127818071/0b8839b0-7444-4d0f-860f-8b7d98b5aa8a)
![cacul sc -4](https://github.com/Soundaryaveeran906/Ex07_Web-Design/assets/127818071/41a6df1b-48b3-4a81-8a81-8f730c6997d6)
![calcul sc-5](https://github.com/Soundaryaveeran906/Ex07_Web-Design/assets/127818071/d6ce4244-a90b-4524-97be-8d465807db6b)

## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
