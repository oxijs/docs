---
description: Makes a JSON request and sets the data for $getJsonReq
---

# $letJsonReq

> It works similarly to $let, but it's not the same. Don't confuse them!

## Usage

```php
$letJsonReq[URL;varName]
```

## Example (using $getJsonReq)

#### Using properties

```javascript
client.command({
  name: "jsonRequest",
  code: `
  $getJsonReq[factJson;fact]
  
  $letJsonReq[https://api.popcat.xyz/fact;factJson]
  ` // Will return just 'fact' property
}),
```

#### Without using properties

```javascript
client.command({
  name: "jsonRequest",
  code: `
  $getJsonReq[factJson]
  
  $letJsonReq[https://api.popcat.xyz/fact;factJson]
  ` // Will return the entire JSON
});
```
