Description
------------------

Provides handy clipboard commands without keybindings.

To assign a new keybinding,

* look for the command name into "Commands.sublime-commands"
* Open ".../Packages/User/Default.sublime-keymap"
* Append there, for example for "paste as plain text":

```
, { "keys": ["ctrl+alt+v"], "command": "clipboard_commands_paste_plain_text" }
```

Installation
------------------

Install this repository via "Package Control" http://wbond.net/sublime_packages/package_control

Source-code
------------------

https://github.com/SublimeText/ClipboardCommands