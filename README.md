# Regex Tutorial

This is the tutorial that illustrating and explaning what is regex and how does it work. Example will be given with clear explanation.

## 📝**Summary**

Regex stands for Regeular Expression. It is the pattern for matching character and number combination in strings. Also it can be used in the validation such as email input validation. 

<br>
Regex is a case-sensitive language. The criteria must be strict when you use it to match the words. Below is the example to be illustraed in this tutorial

<br>

Example:
<br>

```
/^([a-z0-9_\.-]+) @([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

<br>




## 📂**Table of Contents**

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)


## **Regex Components**
There are 2 ways to create regex components which are using the pair of slash and pair of quotation. The examples are given below :

1. Using a pair of slash (//)
``` 
/[a-z0-9_\.-]/ 
```
2. Using a pair of quotation ('')
``` 
'ab+c'
```


### **Anchors**
There are 2 characters in anchor which are `^` and `$`. The `^` sign is to match the string that begins with specfic string or character. For instance,`^[a-z]` means match any string with the words start with a-z character. In contrast, `$[a-z]` means match any string with the words end with a-z character.



<br>

### **Quantifiers**
The quantifier is to constrain the number of the character. `{2,6}` is to constrain limit the string between 2 to 6 character length
<br>

### **Character Classes**
Character class is a set of characters that fulfill the input string. For example,`\d` matches any arabic numeral digit include `0-9`. 
<br>

### **Grouping and Capturing**
Grouping is to divide the string requirement to different parts. When it is using in the matching name, the name must be fully matched. Also, it can used to group different criteria together. `([a-z0-9_\.-]+)` means that the string must match within 0 to 9 and lowercase letter a to z. Also, it need to match `_\.-` and match the previous token between one and unlimited times. 
<br>

### **Bracket Expressions**
Bracket is used to express a range of characters such as `[a-z]`. `[a-z]` will match any alphabet between lowercase a to lowercase z letter. It can also write the form as `[abcdefghijklmnopqrstuvwxyz]` which is equiviliant as `[a-z]`.
<br>
<br>
## **Author**

I am Timothy Lau and I am a graduate of fullstack website developer. My GitHub repository and gist are linked below.

### GitHub Repository: https://github.com/timo9939/Assignment17

### Gist:https://gist.github.com/timo9939/a4c5fee7359011b8b8cdec3d435d16c5