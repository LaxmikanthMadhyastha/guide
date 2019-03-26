---
title: Return Early Pattern for Functions
---
## Return Early Pattern for Functions
There can be multiple solutions and below is one among them

```javascript
function abTest(a, b) {
  if(a < 0 || b< 0)
  return undefined; //any code below this line won't be executed since there is a return statement
  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}
abTest(2,2);
```

