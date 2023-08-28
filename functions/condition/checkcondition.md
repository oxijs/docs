---
description: Checks if the given condition is true or false
---

# $checkCondition

### Usage

```php
$checkCondition[condition]
```

## Example

```javascript
client.command({
  name: "condition",
  code: `Given condition: 1>2
  The given condition is $checkCondition[1>2]`
  // Returns 'false'
});
```

_(See_ [_Operators_](operators.md) _to understand how this function works)_
