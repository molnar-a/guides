---
title: Useful Commands
---
## Saving
1. Press `Escape` to make sure you're in `normal mode`;
2. Type in `:w` ("w" stands for "write");
3. Press `Enter`.

## Exiting Vi, Vim, Nvim, Gvim
1. Press escape to get you into "normal" mode
2. To exit, type `:q` but if you made any changes in file Vim gives error code `E37` in this case:
- To save and exit, type `:wq`
- To ignore changes and exit, type `:q!`

**OR**
- Type `ZZ` in command mode (save and quit)
- Type `:x` in normal mode to quit and write, if there are any changes


## Bare minimum functionality
Most likely you'll find yourself in "normal" mode, it allows you to enter commands by pressing the colon `:` key.
To get here from other modes you can type `ctrl + c` or `escape`.


To edit text and move around in a familiar way press `i`, for "insert" mode.
Try to move around with the arrow keys in "insert" mode.
You can also move around in visual mode with the `h` , `j` , `k` , `l` keys.


Depending on the configuration, you may enter a file browser by typing and entering the command `:e .` in "normal" mode. The 'e' stands for edit, and the period for the file or directory.

## Pasting blocks of code
Very often you will find yourself looking for solutions to problems, and finding someone has written a block of code that does exactly what you want.
If you try to copy and paste the code directly into Vim you might find that the code is weirdly formatted or hasnt't been pasted correctly.
This is due to the fact that vim reads each character that you paste one after the other, meaning any key-combinations that activates a Vim shortcut will be executed and Vim will try (and fail) to automatically indent the pasted code.

To overcome this you can use Vim's **Paste mode** which you can activate by entering normal mode (press `escape` or `crtl + c`) and type `:set paste`, then press ENTER.
You are now in *paste* mode.
You can then enter insert mode with `i` and paste the block of text/code without any issues!
To return to regular Vim without paste mode you can enter normal mode (`escape` or `crtl + c`) and type `:set nopaste`, and press ENTER

## I Want to Learn Vim!
Start by pressing `escape` to check if you're in normal mode, press colon `:`, type `Tutor`, and press `enter`.

## Other Resources
- <a href='https://vimgolf.com/' target='_blank' rel='nofollow'>Vim Golf</a> - A good way to learn from doing vim challenges to get the lowest amount of keystrokes. You can see solutions submitted by others if you can't figure the challenge out.
- <a href='https://vim.rtorr.com/' target='_blank' rel='nofollow'>Vim cheat sheet </a>
- <a href='http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html' target='_blank' rel='nofollow'>Detailed tutorial </a>
- Read the rest of our Vim Guides to get a better understanding of this powerful editor.

