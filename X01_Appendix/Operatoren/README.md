# Operators
A list of the most important operators in TypeScript / JavaScript

## Assignment operator

<table>
<tr align="left"><td width="50">Sign</td><td width="200">Name</td><td width="120">Example</td><td>note</td></tr>  
<tr><td><code>=</code></td><td>Assignment</td><td><code>x = 7;</code></td><td>The value on the right-hand side is assigned to the variable on the left-hand side</td></tr>  
</table>

## Arithmetic operators

<table>
<tr align="left"><td width="50">Sign</td><td width="200">Name</td><td width="120">Example</td><td>note</td></tr>  
<tr><td><code>+</code></td><td>addition</td><td><code>x + 5;</code></td><td>Returns the result of adding the left and right values ​​without storing it.</td></tr>  
<tr><td><code>-</code></td><td>subtraction</td><td><code>17 - x;</code></td><td>Returns the result of subtracting the left and right values ​​without storing it.</td></tr>
<tr><td><code>*</code></td><td>multiplication</td><td><code>5 * x;</code></td><td>Returns the result of multiplying the left and right values ​​without storing it.</td></tr>
<tr><td><code>/</code></td><td>division</td><td><code>x / 2;</code></td><td>Returns the result of dividing the left value by the right value, without storing it.</td></tr>
<tr><td><code>%</code></td><td>Modulo</td><td><code>x % 10;</code></td><td>Returns the remainder of the integer division of the left value by the right value, without storage.</td></tr>
</table>  

## Compound operators

<table>
<tr align="left"><td width="50">Sign</td><td width="200">Name</td><td width="120">Example</td><td>note</td></tr>  
<tr><td><code>+=</code></td><td>Addition assignment</td><td><code>x += 19;</code></td><td>The value of the variable is increased by the value shown on the right. Equivalent to <code>x = x + 19;</code></td></tr>
<tr><td><code>-=</code></td><td>Subtraction assignment</td><td><code>x -= 3;</code></td><td>The value of the variable is reduced by the value shown on the right. Equivalent to <code>x = x - 3;</code></td></tr>
<tr><td><code>*=</code></td><td>Multiplication assignment</td><td><code>x *= 100;</code></td><td>The value of the variable is increased by the factor shown on the right. Equivalent to <code>x = x *100;</code></td></tr>
<tr><td><code>/=</code></td><td>Division assignment</td><td><code>x /= 4;</code></td><td>The value of the variable is reduced by the right-hand divisor. Equivalent to <code>x = x / 4;</code></td></tr>
<tr><td><code>++</code></td><td>Increment</td><td><code>x++;</code></td><td>The value of the variable is incremented by 1. Equivalent to <code>x += 1;</code></td></tr>
<tr><td><code>--</code></td><td>Decrement</td><td><code>x--;</code></td><td>The value of the variable is decreased by 1. Equivalent to <code>x -= 1;</code></td></tr>
</table>

## Comparison operators  

<table>
<tr align="left"><td width="50">Sign</td><td width="200">Name</td><td width="120">Example</td><td>note</td></tr>  
<tr><td><code>==</code></td><td>Equality of value</td><td><code>x == "AB"</code></td><td>Returns true if the values ​​on the left and right sides are equal. Be careful with floats!!</td></tr>
<tr><td><code>===</code></td><td>Equality of value and type</td><td><code>x === "42"</code></td><td>Returns the value true if value equality holds and both expressions are also of the same type.</td></tr>
<tr><td><code>!=</code></td><td>inequality</td><td><code>x != "AB"</code></td><td>Returns the value true if the values ​​on the left and right sides are different.</td></tr>
<tr><td><code>></code></td><td>greater</td><td><code>x > 2.32</code></td><td>Returns the value true if the left value is greater than the right value.</td></tr>
<tr><td><code><</code></td><td>smaller</td><td><code>x < 2.32</code></td><td>Returns the value true if the left value is less than the right value.</td></tr>
<tr><td><code>>=</code></td><td>Greater than or equal to</td><td><code>x >= 2.32</code></td><td>Returns true if the left value is greater than or exactly equal to the right value.</td></tr>
<tr><td><code><=</code></td><td>Less than or equal to</td><td><code>x <= 2.32</code></td><td>Returns true if the left value is less than or exactly equal to the right value.</td></tr>
</table>

## Logical operators 

<table>
<tr align="left"><td width="50">Sign</td><td width="200">Name</td><td width="120">Example</td><td>note</td></tr>  
<tr><td><code>&&</code></td><td>And</td><td><code>x>2 && x<9</code></td><td>Returns true if both the left and right expressions evaluate to true. In this case, if x is between 2 and 9.</td></tr>  
<tr><td><code>||</code></td><td>Or</td><td><code>x<2 || x>9</code></td><td>Returns true if at least one of the two expressions is true. In this case, if x lies outside the range of 2 to 9.</td></tr>  
<tr><td><code>!</code></td><td>Not</td><td><code>!(x > 10)</code></td><td>Negates the expression; thus, it returns true if the following expression is false. In this case, if x <= 10.</td></tr> 
</table>

## Bitwise operators

This directly manipulates bit patterns. See [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)
