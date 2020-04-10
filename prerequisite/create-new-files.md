## Create New files with the New Command

To create a new, empty file in Vim, use the `:new` command.
Type `:new` in normal mode and hit enter.

This command creates a new buffer in a new window.
Run the command `:buffers` to see this new, unsaved buffer.

Save this buffer to disk using the write command (`:w`) and providing a filename.

If you have a file open and run `:new`, Vim will create the new buffer in a horizontal split.

If you prefer vertical splits, use the `:vnew` command.
