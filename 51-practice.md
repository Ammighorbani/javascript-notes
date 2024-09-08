# Pracite

```
var usernumberInpute = prompt("please enter your number")

console.log(usernumberInpute)

var sumNumbers = 0

for (var i = 0; i < usernumberInpute.length; i++) {
    console.log("number " + (i+1) + " is:" + usernumberInpute[i])

    sumNumbers += Number(usernumberInpute[i])

    console.log("sum " + (i+1) + " is:" +sumNumbers)
}


console.log("sum is:" + sumNumbers)
```