---
description: Returns current discord.js version
---

# $djsVersion

## Usage

```php
$djsVersion
```

## Example

```javascript
client.command({
  name: "djsVersion",
  code: `
  Currently using discord.js $djsVersion
  ` // Will return: 'Currently using discord.js 13.16.0'
});
```
