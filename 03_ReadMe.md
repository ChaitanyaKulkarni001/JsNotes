# Arrays

1. slice just give that copied porion
   while spilice cut that portion from original array
```
origi = [1,2,3,4,5];
origi.spice(1,3)// 3 will not included
console.log(origi) >> No change
origi.splice(1,3)// 3 will included
console.log(origi) >> Changes as [1,5]
```

2. Array Concatination
```
let marvel = [ "Thor", "Ironman" , "CaptainAmerika"];
let dc = ["Superman", "Batman", "No More Heroes!"];

// all = marvel.join(dc);
all = marvel.concat(dc) // Don't affecct marvel
// all = marvel.concat(dc)
// all = [...marvel,...dc] // 
// all = marvel.push(dc)  // push affects marvel with []
console.log(marvel);  //  ... don't affect marvel
```

3.
```

let a = [1,2,3,4,5,6,7,[7,[4,8,3,[5]]]]
let b= a.flat(Infinity)
console.log('b',b);
a.isArray ->Boolean
a.from -> makes it an array
a.of -> makes array of diiferent values
```

## Objects

1. We can reference objects containts as . or []
2. 
```
const my = Symbol
let myObj = { 
    key : "value",
    [my] : "talab",
    name:"chaitanya"

// console.log(myObj[my]);
}
```

3. 
```
Object.freeze(myObj)
```
Now we can't change in myObj

4. We can also define an object as singleton
```
let singleTon = new Object();
```

5.  We concanite the objects as follows or by using spread operator (...)
```
const obj = Object.assign({},singleTon,nonSingleTon)
```

6. Object destructor
```
//  Object destructor
let ob = { 
    name : "Chaitanya",
    game : "GTA Sandries"
}

const {game : gta}=ob;
console.log(gta);
```

8. json : javaScript object Notation
9. #### functions can be called before writing defination but writing it and holdingg in a variable will  not allow this

10.  console.log(this) -- > current context
11. this in function will return undefined
12.  ### Arrow Function
```
arrw =()=>{
    console.log("Hello i am an arrow function!!!");
}
console.log(arrw);  // -> Function: arrw 
console.log(arrw());  // -> undefined
```
#### Implicit Return
13.  We don't have need to write a return in an implicit return 
```
let MUL = (num1,num2)=> (num1+num2);
```
#### Explicit Return
14. 
```
let add = (num1,num2)=>{
   return num1*num2;
}
```