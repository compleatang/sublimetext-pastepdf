Description
------------------

Clipboard functionality to copy a block of text from PDF and paste it with the new lines and hyphenated words stripped so that it is a clean paste of a block of text into the target area. 

Given that we do a lot of work between PDFs and Markdown in drafting of documents, it seemed necessary to work on the paste functionality a bit. 

To assign a new keybinding,

* The relevant command name is "paste_pdf"
* Open ".../Packages/User/Default.sublime-keymap"
* Append there:

```
, { "keys": ["ctrl+alt+v"], "command": "paste_pdf" }
```

Installation
------------------

Install this repository via "Package Control" http://wbond.net/sublime_packages/package_control
