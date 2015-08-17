# Atom Cheat Sheet #

There is purposely not that much information in here because there are many other great resources covering the things not mentioned here.



## Building Atom Packages ###

- Need to run `update-package-dependencies:update` (found in command palette) each time dependencies field in package.json is updated.
- Publish Atom packages: (run `apm help publish` for more info)

        cd my-package
        apm publish minor // Updates package.json with new minor version, commits change, creates new git tag, uploads package to registry

- [More info](https://atom.io/docs/latest/creating-a-package)

### How to get started with building packages for Atom ###

1. Open command palette `ctrl+shift+P`, then find "Generate Package".
2. In the prompt that appears, name the package to something like "my-package-name", press enter.
3. A new window will appear, take a little bit of time to explore the directories and auto-generated files.
4.



## Packages I may learn from and try to contribute to ##
- [inline-messenger](https://atom.io/packages/inline-messenger)
- [php-documentation-online](https://atom.io/packages/php-documentation-online)
- [quick-docs](https://atom.io/packages/quick-docs)
- [synesthesia](https://atom.io/packages/synesthesia)
- [unique-code](https://atom.io/packages/unique-code) (generate UUID)

### First package, generate some text, maybe "loren ipsum" or "great idea" ###
- https://atom.io/packages/genrandom
- https://atom.io/packages/hipster-ipsum
- https://atom.io/packages/lorem-ipsum
- https://atom.io/packages/technobabble%20ipsum
- https://atom.io/packages/uuidgen


## My installed packages ##
- atom-terminal
- language-haskell
- minimap
- open-recent
- remove-edit

### Maybe install in the future ###
-



## Idea: Package to create ##
- Quick shortcut view like for Chromebook `ctrl+alt+/` and/or `ctrl+alt+shift+?`
  - Similar: https://atom.io/packages/atom-shortcuts
- Prompt whenever an action is performed with mouse that could have been done with keyboard
- Count use of keybindings, have ability to sort between most and least used



## Further Resources ##
-

- [SO: How do I write a custom command in Atom?](http://stackoverflow.com/questions/24456995/how-do-i-write-a-custom-command-in-atom)
- [discuss.atom.io: Built-in compiler?](https://discuss.atom.io/t/built-in-compiler/2188/4)

- Awesome: [Electron: Build cross platform desktop apps with web technologies](http://electron.atom.io/) (What Atom and Visual Studio Code and more is built on)