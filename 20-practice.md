# Practice

```
var num1 = Number(prompt("Enter your birth date:"))

if (isNaN(num1)){
    alert("سال تولد صحیح نمی باشد")
}

var nowYear = 2024

if (num1>nowYear) {
    alert("هنوز به این سال نرسیدیم")
} else {
    var userAge = nowYear - num1
    alert(userAge)
}
```