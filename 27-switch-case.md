# Switch Case
### It's look like "if", "else", "else if"

### Syntax:
```
switch(x) {
    case 'value1':	//if (x === 'value1')
        ......
        [breake]
    case 'value2': //if (x === 'value2')
        ......
        [breake]
    case 'value3': //if (x === 'value3')
        ......
        [breake]
    case 'value4': //if (x === 'value4')
        ......
        [breake]
    default:
        ......
        [break]
}
```

### Example:
```
var num1 = 3
var num2 = 4

var num3 = num1 * num2

switch(num3) {
    case 10:
        alert("10")
        break
    case 11:
        alert("11")
        break
    case 12:
        alert("12")
        break
    case 13:
        alert("13")
        break
    default:
        alert("nothing")
        break
}
```

### Note: 
**It's better if we have more than 3 or 4 if else if we use "switch case".**

### Note: 
**If we want to say for example something like "or" in switch case for example if x===3 or x===4 we must write it like this.**

### Example:
```
var num1 = 3
var num2 = 4

var num3 = num1 * num2

switch(num3) {
    case 10:
        alert("10")
        break
    case 11:
case 12:
        alert("11,12")
        break
default:
    alert("nothing")
    break
}
```

<br>

### <a href="https://javascript.info/switch" style="text-decoration: none;"> source </a>
