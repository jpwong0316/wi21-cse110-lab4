**Debugging**
The bug with part 1 of the website is that the numbers of the input are being stored as a string instead of a number.
As a result, the result is "12" because it concatenates the strings "1" and "2".
My fix for this bug was to use the function Number() to convert num1 and num2 to numbers instead of strings.
