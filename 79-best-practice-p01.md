# Beast Practice Part 1

### Hear we will tell you some guideline to write better codes.

### 1- If you are writing a code and you have a condition base on a "boolean" data type "variable" and if it's data type is "true" you don't need to compare it.

### Example:

**Input:**
```
var isOnline = true

if (isOnline) {
	console.log("online")
}
```

**Output:**
```
true
```

### "if (isOnline)": 
**It's look like `if (isOnline == true)`**

### Note: 
**If you want to write a code base on "boolean" data type and you want to write a code base on "false" you must to use "!".**

### Example:

**Input:**
```
var isOnline = false

if (!isOnline) {
	console.log("online")
}
```

**Output:**
```
online
```

### "if (!isOnline)": 
**It's mean "isOnline" equal with "false" and you check the other side of "isOnline" data type and it's mean "true".**

### 2- It's better when we want to create a "variable" use "===" don't use "==".

### 3- Never create a "variable" in a loop always create it outside of your loop and in your loop use of that "variable" name.

### 4- Never create a "switch case" without "default" option.

### 5- If you want to append data into "Array" never use the "last-lenght-equal" always use of "push()" method.



<br>

### <a href="https://good.js.org/" style="text-decoration: none;"> source </a>
