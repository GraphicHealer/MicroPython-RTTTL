# MicroPython-RTTTL
An RTTTL Script/Library for MicroPython

# Usage
Copy the `rtttl.py` script to your device to use.
```
import rtttl

song = 'Super Mario - Main Theme:d=4,o=5,b=125:a,8f.,16c,16d,16f,16p,f,16d,16c,16p,16f,16p,16f,16p,8c6,8a.,g,16c,a,8f.,16c,16d,16f,16p,f,16d,16c,16p,16f,16p,16a#,16a,16g,2f,16p,8a.,8f.,8c,8a.,f,16g#,16f,16c,16p,8g#.,2g,8a.,8f.,8c,8a.,f,16g#,16f,8c,2c6'

rtttl.play(song)
```
The `song.py` file is a simple interface and collection of RTTTL songs in one place. You may use it if you wish, but it is not neccissary.
Commands for the `song.py`:
 - **ls()** *List all songs in the SONGS list*
 - **play("Song Name")** *Play song from SONGS list*
 - **playALL()** *What do you think it does?*
