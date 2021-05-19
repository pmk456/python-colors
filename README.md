# Colors In Python 

## Important Note
```
THESE ARE THE CODES FOR COLORS IN LINUX TERMINAL JUST LIKE HTML
BG = BACKGROUND
BR = BRIGHT
BG_BR = BRIGHT BACKGROUND
THIS ONLY WORKS IN LINUX TERMINAL AND DIDN'T WORK IN CMD OR POWERSHELL IN WINDOWS
```
## Installation 
```
sudo apt install python3 python3-pip
pip install python-colors-linux
```
## Installation Using Source Code
```
git clone https://github.com/pmk456/python-colors.git
cd python-colors
python3 setup.py install
```
## Usage
```
For Ex: Using Blue Color
import colors
colors = colors.colors()
print(colors.BLUE + "Your Text")
```
## All Available Colors
```
BG = BACKGROUND
BR = BRIGHT
BG_BR = BRIGHT BACKGROUND
RED
BLUE
CYAN
YELLOW
GREEN
MAGENTA
WHITE
BR_RED
BR_GREEN 
BR_YELLOW 
BR_BLUE 
BR_MAGENTA 
BR_CYAN 
BR_WHITE 
BG_BLACK 
BG_RED 
BG_GREEN 
BG_YELLOW 
BG_BLUE 
BG_MAGENTA 
BG_CYAN 
BG_WHITE
BG_BR_BLACK
BG_BR_GREEN 
BG_BR_YELLOW
BG_BR_BLUE
BG_BR_MAGENTA 
BG_BR_CYAN 
BG_BR_WHITE 
RESET
BOLD 
REVERSE
UNDERLINE
```
