# Practice

```
var i = 0
var hmNumInpute = Number(prompt("how many numbers to receive"))
var sumnums = 0

while (i < hmNumInpute) {
    var userNumberInpute = Number(prompt("Enter your " + (i+1) + " number"))
    console.log(userNumberInpute)

    sumnums += userNumberInpute

    i++
}

console.log(Math.floor(sumnums / i))
```