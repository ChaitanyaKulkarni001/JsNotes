### Some Basic Concepts from CAC 01
#### Some Strings related conversions

1. In JavaScript, there are six falsy values:
- 0
- NaN
- null
- undefined
- "": (empty string)
- false
Reamaing all are true

2. In javaScript conversion don't give error even though it is present 
```
a="abc5"
d=Number(a)
```
Here *output* is 
```
> d NaN  //  (Not a Number)
```

3. true => 1
    false =>0

4. if first is String than it will convert whole to String
```
console.log("1"+2+3)
>>> 123
```
if numbers are first then multiple numbers add to single then converted into string
```
console.log(2+3+"1");
>>> 51
```

5. 
```

console.log(+true)
>>> 1
console.log(+"")
>>> 0 // as false

```

6. Following will not assign 1 to num1 like other some languages
```
num1=num2=5
console.log(num1)
>>> 5

```
