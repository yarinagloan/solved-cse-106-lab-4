Download Link: https://assignmentchef.com/product/solved-cse-106-lab-4
<br>



Write a calculator web app in JavaScript, HTML, and CSS with the following features:

<ol>

 <li>Has an output field that represents the numbers input or the answer</li>

 <li>Has number buttons representing all numbers (0-9)</li>

 <li>Has a decimal (.) button to make decimals that can only be used once (e.g. 3.5 – OK, 4.5.6 – not OK)</li>

 <li>Has arithmetic action buttons for addition, subtraction, multiplication, and division</li>

 <li>Has an equals button that outputs the result from the calculation of the first and second numbers input and the arithmetic action clicked</li>

 <li>Has a clear button that clears the inputs, arithmetic actions, and output field</li>

</ol>

Here are some additional requirements:

<ol>

 <li>The numbers clicked from the number buttons should be appended to the numbers in the output field until an arithmetic action button is pressed. Once an arithmetic action is pressed, a new number can be input.</li>

 <li>The arithmetic action button should be highlighted after it is clicked to show what operation is occurring. The button stays highlighted until another number is input, another arithmetic action button is pressed, or the equals or clear buttons are pressed.</li>

 <li>When the equals button is pressed a second time, it performs the last action with the answer being the first number input (e.g. 2+4 click equals -&gt; 6, click equals again equates to 6+4 -&gt; 10, click equals again equates to 10+4 -&gt; 14)</li>

 <li>When an arithmetic action button is clicked again, after a number is input, an arithmetic action button is clicked and a second number is input, it effectively acts as an equals button and makes the arithmetic action button clicked now active and highlighted</li>

 <li>Have different colors for number buttons, arithmetic actions and equals buttons, and clear buttons</li>

 <li>All buttons and output should be arranged in a grid with a background and border Here is an example of how it could look:</li>

</ol>




Note: If you want a calculator to try out that acts similarly to this one, you may try out:

<a href="https://www.online-calculator.com/">https://www.online</a><a href="https://www.online-calculator.com/">–</a><a href="https://www.online-calculator.com/">calculator.com</a>