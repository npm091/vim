* insert mode
    - \<C-a> move to home
    - \<C-e> move to end 
    - \<C-b> move to right 
    - \<C-f> move to left
    - \<C-u> delete before cursor
    - \<C-w> delete a word
    - \<C-d> shift indent to left
    - \<C-t> shift indent to  right
    - \<C-y> repeat the upper line
    - \<C-c> copy the cursor word (*)
    - \<C-r>(register) paste rgister content
    - \<C-r>=(express) calc express and paste the result
    - \<C-r>=Expand("%:p") current file path
    - \<C-s> save current text (*)
    - \<C-n> search candiates word
    - \<C-x>\<C-f> search the matched file path of cursor
    - \<C-x>\<C-y>\<C-e|y> scroll screen
    - \<Leader>c close the current tab
    - \<Leader>v paste the unnamed register

* normal mode 
    - C delete the line from the cursor to end
    - R change to insert mode as overwriting 
    - S delete the current line
    - \<C-s> save crrent text (*)
    - \<Leader>c close the current tab
    - \<Leader>f execute FZF
    - \<Leader>md display markdown preview
    - "(register)<cmd> copy to the register by cmd execute
    - v change to visual mode
    - K open man page for the word under cursor
    - V change to line visual mode
    - gf open the file of the cursor
    - gv change to vsual mode with the last selection
    - gx open the url of the cursor

* visual mode
    - v change to normal mode
    - o move cursor to another end

* command line mode
    - \<Shift>\<Right> shift word right
    - \<Shift>\<Left> shift word left
    - \<C-w> delete a word
    - \<C-u> delete by head
    - \<C-p> call a previous from history
    - \<C-n> call a next from history
    - r!{shell command} paste shell command result to cursor
    - w !bash execute current file content as bash script
    - terminal {shell} open terminal as bash

* help
    - help-summary  usage
    - index         index
    - quickref      quick references
    - ex-cmd-index  execute command
    - function-list function list
    - map-overview
    - usr_41
    - eval

* TIPS
    - TIP1  : repeat command dot "."
    - TIP2  : DRY (Don't Repeat Yourself)
        - A;\<ESC>, j., j., ... 
    - TIP3 : Insert a space the front of each word
        - f{char}, s{inputs}, ;, .
    - TIP4 : Execute, Repeat, and then revert
    - TIP5 : Search and Replace by manually
        - *, n, cw{word}
    - TIP6 : Repeat dot "."
    - TIP7,8 : give a break - back to normal mode
        - \<C-o> instead of \<CR>
    - TIP9 : operation to enable repeat
        - daw (delete a word)
    - TIP10,11 : Simpe calculate
        - {n}\<C-a>, {n}\<C-x>
    - TIP12 : Integrate and Govern
    - TIP13 : Simple edit in Insert mode
        - \<C-h>, \<C-w>, \<C-u>
    - TIP14 : Return to Normal mode
        - \<C-[>, \<C-o>zz
    - TIP15 : Paste text staying Insert Mode
        - \<C-r>{register}, \<C-r>\<C-p>{register}
    - TIP16 : Paste calculation result
        - \<C-r>={expression}
    - TIP17, 18: Input a character with code or digraph
        - \<C-v>{codes}, \<C-k>{char1}{char2}
    - TIP19 : Overwrite with replacing text
        - R{line}
    - TIP20 : Visual mode
        - \<C-g> Toggle Visual & Select mode
    - TIP21 : Definition of visual selecting area
        - v, V, \<C-v>, gv, o
    - TIP22 : Repeat a command with visual line mode

