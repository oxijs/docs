---
description: This will return the automod rules of the current guild (if any)
---

# $getGuildAutomodNames

## Usage

```php
$getGuildAutomodNames[guildID?]
```

## Example

```javascript
client.command({
    name: 'getGuildAutomodNames',
    code: `
    $getGuildAutomodNames[$guildID]
    `
});
```
