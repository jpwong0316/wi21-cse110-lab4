1. 3: var has no block scope so the variable i is not out of scope
2. 150: var has no block scope so the variable discountedPrice is not out of scope, and redeclarations are allowed with var
3. 150: var has no block scope so the variable finalPrice is not out of scope
4. The function will return \[50, 100, 150], which is the array of discounted prices. Since the discount is 0.5, the function
   halves the price of each price and returns in it a new array.
5. error: i is declared by "let" inside a loop so the variable is out of scope at line 11
6. error: discountedPrice is declared by "let" inside the loop so the variable is out of scope at line 12
7. 150: finalPrice is not declared inside a code block so the variable is not out of scope at line 13
8. The function will still return \[50, 100, 150]. The change in variable declaration from "var" to "let" doesn't change how
   the code functions. While it does change the console log calls, the actual function still performs as expected, giving us
   the array of discounted prices as the return.
9. error: i is declared by "let" inside a loop so the variable is out of scope at line 11
10. error: discountedPrice is assigned as a "const" in a code block so it is out of scope at line 12
11. 0: finalPrice is assigned as a "const" so its value cannot be changed from its initial value of 0
12. \[]: "const" variables are constants and will cause errors if you attempt to reassign them, so running the function
    will produce an error. If the code still ran despite the errors, it would return \[], the initial value of discounted.
13. 
   A. student.name
   B. student\['Grad Year']
   C. student.greeting()
   D. student\['Favorite Teacher'].name
   E. student.courseLoad\[0]
14. 
   A. '32' is the output because '3' is treated as a string, so it interprets the '3'+2 as concatenating the string '3' and the string '2'.
   B. 1 is the output because even though '3' is interpreted as a string initially, subtraction can only be performed on two numbers, so it has to
      treat '3'-2 as the number 3 minus the number 2.
   C. 3 is the output because 3 is interpreted as a number, so that means that the + means addition rather than concatenation. As a result, the null
      must be interpreted numerically as well since addition is between two numbers, and the numeric value of null is 0.
   D. '3null' is the output because '3' is a string, so the + means concatenation rather than addition. Thus, the null is treated as a string as well,
      and the string value of null is just 'null'.
   E. 4 is the output. Since a boolean cannot be added to something else without being type converted, we know that true will have to convert into a
      different type. The value on the other side of the + sign is 3, so we convert true into a numeric value of 1, resulting in 1 + 3 = 4.
   F. 0 is the output. Although neither false nor null are strings or numbers, the compiler will assume addition over concatenation. Thus, false and null
      are converted to numbers, resulting in 0 + 0 = 0.
   G. "3undefined" is the output because "3" is a string so the + means concatenation rather than addition so undefined is string converted to "undefined".
   H. NaN is the output. The minus operation can only be used on numbers, so the compiler attempts to convert both "3" and undefined into numeric values. The
      numeric value of "3" is just 3 but the numeric value of undefined is NaN which makes 3 - NaN = NaN.
