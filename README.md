# Rei Language Server

An open source language server extension for VSCode.

RN I just copied rust syntax highlighter enhanced from [here](https://github.com/dustypomerleau/rust-syntax/blob/master/syntaxes/rust.tmLanguage.json).

## Features

- Syntax Highlighting (really only this rn)
- Printing vars and statements that have a definite result, would be introduced in `rein` too
- Automatic type inference and labelling when you dont specify a type

## Requirements

No dependencies. Will have some once `reic` and `rlsp` works well.

## Icons

Just put this in:

```json
"iconThemes": [
            {
              "id": "reiicon",
              "label": "Rei Icons",
              "path": "./icons/icons.json"
            }
]
```

Or use vscode icons custom icons.
