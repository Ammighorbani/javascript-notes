# String Method Part-2

### Example of value:
```
var text = "I Love Javascript and React"
```

### slice():

**Input:**
```
console.log(text.slice(7,17))
```

**Output:**
```
Javascript
```

### Note: 
**First inpute of slice method is start index and second inpute of slice is end index.**

### Note: 
**"slice()" method only give index of our "String" and our method will get back to us one index before end index.**

### substr():

**Input:**
```
console.log(text.substr(7,10))
```

**Output:**
```
Javascript
```

### Note: 
**First inpute of "substr()" method is start index and second inpute is lenght of string and for example "Javascript" lenght is 10 and we say start from index 7 and go a head for 10 index.**

### substring() :

**Input:**
```
console.log(text.substring(7,17))
```

**Output:**
```
Javascript
```

### Note: 
**It's completely look like "slice()" method, first inpute of slice method is start index and second inpute is end index.**

### Difference between these three methods:

**"slice()" and "substring()" is completely similar but they have a little differente "slice()" if we tell him mines number it mean start of "String" but if in "substring()" we give him mines number it will change to zero.**
