# bash-shortcuts

This is just a curated list of shortcuts that I find useful.
Mostly copied from the bash manpage.

## Sources

READLINE section from the bash manpage

## Shortcuts

M == Meta

- M-b - Move back to the start of the current or previous word.  Words are composed of alphanumeric characters (letters and digits).
- M-f - Move forward to the end of the next word.  Words are composed of alphanumeric characters (letters and digits).

- C-r - Search backward starting at the current line and moving `up' through the history as necessary.  This is
an incremental search.
- C-s - Search forward starting at the current line and moving `down' through the history as necessary.  This is
 an incremental search.

- M-u - Uppercase the current (or following) word.  With a negative argument, uppercase the previous word, but d
o not move point.
- M-l - Lowercase the current (or following) word.  With a negative argument, lowercase the previous word, but do not move point.
- M-c - Capitalize the current (or following) word.  With a negative argument, capitalize the previous word, but do not move point.

- C-k - Kill the text from point to the end of the line.
- C-u - Kill backward from point to the beginning of the line.  The killed  text  is  saved  on  the kill-ring.

- C-w - Kill the word behind point, using white space as a word boundary.  The killed text is  saved on the kill-ring.

- M-? - List the possible completions of the text before point.
- M-# - The value of the readline comment-begin variable is inserted at the beginning of the current line.
