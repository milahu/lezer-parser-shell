# lezer-parser-shell

Shell grammar for the [lezer](https://lezer.codemirror.net/) parser.

## development

To watch and test, install [entr](http://eradman.com/entrproject/) and run `npm run watch`

## usage

* [monaco-lezer-parser](https://github.com/milahu/monaco-lezer-parser) - use lezer parsers in monaco-editor
* [codemirror editor](https://github.com/codemirror/view) has native support for lezer parsers
  * pro: lightweight, modular
  * con: less mature than monaco-editor

## similar projects

* https://github.com/codemirror/codemirror5/blob/master/mode/shell/shell.js - shell parser for codemirror 5

## related

this project is based on

* https://lezer.codemirror.net/docs/guide/#writing-a-grammar
* https://lezer.codemirror.net/docs/ref/
* https://github.com/milahu/lezer-parser-nix
* https://github.com/lezer-parser/clojure/blob/master/src/clojure.grammar
* https://github.com/lezer-parser/javascript/blob/main/src/javascript.grammar
* https://github.com/lezer-parser/javascript/blob/main/src/tokens.js

Shell language spec

* https://www.gnu.org/software/bash/manual/bash.html#Shell-Syntax
* https://en.wikipedia.org/wiki/Bash_(Unix_shell)
* https://en.wikipedia.org/wiki/Bourne_shell#Almquist_shells
* https://stackoverflow.com/questions/40555223/is-there-a-specification-for-bash
* https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html - definition of the Shell Command Language
