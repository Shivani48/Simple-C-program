# Simple-C-program

#### int findNextMultiple(int number1, int number2)
To round off an integer i to the next largest even multiple of another integer j, the following formula can be used:
* int next_multiple = i + j - i % j
    * For example, to round off 256 days to the next largest number of days evenly divisible by a week, values of i = 256 and j = 7 can be substituted into the preceding formula as follows:
    int next_multiple = 256 + 7 - 256 % 7

* Complete the function called `findNextMultiple` to find the next largest even multiple for the following values of i and j:
    *   |i|j|
        |--|--|
        |365|7|
        |12258|28|
        |996|4|

#### float convertFtoC(float fahrenheit)
Write a function, float convertFtoC(float fahrenheit), that converts 40° from degrees Fahrenheit (F) to degrees Celsius (C) using the following formula and returns the result:
    * C = (F - 32) / 1.8

#### int castToInt(long num), double castToDouble(long num), char castToChar(long num)
In the next part of the program we are going to see how choosing the wrong data types and careless casting can result in data loss. You should see inaccurate results. Complete the functions to typecast a long integer to the following datatypes
* int
* double
* char

### int fibonacci()
In the Fibonacci sequence, the first two Fibonacci numbers, called f0 and f1, are defined to be 0 and 1, respectively. Thereafter, each successive Fibonacci number fi is defined to be the sum of the two preceding Fibonacci numbers fi2 and fi1. So fi2 is calculated by adding together the values of fi0 and fi1.
     * Write a function that generates the first 20 fibonacci numbers _(including 0 and 1)_ using a loop.
     * You should return the final resulting value (the 20th value)

### Working with Colors

RGB (red, green, and blue) refers to a system for representing the colors to be used on a computer display. Red, green, and blue can be combined in various proportions to obtain any color in the visible spectrum. Intensity of each color is represented by the range of decimal numbers from 0 to 255 (256 levels for each color), equivalent to the range of binary numbers from 00000000 to 11111111, or hexadecimal 00 to FF.

For the second part of the assignment you will need to work with bit masking to determine the most prominent color in a given RGB value. You should return an integer corresponding to the most prominent color:

0. Unknown
1. Red
2. Green
3. Blue

You will need to separate the Red, Green, and Blue values, and determine which value is largest. Once you have determined the largest value, you must return the corresponding number for that color.

For example, the value 0xFF0000 would return 1 for Red, and 0x00FF00 would return 2 for Green.

If any two of the RGB colors are equal, the function should return 0.


