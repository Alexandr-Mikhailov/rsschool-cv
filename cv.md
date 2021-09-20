# Resume

**First name:** Alexander

**Last Name:**  Mikhailov

**Age:** 34

## Contact info
**E-mail:** mikhailov_as@mail.ru

## Summary
Programming is an interesting and exciting job,so I decided to change my profession.

## Skills
**Programming languages**
+ C#
+ JS
+ SQL
+ HTML/CSS
+ ASM for PIC microcontollers

## Code examples
```JS
mathCalculator
document.getElementById('calculateButton').onclick = function () {
    var str = document.getElementById('input').value;
    var isStrExpression = str.match(/^((\d?\.?\d?\s?\+?\-?\*?\/?)+={1})$/g);

    if (isStrExpression == null || isStrExpression.length !=1) {
        alert("cannot parse arithmetic expression")
    }
    else{
        var expressionParse = str.match(/(\d+(\.*\d)*)|(\+|\-|\*|\/)/g);
    var i, result = 0;

    for (i = 0; i < expressionParse.length; i++){
        switch (expressionParse[i]){
            case '+': {
                result += parseFloat(expressionParse[i+1]);
                i++;
                break;
            }
            case '-': {
                result -= parseFloat(expressionParse[i+1]);
                i++;
                break;
            }
            case '*': {
                result *= parseFloat(expressionParse[i+1]);
                i++;
                break;
            }
            case '/': {
                result /= parseFloat(expressionParse[i+1]);
                i++;
                break;
            }
            default : {
                result = parseFloat(expressionParse[i]);
                break;
            }
        }
    }

    alert(result.toFixed(2));
    }
}
```

## Experience

For a last 13 years I worked in testing and development of electronic devices.

## Education
**Main:**
+ Saratov State University, radio engineering and electrodynamics

**Online:**
+ EPAM BASICS .NET/WEB DEVELOPMENT in 2018
+ Codecademy
+ RSschool 2019Q3

## English
I read english technical documetation, watch english youtube channels.
