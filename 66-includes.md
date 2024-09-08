# "includes"

### This method will check our "Array" and if our object is in will get back to us "true" if not will get back "false".

### Syntax:
```
[Array-name].includes( [object] , [index] )
```

### "object": It's what we are searchin for.

### "index": It's mean this method start to searching from which "index". 

### Note: 
**This method always will get back a "boolean" answer to us.**

### Example:

**Input:**
```
var users = [
	"Ali",
	"Amir",
	"babak"
]

console.log(users.includes("Ali"))
```

**Output:**
```
true
```

### Example:

**Input:**
```
var users = [
	"Ali",
	"Amir",
	"babak"
]

console.log(users.includes("Ali", 1))
```

**Output:**
```
false
```

### Note: **Cause we told him start from index 1 we receive false.**

### Note: 
**This method is a case sensitive method.**

### Example:

```
var users = [
    "Amir",
    "Ali",
    "babak",
]

var userName = prompt("Enter your name")

var isInclude = users.includes(userName)


if (isInclude === true) {
    console.log("welcome")
} else {
    console.log("please create an account")
}
```


<br>

### <a href="https://www.w3schools.com/jsref/jsref_includes_array.asp" style="text-decoration: none;"> source </a>