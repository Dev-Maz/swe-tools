+++
title = "Vim"
type = "chapter"
+++

Vim (vi improved) is a free and open-source, screen-based text editor program. It is an improved clone of Bill Joy's
vi. Vim's author, Bram Moolenaar, derived Vim from a port of the Stevie editor for Amiga and released a version
to the public in 1991. Vim is designed for use both from a command-line interface and as a standalone application
in a graphical user interface. Since its release for the Amiga, cross-platform development has made it available 
on many other systems. In 2018, it was voted the most popular editor amongst Linux Journal readers; in 2015 the 
Stack Overflow developer survey found it to be the third most popular text editor, and in 2019 the fifth most popular
development environment.

Like vi, Vim's interface is not based on menus or icons but on commands given in a text user interface; its GUI mode,
gVim, adds menus and toolbars for commonly used commands but the full functionality is still expressed through its
command line mode. Vi (and by extension Vim) tends to allow a typist to keep their fingers on the home row,
which can be an advantage for a touch typist.

Vim has a built-in tutorial for beginners called vimtutor, which is usually installed along with Vim, but is a separate
executable and can be run with a shell command. The Vim Users' Manual details Vim's features and can be read from 
within Vim, or found online.

Vim also has a built-in help facility (using the `:help` command) which allows users to query and navigate through
commands and features.

Like vi, vim supports multiple editing modes. Depending on the mode, typed characters are interpreted either as
sequences of commands or are inserted as text. In Vim there are 14 editing modes, 7 basic modes and 7 variants:

- Normal mode – used for editor commands. This is generally the default mode and by default hitting `ESC` returns the
editor to this mode.

- Insert mode – used for typing text in a way similar to most modern editors. In this mode, opened text in buffers
can be modified with the text entered from the keyboard.

- Visual mode – used to select areas of text. Commands can be run on the selected area – moving, editing, 
filtering via built-in or external command, etc.

- Visual linewise, a subtype of visual mode which selects one or more whole lines.

- Visual blockwise, another subtype which selects a rectangular block of text across one or more lines.

- Select mode – similar to visual, but the commands are not interpreted, instead, highlighted text is directly
replaced by input from the keyboard; similar to the selection mode used in editors on Microsoft Windows platforms.

- Command-line or Cmdline mode – provides a single line input at the bottom of the Vim window. Commands 
(beginning with `:`) and some other keys for specific actions (including pattern search and the filter command)
activate this mode. On completion of the command, Vim returns to the previous mode.

- Ex mode – accepts a sequence of commands.

- Terminal-Job mode – Interacting with a job in a terminal window.
