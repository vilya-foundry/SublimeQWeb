# SublimeQWeb
Syntax highlighting and navigation for .qq files in Sublime Text 3

To install, copy `qweb.sublime-syntax` and `qweb.tmPreferences` into your user
packages directory.

You can find your user packages directory by opening Sublime Text 3, going to
the Preferences menu and choosing "Browse Packages...". This will open up a
file explorer at the relevant directory.

The `syntax_test_qweb.qq` file is for use when you're working on the syntax
definition. To use it, open the file in Sublime Text and invoke the "Build"
command (e.g. `Ctrl+B` on Windows). It will print the test results to Sublime
Text's console window, which you can open with `Ctrl+'`.

Useful references:
* [Syntax definition docs](https://www.sublimetext.com/docs/3/syntax.html)
* [Scope docs](https://www.sublimetext.com/docs/3/scope_naming.html)