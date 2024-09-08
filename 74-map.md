# "map"

### We use "map" method when we want to make change on "Array" items and have access to their resault.

### Syntax:
```
[Array-name].map(function () {
	[codes]
})
```

### Example:

**Input:**
```
var scores = [2,4,6,8,10]

var scoresPower = scores.map(function (score) {
	return score ** 2
})

console.log(scoresPower)
```

**Output:**
```
[4,16,36,64,100]
```

### Note: 
**"map" method always create an "Array" in that variable.**

### Note: 
**"map" isn't searching for "boolean" data type look like "every" and "some" it will be run untile our items finish.**

### Different Between "forEach" and "map"

**In "forEach" method we can't return any data if we do it we will receive "undifiend" error but in "map" method we can return datas.**


<br>

### <a href="https://www.w3schools.com/jsref/jsref_map.asp" style="text-decoration: none;"> source </a>