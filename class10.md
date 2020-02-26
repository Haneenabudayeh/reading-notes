# summary
## read 10

## Error Handling & Debugging


## To find the source of an error, it helps to know how scripts are processed.

### EXECUT.ION CONTEXTS
- GLOBAL CONTEXT
-  GLOBAL SCOPE 
- EVAL CONTEXT (NOT SHOWN) 

## Error objects
### Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

* Syntax Error
SYNTAX IS NOT CORRECT
This is caused by incorrect use of the rules of the language. It is often the result of a simple typo. 

* VARIABLE DOES NOT EXIST
This is caused by a variable that is not declared or is out of scope

* Ev alError
INCORRECT USE OF eval() FUNCTION The eval () function evaluates text through the interpreter and runs it as code (it is not discussed in this book). It is rare that you would see this type of error, as browsers often throw other errors when they are supposed to throw an Eva 1 Error. 

* UR I Error
INCORRECT USE OF URI FUNCTIONS If these characters are not escap in URls, they will
cause an error: / ? & I : ; 

* Type Error VALUE IS UNEXPECTED DATA TYPE
* RangeError NUMBER OUTSIDE OF RANGE
* Error GENERIC ERROR OBJECT
* NaN NOT AN ERROR

