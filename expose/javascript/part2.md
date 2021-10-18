## 1. 3
Variable i is declared using var and var has no block scope so i is still visible outside the for loop and after the for loop, i has been counted to 3 so it will print 3
## 2. 150
As var ignores code blocks, we've got the the variable discountedPrice still visible outside the for loop. The last time we assigned the variable discountedPrice is when i = 2, so the discountedPrice will be prices[2] * 0.5 = 300*0.5 = 150 so it will print 150
## 3. 150
The last time we assigned the variable finalPrice is when i = 2, so the finalPrice will be the round value of discountedPrices which is 150
## 4. an array with value [ 50, 100, 150 ]
Inside the for loop, the discounted variable will be pushed the finalPrice and for i = 0,1,2, the finalPrices will be 50,100,150 so these value will be store in the array and be the return value of the function.
## 5. ReferenceError: i is not defined
When using let, if a variable is declared inside a code block {...}, it’s only visible inside that block. So it will give an error when you try to call it outside the block.
## 6. ReferenceError: discountedPrice is not defined
When using let, if a variable is declared inside a code block {...}, it’s only visible inside that block. So it will give an error when you try to call it outside the block.
## 7. 150
Variable finalPrice is also declared using let but it's not in the loop block so it's visible inside the function.
## 8. an array with value [ 50, 100, 150 ]
Variable discounted is declared using let but it's not in the loop block so it's visible inside the function and at the end of function, it is visible and can be store as the return value.
## 9. ReferenceError: i is not defined
When using let, if a variable is declared inside a code block {...}, it’s only visible inside that block. So it will give an error when you try to call it outside the loop block.
## 10. 3
length is declared as a constant so it will be the length of array which is 3.
## 11. an array with value [ 50, 100, 150 ]
It does not define a constant array. It defines a constant reference to an array so we can still change the elements of a constant array and use it as a return value and the return value will be the pushed iscountedPrice.
## 12.
A. student.name;
B. student["Grad Year"];
C. student.greeting();
D. student["Favorite Teacher"].name
E. student.courseLoad[0]
## 13. 
A. ‘3’ + 2 = 32                   integers map to their exact string representation so 2 maps to '2'
B. ‘3’ - 2 = 1                    '3' maps to integer 3 so 3-2 = 1
C. 3 + null = 3                   null maps to 0 so 3+0 = 3
D. ‘3’ + null = 3null             null maps to string 'null'
E. true + 3  = 4                  true maps to 1 so 1 + 3 = 4
F. false + null = 0               false maps to 0 and null maps to 0 so 0+0 = 0
G. '3' + undefined = 3undefined   undefined maps to string 'undefined'
H. '3' - undefined = 3undefined   undefined maps to string 'undefined'
## 14. 
A. ‘2’ > 1 = true               '2' maps to integer 2 so 2 > 1 is true.  
B. ‘2’ < ‘12’ = false           '2' maps to integer 2 and '12' maps to integer 12 so 2 > 12 is false.
C. 2 == ‘2’ = true              '2' maps to integer 2 so 2 == 2 is true.
D. 2 === ‘2’ = false             2 and '2' are not in the same type so 2 === ‘2’ is false.
E. true == 2 = false             true maps to integer 1 so 1 == 2 is false.
F. true === Boolean(2) = true    Boolean(2) will gives true so true and true are both boolean type and same value so returns true.
## 15. == in JavaScript is used for comparing two variables, but it ignores the datatype of variable while === is used for comparing two variables, but this operator also checks datatype and compares two values. == is called as comparison operator whereas It is also called as comparison operator. == Return true only if the two operands are equal while === returns true only if both values and data types are the same for the two variables.
## 16. see file part2-question16.js
## 17. First we call the function modifyArray and parse the value [1,2,3] and the fucntion method doSomething. Then inside the modifyArray function, we declared a newArr as a array variable and inside the for loop, we push the value 1,2,3 from array [1,2,3] into callback function(doSomething) so we acturally push the value 1*2, 2*2, 3*2 into newArr so the return value of after we do the call will be [2,4,6].
## 18. see file part2-question18.js
## 19. 1 4 3 2
