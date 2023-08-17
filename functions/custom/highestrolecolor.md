---
description: Will return user's highest role color (if any)
---

# $highestRoleColor

## Usage

```php
$highestRoleColor[userID?;guildID?]
```

## Example

{% code overflow="wrap" %}
```javascript
client.command({
  name: "highestRoleColor",
  code: `
  Your highest role color is $highestRoleColor
  ` // Will return, for example, '#ff0000' (red) or gray if you don't have any roles
})
```
{% endcode %}
