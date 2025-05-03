1. The console prints "3" because i is incremented in the for loop from 0 to 3.
2. The console prints "150" because the discounted price for 300 is calculated as 300 * (1 - 0.5) = 150.
3. The console prints "150" because the final price for 300 after reounding is 150.
4. The function returns [50, 100, 150] because it returns the array of discounted prices, where here the discount is 50% of the original price.
5. ReferenceError: i is not defined. This error occurs because i is declared with let inside the for loop, making it block-scoped and not accessible outside the loop.
6. ReferenceError: discountedPrice is not defined. This error occurs because discountedPrice is declared with let inside the for loop, making it block-scoped and not accessible outside the loop.
7. The console prints "150" because the final price for 300 after rounding is 150. This is because finalPrice is declared outside the for loop, making it accessible in the console.log statement.
8. The function returns [50, 100, 150] because it returns the array of discounted prices, where here the discount is 50% of the original price.
9. ReferenceError: i is not defined. This error occurs because i is declared with let inside the for loop, making it block-scoped and not accessible outside the loop.
10. The console prints "3" because the length of prices is 3.
11. The function returns [50, 100, 150] because it returns the array of discounted prices, where here the discount is 50% of the original price.
12. 
A: student.name
B: student["Grad Year"]
C: student.greeting()
D: student["Favorite Teacher"].name
E: student.courseLoad[0]
13.
A: '32' - String + Int = String Cocatenation
B: 1 - String - Int = Numeric Coercion
C: 3 - Null is coerced to 0
D: '3null' - String + Null = String Concatenation
E: true + 3 - true is coerced to 1
F: 0 - both are coerced to 0
G: '3undefined' - String + Undefined = String Concatenation
H: NaN - Undefined becomes NaN
14.
A: true - '2' is coerced to 2
B: false - lexographical comparison
C: true - == allows type coercion
D: false - === does not allow type coercion
E: false - true is coerced to 1
F: true - Boolean(2) is true
1.  == compares equality with type coercion, while === compares equality without type coercion. For example, '2' == 2 is true because of type coercion, but '2' === 2 is false because they are of different types.
16. See file.
17. This code applies doSomething to each element in the array and pushes it to newArr. This code returns [2, 4, 6].
18. See file.
19. Output:
1  
4  
3  
2
