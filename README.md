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
* C-t swap two letters
* C-x C-t to swap two lines, swap the bottom line with the line above
* C-M-up-arrow/down-arrow move a line up and down, similar to vscode like editor, I think this is space macs specific thing, but it's good.
* C-x C-f toggle function bodies, show {...} for a function body when collapse
* SPC v -> (/[/{ to wrap visual selection with the brackets. One can also achieve the same in normal emacs by highlighting the text and type the desired brackets. (This might be the Spacemacs behavior, may need to type M-(/[/{ in vanilla emacs, need to verify)
* C-x g Magit status
* M-. Find definition at point. Super useful jumping around the code base. But need to have good language server support I think. Works great with Typescript, but not with Javascript :(
* SPC t E e Switch to holy mode from evil mode
* M-m t E e Switch to Hybrid mode from holy mode
