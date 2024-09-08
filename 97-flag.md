# Flag

### In programming we use "flags" to make our conditions base on our "flags".

### Example:

**Input:**
```
var userName = "babak"

var users = ["Amir", "mamad", "taghi"]

var isLogin = flase

for (var i = 0; i < users.lenght; i++) {

	if (users[i] === userName) {
		
		console.log("loged in before")
		isLogin = true

	}

	if (isLogin) {

		console.log("loged in before")			


	} else {

		console.log("not loged in before")			

	}

}
```

**Output:**
```
not loged in before
```