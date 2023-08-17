---
description: Returns your bot's usertag (if any)
---

# $clientTag

## Usage

```php
$clientTag
```

## Example

```javascript
client.command({
  name: "botName",
  code: `
  My userTag is: $clientTag
  ` // Will return your bot's userTag (if any).
});
```
