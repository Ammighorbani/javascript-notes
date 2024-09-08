# Practice

```
var users = [
    {id: 1, name: "Ali", age: 19},
    {id: 2, name: "mamad", age: 10},
    {id: 3, name: "Amin", age: 13},
    {id: 4, name: "Amir", age: 29},
    {id: 5, name: "babak", age: 30},
]

var isAllAd = users.every(function(user) {

    if (user.age >= 18) {
        return true
    } else {
        return false
    }

})

if (isAllAd === true) {
    console.log("welcom")
} else {
    console.log("permission denied")
}
```