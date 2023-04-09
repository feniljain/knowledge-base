<h2 align="center">VIM KB</h2>

## General:

- To encode ROT-13 on current line: g?? and on current word g?iw
- % refers to the current file's relative path
- %:p refers to the current file's absolute path
- :r !ls reads the output of ls and copies in current open file
- :nohlsearch, removes the highlighting of the current text
- $ and g\_ both can be used to move to the end of the line
- %l: Current line
- %L: Total lines
- %F: File path compared to root dir of the project
- %y gives file extension
- Use this: `", just before leaving a buffer and the next time you enter, use this again to jump to last line where you left your cursor.
- Shift $ : End of the line, Shift ^ : Start of the line
- H -> takes you to current visible screen's top and L -> bottom, M -> middle
- Press q: in normal mode to access command history
- guiw -> Convert word to lowercase, gUiw -> Convert word to uppercase
- Tryout: TOhtml -> awesome
- Type B in command mode and have a look at completions, try them out(u need fzf)
- SCROLLING: Scroll Down: C-E, C-D, C-F, Scroll Up: C-Y, C-U, C-B
- Use gO to get manpage outline
- use ga on any char to get its ascii code
- g< to open up last messages
- gU{action} uppercases everything acc. to action, actions eg.: i{ -> in curly brackets, iw -> in word
- gi jump back to last insert location
- g/{search text}/norm! {command}
- <Ctrl-W>= -> Make all splits equal
- ={action} -> auto-ident lines according to action, eg. actions can be i} -> in curly braces
- :dig -> use special characters
- Performing calculations in vim: in insert mode type <C+r>= and do the calculation
- Press o to get to the other end of selection
- 20% Split: :20 vsplit path/to/file
- Changelist cheatsheet:
    :changes – Show position of last 100 changes
    g; – Vim jumps to the last change you made
    g, – Vim jumps forward through the change list
- Use Ctrl-t to jump back from a go-to-definition, jumplist get's polluted so using this is very helpful
- z family of commands ->
    zz: bring cursor to center
- Use Ctrl-t to jump back from a go-to-definition, jumplist get's polluted so using this is very helpful
- z family of commands ->
    zz: bring current line to center
    zt: bring current line to top
    zb: bring current line to bottom
    z.: bring current line to center, and also reposition the cursor to the beginning of the line
    z+[Enter]: bring current line to top, and also reposition the cursor to the beginning of the line
    z-: bring current line to bottom, and also reposition the cursor to the beginning of the line
- :options. It has a listing of all the possible options, grouped into categories, each with their default value, current value and description. It's interactive - you can change values in real time and see the results.

## StatusLine:

- set statusline={content}
- Width and Padding in statusline:
  set statusline = [%4l] => Sets length of content of l register with constraint of 4 characters length (space is kept for empty places)
  set statusline = %04l => Sets length of content of l register with constraint of 4 characters length (0 is kept for empty places)
  set statusline = %.20l => Sets length of content of l register with constraint of 4 characters length (0 is kept for empty places)

## SEARCH:

- If you want to find the word below your cursor, instead of doing /(yourWord), use \*, and it will do the same task.
- To get the current word under the cursor in /(currentWord), type /(Ctrl-r)(Ctrl-w)
- set ignorecase (or) \c & \C can be used with the search pattern itself, where the former is for case insensitive and vice versa for latter.
- After typing /, if you press C-F, it will show you the whole search history
- For replacing globally using s, use %s
- Vim allows you to use any regex delimiter in your pattern substitution. No need to use / at all, try # instead: :s#/usr/local/bin#/usr/sbin#g

## HORIZONTAL SPEED:

- f(character): jump on the first occurence starting with (character)
- t(character): jump just before the first occurence starting with (character)
- F(character): f->go forward F->go backward
- T(character): t->go forward T->go backward
- To repeat your command let's say "fe", i.e. go to first e, instead of doing "fe" everytime, use ";" after the first time,
- if you overshoot, use "," to come back.
- Combine these movements with y, e.g. "yt)", select till ).
- shift-d, delete rest of the line.
- shift-c, delete rest of the line and enter insert mode.
- shift-s, delete whole line and enter insert mode.
- ^, to move at the start of the line.

## Renaming a file:

- Type :Explore, go to the required file name, press R, rename the file and done!

## Auto-formatting by vim:

- Go to the text, type gqip, vim will auto format it in chunks of 80 charaters

## FUGITIVE (NOTE: fugitive affects both git and vim buffers, so one can be assured of the changes and no side effects while deleting or moving files) :

- One git cycle: Type :Gstatus, use - to stage/unstage files, or on heading to stage/unstage all files. Type cc to commit, write the message and preferably use :x(short for :wq), and then use - again to push your files. For removing changes from a modified file from status window use, X.

- Blame or see who made a particular edit, use :Gblame.

- Revert to previous version, use :Gread

- Stage current file, use :Gwrite

- Rename current file, or move it, use :Gmove

- Delete a file, use :Gremove

## Exchanging Case:

- ~ can be used to change case of character under your cursor.
- g~w can be used to change case of next word.
- g~} can be used to change case of next paragraph.
- g~~ can be used to change case of entire line.

## SUBSTITUTING:

- After doing the :s/{word1}/{word2}, one can repeat it using &, or :s

## DELETING:

- Go to any part of the line and type ct{char}, char is the character till which you want to delete evrything, it ends user in insert mode.

## IDENTATION:

- Use gg=G to auto-indent lines

- help expand() -> line number under the cursor(one of it's uses).
- help system() -> Getting the ouput of running commands in cmd.
- help filename-modifiers -> Manipulating file names
- v:throwpoint, v:exception

## PANES:

- Use C-W-X for swapping panes
- Use C-w-h/j/k/l to move between panes
- C-W-s horizontal split
- C-W-v vertical split
- C-W-o only one window

## Coc:

- Use :OR to organize imports(only if supported by lang server)

## FZF:

- :FZF
- :Maps -> Shows all the mappings and search them easily
