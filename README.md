# Calculator
calculator description
<html>
<body>
<script>
const operator = prompt('Enter operator ( either +, -, * or / ): ');


const number1 = parseFloat(prompt('Enter first number: '));
const number2 = parseFloat(prompt('Enter second number: '));
const number3 = parseFloat(prompt('Enter third number: '));
const number4 = parseFloat(prompt('Enter fourth number: '));
var result;


if (operator == '/') {
    result = number1 / number2/number3/number4;
}
    
else if (operator == '-') {
    result = number1 - number2 - number3 - number4;
}
    
else if (operator == '*') {
    result = number1 * number2 * number3 * number4;
}
    
else {
    result = number1 + number2 + number3 + number4;
}

// display the result
document.write(`${number1} ${operator} ${number2} ${operator} ${number3} ${operator} ${number4} = ${result}`);
</script>
</body>
</html>
