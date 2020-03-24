## Open Files from the Terminal

To open files in Vim right from the terminal.

Run `vim` but with a space and path to the file you'd like opened.

`vim path/to/file.ext`

This can also be done with multiple files, using more paths, separated by spaces.

`vim path/to/first.ext path/to/second.ext`

By default these files are inserted into Vim as buffers.
These buffers can be listed using the `:buffers` command or `:ls` for short.

If you prefer to see both files, they can be opened into splits. Using the `-o` flag reads both files into horizontal splits.

`vim path/to/first.ext path/to/second.ext -o`

Doing the same with `-O` flag reads both files into vertical splits.

`vim path/to/first.ext path/to/second.ext -O`

Finally, use the `-p` flag to read both files into tabs.

`vim path/to/first.ext path/to/second.ext -p`
