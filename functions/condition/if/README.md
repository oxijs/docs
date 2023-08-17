---
description: Execute a code block with condition.
---

# $if

### Usage

```php
$if[condition(s);true field;false field?]
```

#### Comparison Operators

* `==` — Equal to
* `!=` — Not equal to
* `>` — Greater than
* `<` — Less than
* `>=` — Greater than or equal to
* `<=` — Less than or equal to

#### Logical Operators

* `&&` — Logical and
* `||` — Logical or

## Example

```javascript
client.command({
  name: "if",
  code: `
  $if[1==;Worked!;\`undefined\` is not equal to 1.]
  `
// Empty means "undefined" (1 == undefined) is not returning true message.
});
```
