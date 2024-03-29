# _____ _JS Notes_ _____

1. console.table gives us a values in a table format
```
name = "Chaitanya";
age=20;
console.table([name,age])
```

2. Taking input from user in NodeJs
```
const readline = require('readline');
const rl = readline.createInterface({
    input: process.stdin,
    output: process.stdout
});

rl.question('What is your name? ', (name) => {
    console.log(`Hello, ${name}!`);
    rl.close();
});
```

3. Following code will execute even we have written in curely brackets
```
{
    console.log("hi")
}
```

4. Treat all js code as a newer version
```
"use Strict"; // treat all js code as a newer version
```
5. Type of null is object. It is considerd as a *bug* in javaScript
```
k=null;// standalone value
l=undefined;// standalone value
console.log(typeof(k)) // type of null is *object* and undefined is *undefined*
```


6. As we are not using js in Browser , Following will not work
```
// k=prompt("hello")
// alert("I am  not Working")
// print(k)
```
7. We will this discusee it in upcoming Readmi's
```
// Symbol => Unique
```


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
