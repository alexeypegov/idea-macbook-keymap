# IntelliJ IDEA Second Keystroke Keymap

Some time ago I've made some changes in IDEA codebase to improve the usability of second keystrokes (i.e. pressing `Command+R` then `R` again). So I started to figure out a new keymap for the default Apple MacBook layout (with special feature keys instead of function `Fn` keys, etc).

Changes within the second keystrokes include:

- Popup for available second keystrokes (press `Command+R` and wait a moment)
- Ability to press the second key with the exact same modifier key as the first one (i.e. pressing `Command+R` then `Command+R` is exactly the same as `Command+R` then `R`)

## Mnemonic rules

I also like an idea of mnemonic rules, e.g. `Command+R` for Refactorings, `Command+F` for Find, `Command+N` for Navigation and so on (see `xml` file for full list of mappings).

## Installation

Copy `MacSekondKeystroke.xml` to `~/Library/Preferences/IntelliJIdeaXX/keymaps` where `XX` is IntelliJ IDEA version number, i.e. for IntelliJ IDEA 12 the path will be `~/Library/Preferences/IntelliJIdea12/keymaps`.

## Second Keystroke Help Popup

To enable second action popup you should go to Registy (by pressing `Command+Option+Shift+/`, choose **Registry**) and check **actionSystem.secondKeystrokeAutoPopupEnabled** 

![Refactor popup](http://dl.dropboxusercontent.com/s/d3wfibahnw3rc7m/2014-06-09%20at%2016.50%202x.png)

## Contacts

Any ideas or suggestions? Please mail me at iam@alexeypegov.com
