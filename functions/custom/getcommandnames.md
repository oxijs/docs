# $getCommandNames

### Usage

```php
$getCommandNames[type?;separator?]
```

### Example

```javascript
client.command({
  name: "commandNames",
  code: `
  My commands are: $getCommandNames[default]
  `
});
```
