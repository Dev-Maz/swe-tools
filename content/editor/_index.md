+++
title = "Code Editor"
type = "chapter"
+++

A source-code editor is a text editor program designed specifically for editing source code of computer programs. 
It may be a standalone application or it may be built into an integrated development environment (IDE).

Source-code editors have features specifically designed to simplify and speed up typing of source code, such as
syntax highlighting, indentation, autocomplete and brace matching functionality. These editors also provide
a convenient way to run a compiler, interpreter, debugger, or other program relevant for the software-development
process. So, while many text editors like Notepad can be used to edit source code, if they do not enhance, automate
or ease the editing of code, they are not source-code editors.

Structure editors are a different form of source-code editor, where instead of editing raw text, one manipulates
the code's structure, generally the abstract syntax tree. In this case features such as syntax highlighting,
validation, and code formatting are easily and efficiently implemented from the concrete syntax tree or abstract
syntax tree, but editing is often more rigid than free-form text. Structure editors also require extensive support
for each language, and thus are harder to extend to new languages than text editors, where basic support only 
requires supporting syntax highlighting or indentation. For this reason, strict structure editors are not popular
for source code editing, though some IDEs provide similar functionality.

A source-code editor can check syntax while code is being entered and immediately warn of syntax problems. 
A few source-code editors compress source code, typically converting common keywords into single-byte tokens,
removing unnecessary whitespace, and converting numbers to a binary form. Such tokenizing editors later 
uncompress the source code when viewing it, possibly prettyprinting it with consistent capitalization and spacing.
A few source-code editors do both.

The Language Server Protocol, first used in Microsoft's Visual Studio Code, allows for source code editors to 
implement an LSP client that can read syntax information about any language with a LSP server. 
This allows for source code editors to easily support more languages with syntax highlighting, refactoring, and 
reference finding. Many source code editors such as Neovim and Brackets have added a built-in LSP client while 
other editors such as Emacs, vim, and Sublime Text have support for an LSP Client via a separate plug-in.
