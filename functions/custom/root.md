---
description: Solves the nth root of a number
---

# $root

### Usage

```php
$root[num1;num2?]
```

### Example

```javascript
client.command({
  name: "pow",
  code: `
  The cube root of 8 is equal to $root[8;3]
  ` // Function will return 2
});
```
