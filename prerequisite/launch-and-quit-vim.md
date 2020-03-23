## Launch and Quit Vim

## Summary

Quitting Vim is something that thousands of developers struggle with every day. Fortunately, for the astute, Vim tells us how to quit right on the launch screen.

Quitting Vim requires a mindset shift. Where most editors open in a persistent insert mode, Vim defaults default mode is different. It's known as normal mode and it allows you to type commands. Quit is one of those commands...

## Lesson

To launch Vim in a terminal, type `vim` (the name of the program) and hit `<Enter>`.

Opening Vim like this shows you a launch screen with important information: how to get help and how to quit.

Unlike traditional editors — which only have an insert mode — Vim's default mode lets you issue commands.

So you exit vim by typing a command.
Type `:q<Enter>`.

This shift can be very disorienting at first, when you're used to always being in a mode like Vim's insert mode — which allows you to type.

If you want to quit and forget the command, hit `<ctrl> c`, which is a commonly used command to halting terminal programs.

This won't quit but it will prompt you with details on how to quit.

Vim will remind use `:qa<Enter>`. This command is is like `:q<Enter>` but will prompt if there are any open files with uncommitted changes.

If you have uncommitted changes that you want to discard, use `:q!<Enter>` to force quit.

That's it.
That's how you launch and quit Vim.
