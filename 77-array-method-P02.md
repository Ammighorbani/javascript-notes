# "Array" methods Part 2

### isArray(): 
**This method will check our variable and if it's "Array" will say "true" if it's not will say "false".**

### Example:

**Input:**
```
var scores = [19,15,16,20]

console.log(Array.isArray(scores))
```

**Output:**
```
"true"
```

### indexof() : 
**This method will check our "Inpute" if it's in our "Array" it will give us that "Inpute" index if it's not it will say "-1".**

### Example:

**Input:**
```
var scores = [19,15,16,20]

console.log(scores.indexof(19))
```

**Output:**
```
0
```

### Note: 
**If we have more than one item of that "Inpute" this method will say the index of first one.**

### lastindexof(): 
**This method is look like "indexof()" method but this method will say the last "Input" item it found.**

### Example:

**Input:**
```
var scores = [19,15,16,20,19]

console.log(scores.lastindexof(19, ?))
```

**Output:**
```
4
```

### Note: 
**This method will receive two item one of them is "search for" and another one is "start index" and second one is optional item.**

### slice(): 
**This method is look like "splice()" method but they have a little diferente.**

### Example:

**Input:**
```
var scores = [19,15,16,20]

console.log(scores.slice(1, 3))
```

**Output:**
```
[15,16]
```

### Note: 
**This method will receive two parameter first one is "start index" and second one is "end index" and both of them are optional items.**

### Example:

**Input:**
```
var scores = [19,15,16,20]

console.log(scores.slice(1, ))
```

**Output:**
```
[15,16,20]
```

### Example:

**Input:**
```
var scores = [19,15,16,20]

console.log(scores.slice( ,2))
```

**Output:**
```
[19,15]
```

### Note: 
**"end index" wont be in our new "Array".**

### join(): 
**This method will join our "Array" items with the seperator we want.**

### Example:

**Input:**
```
var scores = [19,15,16,20]

console.log(scores.join("/"))
```

**Output:**
```
19/15/16/20
```

### reverse(): 
**This method will reverse all of our "Array" items and we don't need to write any "Inupt" for it.**

### Example:

**Input:**
```
var scores = [19,15,16,20]

console.log(scores.reverse())
```

**Output:**
```
[20,16,15,19]
```

### splite(): 
**This method will split our items.**

### Example:

**Input:**
```
var name = "Amin"

console.log(name.split(""))
```

**Output:**
```
["A", "m", "i", "n"]
```

### OR

### Example:

**Input:**
```
var name = "Amir/mahdi"

console.log(name.split("/"))
```

**Output:**
```
["Amir", "mahdi"]
```

### Note: 
**That seperator we enter in "Input" is mean if you see which item in our "String" data type create an other index and other item for us.**

### Note: 
**Differente between "join()" and "split()":**

### join() Example:

**Input:**
```
var Name = ["A", "m", "i", "n"]

console.log(Name.join(""))
```

**Output:**
```
Amin
```

### split() Example:

**Input:**
```
var Name = "Amin"

console.log(Name.split(""))
```

**Output:**
```
["A", "m", "i", "n"]
```

### "split()": 
**It will make some indexes equal with the orginal "String" data type lenght and that new "Array" items equal with the orginal same index of our "String" data type.**

### "join()": 
**It will make "String" data type of our "Array" of items and the new "String" data type indexex are equal with the orginal "Array" items.**