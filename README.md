# simplecalculator
//a project for bharat intern... the topic is simple calculator
this the colde which i have done for the buttons...
html
<!DOCTYPE html>
<html>
<head>
<title>Simple Calculator
</title>
<style>
body {
font-family: Arial

text-align; centre:
sans-serif;
}
input[type="text"],
input[type="button"]
{ margin: 5px;
font-size: 18px; padding: 5px 10px;
}
</style>
</head>
<body>
<h1>Simple Calculator</h1>
<input type="text" id="result" readonly>
<br>
<input type="button" value="1" onclick="appendToResult('1')">
<input type="button" value="2" onclick="appendToResult('2')">
<input type="button" value="3" onclick="appendToResult('3')">
<input type="button" value="+" onclick="appendToResult('+')">
<br>
<input type="button" value="4" onclick="appendToResult('4')">
<input type="button" value="5" onclick="appendToResult('5')">
<input type="button" value="6" onclick="appendToResult('6')">
<input type="button" value="-" onclick="appendToResult('-')">
<br>
<input type="button" value="7" onclick="appendToResult('7')">
<input type="button" value="8" onclick="appendToResult('8')">
<input type="button" value="9" onclick="appendToResult('9')">
<input type="button" value="*" onclick="appendToResult('*')">
<br>
<input type="button" value="0" onclick="appendToResult('0')">
<input type="button" value="=" onclick="calculate()">

<input type="button" value="/" onclick="appendToResult('/')">

<br>
<input type="button" value="C" onclick="clearResult()">
</body>
</html>
