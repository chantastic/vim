## Create New files with the New Command

Create a new, empty file with the `:new` command in normal mode by typing `:new`.

This command creates a new buffer in a new window.
Run the command `:buffers` to see the new, unsaved buffer.

Save this buffer to disk using the write command (`:w`) and providing a filename.

If you have a file open and run `:new`, Vim will create the new buffer in a horizontal split.

If you prefer vertical splits, use the `:vnew` command.
