# Practice

```
var i = 0
var hmunum = Number(prompt(how many number to input))
var mianginarr = []
var miangin = 0

while (i < hmunum) {
    var userNumberInput = Number(prompt(Enter your numbers))

    console.log(userNumberInput)

    mianginarr.push(userNumberInput)
    i++
}

for (var ii = 0; ii < mianginarr.length; ii++) {
    miangin += mianginarr[ii]
}

console.log(miangin / mianginarr.length)
```
