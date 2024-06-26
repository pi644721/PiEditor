# About
A program and Celtic CE appvar editor for the TI-84+CE calculator written by pi644721.
This program requires the Celtic CE libraries, which can be found at [bit.ly/CelticCE](https://bit.ly/CelticCE). 
Please give feedback and report bugs [here](https://cemetech.net/forum/viewtopic.php?t=19472).

# Credits
Thanks to Vital Ash for Aether, the on-calc program editor that I wrote a lot of this program editor in and RoccoLox Programs for Celtic CE, which made this editor possible.

# Use
On the main menu:
- Press `2` or `3` to edit a program or appvar. Use `alpha` to toggle between uppercase characters, lowercase characters (if you're editing an appvar), and numbers. Enter the program/appvar's name and press enter to enter the editor.
- Press `1` to view a list of recently edited programs and choose that program with the `1` - `8` keys, or press `clear` to return to the main menu.

# Keys
| Key(s) | function |
| ------ | -------- |
| `up` and `down` | Moves the cursor up or down one line and to the beginning of the line |
| `left` and `right` | Moves the cursor one token to the left or right |
| `2nd` and `alpha` | changes what token is inserted when typing |
| `mode` | Exits the editor |
| `enter` | Creates a new line, and moves all characters under and after the cursor to the new line |
| All keys below the arrow keys | Types a token based on the current keyboard. See [keyboards](https://github.com/pi644721/PiEditor/blob/main/README.md#keyboards)|
| `Y=`* | Changes the theme of the program |
| `graph`* | Exits the program to the main menu |
| `Zoom`* | Prompts a line to jump to. To jump a relative ammount, put a `+` or `-` before the number |
| `Window`, and `Trace`* | Jump up or down 12 lines |

\* Upcoming feature, not yet working


## Keyboards
Press `alpha` and `2nd` to change what characters are typed when a key is pressed.

### No modifiers
Numbers and Logic
| &nbsp; &nbsp; and &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; != &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; ≥ &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; ≤ &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :---: | :---: | :---: | :---: | :---: |
|  or   |   =   |   >   |   <   |   ^   |
|  not( |   ,   |   (   |   )   |   /   |
|  min( |   7   |   8   |   9   |   *   |
|  max( |   4   |   5   |   6   |   -   |
| sto-> |   1   |   2   |   3   |   +   |
|       |   0   |   .   |  (-)  |newline|

### 2nd
Program control, I/O, String manipulation and more
| Lbl | Goto | Menu( | prgm | |
| :---: | :---: | :---: | :---: | :---: |
|ClrHome| Input |Output(|  Disp |getKey |
|length(|  sub( |toString( | expr( |inString( |
|  det( |  End  | Pause |  Wait |  (?)  |
|rowSwap(|  For( | While |Repeat |  (?)  |
|  (?)  |   If  | Then  | Else  |  (?)  |
|       |Return | Stop  |Delvar |newline|

(?): Not asigned token yet. Feel free to suggest what to put here.

### Alpha
Uppercase characters/Real variables
| &nbsp; &nbsp; &nbsp; A &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; B &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; C &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; StrX &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :---: | :---: | :---: | :---: | :---: |
|   D   |   E   |   F   |   G   |   H   |
|   I   |   J   |   K   |   L   |   M   |
|   N   |   O   |   P   |   Q   |   R   |
|   S   |   T   |   U   |   V   |   W   |
|   X   |   Y   |   Z   | theta |   "   |
|       | space |   :   |  Ans  |newline|

StrX: Planned feature  
Theta: looks like `θ`

### Alpha + 2nd
Lowercase letters
| &nbsp; &nbsp; &nbsp; a &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; b &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; c &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :---: | :---: | :---: | :---: | :---: |
|   d   |   e   |   f   |   g   |   h   |
|   i   |   j   |   k   |   l   |   m   |
|   n   |   o   |   p   |   q   |   r   |
|   s   |   t   |   u   |   v   |   w   |
|   x   |   y   |   z   |   .   |   "   |
|       | space |   !   |   ?   |newline|
