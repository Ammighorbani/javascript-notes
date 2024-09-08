# Difference Between x++, ++x and x--, --x


### x++, ++x: 
**If we want to only add one unit to our variable both of them is correct.**

### x--, --x: 
**If we want to only remove one unit of our variable both of them is correct.**

### x++: 
**First read "x" and then add one unit to it.**

### ++x: 
**First add one unit to it and then read "x".**

### x--: 
**First read "x" and then remove one unit to it.**

### --x: 
**First remove one unit to it and then read "x".**

### Differente Part

### Example of x++:

**Inpute:**
```
var x = 0
console.log(x)
var y = x++
console.log(y)
```

**Output:**
```
x ==> 1
y ==> 0
```

### Example of ++x:

**Inpute:**
```
var x = 0
console.log(x)
var y = ++x
console.log(y)
```

**Output:**
```
x ==> 1
y ==> 1
```

### Example of x--:

**Inpute:**
```
var x = 0
console.log(x)
var y = x--
console.log(y)
```

**Output:**
```
x ==> -1
y ==> 0
```

### Example of --x:

**Inpute:**
```
var x = 0
console.log(x)
var y = --x
console.log(y)
```

**Output:**
```
x ==> -1
y ==> -1
```


<br>

### <a href="https://dev.to/somedood/the-difference-between-x-and-x-44dl" style="text-decoration: none;"> source </a>