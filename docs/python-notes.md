# Notes on the added Python support for Panda 

## Changes specific to Python

* Added `_very-light-blue` for function/method parameters 

## Changes specific to Markdown 



## User settings

* Symantic highlighting enabled by default:
    * The following must be commented-out in VS Code's `settings.json`:
```
// "editor.semanticHighlighting.enabled": false
```

## Build

```
node build.js && cp ./dist/Panda.json ~/.vscode/extensions/tinkertrain.theme-panda-1.3.0/dist/Panda.json
```

## TODO

* Consider the following for Python:
    * Change colour of {} in f-strings to purple
    * Make escape character different colour (e.g. orange)
    * Classes: self.<member variable> should not all be blue (should be orange like other variables) 



Markdown highlighting changes:

– keyword.operator.logical.python
– "." member access (see my cdk files...) 
– [] -> not italicised! 