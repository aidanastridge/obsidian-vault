---
tags: javascript
---
Links: [[Javascript.canvas|Javascript]]
```javascript
// ||
true || false; // true
10 > 5 || 10 > 20; // true
false || false; // false
10 > 100 || 10 > 20; // false

//?
let price = 10.5;
let day = "Monday";
day === "Monday" ? price -= 1.5 : price += 1.5;

//else
const isTaskCompleted = false;
if (isTaskCompleted) {
  console.log('Task completed');
} else {
  console.log('Task incomplete');
}

// &&  
true && true; // true
1 > 2 && 2 > 1; // false
true && false; // false
4 === 4 && 3 > 1; // true

//switch  
const food = 'salad';
switch (food) {
case 'oyster':
console.log('The taste of the sea 🦪');
break;
case 'pizza':
console.log('A delicious pie 🍕');
break;
default:
console.log('Enjoy your meal');
}
//Prints: Enjoy your meal

//if
const isMailSent = true;
if (isMailSent) {
  console.log('Mail sent to recipient');
}

//!
let lateToWork = true;
let oppositeValue = !lateToWork;
console.log(oppositeValue);
// Prints: false

// Comparison
1 > 3       // false
3 > 1       // true
250 >= 250  // true
1 === 1     // true
1 === 2     // false
1 === '1'   // false

//else if
const size = 10;
if (size > 100) {
  console.log('Big');
} else if (size > 20) {
  console.log('Medium');
} else if (size > 4) {
  console.log('Small');
} else {
  console.log('Tiny');
}
// Print: Small
```


```python

```

