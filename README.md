# Inline SQL for PHP

**Inline SQL for PHP** is a Visual Studio Code extension that highlights SQL queries embedded in PHP strings. It uses the `/*sql*/` marker to identify and apply syntax highlighting to the content of the string, ensuring compatibility with other editors by not altering the internal text content.

## Features

- **SQL Syntax Highlighting**: Automatically detects SQL queries preceded by `/*sql*/` and applies syntax highlighting.
- **Compatibility with Other Editors**: The use of the `/*sql*/` comment does not interfere with syntax in other editors or IDEs.
- **Multiline String Support**: Works seamlessly with queries spread across multiple lines.

### Example

```php
$query = /*sql*/"
   SELECT * FROM table
";
```
Visual Studio Code will apply SQL syntax highlighting to the content of the string, improving readability and streamlining development.

### Installation

1. Open Visual Studio Code.
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on Mac).
3. Search for **Inline SQL for PHP**.
4. Click "Install."

### Feedback

Your feedback is invaluable! If you encounter any issues or have suggestions for improvements, please [report them](https://github.com/ericgomez/vscode-php-inline-sql/issues) here.

### License

This extension is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

Enjoy coding with **Inline SQL for PHP**! 🚀
