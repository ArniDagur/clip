# clip: A tool Unix users didn't know they wanted

* If stdin is a tty, spit clipboard contents to stdout.
* If stdin is not a tty, read contents of stdin to clipboard.

## Examples:
 * The command `{0} < text_file.txt` copies the contents of `text_file.txt` to the clipboard.
 * The command `{0} >> file.txt` appends the clipboard contents to `file.txt`.
