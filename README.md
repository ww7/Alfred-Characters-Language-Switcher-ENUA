[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://vshymanskyy.github.io/StandWithUkraine/)

## Description
<img width="150" height="150" align="right" src="https://raw.githubusercontent.com/ww7/Alfred-Characters-Language-Switcher-ENUA/master/icon.png" alt="alfred-keyboard-language-switcher-ua">

Alfred Workflow, which uses Applescript to convert language of selected text. 
Punto Switcher alternative.

For Ukrainian to English and English to Ukrainian conversion. 

Script switches the language (input source) after conversion (via default macOS shortcut), preserves clipboard. 

Based on Applescript by Jeffrey Smith 2016.

## How to install?
1. Download [.workflow](https://github.com/ww7/Alfred-Characters-Language-Switcher-ENUA/blob/main/Characters%20language%20switcher%20(En-Ua).alfredworkflow?raw=true) file and double click to add it to Alfred. 
2. Set your preferred hotkey.

## Known limitation
Can't switch the language if macOS default `Ctrl-Space` shortcut of `Select the previous input source` changed. It can be fixed with updating to current shotcut in `tell application "System Events" to key code 49 using control down`. In future releases this part probably extended with [im-select](https://github.com/daipeihust/im-select) (or similiar) binary.

Switching to previous input source in text with mix of languages can be not exact.

## Links
* Works with [Ukrainian Typographic Keyboard](https://github.com/denysdovhan/ukrainian-typographic-keyboard)
* Alfred Workflow for [English - Russian](https://github.com/j2thex/keyboard-language-switcher) pair
