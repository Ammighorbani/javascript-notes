# Practice

```
var userNumber1 = Number(prompt("Enter your first number"))
var userOperation = prompt("Enter your operation \n 1. Addition \n 2. Subtraction \n 3. Dividing \n 4. Multiply")
var userNumber2 = Number(prompt("Enter your second number"))

if (isNaN(userNumber1) || isNaN(userNumber2)) {

    console.log("invalid value")

} else if (userOperation === "1") {

    console.log(userNumber1 + userNumber2)

}  else if (userOperation === "2") {

    console.log(userNumber1 - userNumber2)

}  else if (userOperation === "3") {

    console.log(userNumber1 / userNumber2)

}  else if (userOperation === "4") {

    console.log(userNumber1 * userNumber2)

} else {

    console.log("We don't have this operation")

}


if (isNaN(userNumber1) || isNaN(userNumber2)) {

    console.log("invalid value")

} else {

    switch (userOperation) {
    
        case "1":
            console.log(userNumber1 + userNumber2)
            break
    
        case "2":
            console.log(userNumber1 - userNumber2)
            break
    
        case "3":
            console.log(userNumber1 / userNumber2)
            break
    
        case "4":
            console.log(userNumber1 * userNumber2)
            break
        
        default:
            console.log("we don't have this operation")
    
    }

}
```