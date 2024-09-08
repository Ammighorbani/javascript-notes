# Object

### Syntax:
```
var [object-name] = {
	[codes]
}
```

### Example:

**Input:**
```
var ali = {
	name: "Amir",
	family: "ghorbani",
	age: 18
}

console.log(ali)
```

**Output:**
```
{name: 'Amir', family: 'ghorbani', age: 18}
```

### Note: 
**In "object" something like "name" is "key" and something like 'Amir' is "value".**

### Note: 
**In "object" we don't some index something like "Array" our index is our "key" and we can see our "value" with their "key".**

### Example:

**Input:**
```
var ali = {
	name: "Amir",
	family: "ghorbani",
	age: 18
}

console.log(ali['name'])
```

**Output:**
```
'Amir'
```

### Or

### Example:

**Input:**
```
var ali = {
	name: "Amir",
	family: "ghorbani",
	age: 18
}

console.log(ali.name)
```

**Output:**
```
'Amir'
```

### Note: 
**We can have an "Array" and in it we can have an "object".**

### Example:

**Input:**
```
var users = [
	{id: 1, name: "Amir", family: "ghorbani", age: 18},
	{id: 2, name: "amin", family: "rad", age: 15}
]

console.log(users)
```

**Output:**
```
(2) [{…}, {…}]
0: {id: 1, name: 'Amir', family: 'ghorbani', age: 18}
1: {id: 2, name: 'amin', family: 'rad', age: 17}
length: 2
[[Prototype]]: Array(0)
```

### Note: 
**We can show our "value" using their "key".**

### Example:

**Input:**
```
var users = [
	{id: 1, name: "Amir", family: "ghorbani", age: 18},
	{id: 2, name: "amin", family: "rad", age: 15}
]

console.log(users[0].name)
```

**Output:**
```
'Amir'
```


<br>

### <a href="https://javascript.info/object" style="text-decoration: none;"> source </a>