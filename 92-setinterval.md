# "setinterval"

### You can repeat something in specefic times.

### Syntax:
```
setinterval(function() {

	[codes]

}, [time/ms])
```

### Example:

**Input:**
```
setinterval (function() {

	console.log("Yes")

}, 1000)

// 1000ms = 1s
```

**Output:**
```
// Repeat "Yes" one time per our time
```

### Example:

**Input:**
```
var i = 10

var timer = setinterval(function() {

	if (i === 0) {
		
		console.log("game over")
		clearInterval(timer)	

	} else {

		console.log(i)
		i--

	}

})
```

**Output:**
```
10
9
8
7
6
5
4
3
2
1
game over
```

### Note: 
**We use "clearInterval" method to stop our "interval".**


<br>

### <a href="https://www.w3schools.com/jsref/met_win_setinterval.asp" style="text-decoration: none;"> source </a>