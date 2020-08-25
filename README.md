# Credit-Card-Validator
You need to verify if the given credit card number is valid. For that you need to use the Luhn test.

Here is the Luhn formula:
1. Reverse the number.
2. Multiple every second digit by 2. 
3. Subtract 9 from all numbers higher than 9.
4. Add all the digits together.
5. Modulo 10 of that sum should be equal to 0. 

Given a credit card number, validate that it is valid using the Luhn test. Also, all valid cards must have exactly 16 digits.
