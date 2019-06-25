# Org-brain/Todo

![](https://raw.githubusercontent.com/bu6hunt3r/brain/master/brain.png)
- org-brain
- org-mode

Generally isnpecting output of `C-h b` (list bindings for current buffer)
should be useful. 

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
