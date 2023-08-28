---
description: Execute a code block with condition.
---

# $if

### Usage

```php
$if[condition(s);true field;false field?]
```

### Example

```javascript
client.command({
  name: "if",
  code: `
  $if[1==;Worked!;\`undefined\` is not equal to 1.]
  `
// Empty means "undefined" (1 == undefined) is not returning true message.
});
```

_(See_ [_Operators_](../operators.md) _to understand how this function works)_
