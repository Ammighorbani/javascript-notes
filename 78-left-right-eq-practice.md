# Practice

```
var userInput = prompt("enter your word")

// console.log(userInput)

userInput = userInput.split("")

console.log(userInput)


var beformiddle = []
var aftermiddle = []


if (userInput.length % 2 === 0) {

    for (var i = 0; i < Math.floor(userInput.length/2); i++) {

        beformiddle.push(userInput[i])

    }

    console.log(beformiddle)

    for (var x = userInput.length-1; x > Math.floor((userInput.length/2)-1); x--) {

        aftermiddle.push(userInput[x])

    }

    console.log(aftermiddle)


    console.log(aftermiddle.join(""))
    console.log(beformiddle.join(""))

    if (aftermiddle.join("") === beformiddle.join("")) {

        console.log("eq")

    } else {

        console.log("not eq")

    }

} else {

    for (var i = 0; i < Math.floor(userInput.length/2); i++) {

        beformiddle.push(userInput[i])

    }

    console.log(beformiddle)

    for (var x = userInput.length-1; x > Math.floor((userInput.length/2)); x--) {

        aftermiddle.push(userInput[x])

    }

    console.log(aftermiddle)


    console.log(aftermiddle.join(""))
    console.log(beformiddle.join(""))

    if (aftermiddle.join("") === beformiddle.join("")) {

        console.log("eq")

    } else {

        console.log("not eq")

    }

}
```