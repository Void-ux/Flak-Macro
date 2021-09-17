__**THIS WILL NOT WORK WITH AHK V2**__

This is a script compiled in AutoHotKey to quickly equip flak from a folder.

To use:
  - Install AutoHotKey [Here](https://www.autohotkey.com/)
  - Download the file in the repo
  - Double click on it to run it, or edit to:
    - Ensure that your **first folder** is the one with the fresh set of flak
    - Double check that `v` **is your inventory key**, else, you can change it in the script or your settings
    - Ensure the Sleep value is **not too short/long**

Customisation:
  - `z::` | Can be changed to anything, this is what executes the code
  - `Sleep, x` | Can be changed to any value (in ms). This is the delay for when you open your inventory as it takes some time. Slower machines often need more time.
  - `Send, v` | Can be changed to any key. This is what open/closes your inventory
