# topaslanguage README

Initial release of Syntax package for text highlighting of .inp and .out files of TOPAS for PXRD analysis

## Features

This package provide useful syntax file for the syntax highlighting of .inp and .out files used to perform PXRD data analysis within TOPAS.
Snippets of useful codes are also available.  
In particular, with this extension the following tokens are identified
- Keywords
- Macro
- Refinable parameters
- Fixed parameters
- Varaible names
- Wrong placement of @ and ! character 

As comparison here are reported three images showing the differences of working with a syntax highlighter (both the common one and the one reported here) and without.   
Plain Text:
![Plain Text](/media/PlainText.png)
With the common syntax highlighter:
![Plain Text](/media/WIthCommonSyntaxHIghlight.png)
With this repo refinable parameters, equations, wrong syntaxes ... are identified:
![Plain Text](/media/WithExtension.png)

## Requirements

- VSCode editor

## Known Issues

Syntax highlighting could not work properly for some commands. In case of errors please, report them.
Parameters value without the "fix" identifier are not identifies as refinable.

## Release Notes

### 0.0.1

Initial release of Syntax package for text highlighting of .inp and .out files of TOPAS for PXRD analysis

## Installation

Download the package from the VSCode store or move the package into %user%\.vscode\extensions\
For a better experience I suggest to also install CommentAnchor extension for VSCode

## Future development

- Better text tokemization
- More code snippets
- Topas Theme for more accurate text highlighting
- Topas extension for a quicker and easier use of TOPAS .inp interface within VSCode together with a multiple set of extensions
- Topas Language server for live suggestions and documentation on TOPAS commands

## Contact
For any doubt and/or information please contact Marco Vandone marco.vandone@unimi.it
