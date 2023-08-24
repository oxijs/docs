---
description: Allows you to use multiple $replaceText in 1 function
---

# $advancedReplaceText

### Usage

```php
$advancedTextSplit[original text;word1:replacement1,word2:replacement2,etc:etc]
```

### Example

```javascript
client.command({
  name: "replaceText",
  code: `
  $advancedReplaceText[Hello, amazing community!;amazing:beautiful,community:people]
  `
}); // Will return 'Hello, beautiful people!'
```
