---
description: Checks if a command exists or not
---

# $commandExists

### Usage

```php
$commandExists[name;type?]
```

### Example

```javascript
client.command({
  name: "check",
  code: `
  Does this command exist?: $commandExists[check;default]
  `
}); // Will return 'true'
```
