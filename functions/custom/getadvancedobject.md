---
description: >-
  Returns stringified JSON Object (or a specified property of it) by it's name
  previously established using $createAdvancedObject
---

# $getAdvancedObject

### Usage

```php
$getAdvancedObject[objName;property?;format?]
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
