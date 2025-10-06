
After finding [this mod](https://www.thingiverse.com/thing:5303395) that relocates the power supply of the Ender 3, I decided to design a box for the front section of the printer. This will create a space for the Raspberry Pi, which needs moved from it's box in the back, and gives a more cohesive aesthetic. Since updating my Ender 3 to Klipper firmware, I've exclusively been using Mainsail in the browser to wirelessly operate the printer. This makes the screen redundant, but it is nice to have the screen for monitoring purposes, and control if required. The brief therefore is to design a box that houses the motherboard, Raspberry Pi and buck convertor, and incorporates the screen into one of the lids which will be easily removable, and held in place with magnets.

This is what the front looked like with the original motherboard box on the left, the blue thing is a drawer I found on Thingiverse, and off to the right hand side is the screen. At the back right you can see the power supply in it's original vertical postion.

![Front](./images/15-ender-3-front.png)

This is what the back looked like with the original Raspberry Pi box I found on Thingiverse.

![Back](./images/15-pi-box-top.jpg)

To save on waste I decided to reuse the orange [fan duct](https://www.thingiverse.com/thing:2935204) for the motherboard fan.

![OG Duct](./images/15-mb-box-and-duct.jpg)

I printed the parts for the power supply mod, and after installation the printer is already looking much tidier.

![PSU Mod](./images/15-PSU-mod.JPG)

I deconstructed everything at the front of the printer to gain access to take measurements. I rewired the Raspberry Pi to sit at the front so the printer still functions, as it will need it to print parts for itself later!

![Front Deconstructed](./images/15-front-deconstructed.png)

I designed the box as a single piece, which will need to be split to be printed in 2 parts on the Ender 3. This is the layout, with motherboard on the left, and the Pi and buck convertor on the right. In the middle at the front is the motherboard fan drawing air in, which hits a splitter diverting the air equally between the Pi and motherboard. At the back behind a thin wall is the Pi's fan which pulls air out.

![Component Layout](./images/15-blender-layout.png)

The box is designed to slide into place, with ridges on the side which interface with the grooves in the aluminium extrusions of the printers frame. In the previous picture the beam in the middle is the air splitter, but it also acts as a structural component, and will have 2 bolts running through it which secure the box to the central y-axis extrusion with t-nuts.

I modelled the frame of the printer for accuracy. The 2 lids fit snuggly and are held with magnets, the right one holds the screen above the Pi. I designed some end caps for the extrusions, based on the back legs from the power supply mod.

![Blender Top](./images/15-blender-top.JPG)

On the bottom the fan duct mounts below the intake fan, and I designed another smaller fan duct for the exhaust fan. I also wanted easy access to the SD card in the Pi, so I made a small cut-out for access.

![Blender Bottom](./images/15-blender-bottom.JPG)

I split the box in two, and designed clips so it can snap together.

![Halved](./images/15-halves.JPG)

I printed the two halves and glued them together with super glue, before installing the magnets, Pi, buck convertor, original fan duct, and the other duct I designed and printed. You can see in this picture that I used a low profile 90° USB cable to connect the Pi and motherboard, as space was very limited.

![Pi Install](./images/15-pi-installed.JPG)

I printed the screen lid and installed the screen and magnets.

![Screen](./images/15-screen.JPG)

I designed the screen lid to work with this orange [back piece](https://www.thingiverse.com/thing:2987100) that I printed for the original printer, but it was a tight fit above the Pi when wired in, so I ended up removing the back piece as it's not essential.

![Screen Back](./images/15-screen-back.JPG)

To install the box: undo the y-axis belt tensioner, line up the t-nuts, lift up the motherboard, slide the box into place, then tighten the 2 bolts from underneath.

![Slide](./images/15-slide.JPG)
<div style="height: 1em"> </div>

![Installed](./images/15-installed.JPG)
<div style="height: 1em"> </div>

![Screen In](./images/15-screen-in.JPG)

At this point everything was installed and working and I just needed to print the other lid and the extrusion end caps. As the screen was originally on the side of the printer, the ribbon cable is long enough that you can print with the screen lid out like this if required.

![Screen Out](./images/15-screen-out.JPG)

Here's the final result!

![Final Top](./images/15-final-top.JPG)
<div style="height: 1em"> </div>

![Final Bottom](./images/15-final-bottom.JPG)

You can download the .stl files here:[Ender 3 (V1) Front Box with Removable Screen](https://www.thingiverse.com/thing:7164459)

<div style="height: 1em"> </div>

![Little Amby](./images/amby-little.gif)[i like chip](https://i-like-chip.github.io/)
