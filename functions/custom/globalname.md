---
description: Will return current user's global name (aka as display name), if any
---

# $globalName

### Usage

```php
$globalName[userID?]
```

### Example

```javascript
client.command({
  name: "globalName",
  code: `
  Your current global name is: $globalName
  `
});
```

**Notice**: If you don't have a global name set, this function will return your username instead.
