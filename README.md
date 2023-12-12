<!DOCTYPE html>
<html>
<head>
    <title>Meters to Yards Converter</title>
</head>
<body>
    <h2>Welcome to the Meters to Yards Converter!</h2>
    <form>
        <label for="meters">Enter length in meters:</label>
        <input type="text" id="meters" name="meters">
        <input type="button" value="Convert" onclick="convertLength()">
    </form>
    <p id="result"></p>

    <script>
        function convertLength() {
            var meters = document.getElementById("meters").value;
            var yards = meters * 1.09361;
            document.getElementById("result").innerHTML = meters + " meters is equal to " + yards + " yards.";
        }
    </script>
</body>
</html>

