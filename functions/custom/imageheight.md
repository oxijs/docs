---
description: Returns an image's height
---

# $imageHeight

### Usage

```php
$imageHeight[url]
```

### Example

{% code overflow="wrap" %}
```javascript
client.command({
  name: "imageHeight",
  code: `
$imageHeight[https://media.discordapp.net/attachments/1026680546513928265/1137058090982850651/Logo.png]
  ` // Will return 351
});
```
{% endcode %}
