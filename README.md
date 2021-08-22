# ATTENTION
This fork been customized to work with DualShock 4 controllers and might not work with other gamepads.
See the [main project by ROMthesheep](https://github.com/ROMthesheep/Arcade-Bongo-Cat) if your gamepad doesn't work with this version.

(Below is the original README file)

___
Right now there are two distinct versions of this software, one focused on hitboxes/switch based sticks and two axis sticks and one focused on single axis fight sticks like the razor panthera and the victrix

To download each one you must seek them in the [releases page](https://github.com/ROMthesheep/Arcade-Bongo-Cat/releases)
or just click the links bellow

### [- Download hitbox/switch based stick and two axis sticks version](https://github.com/ROMthesheep/Arcade-Bongo-Cat/archive/v3.1.1.zip)
### [- Download one axis sticks version](https://github.com/ROMthesheep/Arcade-Bongo-Cat/archive/V3.1.zip)

___
# Fighter hitbox/arcade stick version of Osu Bongo cat!

[Video in action!](https://www.youtube.com/watch?v=QBGh3QNaqsM&feature=youtu.be)

[preview!](https://romthesheep.github.io/Arcade-Bongo-Cat/)

To match your controller button configuration use the usefull website https://html5gamepad.com. 
The default index contains the config for the [brook fighting](https://www.brookaccessory.com/detail/09922855/) pcb, tho changing this is pretty simple.

Atm the only available version is an hitbox controller, maybe in the future I will implement a fight stick version if I see demand for it.

# my controller doesnt match that configuration, what do I do?

[Step by step video guide (spanish)](https://www.youtube.com/watch?v=2YYZuEi9p7Y)

Head to https://html5gamepad.com and write down your Bvalues and the position on the board. 
I've assigned this keyvalues to the values of the board:

![](https://i.gyazo.com/22b7d8d1d8ae089f4074d55824894649.png)

You will have to match your Bvalues to vbX variables at the start of the js file. This is the default configuration:

![](https://i.gyazo.com/fbf4dddb205ad0c66197af03ba44ac5f.png)

If you want to enable the stick mode or your hitbox is axis based you will have to change the parameters below. 
Some users have inform me that their controllers use inverted logic for the X and Y axis, correcting this is as simple as changing the value of invertX and invertY as shown in the image.

![](https://i.gyazo.com/2d041b69a7981b755e389b4913a017c9.png)

# I want to use this on my OBS, how can I do it?

Create a browser source and paste your local directory on the url field like this:

![](https://i.gyazo.com/176f7bfb7af033a2e672b3b4a67cf0b6.png)

then use a color key filter to clear the green background and you are good to go!

# IMPORTANT NOTE
IF YOU ARE USING A CHEAP PCB (no shame) YOU MAY NEED TO UNPLUG AND PLUG AGAIN THE CONTROLLER

___

inspiration from [bongocat-osu](https://github.com/kuroni/bongocat-osu)

This proyect is on the end of its lifecycle, it will not get any new features, only maintenance
