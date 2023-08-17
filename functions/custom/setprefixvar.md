---
description: Sets the prefix variable (if exists)
---

# $setPrefixVar

### Usage

```php
$setPrefixVar[value;guildID?]
```

### Example

```javascript
client.command({
  name: "set-prefix",
  code: `
  Changed the prefix to '?'
  $setPrefixVar[?]
  `
});
```

#### Note: You'll need to add variable 'prefix' to your code before using this function to avoid errors!

<figure><img src="../../.gitbook/assets/prefixVar.png" alt=""><figcaption></figcaption></figure>
