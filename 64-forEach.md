# "forEach"

### This method will do a function per each indexes in an "Array".

### Syntax: 
```
[Array-name].forEach(function () {
	[codes]
})
```

### Example:

**Input:**
```
var users = [
	"ali",
	"amir",
	"taghi",
	"sasan",
	"mamad"
]

users.forEach(function () {
	console.log("hi")
})
```

**Output:**
```
(5) 'hi'
```

### Note: 
**We can write a "variable" in our "function" parantheses and any time "forEach" method go to the next index our "variable" value will be that value our method is.**

### Example:

**Input:**
```
var users = [
	"ali",
	"amir",
	"taghi",
	"sasan",
	"mamad"
]

users.forEach(function (user) {
	console.log("hi " + user)
})
```

**Output:**
```
hi ali
hi amir
hi taghi
hi sasan
hi mamad
```


<br>

### <a href="https://www.freecodecamp.org/news/javascript-foreach-how-to-loop-through-an-array-in-js/" style="text-decoration: none;"> source </a>
