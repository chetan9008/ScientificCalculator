<!DOCTYPE html>
<html>
<!-- We remember about id = input for input bar and 
class = btn for button tags-->

<head>
    <meta name="viewport" content="width=device-width , initial-scale=1.0" >
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Work+Sans&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="Scientific_Calculator.css">
    <title>
        Chetan's Scientific Calculator
    </title>
</head>

<body>
    <!-- <h1>Scientific Calculator</h1> -->
    <div class="whole_calculator" id="somestyle">
        <div id="input_bar">
            <input id="input" type="text" placeholder="0">
        </div>
        <br>
        <table id="allButtons">
            <tbody>
                <tr>
                    <td><button class="btn" id="log10">log<sub>10</sub></button></td>
                    <td><button class="btn" id="power">^</button></td>
                    <td><button class="btn">x!</button></td>
                    <td><button class="btn">%</button></td>
                    <td><button class="btn">&#40</button></td>
                    <td><button class="btn">&#41</button></td>
                    <td><button class="btn" id="back">Back</button></td>
                </tr>

                <tr>
                    <td><button class="btn" id="x">x<sup>-1</sub></button></td>
                    <td><button class="btn">sin</button></td>
                    <td><button class="btn" id="ex">e<sup>x</sup></button></td>
                    <td><button class="btn" id="no" >7</button></td>
                    <td><button class="btn" id="no" >8</button></td>
                    <td><button class="btn"id="no" >9</button></td>
                    <td><button class="btn" id="no" >/</button></td>
                </tr>

                <tr>
                    <td><button class="btn" id="phi">&pi;</button></td>
                    <td><button class="btn">cos</button></td>
                    <td><button class="btn">log</button></td>
                    <td><button class="btn"id="no" >4</button></td>
                    <td><button class="btn"id="no" >5</button></td>
                    <td><button class="btn"id="no" >6</button></td>
                    <td><button class="btn" id="no" >*</button></td>
                </tr>

                <tr>
                    <td><button class="btn">e</button></td>
                    <td><button class="btn">tan</button></td>
                    <td><button class="btn" id="sqr">&Sqrt;</button></td>
                    <td><button class="btn" id="no" >1</button></td>
                    <td><button class="btn" id="no" >2</button></td>
                    <td><button class="btn" id="no" >3</button></td>
                    <td><button class="btn" id="no" >-</button></td>
                </tr>

                <tr>
                    <td><button class="btn" id="ac">AC</button></td>
                    <td><button class="btn" id="x3">x<sup>3</sup></button></td>
                    <td><button class="btn" id="x2">x<sup>2</sup></button></td>
                    <td><button class="btn" id="no" >0</button></td>
                    <td><button class="btn" id="no" >.</button></td>
                    <td><button class="btn" id="equal">=</button></td>
                    <td><button class="btn" id="no" >+</button></td>
                </tr>

            </tbody>
        </table>
    </div>
    <script type="text/javascript" src="Scientific_Calculator.js"></script>
</body>

</html>
