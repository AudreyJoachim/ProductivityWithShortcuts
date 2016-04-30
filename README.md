# ProductivityWithShortcuts
Code with exercises to learn shortcuts and their associated thinking patterns

## What you'll learn
* Increase your productivity by using shortcuts. We'll use IntelliJ on windows as an example.
* Think along with your pair, who's already proficient in using shortcuts.
* In what situations/patterns shortcuts are helpful.
* Some patterns for multi-cursor usage.

## How you'll learn
By doing! The only way to get shortcuts in your fingers is by using them. All. The. Time.

This repo provides a structured aproach to learn with exercises that will help you move forward.

# How to use this repository
`git clone` this repository

The titles in the outline below are links to the different chapters.

Each chapter contains a thorough explanation and exercises. 

Eventhough the progression in these chapters might seem to be naturally increasing in difficulty, you don't need to think of them as thresholds.
The only reason there are chapters is to help your brain make paths even better by trying to categorize certain types of shortcuts so you'll think of them sooner in real life.

## Good Luck, Have Fun!
If you like these exercises, share 'em with your friends and colleagues, `fork` or `watch` it.

GLHF!

# [Outline](outline.md)

## [Chapter 1 - Basics](chapter1.md)
* ![Windows](icons/glyph-windows-20.png)`ctrl+c`, `ctrl+v`
* Keep your hands on your keyboard
* How to look up any actions' shortcut ![Windows](icons/glyph-windows-20.png)`ctrl+shift+a`, `double shift`
* IntelliJ's _Productivity Guide_
* Undo, Redo with ![Windows](icons/glyph-windows-20.png)`ctrl+z` and ![Windows](icons/glyph-windows-20.png)`ctrl+shift+z`
* Indenting, formatting with `tab`, `shift+tab` and ![Windows](icons/glyph-windows-20.png)`ctrl+alt+l`

## [Chapter 2 - Navigation](chapter2.md)
* Word-skipping ![Windows](icons/glyph-windows-20.png)`ctrl+arrows`
* Begin/End of Line ![Windows](icons/glyph-windows-20.png)`home`, `end`
* Begin/End of File ![Windows](icons/glyph-windows-20.png)`ctrl+home`, `ctrl+end`
* CamelHumps (+ how to toggle)
* Jumping methods ![Windows](icons/glyph-windows-20.png)`alt+up,down`
* Jump to error `F2`
* Jump to last edit position ![Windows](icons/glyph-windows-20.png)`ctrl+shift+backspace`
* Jump into/Drill Down/Show Usage ![Windows](icons/glyph-windows-20.png)`ctrl(+alt)+b`
* History and its importance ![Windows](icons/glyph-windows-20.png)`ctrl+alt+left,right`
* Show in Project ![Windows](icons/glyph-windows-20.png)`alt+F1`
* Jump to line ![Windows](icons/glyph-windows-20.png)`ctrl+g` (example with paste from stacktrace)
* Navigate to method ![Windows](icons/glyph-windows-20.png)`ctrl+F12` (example with paste from stacktrace and quick check equals impl)
* ![Windows](icons/glyph-windows-20.png)`alt+F7` vs. ![Windows](icons/glyph-windows-20.png)`ctrl+alt+h`

## [Chapter 3 - Selection](chapter3.md)
* Move + Select ![Windows](icons/glyph-windows-20.png)`ctrl+shift+arrows`
* Expand Selection ![Windows](icons/glyph-windows-20.png)`ctrl+w`
* Using Selection to help Navigation (e.g. _Fluent API_)
* Wrapping (IntelliJ feature)

## [Chapter 4 - Line Editing](chapter4.md)
* Yank ![Windows](icons/glyph-windows-20.png)`ctrl+y`
* Duplicate line ![Windows](icons/glyph-windows-20.png)`ctrl+d`
* Moving lines with and without constraints ![Windows](icons/glyph-windows-20.png)`ctrl+shift+up,down` vs. ![Windows](icons/glyph-windows-20.png)`alt+shift+up,down`
* Start new line ![Windows](icons/glyph-windows-20.png)`ctrl+enter`
* Join lines ![Windows](icons/glyph-windows-20.png)`ctrl+shift+j`

## [Chapter 5 - Embedded Windows](chapter5.md)
* Opening/Closing (Toggling) ![Windows](icons/glyph-windows-20.png)`alt+number` ![Windows](icons/glyph-windows-20.png)`ctrl+F4`
* Switching tabs ![Windows](icons/glyph-windows-20.png)`alt+left,right`
* Why resizing is for dummies ![Windows](icons/glyph-windows-20.png)`ctrl+shift+F12`
* Navigation from Embedded Windows ![Windows](icons/glyph-windows-20.png)`ctrl+enter` vs. `F4`

## [Chapter 6 - IntelliJ's Suggestions](chapter6.md)
* IntelliJ's Auto-correct ![Windows](icons/glyph-windows-20.png)`ctrl+shift+enter`
* Autocomplete ![Windows](icons/glyph-windows-20.png)`ctrl+space` vs. ![Windows](icons/glyph-windows-20.png)`ctrl+shift+space`
* _QuickFix_ (:bulb:) ![Windows](icons/glyph-windows-20.png)`alt+enter`
* Creating _stuff_ ![Windows](icons/glyph-windows-20.png)`alt+ins`
* Deleting _stuff_ ![Windows](icons/glyph-windows-20.png)`alt+del`
* View JavaDoc ![Windows](icons/glyph-windows-20.png)`ctrl+q`
* View parameters ![Windows](icons/glyph-windows-20.png)`ctrl+p`

## [Chapter 7 - Finding/Buffer](chapter7.md)
* Find word and add to buffer ![Windows](icons/glyph-windows-20.png)`ctrl+F3`
* Find next occurrence from buffer `F3`

## [Chapter 8 - Multiple Cursors](chapter8.md)
* Toggle Column Mode ![Windows](icons/glyph-windows-20.png)`alt+shift+ins`
* ![Windows](icons/glyph-windows-20.png)`alt+j`, ![Windows](icons/glyph-windows-20.png)`alt+shift+j` and ![Windows](icons/glyph-windows-20.png)`ctrl+alt+shift+j`

We'll see a lot of different cases, such as but not limited to:
* TestBuilders
* Testing Enum lists
* Making a csv list from XML

## [Chapter 9 - Endgame](chapter9.md)
We'll make a full exercise where you'll:

1. Create a new class that resides in a new package and has to interact with another existing class
2. Create a new test for that class
3. Create a new TestBuilder for the existing class
4. Perform a _red, green, refactor_
5. (Optional) commit and push

# License
The example code is published under the [MIT License](LICENSE.md).

The mac and windows logo icons used are under the [Creative Common License (Attr. 3 Unported)](http://creativecommons.org/licenses/by/3.0/), and are completely attributed to the artist [Bogdan Rosu](https://www.iconfinder.com/bogdanrosu).