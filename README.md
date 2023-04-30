Download Link: https://assignmentchef.com/product/solved-cs-2400-homework2-ancient-multiplication
<br>
An ancient method for multiplying two integers works by repeated multiplication and division by 2.  Let’s say you have two numbers (X and Y). Multiply X by 2 and divide (integer division) Y by 2.  Repeat the process until Y becomes zero and you can’t divide any further. The result of multiplying X by Y is the total of all the values of X whenever Y was odd.

Here is an example of multiplying 30 by 18:

<table width="0">

 <tbody>

  <tr>

   <td width="54"><strong>X </strong></td>

   <td width="54"><strong>Y </strong></td>

  </tr>

  <tr>

   <td width="54">30</td>

   <td width="54">18</td>

  </tr>

  <tr>

   <td width="54">60</td>

   <td width="54">9</td>

  </tr>

  <tr>

   <td width="54">120</td>

   <td width="54">4</td>

  </tr>

  <tr>

   <td width="54">240</td>

   <td width="54">2</td>

  </tr>

  <tr>

   <td width="54">480</td>

   <td width="54">1</td>

  </tr>

  <tr>

   <td width="54"> </td>

   <td width="54">0</td>

  </tr>

 </tbody>

</table>




Result = 60 + 480 = 540.

Write a C++ program that repeatedly asks the user (y/n question) for two positive integers to multiply and uses the method outlined above to calculate and display the result of multiplication.  Validate the input values to make sure they are both positive. Your program should repeatedly ask the user to reenter each number until they enter a positive integer.