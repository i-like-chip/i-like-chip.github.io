
A friend asked me to 3D print a replacement knob for their camping stove, as it was lost on a trip!

### Modelling the Shaft

 All I had to work with was the other original knob from the camping stove, so I started by taking some measurements and modelling the D-shaped shaft. I printed it to test the fit with the original knob.

![D-shaped-shaft](./images/day-11-shaft.png)

### Modelling the Knob

As it's for a camping stove I decided to go for a flower shape to fit the nature vibe. I mainly used Boolean modifiers to combine shapes, cut out the inside, and use the shaft model to cut out the D-shaped hole.

![knob-v1.1](./images/day-11-blender-knob-1.png)
![knob-v1.2](./images/day-11-blender-knob-2.png)

I printed this knob but found that it was a little bit tight on the shaft that I printed earlier. I also wasn't happy with how sharp the edges were, and the mesh in Blender seemed very messy.

### Modelling V2

I tried to do some manual mesh editing but it proved difficult, so I ended up remodelling the whole object from scratch. I then used a method from [this video](https://youtu.be/sB68HUH87dk?si=vFysSH3rJOFzn7ug) to smooth the edges and improve the mesh - essentially you apply the modifiers Remesh, Smooth Corrective, then Decimate.

![knob-v2.1](./images/day-12-blender-knob-1.png)
![knob-v2.2](./images/day-12-blender-knob-2.png)

In Prusaslicer I used concentric infill on the top and bottom layers for aesthetic reasons.

![prusa-1](./images/day-12-prusa-knob-1.png)
![prusa-2](./images/day-12-prusa-knob-2.png)

Here is the final result:

![print-2.1](./images/day-12-knob-v2-top.png)
![print-2.2](./images/day-12-knob-v2-bottom.png)

After making sure it fit nicely on the shaft I printed a second knob so my friend would have a matching pair!

  <div style="height: 1em"> </div>
