# About
A program editor for the TI-84+CE calculator
This program requires the Celtic CE libraries, which can be found at [bit.ly/CelticCE](https://bit.ly/CelticCE). 
Please give feedback and report bugs [here](https://cemetech.net/forum/viewtopic.php?t=19472).

# Credits
Thanks to Vital Ash for Aether, the editor that I wrote a lot of this in, and RoccoLox Programs for the Celtic CE libraries, which made this editor possible.

# Keys
| Key(s) | function |
| ------ | -------- |
| `up` and `down` | Moves the cursor up or down one line and to the beginning of the line |
| `left` and `right` | Moves the cursor one token to the left or right |
| `2nd` and `alpha` | changes what token is inserted when typing |
| `mode` | Exits the editor |
| `enter` | Creates a new line, and moves all characters under and after the cursor to the new line |
| All keys below the arrow keys | Inserts a token based on the current keyboard. See [keyboards](https://github.com/pi644721/PiEditor/blob/main/README.md#keyboards)|
| `trace` and `graph` | moves the cursor down/up 8 lines |
| `clear` | Exits the program |

## Keyboards
Press `alpha` to type an uppercase character, press `2nd` to type lowercase letters. Press `alpha` again to type numbers.

### Numbers and Logic: no modifiers
| &nbsp; ... &nbsp; | &nbsp; ... &nbsp; | &nbsp; ... &nbsp; | &nbsp; ... &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; |
| :---: | :---: | :---: | :---: | :---: |
|   =   |  Ans  |   {   |   }   |   ^   |
|   K   |   ,   |   (   |   )   |   /   |
|   :   |   7   |   8   |   9   |   *   |
|  det( |   4   |   5   |   6   |   -   |
| sto-> |   1   |   2   |   3   |   +   |
|       |   0   |   .   |  (-)  |       |

### Uppercase characters/Real variables: alpha
| &nbsp; &nbsp; A &nbsp; &nbsp; |&nbsp; &nbsp; B &nbsp; &nbsp; | &nbsp; &nbsp; C &nbsp; &nbsp; | &nbsp; &nbsp; ? &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :---: | :---: | :---: | :---: | :---: |
|   D   |   E   |   F   |   G   |   H   |
|   I   |   J   |   K   |   L   |   M   |
|   N   |   O   |   P   |   Q   |   R   |
|   S   |   T   |   U   |   V   |   W   |
|   X   |   Y   |   Z   | theta |   "   |
|       | space |   :   |  Ans  |       |

### Lowercase letters: alpha + 2nd
| &nbsp; &nbsp; b &nbsp; &nbsp; |&nbsp; &nbsp; b &nbsp; &nbsp; | &nbsp; &nbsp; c &nbsp; &nbsp; | &nbsp; &nbsp; ? &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :---: | :---: | :---: | :---: | :---: |
|   d   |   e   |   f   |   g   |   h   |
|   i   |   j   |   k   |   l   |   m   |
|   n   |   o   |   p   |   q   |   r   |
|   s   |   t   |   u   |   v   |   w   |
|   x   |   y   |   z   |   .   |   "   |
|       | space |   :   |   ?   |       | 

## Menus:
When typing numbers, press `math`, `apps`, `prgm`, `vars`, or `stat` to open various menus.
Cycle between different menus under the same key with `left` and `right`.
Press `clear` to exit the menu and `enter` to select the first option.
The menu doesn't actually get displayed, but the menu name is displayed in the top bar. Press number and letter keys to insert the corresponding token.

### Math
#### Test/logic
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 |
| - | - | - | - | - | - | - | - | - | - |
| = | > | < | ≠ | ≥ | ≤ | and | or | not( | xor |

#### Number
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | A |
| - | - | - | - | - | - | - | - | - | - | - |
| abs( | round( | iPart( | fPart( | int | min( | max( | real( | imag( | sum( | mean( |
#### Random
| 1 | 2 | 3 |
| - | - | - |
| rand | randInt( | randIntNoRep( |

### Apps
#### String operators
| 1 | 2 | 3 | 4 | 5 | 6 |
| - | - | - | - | - | - |
| sub( | length( | inString( | eval( | expr( | toString( |

### Prgm
#### Control
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | A | B | C | D | E | F | G | H |
| - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |
| If | Then | Else | For( | While | Repeat | End | Pause | Lbl | Goto | Wait | IS>( | DS<( | Menu( | prgm | Return | Stop | Delvar |
#### I/O
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| - | - | - | - | - | - | - | - |
| Input | Prompt | Disp | Pause | Menu( | Output( | getKey | ClrHome |

### Vars
#### Strings
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 |
| - | - | - | - | - | - | - | - | - | - |
| Str1 | Str2 | Str3 | Str4 | Str5 | Str6 | Str7 | Str8 | Str9 | Str0 |
#### Colors
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | A | B | C | D | E |
| - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |
| BLUE | RED | BLACK | MAGENTA | GREEN | ORANGE | BROWN | NAVY | LTBLUE | YELLOW | WHITE | LTGRAY | MEDGRAY | GRAY | DARKGRAY |

### Stat
#### List
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 |
| - | - | - | - | - | - | - | - | - | - |
| L1 | L2 | L3 | L4 | L5 | L6 | L | { | } | SetUpEditor |

`L1` - `L6` are the default list tokens, `L` is the custom list token.

#### List operators
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 |
| - | - | - | - | - | - | - | - | - | - |
| SortA( | SortD( | dim( | Fill( | seq( | cumSum( | deltaList( | augument( | List>Matr( | Matr>List( |
