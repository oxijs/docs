---
description: Will retrieve the JSON previously set with $letJsonReq (if set)
---

# $getJsonReq

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
  
  $letJsonReq[https://oxiapi.0xtag4.repl.co/json/fact;factJson]
  ` // Will return just 'fact' property
})
```

#### Without using properties

```javascript
client.command({
  name: "jsonRequest",
  code: `
  $getJsonReq[factJson]
  
  $letJsonReq[https://oxiapi.0xtag4.repl.co/json/fact;factJson]
  ` // Will return the entire JSON
})
```
