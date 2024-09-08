# Practice

```
var userName = prompt("please enter your user name:")

var userPass = prompt("please enter your password:")

function log_in(userName="", userPass="") {
    if (userName.length >= 3 || userPass.length >= 8) {
            alert("welcome")
        }  else {
        alert("try again")
    }

}

log_in(userName, userPass)
```

### Note: 

**We must to use "||" because if userName incorrect and userPass be correct it will send error or uesrName correct and userPass be incorrect it will send error or both of theme be incorrect it will send error just when both of theme be correct it will accept it.**


### Example:

```
"true", "true" = "true"
"true", "false" = "false"
"false", "false" = "false"
```