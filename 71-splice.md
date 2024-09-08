# "splice"

### With this method we can change add or remove our items in our "Array".

### Delete Syntax:
```
[Array-name].splice( , )
```

### Note: 
**First free space is "start index" and second one is "how many next step".**

### Example:

**Input:**
```
var numbers = [1,2,3,4,5,6,7,8,9,10]

numbers.splice(2,3)

console.log(numbers)
```

**Output:**
```
[1,2,6,7,8,9,10]
```

### Note: 
**When we enter "how many next step" it will start of our "start index" and first item will delete is our "start index".**

### Replace Syntax:
```
[Array-name].splice( , , ....)
```

### Note: 
**First free space is "start index" and second one is "how many next step" and third one is "replace data".**

### Example:

**Input:**
```
var numbers = [1,2,3,4,5,6,7,8,9,10]

numbers.splice(2,1,4,5)

console.log(numbers)
```

**Output:**
```
[1,2,4,5,4,5,6,7,8,9,10]
```

### Note: 
**First 4,5 is the replaced data of index number 2 and all of that changed to two other number we entered.**



<br>

### <a href="https://www.w3schools.com/jsref/jsref_splice.asp" style="text-decoration: none;"> source </a>