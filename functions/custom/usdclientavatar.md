---
description: Returns your bot's avatar
---

# $clientAvatar

## Usage

```php
$clientAvatar
```

## Example

```javascript
client.command({
  name: "botAvatar",
  code: `
  My avatar is: $clientavatar
  ` // Will return your bot's avatar URL.
})
```
