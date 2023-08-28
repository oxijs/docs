---
description: Allows you to assign a key to a value
---

# $let

### Usage

```php
$let[key;value]
```

### Example

```javascript
client.command({
  name: "cats",
  code: `
  Cats are $get[1] and $get[2]
  $let[1;cute]
  $let[2;funny] 
  `
});
```
