
#### Spinning an HDRI

My previous attempts to create the feeling of moving through space were not ideal, so I had the idea to rotate an HDRI through 360°. This would eliminate the spinning feeling with the previous videos, as the HDRI is a large sphere with the camera at the centre, the video will mostly 'come in' on one side of the viewport and 'go out' on the other. This should result in the feeling of looking out a window of a spaceship travelling in a straight line as the stars should slide past the window horizontlly.

The HDRI was a free one on BlenderKit, called 'Deep Dark Space with Stars' by EB Adventure Photoscans. In the shading tab I used keyframes to automate the rotation in the mapping node. Starting at 0° and finishing at 360° at frame 14,400 (10minutes at 24fps).

![hdri](./images/day-9-spinning-the-hdri.PNG)

Here's the result as a .gif:

![stars going by 10min](./images/day-9-stars-going-by-10min.gif)

You can watch the full 4K video here:

<iframe width="1000" height="315"
src="https://www.youtube.com/embed/z6IF3eYsmPw">
</iframe>

The upload to YouTube took about 15mins, +70mins extra for 4K (I don't think it actually took this long).  

Exporting the render took a few hours, so I exported each frame individually into a folder in case Blender crashed. This required about 70GB free space. I composited the frames into a 4K video using the Blender video editor, I can't remember how long the rendder took, maybe an hour?

<div style="height: 1em"> </div>

Layering the video into the spaceship scene made it clear that 10mins is not long enough as it felt like the spaceship was moving too quickly. Slowing the video down in the video editor meant that it no longer felt smooth.  

Here's the result as a .gif:

 ![scene with 10min stars](./images/day-9-10min-spin-layered-13.5s-25fps.gif)

  <div style="height: 1em"> </div>

#### Slowing Down

I repeated the process of spinning the HDRI but this time over 1 hour, and at 30fps as I found out this is preferred by YouTube. The render required about 250GB of free space as there were 108,000 4K frames, it took about 16hrs.

Here's the result as a .gif:

![stars going by 1hr](./images/day-9-stars-going-by-1hr.gif)

You can watch the full video here:

<iframe width="1000" height="315"
src="https://www.youtube.com/embed/">
</iframe>

The upload to YouTube took about 1hr and 55mins, so a 10hr video at that rate would take a little more than 19hrs to upload.  

  <div style="height: 1em"> </div>

Layering this version into the scene has a more relaxing feel to it, like drifting through space.  
Here's the result as a .gif:

![scene with 1hr stars](./images/day-9-1hr-spin-layered-13.5s-25fps.gif)



<div style="height: 1em"> </div>
