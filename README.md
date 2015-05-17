# Simplified Emmet plugin Atom editor

[Emmet](http://emmet.io) support for [Atom](http://atom.io).

### Manual installation

You can install the latest Emmet version manually from console:

```bash
cd ~/.atom/packages
git clone https://github.com/Yatoom/emmet-atom
cd emmet-atom
npm install
```

Then restart Atom editor.

## Features:

* Expand abbreviations by <kbd>shift-space</kbd>.
* Multiple cursor support: most [Emmet actions](http://docs.emmet.io/actions/) like Expand Abbreviation, Wrap with Abbreviation, Update Tag can run in multi-cursor mode.

## Shift-space key

Simplified Emmet expands abbreviations by shift-space key only for HTML, CSS, Sass/SCSS and LESS syntaxes. 

## Default Keybindings

You can change these Preferences > Emmet.

Command | Darwin | Linux/Windows
------- | ------ | -------------
Expand Abbreviation | <kbd>shift-s</kbd> or <kbd>shift</kbd> + <kbd>⌘</kbd> + <kbd>e</kbd> | <kbd>tab</kbd> or <kbd>ctrl</kbd> + <kbd>e</kbd>
