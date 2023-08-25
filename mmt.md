## React

- Basics of React, Virtual DOM, etc.
- Latest React version and updates
- React hooks and examples
- Angular vs React which one to choose?

## Browser
- What is CORS?
- How to set CORS on the client or server side
- diff CORS MODE?
- How to handle and avoid CORS errors
- Where are cookies stored, and what is the purpose of cookies?
- different cookie properties like HTTPOnly, Secure, etc. (You can find all properties in the - application tab.)
- How to pass cookies in an API call, and how can I pass all cookies at once in a request?
- What if we manipulate cookies and change the domain name?
- Chrome Browser Latest feature 
- when we click on link & open new instance of chrome can we transfer current session info to new window? (Latest chrome feature)

## Javascript
- Hoisting behavior
- code snippets
```js
console.log('start');
const promise1 = new Promise((resolve, reject) => {
console.log(1)
})
console.log('end');
```

```js
function parent() {
    var hoisted = "I'm a variable";
    function hoisted() {
      return "I'm a function";
     }
    return hoisted();
}
console.log(parent());
```

```js
function foo() {
  var bar = function() {
    return 3;
  };
  return bar();
  var bar = function() {
    return 8;
  };
}
console.log(foo())
```


