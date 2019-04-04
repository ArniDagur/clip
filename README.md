# clip: A tool Unix users didn't know they wanted

* If stdin is a tty, spit clipboard contents to stdout.
* If stdin is not a tty, read contents of stdin to clipboard.

## Examples:
 * The command `clip` spits the contents of the clipboard to stdout.
 * The command `clip < text_file.txt` copies the contents of `text_file.txt` to the clipboard.
 * The command `clip >> file.txt` appends the clipboard contents to `file.txt`.
 * The command `clip | someotherprogram` pipes the contents of the clipboard to `someotherprogram`.
