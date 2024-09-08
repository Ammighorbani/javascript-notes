# Practice

```
var users = [

    {id: 1, name: "amir", pass: "f;jb"},
    {id: 2, name: "babak", pass: ";SR"},
    {id: 3, name: "amin", pass: ";ASJKF"},
    {id: 4, name: "ali", pass: "sidijb"},

]

var userName = prompt("Enter your name to get your password")

var findUserPass = users.find(function(user) {

    return user.name === userName

})

if (findUserPass !== undefined) {

    console.log("Your Password: " + findUserPass.pass)

} else {

    console.log("We don't have your name in our website")

}
```