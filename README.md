# Org-brain/Todo

![](https://raw.githubusercontent.com/bu6hunt3r/brain/master/brain.png)
- org-brain
- org-mode

Generally isnpecting output of `C-h b` (list bindings for current buffer)
should be useful. 

## General Editing
| Binding       |  Purpose                             |
| --------------|:-------------------------------------|
| `C-x C-f`         |    Find (open) a file            |
| `C-x C-s`         |    Save the buffer              |
| `C-x b`           |    Switch buffer                |
| `C-x k`           |    Kill (close) a buffer        |
| `C-x C-b`         |    Display all open buffers     |
| `C-x C-c`         |    Exits Emacs                  |
| `ESC ESC ESC`     |    Exits out of prompts        |
| `C-/`             |    Undo changes |

### Moving

| Binding       |  Purpose                             |
| --------------|:-------------------------------------|
| `<left>, ...`      | move by character in all four directions  |
| `C-<left>, ...`    | move byi word in all four directions  |
| `<insert>`         | Activates overwrite-mode |
| `<delete>`         | Deletes character after point |
| `<prior>, <next>`  | Up and down nearly page |
| `<home>,<end>`     | Beginning or end of line |
| `C-f`              | Move forward by character  |
| `C-b`              | Move backward by character |
| `C-p`              | Move to previous line      |
| `C-n`              | Move to next line          |
| `C-a`              |    Moves point to the beginning of the line |
| `C-e`              |    Moves point to the end of the line |
| `M-m`              |    Moves point to the first non-whitespace character on this line |
| `M-f`                |    Move forward by word  |
| `M-b`                |    Move backward by word |
| `C-M-d`                |   Move down into a list |
| `C-M-u`                |   Move up out of a list |
| `C-M-n`                |   Move forward to next list |
| `C-M-n`                |   Move backward to prevoius list |
| `M-}`                |   Move forward to end of paragraph |
| `M-{`                |   Move backward to start of paragraph |
| `M-a`                  |   Move to beginning of sentence |
| `M-e`                  |   Move to end of sentence       |
| `C-v`               |  Scroll down one page         |
| `M-v`               |  Scroll up one page           |
| `C-M-v`             |  Scroll down the other window |
| `C-M-S-v`           |  Scroll up the other window   |
| `C-x <`             |   Scroll left  |
| `C-<next>`          |   Scroll left  |
| `C-<prior>`         |   Scroll right |
| `C-x >`             |   Scroll right |

### Writing / Saving
* `C-x C-w`: Write buffer to file

### Exiting
* `C-x C-c`: Exits emacs
| Binding       |  Purpose                             |
| --------------|:-------------------------------------|
| `Y or yes`  | Saves the file   |
| `N or DEL`  | Skips current buffer |
| `q or RET`  | Aborts the save, cont, with exit |
| `C-q` | Aborts save and the exit |
| `!`  | Save all remaining buffers |
| `d`   | Diff the file on file system with one in buffer |

### Switch/Kill buffer
* `C-x b `: Switch buffer
* `C-x C-s`: Save buffer to file
* `C-x k`: Kill buffer

### Window management
| `C-x 0`    | Deletes the active window  |
| `C-x 1`    | Deletes other windows      |
| `C-x 2`    | Split window below         |
| `C-x 3`    | Split window right         |
| `C-x 5`    | Switch active window       |

## Keybindings org-mode
* `ALT+RET`: Create new headline
* `SHIFT+LEFT/RIGHT`: Toggle TODO status
* `ALT+LEFT/RIGHT`: Raise/Demote headline
* `SHIFT+ALT+LEFT/RIGHT`: Raise/Demote headline and children
* `C-c .`: Add date
* `C-c C-s`: Schedule item
* `C-u C-c .`: Add date and time
* `C-g`: Stop doing what you are trying to do, escape
* `C-c [`: Add document to the list of agenda files
* `C-c ]`: Remove document from the list of agenda files
* `M-x org-agend-*`: Show agenda
* `C-c C-o`: Open link at point
* `ALT+RET`: Create new list item within lists
* `ALT-UP/DOWN` will move items to top/bottom

## Structure editing
| Binding |  Command   |
| ------- |:-------------------------------------|
| `C-RET` 			 | (org-insert-heading-respect-content) | 
| `M-S-RET` 	 	 | 	(org-insert-todo-heading) |
| `C-S-RET`     	 | (org-insert-todo-heading-respect-content) |
| `TAB`     	 	 | (org-cycle) |
| `M-LEFT`      	 | (org-do-promote) |
| `M-RIGHT`     	 | (org-do-demote) |
| `M-S-LEFT`    	 | (org-promote-subtree) |
| `M-S-RIGHT`   	 | (org-demote-subtree) |
| `M-UP`     	  	 | (org-move-subtree-up) |
| `M-DOWN`      	 | (org-move-subtree-down) |
| `M-h`         	 | (org-mark-element) |
| `C-c @`       	 | (org-mark-subtree) |
| `C-c C-x C-w`	     | (org-cut-subtree) |
| `C-c C-x M-w`      | (org-copy-subtree) |
| `C-c C-x C-y`	     | (org-paste-subtree) |
| `C-y`     		 | (org-yank) |
| `C-c C-x c`        | (org-clone-subtree-with-time-shift) |
| `C-c C-w`     	 | (org-refile) |
| `C-c ^`     		 | (org-sort) |
| `C-x n s`     	 | (org-narrow-to-subtree) |
| `C-x n b`     	 | (org-narrow-to-block) |
| `C-x n w`     	 | (widen) |
| `C-c *`  		     | (org-toggle-heading) |

## Tables

| Binding |  Command   |
| ------- |:-------------------------------------|
| C-c C-c 		| (org-table-align) |
| TAB 			| (org-table-next-field) |
| C-c SPC 		| (org-table-blank-field) |
| S-TAB 		| (org-table-previous-field) |
| RET 			| (org-table-next-row) |
| M-a 			| (org-table-beginning-of-field) |
| M-e 			| (org-table-end-of-field) |

### Column and row editing

| Binding |  Command   |
| ------- |:-------------------------------------|
| M-LEFT 			| (org-table-move-column-left) |
| M-RIGHT 			| (org-table-move-column-right) |
| M-S-LEFT 			| (org-table-delete-column) |
| M-S-RIGHT 		| (org-table-insert-column) |
| M-UP 				| (org-table-move-row-up) |
| M-DOWN 			| (org-table-move-row-down) |
| M-S-UP 			| (org-table-kill-row) |
| M-S-DOWN 			| (org-table-insert-row) |
| C-c - 			| (org-table-insert-hline) |
| C-c RET 			| (org-table-hline-and-move) |
| C-c ^				| (org-table-sort-lines) |

### Regions
| Binding |  Command   |
| ------- |:-------------------------------------|
| C-c C-x M-w 		| (org-table-copy-region) |
| C-c C-x C-w 		| (org-table-cut-region) |
| C-c C-x C-y 		| (org-table-paste-rectangle) |
| M-RET 			| (org-table-wrap-region) |

### Calculations
| Binding |  Command   |
| ------- |:-------------------------------------|
| C-c + 			| (org-table-sum) |
| S-RET 			| (org-table-copy-down) |

## Tags in org-mode
* You can add tags by surrounding a word by :, e.g: `:urgent:`
* Search for tags by: `(org-tags-view)`

## Keybindings org- brain
* `o`: Open headline
* `TAB`: Collapse
* `l`: Add Resource
* `c`: Add child
* `d`: Delete entry
* `f`: Add friendship
* `g`: Revert buffer
* `h`: Add child headline
* `j`: Forward button
* `k`: Backward button
* `l`: Add resource
* `m`: Visualize mind map
* `n`: Pin
* `o`: Goto current
* `p`: Add parent
* `q`: Visualize quit
* `r`: Open resource

## Tips
* enabling `org-indent-mode` will automatically indent headlines/list items
