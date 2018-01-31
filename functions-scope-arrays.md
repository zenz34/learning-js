# Function

a block of reusable code

parameterized?

1 parameters

2 arguments

3 this for invocation

Best Practice for declaration:

Use expression / function literal notation

**no hoisting**

let multiply = function\(x, y\) {return x\*y;};

**Functions is an Object \( with Code block\)**

---

\|     \|     Object Filed

\|     \|

---

\|     \|    Code content

\|     \|

\_\_\_\_

![](/assets/function_in_memory.png)

return undefined if no return values

Usage for Functions

functions

methods

constructor

methods for calling functions

function\(\)

obj.method\(\)

obj constructor

apply\(\), call\(\)

```
when call f\(\) f.call\(\) is used internally
```









# Scope

Global Scope

outside of any function

visible everywhere in a js program

!!use it without declaring first - not allowed under 'strick' mode

    for \(x in list\)   need the "let" keyword for \(let x in list\)



var 

function scoped



const

immutable but

change object value is possible, change address is not.

const a = {par:3}

a.par = 4   //good

a = 3 // TypeErrof



Making object values const can be achieved by using freeze\(\)

Object.freeze\(a\);

a.par = 5; // TypeError





## Let

**not hoisted**



Deep copy vs shallow copy

deep copy:

duplicates, allocates new memory, creates new virables

A = B

change A will not effect B



shallow copy:

not allocate new memory, only copy reference

A = B

change A, B changes also

deep copy: simple data types \(number, string, Boolean\)

shallow copy: array, object, function



Arrays

not fixed size

individual element can be any type

can have gap inside  \[1,2, , 3\]

can have other type keys instead of int 0 - n.

\["a": 1, "b": 2\]



Manipulation

push pop for tail



shift unshift for head



map



filter

reduce





How to create a array object?

a1 = \[\];

a1 = new Array\(\_;





Interview:

var a2 = 2, b2 = c2 = 5;

same as

var a2 = 2;

var b2 = 5;

c2 = 5; // global!!









