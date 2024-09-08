# "some"

### Note: 
**It's a method it work look like "includes" but with "forEach" syntax.**

### Syntax:
```
[Array-name].some(function () {
	[codes]
})
```

### Example:
```
users.some(function (user) {
	console.log(user)
})
```

### Note: 
**Why it's better to use "some" and don't use of "includes"? Because in "includes" we can't for example enter an "object" but in "some" method we can.**

### Note: 
**"some" method only run untile receive "true" in "return" method but "forEach" will do a function per each indexes in our "Array".**

### Example:

**Input:**
```
var users = [
    {id: 1, name: "amir", family: "ghorbani"},
    {id: 2, name: "mamad", family: "salighe"},
    {id: 3, name: "ali", family: "mardani"},
]


var isInuser = users.some(function (user) {
	console.log(user)
	return user.name == "ali"
})

console.log(isInuser)
```

**Output:**
```
{id: 1, name: 'amir', family: 'ghorbani'}
true
```


<br>

### <a href="https://www.w3schools.com/Jsref/jsref_some.asp" style="text-decoration: none;"> source </a>