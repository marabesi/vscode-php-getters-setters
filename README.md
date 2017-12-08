# PHP getters and setters for Visual Studio Code

> Fast generator of getters and setters for your PHP class properties.

![Demo](images/demo.gif)

## Features

This extension allows you to quickly generate getters and setters with one single command.

Features:

* Detects indentation. No matter if you use spaces or tabs.
* Uses configuration options to show doc blocks as you like them.
* Generates method's descriptions based on the property description.
* Detects valid type hints to use them in the setter.

It adds 3 comands to vscode's command palette:

* Insert PHP getter.
* Insert PHP setter.
* Insert PHP getter and setter.

## Extension Settings

This extension contributes the following settings:

* `phpGettersSetters.spacesAfterParam`: Number of spaces to insert between @param tag and variable name in doc blocks. Default: 2
* `phpGettersSetters.spacesAfterParamVar`: Number of spaces to insert after the variable name in the @param tag line. Default: 2
* `phpGettersSetters.spacesAfterReturn`: Number of spaces to insert after the @return tag. Default: 2
* `phpGettersSetters.redirect`: Redirect editor to generated functions after generating them? Default: true

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial version
