# "every"

**This method will check our items with a condition and if all of our items be in that condition we will receive "true" else we will receive "false".**

### Syntax:
```
[Array-name].every(function ()) {
	[codes]
}
```

### Example:
```
ages.every(function (age) {
	console.log(age)

	// return true
})
```

### Note: 
**We use "return true" to protect of our loop break.**

### Note: 
**We say "every" method check our items with a condition if all of items be in our condition we will receive "true" else we will receive "false".**

### Example:

**Input:**
```
var ages = [19,18,11,15,18]

var isAllAd = ages.every(function (age) {
	return age > 18
})

console.log(isAllAd)
```

**Output:**
```
false
```

### Note: 
**Because all of our items not in our condition we received "false".**

### Note: 
**"every" method look like "some" method is run untile receive a specific "boolean" data type in "some" our loop is run untile reveive "true" but in "every" method our loop is run untile our loop receive "false".**

### Note: 
**When we want to check a condition for all of our items we use "every" method.**



<br>

### <a href="https://www.w3schools.com/jsref/jsref_every.asp" style="text-decoration: none;"> source </a>