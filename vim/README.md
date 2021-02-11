# VIM TIPS

## Cheatsheets:

- https://www.reddit.com/r/vim/comments/kq0sbd/a_quick_reference_was_made_for_vim_navigation/
- https://www.reddit.com/r/neovim/comments/lfvr3z/a_useful_vim_cheat_sheets/

## Videos:

- http://derekwyatt.org/vim/tutorials/index.html
- VimConf 2020: https://www.youtube.com/channel/UCPK_UHtbfcWABCi0F0GPG6w
- Making tech presentations in vim: https://www.youtube.com/watch?v=GDa7hrbcCB8&feature=emb_logo
- https://www.youtube.com/watch?v=_NUO4JEtkDw
- https://www.youtube.com/watch?v=wlR5gYd6um0
- https://www.youtube.com/watch?v=XA2WjJbmmoM
- VimSpector: https://www.youtube.com/watch?v=-AZUIL1rY3U&feature=youtu.be
- VimMarks: https://www.youtube.com/watch?v=o4x4jUcHJwk

## Blogs, Articles and threads:

- https://medium.com/actualize-network/how-to-learn-vim-a-four-week-plan-cd8b376a9b85
- http://vimcasts.org/blog/2011/05/the-fugitive-series/
- https://stackoverflow.com/questions/tagged/vim?tab=votes&pagesize=50
- https://stackoverflow.com/questions/1218390/what-is-your-most-productive-shortcut-with-vim
- Good resources for learning vimscript, lua, etc. https://www.reddit.com/r/neovim/comments/l1mne8/learning_vimscript_vs_lua/
- https://countvajhula.com/2021/01/21/vim-tip-of-the-day-a-series/
- Some really good tips: https://jdhao.github.io/2021/01/07/nifty_nvim_techniques_s9/
- Hardcore vanilla vim user views: https://gist.github.com/romainl/6b952db7a6138b48657ba0fbb9d65370
- https://www.mahmoudashraf.dev/blog/no-more-postman-just-curl-and-vim/
- https://nazarii.bardiuk.com/posts/vim-curl.html
- https://linuxhint.com/how_vim_buffers_work/
- Everything about vim buffers:https://vim.fandom.com/wiki/Buffers
- https://www.reddit.com/r/neovim/comments/lcqele/vscodelike_completion_icons/
- https://icyphox.sh/blog/nvim-lua/
- https://learnxinyminutes.com/docs/lua/
- https://github.com/nanotee/nvim-lua-guide

## Vimscript:

- Vimscript: https://devhints.io/vimscript
- https://github.com/nanotee/nvim-lua-guide
- https://learnvimscriptthehardway.stevelosh.com/
- https://stackoverflow.com/questions/3997078/how-to-paste-yanked-text-into-the-vim-command-line
- https://this-week-in-rust.org/blog/2021/02/03/this-week-in-rust-376/
- https://www.reddit.com/r/neovim/comments/lboe92/people_who_rewrote_their_initnvim_in_lua_was_it/

## Websites:

- http://vimcasts.org/
- https://danielmiessler.com/study/vim/
- https://openvim.com
- https://vim-adventures.com/
- https://vimcolorschemes.com/
- Vim statusline generator: https://tdaly.co.uk/projects/vim-statusline-generator/

## Repos:

- Interesting IDE: https://github.com/onivim/oni2
- https://github.com/iggredible/Learn-Vim
- Good cheatsheet about everything in vim: https://github.com/mhinz/vim-galore
- https://github.com/akrawchyk/awesome-vim

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

## Plugins:

- https://github.com/glacambre/firenvim
- https://github.com/tree-sitter/tree-sitter
- https://github.com/alexaandru/nvim-lspupdate
- https://github.com/andrmuel/vim-curl
- https://github.com/diepm/vim-rest-console
- https://github.com/alexaandru/nvim-lspupdate
- https://github.com/kkoomen/vim-doge
- https://github.com/skywind3000/asyncrun.extra
- https://github.com/kosayoda/nvim-lightbulb
- Merge branches and tags with fzf: https://github.com/stsewd/fzf-checkout.vim
- https://github.com/vimwiki/vimwiki
- https://github.com/ap/vim-buftabline
- https://github.com/mhinz/vim-signify
- https://github.com/onsails/lspkind-nvim
- https://github.com/glepnir/galaxyline.nvim

## VimRCs for reference:

- https://github.com/yunong/dotvim/blob/master/.vimrc#L199
- https://github.com/awesome-streamers/awesome-streamerrc/blob/master/TheAltF4Stream/init.vim
- https://github.com/petobens/dotfiles/blob/master/vim/init.vim
- https://github.com/kutsan/dotfiles/tree/master/.config/nvim
- https://github.com/awesome-streamers/awesome-streamerrc/blob/master/ThePrimeagen/init.vim
- https://github.com/awesome-streamers/awesome-streamerrc/blob/master/MelkeyDev/init.vim

