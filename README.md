Toggle Symbol for Sublime Text 2/3
==================================

A plugin useful for ruby developers. It toggles single and double quoted words into symbols and string. Only changing quotations for a semi colon here.

    - :dude -> 'dude'
    - 'dude' -> "dude"
    - "dude" -> :dude


Install
-------

Clone this repo into 

    - OS X: ~/Library/Application Support/Sublime Text 2/Packages/
    - Windows: %APPDATA%/Sublime Text 2/Packages/
    - Linux: ~/.Sublime Text 2/Packages/

If you're using Sublime 3, make that 2 a 3 and Bob's your uncle.

Troubleshooting
---------------

The default keymapping for this plugin is "ctrl+shift+;". That requires an american keyboard layout to work. If you're not running an american keyboard, try changing that to something you use. "ctrl+shift+," might do the trick? Go to the menu Preferences -> Key Binding - User and add this to the hash.

    { "keys": ["ctrl+shift+,"], "command": "toggle_symbol" }

That should work.
