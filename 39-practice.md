# Practice

```
var userName = prompt("Enter your name please")
var userPass = prompt("Enter your password please")

function log_in (userName="", userPass="") {
    if (userName.toLowerCase() == "ali"){
        alert("welcome")
    } else {
        alert("permission denied")
    }
}

log_in(userName, userPass)
```