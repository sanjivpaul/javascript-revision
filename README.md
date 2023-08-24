# javascript-revision
This is javascript course

### **Strings in javascript(methods)**:

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
return the string from given start or end indexes
``` js
// substring(startIndex, endIndex);
const gameName = new String("sanjiv");
const newString = gameName.substring(0, 4);
console.log(newString); //sanj
```

#### 6. `slice()` 
return the string from given start or end index and negative slicing is possible
``` js
// slice(startIndex, endIndex);
const gameName = new String("sanjiv");
const newStringOne = gameName.slice(0, 4); // => negative slicing is possible
console.log(newStringOne); //sanj
```

#### 7. `trim()` 
trim remove extra spaces from string
``` js
const instaName = "   paulsanjiv  ";
const newStringTwo = instaName.trim(); // => it remove extra spaces
console.log(instaName); //   paulsanjiv  
console.log(newStringTwo); //paulsanjiv
```

#### 8. `replace()` 
replace take two parameters pattern or replacement. replace search pattern in string if pattern is match then it will replace with replacement value.
``` js
// replace(pattern, replacement);
// replaceAll();
const url = "https://sanjivpaul.com/sanjiv%20events";
console.log(url.replace("%20", "-")); //https://sanjivpaul.com/sanjiv-events
```

#### 9. `includes()` 
Includes take a value if value is present in the string then it return true if not present then return false. Basically includes search in the string and retrun a boolean value.
``` js
const url = "https://sanjivpaul.com/sanjiv%20events";

console.log(url.includes("sanjiv")); //true
console.log(url.includes("dev")); //false
```

#### 10. `split()` 
split method take pattern as input after split it returns a array of divide substring.

``` js
const words = "sanjiv-paul-is-a-good-dev"
console.log(words.split("-")); 
//[ 'sanjiv', 'paul', 'is', 'a', 'good', 'dev' ] => splited and created as array of substrings
```



