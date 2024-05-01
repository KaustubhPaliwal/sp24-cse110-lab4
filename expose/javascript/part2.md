Question 1: It will print '3'

Question 2: It will print '150'

Question 3: It will print '150'

Question 4: It will return an array of '[ 50, 100, 150 ]'

Question 5: The code return an error! 'ReferenceError: i is not defined'. This is because the scope of the variable result, due to the 'let' keyword, it only within the code block from line 6 - line 10. Therefore, at line 12, no variable i exists.

Question 6: The code return an error! 'ReferenceError: discountedPrice is not defined'. This is because the scope of the variable result, due to the 'let' keyword, it only within the code block from line 6 - line 10. Therefore, at line 12, no variable i exists.

Question 7: It will print '150'

Question 8: It will return an array of '[ 50, 100, 150 ]'

Question 9: The code return an error! 'ReferenceError: i is not defined'. This is because the scope of the variable result, due to the 'let' keyword, it only within the code block from line 6 - line 9. Therefore, at line 11, no variable i exists.

Question 10: It will print '3'

Question 11: It will return an array of '[ 50, 100, 150 ]'

Question 12: 
- student.name
- student['Grad Year']
- student.greeting()
- student['Favorite Teacher'].name
- student.courseLoad[0]

Question 13: 
- '3' + 2 = '32', 
    - This is because when you use the + operator with a string and a number, it performs concatenation, converting the number to a string and concatenating it with the other string.
- '3' - 2 = 1,
    - This is because when you use the - operator with a string that can be converted to a number and a number, JavaScript converts the string to a number and performs subtraction.  
- 3 + null = 3,
    - Because in JavaScript, when you use the + operator with a number and null, null is treated as 0, so the result is the number.   
-  '3' + null = '3null'
    - This is because when you use the + operator with a string, it performs concatenation, converting the second operand to a string and concatenating it with the other string.
- true + 3 = 4
    - True is converted to 1, so adding 1 (the value of true) to 3 results in 4. 
- false + null = 0
    - Both false and null are converted to 0, so the result is 0.
- '3' + undefined = 3undefined
    -  This is because when you use the + operator with a string, it performs concatenation, converting the second operand to a string and concatenating it with the other string.
- '3' - undefined = NaN
    - This happens because when you try to perform arithmetic operations involving undefined, the result is NaN because undefined cannot be converted to a number.

Question 14: 

- '2' > 1 = true 
    - When comparing strings and numbers, JavaScript converts the string to a number before comparison, so '2' (as a number) is greater than 1.
- '2' < '12' = false
    - This is a string comparison. JavaScript compares strings character by character. '2' is not less than '12' because the comparison starts with the first character, where '1' is greater than '2'.
- 2 == '2' = true
    - The == operator performs type coercion before comparison. So, '2' is converted to a number before comparison, and 2 is equal to 2.
- 2 === '2' = false
    - The === operator does not perform type coercion. Since 2 is a number and '2' is a string, they are of different types and therefore not equal.
- true == 2 = false
    -  This is because the value of true is 1, which is not equal to 2
- true === Boolean(2) = true
    - Because Boolean(2) returns true and it is strictly equal to true

Question 15: 

The main difference between == and === is that 
- The == operator compares the values of two variables after performing type conversion if necessary. 
- The === operator compares the values of two variables without performing type conversion.

Question 16:

In part2-question16.js

Question 17:

When the function <code>modifyArray([1,2,3], doSomething)</code> is called with the given parameters, the result will be [2, 4, 6].

Here's how we arrive at this result:

The modifyArray function takes two parameters: an array and a callback function.
- Inside modifyArray, a new array newArr is initialized.
- The function iterates through each element of the input array using a for loop.
- For each element of the input array, it calls the callback function with the current element as an argument (callback(array[i])).
- The return value of the callback function (in this case, doSomething) is then pushed into the newArr.
- Finally, the newArr containing the modified elements is returned.

The doSomething function simply doubles the input number. So when modifyArray([1,2,3], doSomething) is called:

- For 1, doSomething(1) returns 1 * 2 = 2.
- For 2, doSomething(2) returns 2 * 2 = 4.
- For 3, doSomething(3) returns 3 * 2 = 6.
- Therefore, the result of modifyArray([1,2,3], doSomething) will be [2, 4, 6].

Question 18: 

In part2-question18.js

Question 19:

The output will be:

<code>1</code>   
<code>2</code>  
<code>3</code>  
<code>4</code>
