# Integer-Analysis
Defines 7 functions related to analyzing integers and applies them to integers between two user-supplied values; Python

## The Functions Module
The functions defined in integeranalysis are as follows:

**is_divisible_by**
This function checks if the first integer is divisible by the second integer using a simple if-then statement whose conditions utilize the modulo operator. 

**get_sum_of_divisors**
This function using a for loop to check every integer in the range of 1 to the integer to check if that integer is a factor of the argument. If it is, then it gets added to the sum, which is kept track of using an accumulator variable. 

**get_greatest_divisor**
This function again uses a for loop to check if every integer in the range of 1 to the integer is a divisor of the argument in ascending order, replacing each greater divisor it finds to the variable greatest. It returns the greatest integer.

**is_prime**
This funciton assumes the integer is prime, then uses a for loop to check for any factors. If it finds a factor, the variable prime becomes False. It returns the contents of the prime variable.

**is_perfect**
This function uses a for loop to evaluate for factors, sum them, and then compares the sum to the integer to determine if the number is perfect.

**is_abundant***
This function also uses a for loop to evaluate for factors, sum them, and then compares the sum to the integer to determine if the number is abundant.

**is_binary**
This function applies the binary algorithm in a while loop to an integer to convert it to its binary string.

## The Solution
The final code asks the user to input two integers, validating that the second integer is greater than the first, and then evaluates each integer in that range with the functions defined in the module. The analysis is printed to the user in a formatted table.
