## Save Files with the Write Command

To save a vim buffer to disk use the write command by typing `:write` in normal mode.

This is a common command can can be abbreviated `:w`.

If the buffer being saved has not yet been written to disk, you have to provide a filename.

Once you've done that, you can make further changes with `:w` alone.

The write command can be paired with the quit command (`:q`).
Type `:wq<enter>` to write changes to disk and quit vim in one motion.

If you have a file that is read-only, `:w` will prompt you to use the `!` option to override.

Type `:w!<enter>` to save over read-only files.
