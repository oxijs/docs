---
description: Returns an attachment's height (if any)
---

# $attachmentHeight

### Usage

```php
$attachmentHeight
```

### Example

```javascript
client.command({
  name: "attHeight",
  code: `
  Your attachment's height is: $attachmentHeight.
  `
});
```

#### Note: You'll need to obviously attach something, function currently only supports images.

<div align="left" data-full-width="false">

<figure><img src="../../.gitbook/assets/exAttHeight.png" alt=""><figcaption></figcaption></figure>

</div>
