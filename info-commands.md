# GNU Info commands

A node contains text describing a specific topic at a specific level of detail.
The mode line at the bottom `(info)Help` says that this is node ‘Help’ in the file ‘info’.
The top line of a node is its “header”. The header `Next: Help-P,  Prev: Help-Small-Screen,  Up: Getting Started` 
says that the ‘Next’ node after this one is the node called ‘Help-P’. Below the header line is node's topic or title. 

## Basic commands

Description | Command
--- | ---
Move forward: scroll down or go to the next node | `SPC`
Move backward: scroll up or go to the prev node | `Del` or `Backspace`
Scroll down the current node | `PageDown`
Scroll up the current node | `PageUp`
Go to the beginning of the node | `b`, `Home`
Go to the end of the node | `End`
Redraw the screen | `Ctrl-l`
**List commands** | `H` or `?`
Next (sub)node | `]`
Prev (sub)node | `[`
Next node (on the same level) | `n`
Prev node (on the same level) | `p`
Parent node | `u`
Choose the menu item | `m`
Choose the cross reference | `f`
Cancel the command | `Ctrl-g`
Move between menu items or cross references | `Tab`, `Shift-Tab` or `Alt-Tab`

## Menu
The beginning of a menu is always identified by a line which starts with `* Menu:`.
After the start of the menu, each line that starts with a `*` identifies one subtopic.
The line usually contains a brief name for the subtopic (followed by a ‘:’, normally hidden in Emacs),
the name of the node that talks about that subtopic (again, normally hidden in Emacs),
and optionally some further description of the subtopic.
Here is an example:

    * Foo:  Node about FOO.      This tells about FOO.

The subtopic name is 'Foo', the node describing it is 'Node about FOO', and the description is 'This tells about FOO'.

## Cross references
Cross references look like this: `*Note Cross: Help-Cross.`  That text is a real, live cross reference,
whose name is ‘Cross’ and which points to the node named ‘Help-Cross’.

Sometimes a cross reference (or a node) can lead to another file (in other words another "manual").
Such a cross reference looks like this: `*Note Overview of Texinfo: (texinfo)Top.`
Here the name ‘texinfo’ between parentheses refers to the file name. This file name appears in cross
references and node names if it differs from the current file, so you
can always know that you are going to be switching to another manual and
which one.
