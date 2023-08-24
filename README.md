# javascript-revision
This is javascript course

### Strings in javascript:
**String Methods**
#### 1. `Length` 
return the length of the string
``` js
const gameName = new String("sanjiv");
console.log(gameName.length); // 6
```
#### 2. `toUpperCase()` 
convert all strings to upper case
``` js
const gameName = new String("sanjiv");
console.log(gameName.toUpperCase()); // SANJIV
```

#### 3. `charAt()` 
take index as input and give tha value at index
``` js
const gameName = new String("sanjiv");
console.log(gameName.charAt(2)); // n
```

#### 4. `indexOf()` 
return the index of given string
``` js
const gameName = new String("sanjiv");
console.log(gameName.indexOf("n")); // 2
```

#### 5. `substring()` 
return the string from given start or end indexe
``` js
// substring(startIndex, endIndex)
const gameName = new String("sanjiv");
const newString = gameName.substring(0, 4);
console.log(newString); //sanj
```



