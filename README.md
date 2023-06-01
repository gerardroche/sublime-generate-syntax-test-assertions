# GenerateSyntaxTestAssertions

Generate Sublime Text syntax test assertions for the current cursor position.

## Installation

**Pending availability in Package Control.**

Install [GenerateSyntaxTestAssertions](https://packagecontrol.io/packages/GenerateSyntaxTestAssertions) via Package Control.

## Commands

Command                             | Description
:-----------------------------------| :----------
**Generate Syntax Test Assertions** | Generates syntax test assertions and inserts them at the cursor.

## Usage

Put your cursor on a line that you want to generate syntax test assertions for and run the
command.

**Command Palette → Generate Syntax Test Assertions**

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

The generator inserts test assertions for all points on the line. Adjust as needed. See [Sublime Text Syntax Definition Documentation](https://www.sublimetext.com/docs/syntax.html).

## License

Released under the [GPL-3.0-or-later License](LICENSE).
