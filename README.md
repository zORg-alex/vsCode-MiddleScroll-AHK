# VS Code MiddleClick Scroll AutoHotkey Script

This will allow scrolling vertically with middle click and middle drag, right click or left click will interrupt drag

## How to set up

Install [AutoHotkeys2](https://www.autohotkey.com/)

After VS Code installed and ran:

* Ctrl+R "%appdata%\Microsoft\Windows\Start Menu\Programs\Startup"

* Copy task.json and CodeMiddleClickFix.ahk

* RightClick CodeMiddleClickFix.ahk -> Compile Script (GUI)

* In options select 1.1.37.xx

![AHK Compile Settings](https://github.com/user-attachments/assets/3f03285e-473e-48cc-a7ba-f4d33615b374)

* Hit Convert

This task.json will run this script on VSCode start, and script will exit on first click, after VSCode is closed.

Thanks to [Qooqu](https://github.com/qooqu/vs-code-mbutton-scroll-ahk) for the base of this script.
