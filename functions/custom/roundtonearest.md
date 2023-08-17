---
description: Rounds a number to its nearest integer
---

# $roundToNearest

### Usage

```php
$roundToNearest[number]
```

### Example

```javascript
client.command({
  name: "round",
  code: `
  $roundToNearest[29340]
  ` // Will return 29000
});
```
