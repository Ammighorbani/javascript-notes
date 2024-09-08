# "push()", "pop()", "shift()", "unshift()"

### Add a number at the end of "Array":

**Input:**
```
var scores = [17,18]
console.log(scores)

scores[3] = 19
console.log(scores)
```

**Output:**
```
(3) [17,18,19]
```

### "push()": 
**This method will do this mission for us.**

### Example:

**Input:**
```
var scores = [17,18]
console.log(scores)

scores.push(19)
console.log(scores)
```

**Output:**
```
(3) [17,18,19]
```

### "pop()": 
**This method will delete last index value for us.**

### Example:

**Input:**
```
var scores = [17,18]
console.log(scores)

scores.pop()
console.log(scores)
```

**Output:**
```
(1) [17]
```

### Note: 
**We don't need to enter any value in parentheses for "pop()" method.**


### "shift()": 
**This method completely look like "pop()" method but this mehtod won't delete last index it will delete zero index value.**


### Example:

**Input:**
```
var scores = [17,18]
console.log(scores)

scores.shift()
console.log(scores)
```

**Output:**
```
(1) [18]
```

### "unshift()": 
**This method completely look like "push()" but it won't add at the end of the "Array" it will append the value at the start of "Array".**

### Example:

**Input:**
```
var scores = [17,18]
console.log(scores)

scores.unshift(19)
console.log(scores)
```

**Output:**
```
(3) [19,17,18]
```

### Note: 
**We can give more than one value.**



<br>

### <a href="https://javascript.info/array" style="text-decoration: none;"> source </a>