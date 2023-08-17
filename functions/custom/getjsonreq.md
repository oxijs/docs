---
description: Will retrieve the JSON previously set with $letJsonReq (if set)
---

# $getJsonReq

> It works similarly to $let and $get, but it's not the same. Don't confuse them!

## Usage

```php
$getJsonReq[varName;property?]
```

## Example

#### Using properties

```javascript
client.command({
  name: "jsonRequest",
  code: `
  $getJsonReq[factJson;fact]
  
  $letJsonReq[https://api.popcat.xyz/fact;factJson]
  ` // Will return just 'fact' property
})
```

#### Without using properties

```javascript
client.command({
  name: "jsonRequest",
  code: `
  $getJsonReq[factJson]
  
  $letJsonReq[https://api.popcat.xyz/fact;factJson]
  ` // Will return the entire JSON
})
```
