# ExtendScript Language Server
This project aims to create a feature complete [language server](https://microsoft.github.io/language-server-protocol/).
This would allow for easy integration of ExtendScript into code editors like Visual Studio Code, Vim, Neovim, Emacs, Jetbrains IDEs, etc. 

## The Challenge
To date there are 2(3) language servers for Javascript all based on ES6 or newer:

* Javascript/Typescript Language Server built into VSCode
* [Sourcegraphs Javascript/Typescript Language Server](https://github.com/sourcegraph/javascript-typescript-langserver)
* [Flowtypes Flow Javascript Language Server](https://github.com/flowtype/flow-for-vscode)

All of these work great for Javascript and Typescript, but due to ExtendScripts old E4X/Ecmascript 4 limitations they do cause issues with ExtendScript code.

This also means there's no existing Language Server to base ours on, giving us two options:

* Make a brand new language server from scratch specifically for ExtendScript (Possibly making a plain E4X and ES4 as well, because why not?)
* Use one of the existing Javascript Language Servers as a basis and add and remove features to shape it into an ExtendScript language server.

Of the two options the first one is the most enticing, but also the one that will require the most work, the second one could lead to issues and might not be a perfect solution, especially not longterm.

## I need help
While i do use ExtendScript on a semi-frequent basis, i am far from an expert on the language, which is why i'm asking all of you talented ExtendScript efficianados out there to help bring this project to reality. Any help is appreciated!

## More info to come (hopefully)

