# Pawn ANSI
Simple ANSI colored terminal text in Pawn.
## Attention
Windows is not supporting now! Please wait for updates.
## How to use?
If you working in Unix, just use it firstly:
```pawn
#include <ansi>
```
### List of Colors
```pawn
enum E_COLORS {
	BLACK,
	RED,
	GREEN,
	YELLOW,
	BLUE,
	MAGENTA,
	CYAN,
	WHITE,
	DEFAULT = 49
}
```
### Colored Output
You can change color of text or background by relevant functions:
```pawn
SetForeground(color);
SetBackground(color);
```
### Clearing
With **Pawn ANSI** you can clear line or screen in your console:
```pawn
ClearScreen(mode);
ClearLine(mode);
```
## ToDo
- [x] Unix foreground and background colouring
- [ ] Windows supporting
- [x] Screen and line clearing
- [ ] Cursor positioning
