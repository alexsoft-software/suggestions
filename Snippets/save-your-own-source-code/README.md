# PHP Self-Reading Script with File Output

This PHP snippet reads its own source code and saves it to a text file.

### Functionality:
- **`file_get_contents(__FILE__)`**: Reads the content of the current PHP file.
- **`file_put_contents('output.txt', ...)`**: Writes the source code to a file named `output.txt`.

### Usage:
Run the script on a PHP-enabled server. It creates or overwrites `output.txt` with the script's source code.

### Notes:
- Ensure the script has write permissions in the directory to create `output.txt`.
- Use with caution, as it overwrites `output.txt` without warning.

### Example Output:
The content of `output.txt` will be:
```php
<?php
file_put_contents('output.txt', file_get_contents(__FILE__));
?>
```