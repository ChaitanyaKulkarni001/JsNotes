### Some Basic Concepts from CAC 00

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