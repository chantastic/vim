# Install the Latest Vim on a Mac with Homebrew

## Summary

The version of Vim that comes with your operating system is out of date.
You can find download instructions at vim.org for all platforms.
However, the easiest way to get the latest Vim on a mac is with Homebrew...

## Lesson

If you have a Vim installed, run `vim` to launch it. The version number is shown on the launch screen.

The version of vim that came with your operating system is probably out of date. As of this recording 8.2 is the latest.  
So I am behind.

You can leave vim by typing `:q<enter>`.

Visit [vim.org](https://www.vim.org/) to get download instructions specific to your platform.

On my Mac, I prefer [homebrew](https://brew.sh/) for managing software dependencies.

With brew installed, run `brew update && brew install vim`.

This can take several minutes.

Once installation is complete, run `vim` again and the version should have changed to the latest available.
(As of this recording that is 8.2.400)

If you don't see difference, try opening a new terminal tab and launching `vim` again. You Might need a fresh terminal instance to pick up the new version.

That's it.
That's how you install the latest version of Vim on a Mac, with Homebrew.
