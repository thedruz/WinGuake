# WinGuake
A Windows-oriented version of the popular Guake Terminal for Linux.

<img src="http://i.imgur.com/iEoAsA2.png" height=100 width=100></img>

Check out the original Linux version here: https://github.com/Guake/guake/

# What is it?
Remember the days when playing Quake (or even as recent as CS:GO) where you pressed a key and the console came up? Wouldn't it be very convenient if Windows did this?
**Enter WinGuake!**
WinGuake is a Windows version of the popular [Guake Terminal](https://github.com/Guake/guake/) for Linux. It allows you to use the Windows Command Prompt with just a few button presses, and to hide it just as easy!

# Get Pre-compiled Version
- Download from the [releases](https://github.com/chand1012/winguake/releases) tab.
- Extract the zip to the directory of your choice
- Run `console.exe`
- Press Ctrl+Alt+T to start up the console
- When done, type `exit` to close the console
- To run on startup, make a shortcut to `console.exe` and place it in `shell:startup`

# Prerequisites
 To run from source, you need a working version of [Python](http://python.org) 3.x with Tkinter (Python 2.x is untested) installed and added to PATH, have [AutoHotKey](https://autohotkey.com/) installed, and the latest version of [PyWin32](https://sourceforge.net/projects/pywin32/).

# How to use
After the requirements are met, clone the repository to a safe location (or download as a ZIP):
`git clone https://github.com/chand1012/WinGuake.git`
Double click Console.ahk and just press Ctrl+Alt+T. Something like this should show up:
![](https://i.imgur.com/LbEgJKY.png)
To exit, just type `exit` into the console. AutoHotKey will run in the background for when you need to bring up the CMD again.

# Planned Features
- Have tab key work
- Get settings working correctly
- Finish Settings editor
- Custom starting directories and color changing
- Quake Style drop-down animation
