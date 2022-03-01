# Vscode Terminal Color Settings
My Personal VSCode colorization settings for terminal 

1. Open vscode]
2. Open User Settings
 - Windows: `CTRL`+`,`
 - Mac: `CMD`+`P`

3. In the window that pops up, search for `workbench: color customizations" and edit the settings.json. 
4. Paste the following within the existin {} brakcets then customize as you like:
```json
"workbench.colorCustomizations": {
    "terminal.background":"#131212",
    "terminal.foreground":"#dddad6",
    "terminal.ansiBlack":"#1D2021",
    "terminal.ansiBrightBlack":"#665C54",
    "terminal.ansiBrightBlue":"#0D6678",
    "terminal.ansiBrightCyan":"#8BA59B",
    "terminal.ansiBrightGreen":"#237e02",
    "terminal.ansiBrightMagenta":"#8F4673",
    "terminal.ansiBrightRed":"#FB543F",
    "terminal.ansiBrightWhite":"#FDF4C1",
    "terminal.ansiBrightYellow":"#FAC03B",
    "terminal.ansiBlue":"#00a1f9",
    "terminal.ansiCyan":"#8BA59B",
    "terminal.ansiGreen":"#95C085",
    "terminal.ansiMagenta":"#8F4673",
    "terminal.ansiRed":"#FB543F",
    "terminal.ansiWhite":"#A89984",
    "terminal.ansiYellow":"#FAC03B"
},
```
