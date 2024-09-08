# Practice

```
var userMinute = Number(prompt("Enter how many minute"))
var userSecond = Number(prompt("Enter how many second"))


var timer = setInterval(function() {

    if (userSecond === -1) {

        userMinute--
        userSecond += 60

    }
    
    if (userMinute === 0 && userSecond === 0) {

        console.log("Time: " + userMinute + ":" + userSecond)
        console.log("Time out")
        clearInterval(timer)

    } else {
        
        console.log("Time: " + userMinute + ":" + userSecond)
    
        userSecond--

    }


}, 1000)
```