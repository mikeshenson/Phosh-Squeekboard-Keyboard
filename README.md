# Phosh-Squeekboard-Keyboard
Custom Phosh Squeekboard Keyboard Layout that looks like a US English 104 Keyboard layout. This needs to be use added locally because it has quick preset keys for text. 

## How to use
Make the ~/.local/share/squeekboard/keyboards/ directory <br>
Copy all these files to ~/.local/share/squeekboard/keyboards/  <br>
File structure should look like: <br>
~/.local/share/squeekboard/keyboards/us.yaml <br>
~/.local/share/squeekboard/keyboards/number/us.yaml <br>
~/.local/share/squeekboard/keyboards/terminal/us.yaml <br>
From there it should get picked up by squeekboard automatically. <br>

Manual inputs <br>
Open the yaml files up and look for "M4" replace the text and label with your own strings.

## Screenshots
![ScreenShot](Keyboard_Portrait.png) <br>
![ScreenShot](Keyboard_Landscape.png)

References
--------

- Squeekboard source
- https://gitlab.gnome.org/World/Phosh/squeekboard
- 
- creating layouts
- https://developer.puri.sm/projects/squeekboard/tutorial.html

