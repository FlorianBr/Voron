
# Build Log

## The Frame

Mostly according to the documentation. Instead of Misumi profiles I used ITEM profiles and ITEM standard fasteners. Mostly works without problems, but some parts need minor modifications.

All screws are secured with Loctite Medium.

<img src="./imgs/frame1.jpg" width="25%" height="25%">
<img src="./imgs/frame_01.jpg" width="25%" height="25%">

## The Feet

The four feet in the corners with steppers. All parts are printed with black or red ASA.

<img src="./imgs/riemenantriebe.jpg" width="25%" height="25%">
<img src="./imgs/fuesse_01.jpg" width="25%" height="25%">
<img src="./imgs/fuesse_02.jpg" width="25%" height="25%">

## Controllers

View from the bottom with the wiring and controller boards.
The Octopus Pro can power the Raspberry Pi directly, no need for an additional 5V PSU.
I also have the Raspi connected twice to the Controller, with USB as well as serial.

<img src="./imgs/elektro_01.jpg" width="25%" height="25%">

Final (maybe) wiring. Including front display, the shelly for auto-off, fans and so on.

<img src="./imgs/elektro_02.jpg" width="25%" height="25%">

## Stealthburner

The Stealtburner with the 2 PCBs of the CAN board. The main PCB with controller and stepper driver in the extruder, another PCB with fan connectors in the front. The eddy probe will be connected to the front too.

<img src="./imgs/SB_Front.png" width="25%" height="25%">
<img src="./imgs/SB_Extruder.jpg" width="25%" height="25%">


### Voron TAP

The voron tap CNC, replacing the printed carriage.

<img src="./imgs/VoronTap.jpg" width="25%" height="25%">

### Eddy Probe

NOTE: Klipper supports only one probe, Eddy or Tap. I currently disabled Eddy, Tap seems to be more reliable.

Normally the eddy probe replaces the inductive probe in the carriage, but with the voron tap there is no room for that anymore. So it is placed at the side of the hotend.

<img src="./imgs/SB_Hotend.png" width="25%" height="25%">

### Brush Bucket

Close to the Z-Endstop is the [Nozzle Brush with Bucket](https://www.printables.com/model/201999-nozzle-scrubber-with-a-little-bucket-for-voron-24?lang=de). The bucket is removable and is secured by magnets. I am thi I am thinking about moving it to the front for easier access.

<img src="./imgs/brush_cam.jpg" width="25%" height="25%">

### LED Lights

In the front top corner are the LED lights. At first I wanted to use three separated holders, but I was too lazy and use a larger, single one now. Still with 3 Neopixel LED-Strips.

<img src="./imgs/cam_led.jpg" width="25%" height="25%">

### Primary Cam

The primary Cam is looking down at the print, using the [AngryCam](https://mods.vorondesign.com/details/RYpQW53mtem8Nj1JKqiSQ) case. My cams PCB is slightly different so the AngryCam parts are not fitting very well. But I am thinking about replacing all the cams anyways, the video quality of these USB cameras is horrible.

<img src="./imgs/cam_led.jpg" width="25%" height="25%">

### Secondary Cam

Close to the bucket at the back is the secondary cam in a [CamHolder](https://www.printables.com/model/673803-5mp-cam-usb-for-76-degree-auto-fixed-focus-usb-cam)

<img src="./imgs/brush_cam.jpg" width="25%" height="25%">

### BTT Touch Display

Replacing the original small display with encoder with a 5" Touch-Panel from BTT, KlipperScreen and a [Display Mount](https://www.printables.com/model/926845-btt-hdmi5-v12-display-mount-voron). Much more comfortable to control the printer!

<img src="./imgs/display.jpg" width="25%" height="25%">
