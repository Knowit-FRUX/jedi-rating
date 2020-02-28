# Rate my Jedi

## Functions in javascript 

### Function declarations

```javascript
function hello(what = "world") {
    return `Hello ${what}!`;
}
```

### Arrow functions 

Behåller värdet av `this` där den används. 

```javascript
const hello = (what = "world") => {
    return `Hello ${what}!`;
}
// or with implicit return 
const hello = (what = "world") => `Hello ${what}!`;
```

### Anonymous functions 

Praktiskt som callbacks. Namnge gärna för enklare debugging.

```
document.addEventListener("click", function handleClickEvent(event) {
    console.log(event.target);
});
```

## Datatyper 

* Array 
* Object 
* Number
* Boolean
* String
* Undefined
* Null
* Map (> ES6)
* Set (> ES6)
* and a few more 

## Array functions 

### map

### filter

### find 

### forEach

### for of 

### reduce 

## Conditionals 

```javascript
let a = maybeTrue ? 1 : 0;  // a will be true if maybeTrue is true 
let b = maybeTrue || 1;     // b will be 1 if maybeTrue is false
let c = maybeTrue && 1;     // c will be 1 when isTrue is true.
```

### Common pattern in react 

```
<JSXComponent>
    {isTrue && <p>Only render this text if <strong>isTrue</strong> is true</p>}
</JSXComponent>
```

- Datatyper
    - Map, filter, for, forEach

- UI som funktion av state
- Webpack / Babel / Create-react-app

