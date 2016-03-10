SublimeMoveTabs
===============

A short plugin for [Sublime Text 2][1] that allows rearrangement of tabs/'views' with the keyboard.

Installation
============

Please use [Package Control](https://sublime.wbond.net/installation) to install this plugin. This will ensure that it will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command Palette](http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html) and type `install`. Among the commands you should see `Package Control: Install Package`. If that command is not highlighted, use the keyboard or mouse to select it. There will be a pause of a few seconds while Package Control fetches the list of available plugins.

2. When the plugin list appears, type `MoveT`. Among the entries you should see `MoveTab`. If that entry is not highlighted, use the keyboard or mouse to select it.

How to Use
==========

Add keybindings for `move_view_left` and `move_view_right` at **Preferences -> Key binding -> User** or **Command Palette : Preferences : Key Bindings - User**. My example bindings on OS X:

    // Enable tab rearrangement
    { "keys": ["ctrl+shift+pageup"], "command": "move_view_left" },
    { "keys": ["ctrl+shift+pagedown"], "command": "move_view_right" },


License
=======

SublimeSwitchViewInGroup is released under the MIT license.

Copyright (c) 2016 Adam Johnson <me@adamj.eu>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.




[1]: http://www.sublimetext.com/2
