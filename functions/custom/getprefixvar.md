---
description: Returns current prefix variable (if it exists)
---

# $getPrefixVar

## Usage

```php
$getPrefixVar
```

## Example

```javascript
client.command({
  name: "prefix",
  code: `
  Current prefix is: $getPrefixVar
  ` // Will return, for example, '!'
})
```

#### Note: You'll need to add variable 'prefix' to your code before using this function to avoid errors!

<div align="left" data-full-width="true">

<figure><img src="../../.gitbook/assets/prefixVar.png" alt=""><figcaption></figcaption></figure>

</div>
