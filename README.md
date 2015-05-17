# Simplified Emmet plugin Atom editor

[Emmet](http://emmet.io) support for [Atom](http://atom.io). This is a fork of the emmet package, and has one key-binding, and one key-binding ony: the <kbd>shift-space</kbd> key for emmet expanding. This solves all keybinding conflicts with the Atom Core, such as the <kbd>ctrl-shift-M</kbd> for toggling the Markdown preview, the <kbd>ctrl-,</kbd> for opening the Settings View, and recently <kbd>tab</kbd> for [Atom's new autocomplete](http://blog.atom.io/2015/05/15/new-autocomplete.html). Other than that, there are - as of yet - no differences with emmet-atom, which means you have the freedom to manually add other emmet keybindings in your `keymap.cson`.

### Manual installation

You can install the latest Emmet version manually from console:

```bash
cd ~/.atom/packages
git clone https://github.com/Yatoom/emmet-atom-simplified
cd emmet-atom-simplified
npm install
```

Then restart Atom editor.

## Features:

* Expand abbreviations by <kbd>shift-space</kbd>.

## Shift-space key

Simplified Emmet expands abbreviations by shift-space key only for HTML, CSS, Sass/SCSS and LESS syntaxes. 

## Default Keybindings

You can change these Preferences > Emmet.

Command | Darwin | Linux/Windows
------- | ------ | -------------
Expand Abbreviation | <kbd>shift-space</kbd> | <kbd>shift-space</kbd>
