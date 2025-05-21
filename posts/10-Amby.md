
### Amby - Modelling and Animation

I decided that it would be cool to have a mascot for the ambient youtube channel so I created Amby. This was my first time doing sub-division modelling, and doing animation in Blender. I used an image on the xz plane as a reference for modelling, and used the mirror modifier to position the ears, ayes, and arms.

![amby](./images/day-10-amby-solid.PNG)

To animate Amby I had to rig the model, so I followed another couple of Joey Carlino's videos, [Rigging for beginners](https://youtu.be/m-Obo_nC3SM?si=KPkxLuXf9UDc9T2W) and [Rigging for impatient people](https://youtu.be/DDeB4tDVCGY?si=ILNaJpjzpzyMmocK).

Here's Amby rigged up for ear, eye, and arm movement:

![amby-rigged](./images/day-10-amby-bones.PNG)

Here's a test animation:

![amby-animated](./images/day-10-amby-v1.gif)

  <div style="height: 1em"> </div>

### Amby - Holographic

As the scene I've been making is sc-fi themed I decided to try and make Amby into a hologram. I followed [this video](https://youtu.be/0OsgS2JpM8k?si=BROIPg1-HVckylGX) by Blender Guru where he shows a really cool way of turning an object into a hologram using geomery nodes. Essentially you make a 3D array of glowing orbs wich are effectively pixels. You then place an object within array, and only 'turn on' the pixels which intersect the object!

Here you can see how I've separated out the ears and nose and they now appear as collection of pink glowing orbs.

![amby-geo-nodes](./images/day-10-amby-holo-geo-nodes.PNG)

Repeating this for each colour give this, which looks pretty cool!

![amby-holo](./images/day-10-amby-holo.PNG)

It is quite intensive for the computer as I am using four colours, which means there are four 3D arrays of glowing orbs occupying the same space, as you need a separate array for each colour. You could probably scale down the arrays so you have fewer 'pixels' that are not 'turned on.'

<div style="height: 1em"> </div>
