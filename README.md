# gboyega
<html lang="en">
    <head>
        <title>functional calculator</title>
        <link rel="stylesheet" href="style.css" class="rel">
    </head>
    <body>
        <div id="calculator">
            <input id="display" readonly>
            <div id="keys">
                <button onclick="appendtoDisplay('+')" class="operator-btn">+</button>
                <button onclick="appendtoDisplay('7')">7</button>
                <button onclick="appendtoDisplay('8')">8</button>
                <button onclick="appendtoDisplay('9')">9</button>
                <button onclick="appendtoDisplay('-')" class="operator-btn">-</button>
                <button onclick="appendtoDisplay('4')">4</button>
                <button onclick="appendtoDisplay('5')">5</button>
                <button onclick="appendtoDisplay('6')">6</button>
                <button onclick="appendtoDisplay('*')" class="operator-btn">*</button>
                <button onclick="appendtoDisplay('1')">1</button>
                <button onclick="appendtoDisplay('2')">2</button>
                <button onclick="appendtoDisplay('3')">3</button>
                <button onclick="appendtoDisplay('/')" class="operator-btn">/</button>
                <button onclick="appendtoDisplay('0')">0</button>
                <button onclick="appendtoDisplay('.')">.</button>
                <button onclick="calculate()">=</button>
                <button onClick="clearDisplay()" class="operator-btn" >C</button>
                <button onclick="appendtoDisplay('**')" class="operator-btn">^</button>
                <button onclick="appendtoDisplay('%')" class="operator-btn">%</button>
                
            </div>
        </div>

        <script src="index.js"></script>
    </body>
</html>
