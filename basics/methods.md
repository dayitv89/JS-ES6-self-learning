# Functions / Methods in JS-ES6

### Define

- This all methods are the same. Even `let` and `var` are related to scope define, not related to definition of method.
[read more](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Method_definitions)

```JavaScript
function add1(a,b) {
  console.log(a + b);
};

let add2 = function(a,b) {
  console.log(a + b);
};

var add3 = (a,b) => {
  console.log(a + b);
};

add1(1,2); // 3
add2(1,2); // 3
add3(1,2); // 3
```
