# Defaulte func inpute

### We can change defaulte inpute of our functions.

### syntax:
```
function showresault (num1, num2) {
	if (num1 == undifiend) {
		num1 = 1
	}
	
	
	if (num2 == undifiend) {
		num2 = 2
	}

	alert(num1+num2)
}

showresault()
```

### Note: 
**If we don't enter any number or any value in calling function parentheses it will get that value from our codes**

### Note:

**this isn't a correct way to set default value for our function inputes**

### Best way:
```
function showresault (num1 = 1, num2 = 2) {
	alert(num1+num2)
}

showresault()
```

<br>

### <a href="javascript.info/function-basics#default-values" style="text-decoration: none;"> source </a>