---
description: Returns an attachment's width (if any)
---

# $attachmentWidth

## Usage

```php
$attachmentWidth
```

## Example

```javascript
client.command({
  name: "attWidth",
  code: `
  Your attachment's width is: $attachmentWidth.
  `
});
```

#### Note: You'll need to obviously attach something, function currently only supports images.

<div align="left" data-full-width="false">

<figure><img src="../../.gitbook/assets/exAttWidth.png" alt=""><figcaption></figcaption></figure>

</div>
