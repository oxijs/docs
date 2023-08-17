---
description: An alternative way of using $if function
---

# Alternative $if

### How to enable it

Before typing your command's code you'll need to add this field:

```
$if: 'alt'
```

### Notice

This will enable 4 more functions, called `$else`, `$elseIf`, `$endElseIf` and `$endIf`

#### $elseIf

Useful if you want to add 2 or more conditions when using alternative `$if`

### Examples

* Without using `$elseIf`, `$endElseIf`

```javascript
client.command({
  name: "conditions",
  $if: "alt",
  code: `
  $if[2==1]
  2 equals 1!
  $else
  2 doesn't equal 1!
  $endIf
  `
});
```

* Using `$elseIf`, `$endElseIf`

```javascript
client.command({
  name: "conditions",
  $if: "alt",
  code: `
  $if[2==1]
  2 equals 1!
  $elseIf[1==1&&2!=1]
  1 equals 1 but 2 doesn't equal 1!
  $endElseIf
  $endIf
  `
});
```

_(See_ [_Logical Operators_](https://oxi.js.org/functions/condition/if#logical-operators) _for understanding the 2nd example)_
