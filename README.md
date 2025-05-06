<!DOCTYPE html>
<html>
<head>
    <title>Simple Calculator</title>
</head>
<body>
    <h2>Simple Addition Calculator</h2>
    <p>Enter two numbers:</p>

    <input type="number" id="num1" placeholder="third number">
    <input type="number" id="num2" placeholder="Second number">
    <button onclick="calculate()">Add</button>

    <p>Result: <span id="result">0</span></p>

    <script>
        function calculate() {
            var n1 = parseFloat(document.getElementById("num1").value);
            var n2 = parseFloat(document.getElementById("num2").value);
            var sum = n1 + n2;
            document.getElementB
