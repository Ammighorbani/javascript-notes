# Practice

### Example:

**Inpute:**
```
var i = 0
var userInpute = prompt("Enter your number")
var sumNumbers = 0

console.log(userInpute)
console.log(userInpute.length)

while (i < userInpute.length) {
    
    console.log("i's number" + i)
    console.log("sumNumbers befor add:" + sumNumbers)

    sumNumbers += Number(userInpute[i])

    console.log("sumNumbers after add:" + sumNumbers)

    i++
}

console.log(sumNumbers)
```

**Output:**
```
15
```

### Example:

**Inpute:**
```
var i = 0
var userInpute = prompt("Enter your number")
var sumlenght = 0

while (i < userInpute.length) {
    sumlenght++
    i++
}

console.log(sumlenght)
```

**Output:**
```
3
```