# "Anonymous" and "IIFE" function

### "Anonymous" function:

### Example:
```
var users = [

	{id: 1, name: "amir"},
	{id: 2, name: "mamad"},
	{id: 3, name: "amin"},
	{id: 4, name: "babak"},

]

var findUser = users.filter(function (user) {

	return user.id === 10

})
```

### Note: 
**In this method we never choose a name for our function is in our method.**

### "IIFE" function: (Immediately Invoked Function Expression)

### Example:
```
(function () {
	alert("salam")
})()
```

### Note: 
**In this method we created a function if we run our codes this function and codes in it will run without any condition.**

### Note: 
**When we want to run something without any condition or input or something like this we use of this method.**



<br>

### <a href="https://developer.mozilla.org/en-US/docs/Glossary/IIFE" style="text-decoration: none;"> source </a>
