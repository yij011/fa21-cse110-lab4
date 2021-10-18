##1. values added:  20
##2. final result:  20
##3. values added:  20
##4. line 13: ReferenceError: result is not defined。
This is because that if a variable is declared inside a code block with let, it's only visible inside that block. for the line 13, it's outside the block so that variable name cannot be recognized.
##5. line 7: TypeError: Assignment to constant variable.
This is because variable result is declared as a constant and it cannot be reassigned so attempt to reassign this variable will cause a error
##6. line 7: TypeError: Assignment to constant variable.
This is because variable result is declared as a constant and it cannot be reassigned so attempt to reassign this variable will cause a error
