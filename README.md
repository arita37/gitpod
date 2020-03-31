# gitpod


Launch :

https://gitpod.io/#https://github.com/arita37/gitpod/tree/master



Buikd :

https://gitpod.io/#prebuild/https://github.com/arita37/gitpod



'''



tasks:
  - command: python3 -m http.server 8080
    name: Static Server
  - openMode: split-right
    command: echo SplitTerminal
  - openIn: left
    command: echo LeftPanelTerminal
openIn
You can configure where in the IDE the terminal should be opened:

openIn	Where
openIn:bottom	the bottom panel (default)
openIn:left	the left panel
openIn:right	the right panel
openIn:main	the main editor area



'''
