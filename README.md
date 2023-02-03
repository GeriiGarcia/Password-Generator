# Password-Generator
The idea is make a password generator in Web.

## How I make the random password?

First of all I save the desired length. 
Then I generate as many random numbers as desired length.

I verify which buttons are pressed and I generate the number of that combination.
For each button there is a number power of 2 associated. 
When I sum the numbers associated to the buttons pressed I make a unic number 
for unic combination of buttons pressed. 

Then, according to the unic combination, I try random character in a vector of character tried randomly for each number of the random number generated at start.
