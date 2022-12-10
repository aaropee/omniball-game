# omniball-game
An attempt to make a sports-ish game for people who generally don't care about sports. And why not for people who do, sure.


Known issues by date:

09.12.2022:
  - Probuilder mesh creates a copy of plane as a copy of Field (Plane-preview in hierarchy) when selecting Play - mode
    - Seems like it's a fresh copy every time --> overrides the previous one <-- tried to rename the object, defaults back to plane-preview every time
    - FIXED : ^ this happens if you leave the 'New Shape' - window open in the background. So don't do that.
