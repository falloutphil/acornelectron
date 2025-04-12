
# Unfinished Space Invaders

In less than 600 bytes - with some caveats!

There is only one alien, the score breaks beyond 9, and the code is a poor-man's replacement for proper sprite use, etc.  All of these problems have solutions, if I ever have the time (probably not given I wrote this 12 year ago!).

The ghosting on the screenshot is the GIF compression not a problem with the game - if anything the animation of the bugs legs and antennae is the coolest thing in the code!

![Space Invaders Screenshot](spaceinv_screenshot.gif)

# Directions
The SSD file is a single side disk (DFS format) - you should be able to mount it on most Acorn Electron emulators.
The following commands will then load, assemble, and run the demo:

```
*DISC
CHAIN "SPACE"
```

SSD files can also be loaded onto Acorn Electron hardware using and Elk64SD or Elk128SD device - see EBay.

```
*DCAT
*DIN <disk image number containing ssd>
CHAIN "SPACE"
```

Failing that Electrem and BeebEm both allow you to cut and paste the raw text provided here into the emulator.
Then just type `RUN`.


