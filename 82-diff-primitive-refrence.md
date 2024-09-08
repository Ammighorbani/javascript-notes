# Difference between "Primitive" and "Reference" Datas.

### "Reference": 
**1-"Array", 2-"Object", 3-"Function" types are "reference" data type.**

### "Primitive": 
**All other datas are "primitive" if they aren't in "reference" data type.**

### "Primitive" Example:

**Input:**
```
var num1 = 10
var num2 = num1
num2 += 3

console.log(num1)
console.log(num2)
```

**Output:**
```
10
13
```

### "Reference" Example:

**Input:**
```
var mylist = ["Ali", "Mamad", "Taghi"]
var mynewlist = mylist
mynewlist.push = "babak"

console.log(mylist)
console.log(mynewlist)
```

**Output:**
```
["Ali", "Mamad", "Taghi", "babak"]
["Ali", "Mamad", "Taghi", "babak"]
```

### "Primitive" Note: 
**In "Primitive" datas if you create a variable and you put that variable value equal with your recent variable and make change on new variable the change will only apply on new variable.**

### "Reference" Note: 
**In "Reference" datas if you do something look like "Primitive" datas what you see is the change was applyed on both variables.**

### Reason: 
**In "Primitive" datas the second variable is a copy of first variable and for this reason that change will only apply on second variable but in "Reference" datas the second variable is a link of first variable and for this reason the change will apply on first variable and our change will impact on both variables.**



<br>

### <a href="https://dev.to/js_catch/ 02-primitive-and-non-primitive-data-types-in-javascript-2dhd" style="text-decoration: none;"> source </a>

### <a href="https://medium.com/@junshengpierre/javascript-primitive-values-object-references-361cfc1cbfb0" style="text-decoration: none;"> source </a>
