#### comparison in datatype
1. 
```
console.log(null>0);
console.log(null==0);
console.log(null>=0);
>>> false
>>> false
>>> true
```

The reason is that equallity and greater than works differently
1 and 3 converts null as 0

2. For undefined these will always false
3. === checks datatypes also
4.  It automatically converts string to integer
```
console.log("2">1)
>>>true
```
5. 
```
const a =Symbol('1234');
const b =Symbol('1234');
console.log(a===b);
>>> false
console.log(typeof a);
>>> symbol
```

6. to call this we have to give ( ) 
```
const readme =function(){
    console.log('Hello World!');
    
}
```
7. For non primitive datatypes, refereance of same obj is assigned
```
let a= {
    nm="csk"
}
b=a
b.nm= "tcs"
c-log(a.nm)
>>>tcs
```
but for stack it sends copies

8. 
```
console.log(a.toUpperCase())
console.log(a.toLowerCase())
console.log(a.charAt(2))
console.log(a.indexOf('s'))
>>> CSK
>>> csk
>>> k
>>> 1
>>> {}
>>> aCSK
>>>rg
```

9. all functions can get as
```
a="Talab Talab";
console.log(a.__proto__)
b = a.subString(0,6);
b = a.slice(0,6);  
>>>Talab
```

For slice we can give negative values also

10. 
```
a.trim()
removes all extra spaces
a.replace('%20','-')
a.includes('csk')
>>>bolean
a.split('-')
```