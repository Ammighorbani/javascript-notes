# "while" Loop

### Syntax: 
```
while ([condition]) {
	[codes]
}
```

### Example:

**Inpute:**
```
var i = 0
while (i < 3) {
	console.log(i)
	i++
}
```

**Output:**
```
0
1
2
```

### Note: 
**Our condition must be "true" to our while loop start.**

### Example:

**Inpute:**
```
var i = 0
while (i < 100) {
	if (i % 2 === 0) {
		console.log(i)
	}
}
```

**Output:**
```
0
2
...
96
98
```

### Example:

**Inpute:**
```
var i = 0
var meiangin = 0

while (i < 3) {
	var userinpute = Number(prompt("Enter your number"))
	meiangin += userinpute
	i++
}

console.log(meiangin / i)
```

**Output:**
```
6
```


<br>

### <a href="javascript.info/while-for#the-while-loop" style="text-decoration: none;"> source </a>
