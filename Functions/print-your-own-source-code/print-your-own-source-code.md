# Self-Reading PHP Program

This PHP snippet prints its own source code.

### Functionality:
- **`file_get_contents(__FILE__)`**: Reads the content of the current PHP file.
- **`htmlentities()`**: Converts special characters to HTML entities for safe display.
- **`echo`**: Outputs the result within a `<pre>` tag to preserve formatting.

### Usage:
Displays the script's own code in the browser.