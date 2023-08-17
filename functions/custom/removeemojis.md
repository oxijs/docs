---
description: Removes emojis from given text
---

# $removeEmojis

### Usage

```php
$removeEmojis[text]
```

### Example

```javascript
client.command({
  name: "removeEmojis",
  code: `
  $removeEmojis[Hello! 😄]
  ` // Will return 'Hello!' without '😄'
});
```
