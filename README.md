
# ultimate macOS [**中文**](https://github.com/suliveevil/Capslock/blob/master/README_cn.md)


forked from [Vonng/Capslock](https://github.com/Vonng/Capslock/) : *Make <kbd>CapsLock</kbd> Great Again!* 

[![openIssues](https://img.shields.io/github/issues-raw/suliveevil/Capslock.svg)](https://github.com/suliveevil/Capslock/issues/new) [![pullRequests](https://img.shields.io/github/issues-pr/suliveevil/Capslock.svg)](https://github.com/suliveevil/Capslock/compare)   [![star this repo](http://githubbadges.com/star.svg?user=suliveevil&repo=capslock&style=flat)](https://github.com/suliveevil/capslock) [![fork this repo](http://githubbadges.com/fork.svg?user=suliveevil&repo=capslock&style=flat)](https://github.com/suliveevil/capslock/fork)[![Downloads](https://img.shields.io/github/downloads/suliveevil/Capslock/total.svg)]()[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)

![](images/ANSI_60_80_100.png)



## Why <kbd>CapsLock</kbd>

### Transform Capslock into *Hyper*, improve your productivity tremendously!

* Powerful: Make Capslock a great new modifier key: **<kbd>Hyper(✱)</kbd>**. 
* Well-Designed:  High-Freq key in hot-area. Bring lots of useful functionalities.
* Compatiable: Work well with other modifiers, appliactions, devices.
* Light-Weight:  Just a small script, carry it everywhere !
* [Design Document](design.md) 
* [KeyRemap Document](mac/ultimate_macOS.key)

### Platforms

- [ultimate macOS](mac/)  via  [Karabiner-Elements](https://pqrs.org/osx/karabiner/)
  - macOS Mojave (10.14)
  - macOS High Sierra (10.13)
  - macOS Sierra (10.12)
  - macOS EI Capitan (10.11)


### Install

1. Download [Karabiner-Elements](https://pqrs.org/osx/karabiner/) and Install

2. Copy URL to your browser(**open in safari**) to import configuration script.

```bash
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/suliveevil/Capslock/master/mac/ultimate_macOS.json
```

or import config file from Karabiner-Elements Offical Script Gallery

```bash
https://pqrs.org/osx/karabiner/complex_modifications/#ultimate_macOS
```

3. Open Karabiner, Tab "ComplexModification", Button "Add Item", and enable entries you like.

4. Default conf file path is `$HOME/.config/karabiner/assets/complex_modifications`. Modify it if you like.

5. Enable functions: `[App] karabiner-elements -> [Tab] Complex Modification -> Add Item`


## Usage

![](images/keyboard.png)

### Basic

<details>
<summary>details</summary>

<kbd>✱</kbd> Hyper actually maps to <kbd>⌃</kbd> <kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>⌘</kbd> (all right modifiers) , It works well with additional left modifiers. And compatible with most application. Hold CapsLock to enable `Hyper` funcationality while press it will emit an `Escape`.

| Origin    | Maps to    | Comment                    |
| :-------: | ---------- | -------------------------- |
| <kbd>⇪</kbd> Press  | <kbd>⎋</kbd> Escape | Single press to escape     |
| <kbd>⇪</kbd> Hold   | <kbd>✱</kbd>  Hyper | Enable Hyper Functionality |

</details>


### Navigation

<details>
<summary>details</summary>

- Hold  <kbd>✱</kbd> Hyper to enable navigators
- Hold additional <kbd>⌘</kbd> Command for **selection** . (just like holding ⇧shift in normal)
- Hold additional <kbd>⌥</kbd>  with <kbd>H</kbd><kbd>J</kbd><kbd>K</kbd><kbd>L</kbd>  for **mouse movement**
- Hold additional <kbd>⇧</kbd> with <kbd>H</kbd><kbd>J</kbd><kbd>K</kbd><kbd>L</kbd> for **switching tab/app**
- Hold additional <kbd>⌃</kbd>  with <kbd>H</kbd><kbd>J</kbd><kbd>K</kbd><kbd>L</kbd>  for **desktop management** . (just like holding ⌃ctrl with arrow key)


| Origin  | Maps to         | Comment                    |
| -----:  | --------------  | ------------------------   |
| <kbd>⌘</kbd><kbd>0</kbd>    | <kbd>⌘</kbd><kbd>←</kbd> LeftArrow  | cursor move to the begin of the line  |
| <kbd>⌘</kbd><kbd>4($)</kbd>    | <kbd>⌘</kbd><kbd>→</kbd> RightArrow | cursor move to the end of the line |
| <kbd>H</kbd>                | <kbd>←</kbd> LeftArrow              | cursor left                |
| <kbd>J</kbd>                | <kbd>↓</kbd> DownArrow              | cursor down                |
| <kbd>K</kbd>                | <kbd>↑</kbd> UpArrow                | cursor up                  |
| <kbd>L</kbd>                | <kbd>→</kbd> RightArrow             | cursor right               |
| <kbd>⌘</kbd><kbd>H</kbd>    | <kbd>⇧</kbd><kbd>←</kbd> LeftArrow  | cursor left and selection  |
| <kbd>⌘</kbd><kbd>J</kbd>    | <kbd>⇧</kbd><kbd>↓</kbd> DownArrow  | cursor down and selection  |
| <kbd>⌘</kbd><kbd>K</kbd>    | <kbd>⇧</kbd><kbd>↑</kbd> UpArrow    | cursor up and selection    |
| <kbd>⌘</kbd><kbd>L</kbd>    | <kbd>⇧</kbd><kbd>→</kbd> RightArrow | cursor right and selection |
| <kbd>⌥</kbd><kbd>H</kbd>    | <kbd>←</kbd> LeftArrow              | <kbd>⌥</kbd> <kbd>←</kbd> |
| <kbd>⌥</kbd><kbd>J</kbd>    | <kbd>↓</kbd> DownArrow              | <kbd>⌥</kbd> <kbd>↓</kbd> |
| <kbd>⌥</kbd><kbd>K</kbd>    | <kbd>↑</kbd> UpArrow                | <kbd>⌥</kbd> <kbd>↑</kbd> |
| <kbd>⌥</kbd><kbd>L</kbd>    | <kbd>→</kbd> RightArrow             | <kbd>⌥</kbd> <kbd>→</kbd> |
| <kbd>⌃</kbd><kbd>H</kbd>    | <kbd>←</kbd> LeftArrow              | expose all                 |
| <kbd>⌃</kbd><kbd>J</kbd>    | <kbd>↓</kbd> DownArrow              | show desktops              |
| <kbd>⌃</kbd><kbd>K</kbd>    | <kbd>↑</kbd> UpArrow                | switch prev desktop        |
| <kbd>⌃</kbd><kbd>L</kbd>    | <kbd>→</kbd> RightArrow             | switch next desktop        |
| <kbd>U</kbd>     | <kbd>⇞</kbd> PageUp      | cursor page up             |
| <kbd>I</kbd>     | <kbd>↖</kbd> Home        | cursor to line(doc) head   |
| <kbd>O</kbd>     | <kbd>↘</kbd>  End        | cursor to line(doc) end    |
| <kbd>P</kbd>     | <kbd>⇟</kbd> PageDn      | cursor page down           |
| <kbd>⌘</kbd><kbd>U</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌘</kbd><kbd>I</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌘</kbd><kbd>O</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌘</kbd><kbd>P</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>U</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>I</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>O</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>P</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>U</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>I</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>O</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>P</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |

</details>



### Mousekey

<details>
<summary>details</summary>

* Emulate mouse with keyboard
* ~~Also can be archived by <kbd>⌥</kbd>  with <kbd>U</kbd><kbd>I</kbd><kbd>O</kbd><kbd>P</kbd>~~

| Origin | Maps to        | Comment                  |
| -----: | -------------- | ------------------------ |
| <kbd>←</kbd>    | MouseLeft       | mouse cursor left         |
| <kbd>↓</kbd>    | MouseDown       | mouse cursor down         |
| <kbd>↑</kbd>    | MouseUp         | mouse cursor up           |
| <kbd>→</kbd>    | MouseRight      | mouse cursor right        |
| <kbd>↩</kbd>    | MouseLeft       | mouse left button click   |
| <kbd>⌥</kbd> <kbd>↩</kbd>    | MouseMiddle       | mouse Middle button click   |
| <kbd>⌘</kbd> <kbd>↩</kbd>   | MouseRight      | mouse right button click  |

</details>


### Deletion

<details>
<summary>details</summary>

| Origin    | Maps to                            | Comment             |
| --------: | ---------------------------------- | ------------------- |
| <kbd>N</kbd>       | <kbd>⌥⌫</kbd>  Option + ForwardDelete       | Delete a word ahead |
| <kbd>M</kbd>       | <kbd>⌫</kbd> ForwardDelete                  | Delete a char ahead |
| <kbd>,</kbd>       | <kbd>⌦</kbd> Delete                         | Delete a char after |
| <kbd>.</kbd>       | <kbd>⌥⌦</kbd> Option + Delete               | Delete a word after |
| <kbd>⌘</kbd><kbd>M</kbd>,<kbd>⌘</kbd><kbd>N</kbd> | <kbd>⌘⌥⌫</kbd> Command+Option+ForwardDelete | Delete to line head |

</details>

### Window Control

<details>
<summary>details</summary>

| Origin           | Maps to                 | Comment                                       |
| ---------------: | ----------------------- | --------------------------------------------  |
| <kbd>⇥</kbd> Tab          | <kbd>⌘⇥</kbd> Command+Tab        | Switch Window                                                        |
| <kbd>⌘⇥</kbd> Command+Tab | <kbd>⌘⇧⇥</kbd> Command+Shift+Tab | Switch Window Reversely                                              |
| <kbd>Q</kbd>              | <kbd>⌘Q</kbd>                    | Close Window                                                         |
| <kbd>W</kbd>              | <kbd>⌘W</kbd>                    | Close Tab                                                            |
| <kbd>A</kbd>              | <kbd>⌃⌥⇧⌘A</kbd>                 | Leaves to [Moom](https://manytricks.com/moom/), ※a window resize app |
| <kbd>⌘A</kbd>             | <kbd>⌃↑</kbd>  Ctrl+UpArrow      | OSX Expose All                                                       |
| <kbd>S</kbd>              | <kbd>⌃⇥</kbd>  Ctrl+Tab          | Switch Tab                                                           |
| <kbd>⌘S</kbd>             | <kbd>⌃⇧⇥</kbd> Ctrl+Shift+Tab    | Swtich Tab Reversely                                                 |
| <kbd>⌥D</kbd>             | <kbd>F11</kbd>                   | Show Desktop                             |

</details>


### Bash Control

<details>
<summary>details</summary>

- Common bash utils: EOF, SIGINT, SIGTSTP, VIM/Tmux Prefix

| Origin | Maps to     | Comment                                      |
| -----: | ----------- | -------------------------------------------- |
| <kbd>D</kbd>    | <kbd>⌃</kbd><kbd>D</kbd> Ctrl+D  | EOF                                          |
| <kbd>Z</kbd>    | <kbd>⌃</kbd><kbd>Z</kbd> Ctrl+Z  | SIGTSTP                                      |
| <kbd>X</kbd>    | <kbd>⌃</kbd><kbd>R</kbd> Ctrl+R  | IDE Run                                      |
| <kbd>C</kbd>    | <kbd>⌃</kbd><kbd>C</kbd> Ctrl+C  | SIGINT                                       |
| <kbd>V</kbd>    | <kbd>⌃</kbd><kbd>V</kbd> Ctrl+V  | Vim Prefix                                   |
| <kbd>B</kbd>    | <kbd>⌃</kbd><kbd>B</kbd> Ctrl+B  | [Tmux](http://tmux.github.io) Default Prefix |

</details>


### Applications

<details>
<summary>details</summary>


- Maybe you'd like overwrite these with your own favorite apps.

| Origin | Maps to                 | Comment                                         |
| -----: | ----------------------- | ----------------------------------------------- |
| <kbd>E</kbd>              | Open **Finder**         | Open File Browser                               |
| <kbd>⌘E</kbd>             | Open Safari             | Open Web Browser                                |
| <kbd>R</kbd>              | Open **iTerm2**         | Great terminal for osx (`Run`)                  |
| <kbd>⌘R</kbd>             | Open Pycharm            | Open IDE                                        |
| <kbd>T</kbd>              | Open **Visual Studio Code** | Text Editor: Visual Studio Code             |
| <kbd>⌘T</kbd>             | Open Typora             | Text Editor: Typora , a great WYSIWYG md editor |
| <kbd>T</kbd>              | Open **Visual Studio Code** | Text Editor: Visual Studio Code             |
| <kbd>Y</kbd>              | Open **Siri**               | Siri                                        |
| <kbd>⌘D</kbd>          | Open Dictionary                  | Find words                                |
| <kbd>F</kbd>               | Open Alfred                             |                                                     |
| <kbd>⌘F</kbd>            | Open Dash               | Find API Document                               |
| <kbd>G</kbd>               | Open GitHub Desktop     | GitHub Desktop                                  |
| <kbd>⌘G</kbd>           | Open Chrome             | Google Chrome                                   |

</details>
         
### Functional

<details>
<summary>details</summary>

- Use <kbd>hyper</kbd> + <kbd>1~9</kbd> and <kbd>0</kbd> and <kbd>-</kbd> and <kbd>=</kbd> as standard functional keys(F1,…F12).


| Origin            | Maps to              | Comment                          |
| ----------------: | -------------------- | -------------------------------- |
| <kbd>⌥</kbd><kbd>1</kbd>              | <kbd>BrightnessDown</kbd>     |                                  |
| <kbd>⌥</kbd><kbd>2</kbd>              | <kbd>BrightnessUp</kbd>       |                                  |
| <kbd>⌥</kbd><kbd>3</kbd>              | <kbd>ExposeAll</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>4</kbd>              | <kbd>LaunchPad</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>5</kbd>              | <kbd>KeyboardLightDown</kbd>  |                                  |
| <kbd>⌥</kbd><kbd>6</kbd>              | <kbd>KeyboardLightUp</kbd>    |                                  |
| <kbd>⌥</kbd><kbd>7</kbd>              | <kbd>MusicPrev</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>8</kbd>              | <kbd>MusicPlay</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>9</kbd>              | <kbd>MusicNext</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>0</kbd>             | <kbd>Mute</kbd>               |                                  |
| <kbd>⌥</kbd><kbd>-</kbd>             | <kbd>VolumeDown</kbd>         |                                  |
| <kbd>⌥</kbd><kbd>=</kbd>             | <kbd>VolumeUp</kbd>           |                                  |
| <kbd>F13</kbd> PrintScreen | <kbd>MusicPrev</kbd>          |                                  |
| <kbd>F14</kbd> ScrollLock  | <kbd>MusicNext</kbd>          |                                  |
| <kbd>F15</kbd> Pause       | <kbd>MusicPlay</kbd>          | Just as it shows                 |
| <kbd>Insert</kbd>          | <kbd>⌥BrightnessUp</kbd>      | Fine grained brightness up       |
| <kbd>Delete</kbd>          | <kbd>⌥BrightnessDown</kbd>    | Fine grained brightness down     |
| <kbd>Home</kbd>            | <kbd>⌥KeyboardLightUp</kbd>   | Fine grained keyboard light up   |
| <kbd>End</kbd>             | <kbd>⌥KeyboardLightDown</kbd> | Fine grained keyboard light down |
| <kbd>PgUp</kbd>            | <kbd>⌥VolumeUp</kbd>          | Fine grained volume up           |
| <kbd>PgDn</kbd>            | <kbd>⌥VolumeDown</kbd>        | Fine grained volume down         |

</details>


### Shifter

<details>
<summary>details</summary>

- A more convient shift for most case
- Semicolon <kbd>;</kbd> and Quote  <kbd>'</kbd> have some special treatment, makes input <kbd>!=</kbd> and <kbd>:=</kbd>  easier

| Origin             | Maps to | Comment                  |
| -----------------: | ------- | ------------------------ |
| <kbd>1</kbd>                           | <kbd>!</kbd>     | Exclamation              |
| <kbd>2</kbd>                           | <kbd>@</kbd>     | At                       |
| <kbd>3</kbd>                           | <kbd>#</kbd>     | Sharp                    |
| <kbd>4</kbd>                           | <kbd>$</kbd>     | Dollar                   |
| <kbd>5</kbd>                           | <kbd>%</kbd>     | Percent                  |
| <kbd>6</kbd>                           | <kbd>^</kbd>     | Caret                    |
| <kbd>7</kbd>                           | <kbd>&</kbd>     | Ampersand                |
| <kbd>8</kbd>                           | <kbd>*</kbd>     | Star                     |
| <kbd>9</kbd>                           | <kbd>(</kbd>     | Left Round Bracket       |
| <kbd>0</kbd>                           | <kbd>)</kbd>     | Right Round Bracket      |
| <kbd>-</kbd> Minus                     | <kbd>_</kbd>     | Hyphen                   |
| <kbd>=</kbd> Equal                     | <kbd>+</kbd>     | Plus                     |
| <kbd>[</kbd> Left Bracket              | <kbd>{</kbd>     | Left Bracket <kbd>⇧</kbd> <kbd>{[</kbd>  |
| <kbd>]</kbd>  Right Bracket            | <kbd>}</kbd>     | Right Bracket <kbd>⇧</kbd> <kbd>}]</kbd>  |
| <kbd>;</kbd> Semicolon                 | <kbd>!</kbd>     | Exclamation              |
| <kbd>'</kbd> Single Quote              | <kbd>=</kbd>     | EqualSign                |
| <kbd>⌘</kbd><kbd>;</kbd> Semicolon     | <kbd>!</kbd>     | Colon                    |
| <kbd>⌘</kbd><kbd>'</kbd> Single Quote  | <kbd>=</kbd>     | EqualSign                |

</details>


### Misc

<details>
<summary>details</summary>

| Origin                 | Maps to             | Comment                                        |
| ---------------------: | ------------------- | ---------------------------------------------- |
| <kbd>⎋</kbd> Escape             | <kbd>⇪</kbd>  CapsLock       | Bug: Difficult to turn capslock off after emit |
| <kbd>~</kbd> BackQuote          | <kbd>⇧⌘4</kbd>              | macOS Area Screenshot to Desktop  file           |
| <kbd>⌘</kbd><kbd>~</kbd> Command+BackQuote | <kbd>⌃⇧⌘4</kbd>               | macOS Area Screenshot to Clipboard          |
| <kbd>⌫</kbd> Backspace          | <kbd>⌘</kbd><kbd>⌫</kbd>                | macOS Delete File                              |
| <kbd>/</kbd> Slash              | <kbd>⌘</kbd><kbd>/</kbd> Command+Slash  | Comment/Uncomment in many IDE                  |
| <kbd>\\</kbd> Backslash         | <kbd>⌘</kbd><kbd>/</kbd> Command+Slash  | Comment/Uncomment in many IDE                  |
| <kbd>␢</kbd> Spacebar           | <kbd>⌃</kbd><kbd>␢</kbd>  Ctrl+Spacebar | Switch Input Source                            |

</details>




## Symbol Reference

<details>
<summary>Modifiers:  Mac</summary>


| Sym    | Key     |
| :----: | ------- |
| <kbd>✱</kbd>      | Hyper   |
| <kbd>⌃</kbd>      | Control |
| <kbd>⌥</kbd>      | Option  |
| <kbd>⇧</kbd>      | Shift   |
| <kbd>⌘</kbd>      | Command |


</details>


<details>
<summary>Modifiers: ⊞ Windows</summary>

|  Sym   | Key     |
| :----: | ------- |
| <kbd>✱</kbd>      | Hyper   |
| <kbd>⌃</kbd>      | Control |
| <kbd>⊞</kbd>      | Windows |
| <kbd>⇧</kbd>      | Shift   |
| <kbd>⎇</kbd>     | Alter   |

</details>


<details>
<summary>Normal Keys</summary>


|   GLYPH   | NAME                                   |
| :-------: | -------------------------------------- |
| <kbd></kbd>       | Apple                                  |
| <kbd>⌘</kbd>       | Command, Cmd, Clover, (formerly) Apple |
| <kbd>⌃</kbd>       | Control, Ctl, Ctrl                     |
| <kbd>⌥</kbd>       | Option, Opt, (Windows) Alt             |
| <kbd>⎇</kbd>       | Alt                                    |
| <kbd>⇧</kbd>       | Shift                                  |
| <kbd>⇪</kbd>       | Caps lock                              |
| <kbd>⏏</kbd>       | Eject                                  |
| <kbd>↩</kbd>, <kbd>↵</kbd>, <kbd>⏎</kbd> | Return, Carriage Return                |
| <kbd>⌤</kbd>       | Enter                                  |
| <kbd>⌫</kbd>       | Delete, Backspace                      |
| <kbd>⌦</kbd>       | Forward Delete                         |
| <kbd>⎋</kbd>       | Escape, Esc                            |
| <kbd>→</kbd>       | Right arrow                            |
| <kbd>←</kbd>       | Left arrow                             |
| <kbd>↑</kbd>       | Up arrow                               |
| <kbd>↓</kbd>       | Down arrow                             |
| <kbd>⇞</kbd>       | Page Up, PgUp                          |
| <kbd>⇟</kbd>       | Page Down, PgDn                        |
| <kbd>↖</kbd>       | Home                                   |
| <kbd>↘</kbd>       | End                                    |
| <kbd>⌧</kbd>       | Clear                                  |
| <kbd>⇥</kbd>       | Tab, Tab Right, Horizontal Tab         |
| <kbd>⇤</kbd>       | Shift Tab, Tab Left, Back-tab          |
| <kbd>␢</kbd>       | Space, Blank                           |
| <kbd>␣</kbd>       | Space, Blank                           |
| <kbd>❘⃝</kbd>      | Power                                  |
| <kbd>⇭</kbd>       | Num lock                               |
| <kbd>?⃝</kbd>      | Help                                   |
| <kbd></kbd>       | Context menu                          |

</details>



## About

Author：suliveevil (suliveevil@outlook.com)

License： [![WTFPL](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/WTFPL_logo.svg/50px-WTFPL_logo.svg.png)]()

```
Do What The Fuck you want to Public License

Version 1.0
Copyright (C) 2018 Feng Ruohang (Vonng).
Everyone is permitted to copy and distribute verbatim copies
of this license document, but changing it is not allowed.

Ok, the purpose of this license is simple
and you just

DO WHAT THE FUCK YOU WANT TO.
```

