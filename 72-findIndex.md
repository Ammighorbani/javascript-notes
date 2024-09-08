# "findIndex"

### We can find that item we want in our "Array" with this method.

### Syntax:
```
[Array-name].findIndex(function () {
	[codes]
})
```

### Example:

**Input:**
```
var users = ["ali", "amin", "babak", "amir"]

var userNameIndex = users.findIndex(function (user){
	return user === "ali"
})
```

**Output:**
```
0
```

### Object Example:

**Input:**
```
var users = [
    {id: 1, name: "amin", age: 54},
    {id: 2, name: "babak", age: 30},
    {id: 3, name: "amir", age: 18},
]

var userIndex = users.findIndex(function (user){
	return user.name === "amir"
})
```

**Output:**
```
2
```


<br>

### <a href="https://www.w3schools.com/jsref/jsref_findindex.asp" style="text-decoration: none;"> source </a>