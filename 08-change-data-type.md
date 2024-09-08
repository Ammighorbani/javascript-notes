# Change Data Type

### Change String data type to Number data type

### Example:
```
var userAge = "13"
var userNumberAge = Number(userAge)

alert(userNumberAge)
alert(typeof userNumberAge)
```

### Better way:
```
var userNumberAge = +userAge
```

### Note: 
**"+" is look like you write "Number(userAge)"**

### Note: 
**If we put something and that thing real type is String that thing never can't change to Number data type and if we try to do it we will get "NaN" error**

### NaN:
 **Meaning is "Not a Number"**

### Change Number data type to String data type:

```
var userStringAge = String(userAge)
```

### Change String data type to Boolean data type:

```
var booleanAge = Boolean("1")
```

### Importante Note:
 **All the numbers is "true" except zero(0) the zero number is "false"**

## true:
 **The "true" meaning is correct or it's real or it have a value and it's not empty**

## false: 
**The "false" meaning is incorrect or its not real or it have not a value and it's empty**

## Note: 
**If a string is empty it's "false" and if it isn't empty it's "true"**


<br>

### <a href="javascript.info/type-conversions" style="text-decoration: none;"> source </a>
