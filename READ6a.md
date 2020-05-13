# linking javaScript with htmal 

to link javaScript with html we use **script** tag 

the best place to add the **script** tag is before the closing **body**tag

```

<script src="js/ add-content.js"></ script> 

```


***Note that JavaScript is case sensitive so hourNow means something different to HourNow or HOURNOW.*** 

## Data Type :
- Numeric 
- String 
- Boolean 

***Note that Numbers are not only used for things like calculators; they are also used for tasks such as:***

 - determining the size of the screen
 - moving the position of an element on a page
 - setting the amount of time an element should take to fade in


example of script :

```

var today = new Date(); 
var hourNow = today.getHours(); 
var greeting; 
if (hourNow > 18) { 
    greeting = 'Good evening!'; 
    else if (hourNow > 12) { 
    greeting = ' Good afternoon!'; 
    else if (hourNow > 0) { 
    greeting = 'Good morni ng!'; 
    else { greeting = 'Welcome! ' ; 

document .write( ' <h3>' +greeting + ' </ h3>'); 

```