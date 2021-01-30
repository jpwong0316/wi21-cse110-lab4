### **Debugging**

The bug with part 1 of the website is that the numbers of the input are being stored as a string instead of a number.
Thus, the result when 1 is input for num1 and 2 for num2 is the string "12" because it concatenates the strings "1" and "2".
My fix for this bug was to use the function Number() to convert num1 and num2 to numbers instead of strings.
The new result is 3 when num1 is 1 and num2 is 2.

### **Network**

1. citylots.json
2. part2.js:2
3. 11.7 MB
4. 80 ms
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.141 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData @ part2.js:2
