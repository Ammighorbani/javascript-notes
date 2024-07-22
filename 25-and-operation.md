# "and" Operation: 

### "and" model ==> "&&"

### & : It's and mark

### Note: 
**"and" looking for only two "true" condition and if we don't have two "true" condition it won't go into our scope.**

### Example:

```
if (2+2 === 4 && 3+3 === 6) {
    alert("welcome")
} else if (2+2 === 6 && 3+3 === 2) {
    alert("bye")
}
```

### Note:
```
	"true", "true" ==> "true"

	"true", "false" ==> "false"

	"false", "false" ==> "false"
```

****

### !: bang mark

### Note: 
**We use bang mark to create a situation like a mines behind parentheses or if you read mathematic it's like to creating contrary to something.**

### Example: `-(x)`

### Example:
```
var myBool1 = true
alert(myBool1) ======> "true"
alert(!myBool1) =====> "false"
```

### Note: 
**If you use double bang "!" it will take the orginal format.**

### Eexample: 
```
var myBool1 = true
alert(myBool1) ======> "true"
alert(!myBool1) =====> "false"
alert(!!myBool1) =====> "true"
```


<br>

### <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND" style="text-decoration: none;"> source-1 </a>

### <a href="https://www.w3schools.com/js/js_bitwise.asp" style="text-decoration: none;"> source-2 </a>