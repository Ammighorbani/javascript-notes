# Practice

```
var userNumberInpute1 = Number(prompt("Enter your number 1"))
var userNumberInpute2 = Number(prompt("Enter your number 2"))


if (userNumberInpute1 < userNumberInpute2) {
    while (userNumberInpute1 < userNumberInpute2) {
        if (userNumberInpute1 % 2 == 0) {
            console.log(userNumberInpute1)
        }
        userNumberInpute1++
    }
} else {
    while (userNumberInpute1 > userNumberInpute2) {
        if (userNumberInpute2 % 2 == 0) {
            console.log(userNumberInpute2)
        }
        userNumberInpute2++
    }
}
```