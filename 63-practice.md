# Practice

```
var users = [
    {id: 1, name: "Ali", family: "bagheri", age: 18, email: "alibagheri@gmail.com"},
    {id: 2, name: "Amir", family: "ghorbani", age: 19, email: "amirghorbani@gmail.com"},
    {id: 3, name: "mamad", family: "rad", age: 20, email: "mamad.rad@gmail.com"},
]


var userNameInput = prompt("Enter your name")
var userFNameInput = prompt("Enter your family name")
var userAge = prompt("Enter your age")
var userEmail = prompt("Enter your email")


if (userAge.length > 3) {
    console.log("invalid age")
} else if (userNameInput.length < 3 || userNameInput.length > 10) {
    console.log("invalid name")
} else if (userFNameInput.length < 3 || userFNameInput.length > 15) {
    console.log("invalid family name")
} else {
    users.push({id: (users[users.length-1].id) + 1, name: userNameInput, family: userFNameInput, age: Number(userAge), email: userEmail},)
}


for (var i = 0; i < users.length ; i++) {
    console.log(users[i])
}
```