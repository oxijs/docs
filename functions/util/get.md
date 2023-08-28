---
description: Gets the value of the key previously established using $let
---

# $get

### Usage

```php
$get[keyName]
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
