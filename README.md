# dotemacs
Repo for my dot emacs/spacemacs files

## Cheat sheet (Some commands could be Spacemacs specific)

* C-w Cut (kill)
* M-w Copy
* C-y Paste
* M-y cycle through killing ring, use it after C-y
* C-M-f Forward-sexp move to the closing parenthesis
* C-M-b Backford-sexp move to the open parenthesis
* C-h w {Command_name} to see the key binding of the given command
* C-h v describe variable's current value 
* more C-h commends here https://stackoverflow.com/a/965284                                                                              
* C-t swap two letters
* C-x C-t to swap two lines, swap the bottom line with the line above
* C-M-up-arrow/down-arrow move a line up and down, similar to vscode like editor, I think this is space macs specific thing, but it's good.
* SPC v -> (/[/{ to wrap visual selection with the brackets. One can also achieve the same in normal emacs by highlighting the text and type the desired brackets. (This might be the Spacemacs behavior, may need to type M-(/[/{ in vanilla emacs, need to verify)
* C-x g Magit status
* M-. Find definition at point. Super useful jumping around the code base. But need to have good language server support I think. Works great with Typescript, but not with Javascript :(
* SPC t E e Switch to holy mode from evil mode
* M-m t E e Switch to Hybrid mode from holy mode
* C-c RET open url in browser
* C-c $ to add a new word to dictionary
* C-x s Save all files
* C-x C-c: Exits Emacs
  Key Binding	Purpose
  Y or yes	Saves the file
  N or DEL	Skips current buffer
  q or RET	Aborts the save, continues with exit
  C-g	Aborts save and the exit
  !	Save all remaining buffers
  d	Diff the file on the file system
  with the one in the buffer
* C-x 0	Deletes the active window
C-x 1	Deletes other windows
C-x 2	Split window below
C-x 3	Split window right
C-x o	Switch active window
Key Binding	Purpose
C-x 4 C-f	Finds a file in the other window
C-x 4 d	Opens M-x dired in the other window
C-x 4 C-o	Displays a buffer in the other window
C-x 4 b	Switches the buffer in the other window
and makes it the active window
C-x 4 0	Kills the buffer and window

M-m	Moves point to the first non-whitespace
character on this line

M-x toggle-truncate-lines.

M-x subword-mode	Minor mode that treats CamelCase
as distinct words
M-x superword-mode	Minor mode that treats snake_case
as one word

M-x customize-option global-subword-mode
M-x customize-option global-superword-mode

C-M-f	Move forward by s-expression
C-M-b	Move backward by s-expression

C-M-d	Move down into a list
C-M-u	Move up out of a list
C-M-k for kill-sexp

C-M-n	Move forward to the next list
C-M-p	Move backward to the previous list

M-}	Move forward to end of paragraph
M-{	Move backward to start of paragraph

M-a	Move to beginning of sentence
M-e	Move to end of sentence

C-M-a	Move to beginning of defun
C-M-e	Move to end of defun

Key Binding	Purpose
C-v	Scroll down a near full screen
M-v	Scroll up a near full screen
C-M-v	Scroll down the other window
C-M-S-v	Scroll up the other window

For instance, if you type M-< to jump to the beginning of the buffer, you can type C-u C-<SPC> to go back.

C-x r m	Set a bookmark
C-x r l	List bookmarks
C-x r b	Jump to bookmark

M-h	Marks the next paragraph
C-x h	Marks the whole buffer
C-M-h	Marks the next defun
C-x C-p	Marks the next page
M-@	Marks the next word
C-M-<SPC> and	
C-M-@	Marks the next s-expression
C-<SPC>, C-g	Deactivates the region

C-M-s	Begins a regexp incremental search
C-M-r	Begins a regexp backward incremental

M-n	Move to next item in search history
M-p	Move to previous item in search history
C-M-i	“TAB”-complete search string against previous search ring

C-w	Add word at point to search string
C-M-y	Add character at point to search string
M-s C-e	Add rest of line at point to search
string (Emacs 24.4 or later)
C-y	Yank (“paste”) from clipboard
to search string (Emacs 24.4 or later)

M-s c	Toggles case-sensitivity
M-s r	Toggles regular-expression mode
M-s w	Toggles word mode
mystruct->foo = 42;
Searching for mystruct foo will match the element access above if you toggle word search with M-s w.
M-s _	Toggles symbol mode
M-s <SPC>	Toggles lax whitespace matching
M-s '	Toggles character folding
It’s quite neat: when you search for a Emacs will attempt to match characters like á or å;

M-s o	Occur mode
M-s o	Activate occur on current search string
inside Isearch

M-n, M-p	Go to next and previous occurrence
<, >	Go to beginning and end of buffer
g	Revert the buffer, refreshing the 
search results
q	Quits occur mode
e	Switches to occur edit mode
C-c C-c	Exits occur edit mode and
applies changes

M-g M-n	Jump to next “error”
M-g M-p	Jump to previous “error”

Multi-Occur

M-x multi-occur-in-matching-buffers takes a regular expression of buffers to match – for instance \.py$ to search all Python buffers
