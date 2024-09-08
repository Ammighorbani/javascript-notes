# String Method Part-1

### Note: 
**Methods are functions but they will do some important thing on our objects and they have important target.**

### Give the letter with index:

```
console.log(text[0])
```

### Better way:

### CharAt() :
```
console.log(text.CharAt(0))
```

### Note: 
**This function will receive the index.**

### CharCodeAt() :

```
console.log(text.CharCodeAt(0))
```

### Note: 
**This method will receive index either but it won't give back us the letter it will give back the Ascii code of our letter.**

### Ascii: 
**"Ascii" is a table of all characters in english and each character have a unique Ascii code.**

### Note: 
**Capital letters Ascii code is different of small letters Ascii code.**

### concat() :
```
console.log(text.concat(" & React"))
```

### Note: 
**Before this method we used "+" to concat letters but now we must to use this method to concat letters to getter.**

### trim() :
```
console.log(text.trim())
```

### Note: 
**"trim()" will remove all first space before first letter and all last space after last letter.**


### toLowercase():
```
console.log(text.toLowercase())
```

### Note: 
**"toLowercase()" method will change all capital or small letters to lower case letters.**

### toUppercase():
```
console.log(text.toUppercase())
```

### Note: 
**"toUppercase()" method will change all capital or small letters to upper case letters.**

### serch() :
```
console.log(text.search("Java"))
```

### Note: 
**This method will check is our method inpute is in our String or not and if is in it will get back that word starting index to us.**

### Note: 
**If that word isn't in our String we will receive "-1" and it's mean we don't have it in our String.**

### indexof() :
```
console.log(text.indexof("Java"))
```

### Note: 
**"search()" method will search for regular expression or "regex" of that word but "indexof()" method will search for that word in String.**