Syntax highlighting for cFos ml-files
=====================================

![alt text](http://www.xland.com.ua/github/cfos-ml-syntax_preview--v5.png "Syntax highlighting for cFos ml-files preview")

Simple yet effective Sublime Text and TextMate syntax highlighting for cFos ml-files

Installation
------------

### Sublime Text

#### Package Control

1. Make sure you already have [Package Control][1] installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows and Linux, `⇧+⌘+P` on Mac OS)
3. Select *cFos ml syntax* and press `Enter`

With [auto_upgrade][2] enabled, Package Control will keep all installed packages always up-to-date!

#### Manual Installation

1. Download `Syntaxes` folder
2. *Browse Packages* from the Command Palette (`Ctrl+Shift+P` on Windows and Linux, `⇧⌘P` on OS X)
3. Copy `Syntaxes` folder to `Packages\User`

### TextMate

*Note: cFos ml syntax wasn't tested in TextMate, but it should work as expected*

1. Download `.tmLanguage` files
2. Double-click it or drag and drop into TextMate

Usage
-----
* Use *.cfos.txt extension to make Sublime Text or TextMate open cFos ml-files with cFos ml-files syntax highlighting by default

or

* Enable it via `ctrl+shift+p` and typing `set syntax cfos ml-file`


### Unvalidated version

To activate unvalidated version (which doesn't highlight syntax errors with red)

* Call command promt (`ctrl+shift+p`)
* Start typing `set syntax cfos ml-file unvalidated`
* Press `Enter`


Notes
-----
Some themes do not have coloring for certain elemets. For example, Monokai Soda do not color entity elements, thus all escaping will be like plain text

[1]: http://wbond.net/sublime_packages/package_control/
[2]: http://wbond.net/sublime_packages/package_control/settings/
