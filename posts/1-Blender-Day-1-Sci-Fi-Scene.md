
### A Sci-Fi Scene

I've used various other CAD and 3D modelling software, both for work and personal projects, but so far have not used Blender. It's free and is capable of doing all sorts of things that I want to explore so I decided to start learning. I'd been watching a lot of ambient videos on youtube, and I figured making an ambient scene would be a good first project in Blender.

I decided to make a room on a spaceship, and began by making a box using planes, so I can remove individual walls and the ceiling for easier access to the interior. With a cylinder, I used the Boolean modifier in difference mode to punch a hole in one of the planes to make a window.

![Box](./images/1-box.png)

After this I started thinking about how I might make some stars move past the window...

<div style="height: 1em"> </div>

### Spinning the Crystal Ball Nebula

To create the desired effect I came up with a method: I decided to try rotating a square image, with the viewport zoomed in so that it traces a circle around the centre, which will output a looped video.

I used an image of the [Crystal Ball Nebula](https://www.jpl.nasa.gov/news/wise-image-reveals-strange-specimen-in-starry-sea/#carousel-4cca880b-e47b-4039-af7b-fc3bb27c303f-3) by NASA.

To illustrate how this works I've un-linked the image file so what's visible through the viewport appears as a pink rectangle - the white square is the outline of the image:

![nasa-star-spin-blender.gif](./images/2-nasa-star-spin-blender.gif)

I made the animation length 8640 frames i.e 6mins, and set keyframes on the rotation transform:

![nasa-star-spin-blender.png](./images/2-nasa-star-spin-blender.PNG)

Here's a segment of the video as a 15s .gif at 24fps:

![nasa-star-spin-15s-25fps](./images/2-nasa-star-spin-15s-25fps.gif)

You can watch the full video [here](https://www.youtube.com/embed/PAQsf1-hg3c). The image used was 2618x2618 pixels, so I'll need a much bigger image to produce a video with good resolution at 4k, and feels more like linear movement.

<div style="height: 1em"> </div>

### Spinning Stephan's Quintet

I repeated the process with a much higher resolution image which is 12654x12132, of [Stephan's Quintet](https://webbtelescope.org/contents/media/images/2022/034/01G7DA5ADA2WDSK1JJPQ0PTG4A) from the James Webb telescope,

Here's a segment of the video as a 15s .gif at 24fps:

![james webb](./images/2-james-webb-spin-15s-25fps.gif)

You can watch the full video [here](https://www.youtube.com/embed/PT7LtP-Jvtk). The resolution is much better with this image, but I think I can do better, and have another idea I'm going to try later...

<div style="height: 1em"> </div>

### Video on a Plane

Now that I have some video of stars, I wanted to figure out how to position the video in the scene. I found [this](https://www.youtube.com/watch?v=ssnJ8yewQ2A&t=2s) video by TLDStudios to be helpful.  

Here's what I did:  

* Created a plane and changed the colour to ‘Image texture’ before selecting one of the videos made earlier.
* Changed the surface to ‘Emission’ to prevent light reflecting off the video surface.
* Placed the plane outside the ‘window’ of the box.


![plane](/images/3-plane.png)

![scene](/images/3-scene.png)

<div style="height: 1em"> </div>

### Blenderkit and Lighting

I downloaded BlenderKit and placed a rug and plant in the scene, then played around with lighting and colours after watching [this video](https://www.youtube.com/embed/JJV8l6MaXxA) on lighting by Ryan King.

![rug and plant](/images/3-rug-plant.jpeg)

<div style="height: 1em"> </div>

![Little Amby](./images/amby-little.gif)[i like chip](https://i-like-chip.github.io/)
<div style="height: 1em"> </div>
