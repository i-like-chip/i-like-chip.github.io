I designed this body modification for my Ender 3 (V1) which is both functional and improves aesthetics. Here's the before and after:

![Before/After](./images/15-before-after.png)

I found [this mod](https://www.thingiverse.com/thing:5303395) that relocates the power supply unit (PSU) of the Ender 3. Originally in a vertical position on the side, the mod moves the PSU to a horizontal position under the bed at the back. As I have upgraded to Klipper firmware, I had a Raspberry Pi in a box at the back already, so that needed relocated. I also wanted to move the screen into a more compact position, as I rarely use it since upgrading to Klipper and Mainsail OS for wireless control.

This is what the back looked like with the original Raspberry Pi box I found on Thingiverse.

![Back](./images/15-pi-box-top.jpg)

To save on waste I decided to reuse the orange [fan duct](https://www.thingiverse.com/thing:2935204) that was mounted like this for the motherboard fan.

![OG Duct](./images/15-mb-box-and-duct.jpg)

I printed the parts for the power supply mod, and after installation the printer was already looking much tidier.

![PSU Mod](./images/15-PSU-mod.JPG)

I deconstructed everything at the front of the printer to gain access to take measurements. I rewired the Raspberry Pi to sit at the front so the printer still functions, as it will need it to print parts for itself later!

![Front Deconstructed](./images/15-front-deconstructed.png)

The brief is to design a box that houses the motherboard, Raspberry Pi, the Pi's buck convertor, and incorporates the screen into the design in a compact way. The design must incorporate the original motherboard fan and the Pi's fan for cooling.

This is the layout, with motherboard on the left, and the Pi and buck convertor on the right. In the middle at the front is the intake fan (the original motherboard fan), which hits a splitter diverting the air equally between the Pi and motherboard. At the back behind a thin wall is the exhaust fan, from the Raspberry Pi. I thought it would be nice to try and optimise airflow to improve cooling, for printing fast!

![Component Layout](./images/15-blender-layout.png)

The box is designed to slide into place, with ridges on the side and back which interface with the slots in the printer's aluminium extrusions.

![Ridges](./images/15-ridges.png)

The beam in the centre is shaped on the underside to split the intake air, but it also acts as a structural component. It interfaces with the central y-axis extrusion, and will have 2 bolts running through it which secure the box to the frame with two M3 bolts and t-nuts.

![Middle Beam](./images/15-middle-beam.png)

I modelled the frame of the printer, and added in the PSU mod parts. The 2 lids fit snuggly, with the right one holding the screen. I made some end caps for the extrusions, modified from the back legs of the PSU mod.

![Top View](./images/15-top-view.png)

The front edge of the box is bevelled, so that the lids overhang to make it easier to remove them. The lids and end caps have a matching bevel for aesthetics.

![Bevels](./images/15-lid-bevel.png)

On the bottom the fan duct mounts below the intake fan, and I designed another smaller fan duct for the exhaust fan. I also wanted easy access to the SD card in the Pi, so I made a cut-out for access.

![Bottom View](./images/15-bottom-view.png)

I designed clips on either side of the box so the two halves can be aligned and glued together easily.

![Side Clips](./images/15-side-clips.png)

I also made a tongue and groove in the centre beam for alignment and gluing.

![Tongue and Groove](./images/15-middle-tongue-groove.png)

With the design complete I printed the two halves with supports for the central beam.

![Halved](./images/15-halves.JPG)

I used super glue to bond the two halves, and glue in the magnets. I installed the Pi, buck convertor, and the two fans and their ducts. You can see in this picture that I used a low profile 90° USB cable to connect the Pi over to where the motherboard will be, as space was very limited. This cable replaces the USB cable that used to stick out the front of the printer, and awkwardly trail around to the Raspberry Pi which was at the back.

![Pi Install](./images/15-pi-installed.JPG)

I printed the screen lid and installed the screen and magnets.

![Screen](./images/15-screen.JPG)

I designed the screen lid to work with this orange [back piece](https://www.thingiverse.com/thing:2987100) that I printed for the original screen mount, but it was a tight fit above the Pi when wired in, so I ended up removing it as it's not essential.

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

![Final Screen Out](./images/15-print-with-screen-out.JPG)
<div style="height: 1em"> </div>

![Final Bottom](./images/15-final-bottom.JPG)

You can download the .stl files here:[Ender 3 (V1) Front Box w. Detachable Screen + Optimised Air Flow](https://www.thingiverse.com/thing:7164459)

<div style="height: 1em"> </div>

![Little Amby](./images/amby-little.gif)[i like chip](https://i-like-chip.github.io/)
