# Description

Clipboard functionality to copy a block of text from PDF and paste it with the new lines and hyphenated words stripped so that it is a clean paste of a block of text into the target area. 

Given that we do a lot of work between PDFs and Markdown in drafting of documents, it seemed necessary to work on the paste functionality a bit. 

The default keybinding is CTRL+ALT+V in Linux and Windows, CTRL+Super+V on OsX. To assign a new keybinding,

* Open ".../Packages/User/Default.sublime-keymap"
* The relevant command name is "paste_pdf"

```
, { "keys": ["ctrl+alt+v"], "command": "paste_pdf" }
```

# Installation

Install this repository via "Package Control" http://wbond.net/sublime_packages/package_control

# Source Code

https://github.com/compleatang/sublimetext-pastepdf