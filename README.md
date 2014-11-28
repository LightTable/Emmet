##Emmet.io plugin for Light Table

A simple integration of Emmet.

## Usage

This plugin implements a [number of Emmet actions](http://docs.emmet.io/actions/). For example, in an html page if you type `ul>li` and press `TAB`, it will get expanded to `<ul><li></li></ul>. See [emmet.keymap](emmet.keymap) for other actions that have keybindings

Note that this plugin overrides `TAB` to expand an emmet abbreviation. If you don't want that and would rather rely on just `pmeta-e`, remove the keybinding in your `user.keymap` with:

```clojure
[:editor.keys.normal.emmet "-tab" :editor.codemirror.command "emmet.expand_abbreviation_with_tab"]
```



