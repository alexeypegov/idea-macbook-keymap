# IntelliJ IDEA Sekond Keystroke Keymap

Some time ago I made some changes in the IDEA codebase to improve the usability of second keystrokes (i.e. pressing Command+R then R again). So I started to figure out a new keymap for the default Apple MacBook layout (with special feature keys instead of function Fn keys, etc).

Changes within the second keystrokes include:

- Popup for available second keystrokes (press Command+R and wait a moment)
- Ability to press the second key with the exact same modifier key as the first one (i.e. pressing Command+R then Command+R is exactly the same as Command+R then R)

## Mnemonic rules

I also like an idea of mnemonic rules, e.g. Command+R is for Refactorings, Command+F is for Find, Command+N is for Navigation.

## Installation

Copy `MacSekondKeystroke.xml` to `~/Library/Preferences/IntelliJIdeaXX/keymaps` where `XX` is IntelliJ IDEA version number, i.e. for IntelliJ IDEA 12 the path will be `~/Library/Preferences/IntelliJIdea12/keymaps`.

To enable second action popup you should go to Registy (by pressing Command+Option+Shift+/, choose "Registry") and check "actionSystem.secondKeystrokeAutoPopupEnabled" 

## Contacts

Any ideas or suggestions? Please email me at iam@alexeypegov.com
