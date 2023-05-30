# GenerateSyntaxTestAssertions

A Sublime Text plugin to generate syntax test assertions.

## Setup

**Pending availability in Package Control.**

Install [GenerateSyntaxTestAssertions](https://packagecontrol.io/packages/GenerateSyntaxTestAssertions) via Package Control.

## Commands

Command                          | Description
:--------------------------------| :----------
**GenerateSyntaxTestAssertions** | Generates syntax test assertions and inserts them at the cursor.

## Example

```php
<?php

declare(strict_types=1);
// ^^^^ embedding.php text.html.php meta.embedded.php source.php.embedded.html keyword.declaration.php
//     ^ embedding.php text.html.php meta.embedded.php source.php.embedded.html meta.group.php punctuation.section.group.begin.php
//      ^^^^^^^^^^^^ embedding.php text.html.php meta.embedded.php source.php.embedded.html meta.group.php constant.other.php
//                  ^ embedding.php text.html.php meta.embedded.php source.php.embedded.html meta.group.php keyword.operator.assignment.php
//                   ^ embedding.php text.html.php meta.embedded.php source.php.embedded.html meta.group.php meta.number.integer.decimal.php constant.numeric.value.php
//                    ^ embedding.php text.html.php meta.embedded.php source.php.embedded.html meta.group.php punctuation.section.group.end.php
//                     ^ embedding.php text.html.php meta.embedded.php source.php.embedded.html punctuation.terminator.statement.php
```

## License

Released under the [GPL-3.0-or-later License](LICENSE).
