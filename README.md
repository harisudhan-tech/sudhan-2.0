<html>
<head>
    <title>Baggage Weight Checker</title>
    <script>
        function checkBaggageWeight() {
            const weight = parseFloat(document.getElementById("baggageInput").value);
            
            if (isNaN(weight)) {
                alert("Please enter a valid number.");
                return;
            }

            if (weight > 15) {
                alert("Baggage exceeds the 15kg allowance.");
            } else {
                alert("Baggage is within the allowed limit.");
            }
        }
    </script>
</head>
<body>
    <h2>Baggage Weight Checker</h2>
    <label for="baggageInput">Enter baggage weight (kg):</label>
    <input type="number" id="baggageInput" placeholder="e.g. 12.5">
    <button onclick="checkBaggageWeight()">Check Weight</button>
</body>
</html>

