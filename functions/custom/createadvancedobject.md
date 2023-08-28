---
description: Creates an object with a name, can be used multiple times in your code
---

# $createAdvancedObject

### Usage

```php
$createAdvancedObject[name;{json}]
```

### Example

```javascript
client.command({
  name: "advancedObjects",
  code: `
  $getAdvancedObject[obj1]
  $getAdvancedObject[obj2;property]
  $createAdvancedObject[obj1;{"property": "Hello, world!"}]
  $createAdvancedObject[obj2;{"property": "Hello there"}]
  `
})
```
