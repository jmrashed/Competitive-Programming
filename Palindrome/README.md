# Check Whether a Number is Palindrome or Not

The purpose of the code is to determine whether an integer entered by the user is a palindrome number or not.

Here's a breakdown of how the code works:

1. First, the code declares four integer variables: num, rev, rem, and temp. num is the user input number, rev is the reversed number, rem is the remainder, and temp is a temporary variable used to store the value of num for later use.
2. The user is prompted to enter an integer using cin.
temp is set equal to num so that the original value of num can be preserved.
3. The code enters a while loop that will continue to run until temp is equal to 0. Inside the loop:
    a. The remainder of temp divided by 10 is assigned to rem.
    b. rem is added to rev multiplied by 10, which shifts the digits of rev to the left by one place and adds rem to the rightmost position.
    c. temp is divided by 10 so that the rightmost digit is removed, and the loop can continue with the remaining digits.
4. Once the loop is complete, the code uses an if statement to compare num with rev. If they are equal, the code outputs that num is a palindrome number. Otherwise, the code outputs that num is not a palindrome number.
5. The code returns 0 to indicate successful program execution and termination.

In summary, the code takes an integer input from the user, reverses the integer, and then compares the original integer with the reversed integer to determine whether it is a palindrome number or not.