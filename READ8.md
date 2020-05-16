# Comparison Operators :
## Evaluation conditions :
 - == :is equal to, compares two values to see if they are the same 
 - != : isn't equal to, compares two values to see if they are not the same
 - === : strict equal to,  to check both data type and value are the same
 - !== : strict not equal to, to check both data type and value are not the same


## Logical Operators :

- and (&&) : test more than one condition, it will alwayes return false but in the case of both of the conditions are true it will return true 
- or (||) : test more than one condition, it will alwayes return true but in the case of both of the conditions are false it will return false
-  not (!) : it takes a single boolean value and inverts it 

## Loops :
it check a condition if it returns true a code block will run and the condition will be checked until it returns false.

### Types of loops :
- For : to run a code a specific number of times
 - initialization 
 - condition
 - update

 ```
for (var i = 0; i < 10; i++) {

}

```

- While : if you dont know how many times the code should be run.

```

var i = l ; var msg = ' ' ; 
while (i < 10) {
     msg += i + ' x 5 = ' + (i * 5) + '<br I>'; i++;
 }
document.getEl ementByid( ' answer') . innerHTML = msg; 

```







