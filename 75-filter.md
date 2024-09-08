# "filter"

### This method will help us to choose speceific datas in our "Array".

### Syntax:
```
[Array-name].filter(function() {
	[codes]
})
```

### Example:

**Input:**
```
var scores = [1,5,17,18,20]

var filterScores = scores.filter(function(score) {
	
	return score > 10

})

console.log(filterScores)
```

**Output:**
```
[17,18,20]
```

### Note: 
**"filter" method look like "map" method will create an "Array" for us.**


<br>

### <a href="https://www.w3schools.com/jsref/jsref_filter.asp" style="text-decoration: none;"> source </a>