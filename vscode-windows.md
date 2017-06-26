# Setup Elm with Visual Studio Code on Windows

This document will guide through a basic development environment setup for Elm with VSCode on Windows.
If you don't do this for the first time, this is the short list:

* Install the Elm Platform
* Setup elm-format
* Install Visual Studio Code
* Install the elm vscode plugin

## Install the Elm Platform

Download and install the Elm Platform for Windows binaries from [elm-lang.org](https://guide.elm-lang.org/install.html).

## Setup elm-format

Download elm-format-0.18-0.7.0-exp-win-i386.zip from [elm-format github](https://github.com/avh4/elm-format/releases/tag/0.7.0-exp).

Copy it to the folder, where the Elm binaries reside, usually:

```C:\Program Files (x86)\Elm Platform\0.18\bin```

## Install Visual Studio Code

Download and install Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com/download).
Make sure to check "Add Open with Code action..." during Setup.

![alt text](/img/VSCodeInstall.png "Open with Code action")

## Install the elm vscode plugin

In Visual Studio Code press ```Ctrl+P``` and type:

```ext install elm```

Press Enter.

Then, press ```Ctrl+,``` to open the Settings and configure vscode to format your elm code whenever you save:

![alt text](/img/VSCodeFormat.png "Format on save")

Save your settings.

## Finally

Congratulations, you're done. Before you leave this page consider one more thing:

The standard vscode theme does not have different colors for types and functions. Since Elm is a functional language and types and functions are mainly all you have (and need) you may want to choose a different theme like Monokai or Atom One Dark.

To change your theme, press ```Ctrl+K Ctrl+T``` and choose one. You can always install more of those as extensions.