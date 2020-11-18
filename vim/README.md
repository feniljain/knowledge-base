# VIM TIPS

## Videos:
	* http://derekwyatt.org/vim/tutorials/index.html
	* VimConf 2020: https://www.youtube.com/channel/UCPK_UHtbfcWABCi0F0GPG6w

## Blogs and Articles:
	* https://medium.com/actualize-network/how-to-learn-vim-a-four-week-plan-cd8b376a9b85
	* vimcasts.org/blog/2011/05/the-fugitive-series/
	* https://stackoverflow.com/questions/tagged/vim?tab=votes&pagesize=50
	* https://stackoverflow.com/questions/1218390/what-is-your-most-productive-shortcut-with-vim

## Websites:
	* http://vimcasts.org/

## Repos:
	* Interesting IDE: https://github.com/onivim/oni2

## General:
 * To encode ROT-13 on current line: g?? and on current word g?iw
 * % refers to the current file's relative path
 * %:p refers to the current file's absolute path
 * :r !ls reads the output of ls and copies in current open file
 * :nohlsearch, removes the highlighting of the current text
 * $ and g_ both can be used to move to the end of the line
 * %l: Current line
 * %L: Total lines
 * %F: File path compared to root dir of the project
 * %y gives file extension
 * Use this: `", just before leaving a buffer and the next time you enter, use this again to jump to last line where you left your cursor.
 * Shift $ : End of the line, Shift ^ : Start of the line

## StatusLine: 
* set statusline={content}
* Width and Padding in statusline:
	set statusline = [%4l] => Sets length of content of l register with constraint of 4 characters length (space is kept for empty places)
	set statusline = %04l => Sets length of content of l register with constraint of 4 characters length (0 is kept for empty places)
	set statusline = %.20l => Sets length of content of l register with constraint of 4 characters length (0 is kept for empty places)


## SEARCH:
* If you want to find the word below your cursor, instead of doing /(yourWord), use *, and it will do the same task.
* To get the current word under the cursor in /(currentWord), type /(Ctrl-r)(Ctrl-w)
* set ignorecase (or) \c & \C can be used with the search pattern itself, where the former is for case insensitive and vice versa for latter.
* After typing /, if you press C-F, it will show you the whole search history
* For replacing globally using s, use %s

## HORIZONTAL SPEED:
* f(character): jump on the first occurence starting with (character)
* t(character): jump just before the first occurence starting with (character)
* F(character): f->go forward F->go backward
* T(character): t->go forward T->go backward
* To repeat your command let's say "fe", i.e. go to first e, instead of doing "fe" everytime, use ";" after the first time,
* if you overshoot, use "," to come back.
* Combine these movements with y, e.g. "yt)", select till ).
* shift-d, delete rest of the line.
* shift-c, delete rest of the line and enter insert mode.
* shift-s, delete whole line and enter insert mode.
* ^, to move at the start of the line.

## Renaming a file:
* Type :Explore, go to the required file name, press R, rename the file and done!

## Auto-formatting by vim:
* Go to the text, type gqip, vim will auto format it in chunks of 80 charaters

## FUGITIVE (NOTE: fugitive affects both the git and vim buffers, so one can be assured of the changes and no side effects while deleting or moving files) :
* One git cycle: Type :Gstatus, use - to stage/unstage files, or on heading to stage/unstage all files. Type cc to commit, write the message and preferably use :x(short for :wq), and then use - again to push your files. For removing changes from a modified file from status window use, X.

* Want to blame or see who made a particular edit, use :Gblame.

* Want to revert to previous version, use :Gread

* Want to stage current file, use :Gwrite

* Want to rename current file, or move it, use :Gmove

* Want to delete a file, use :Gremove

## Exchanging Case:

* ~ can be used to change case of character under your cursor.
* g~w can be used to change case of next word.
* g~} can be used to change case of next paragraph.
* g~~ can be used to change case of entire line.

## SUBSTITUTING:

* After doing the :s/{word1}/{word2}, one can repeat it using &, or :s

## DELETING:
* Go to any part of the line and type ct{char}, char is the character till which you want to delete evrything, it ends user in insert mode.

## IDENTATION:
* Use gg=G to auto-indent lines

* help expand() -> line number under the cursor(one of it's uses).
* help system() -> Getting the ouput of running commands in cmd.
* help filename-modifiers -> Manipulating file names
* v:throwpoint, v:exception

## PANES:
* Use C-W-X

## PRESENTATIONS:
	* https://www.youtube.com/watch?v=GDa7hrbcCB8&feature=emb_logo
