---
description: Power a number by another
---

# $pow

### Usage

```php
$pow[num1;num2]
```

### Example

```javascript
client.command({
  name: "pow",
  code: `
  2^2 = $pow[2;2]
  ` // Will return 4
});
```
