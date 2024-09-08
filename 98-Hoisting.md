# Hoisting

### some key words look like "var" or "function" if we create them in last lines and use them on higher lines they will work be cause they will Hoist and comes top of our codes.

### Note: 
**If we write a "function" in variable and use it Hoisting wont work.**

### Example:

**Input:**
```
num1 = 10
console.log(num1)
var num1
```

**Output:**
```
10
```

### Example:

**Input:**
```
showval()

function showval () {

	console.log(10)

}
```

**Output:**
```
10
```

### Note: 
**We can create lots of variables in one "var".**

### Example:

**Input:**
```
num1 = 10
num2 = 2
console.log(num1 + num2)
var num1, num2
```

**Output:**
```
12
```

### Note: 
**If we get the variable value when we are creating the variable Hoisting wont work either.**



<br>

### <a href="https://www.w3schools.com/js/js_hoisting.asp" style="text-decoration: none;"> source </a>