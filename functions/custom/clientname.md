---
description: Returns your bot's username
---

# $clientName

## Usage

```php
$clientName
```

## Example

```javascript
client.command({
  name: "botName",
  code: `
  My name is: $clientName
  ` // Will return your bot's name.
})
```
