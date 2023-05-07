Download Link: https://assignmentchef.com/product/solved-igc-homework4-make-a-20-%cc%b445-seconds-video
<br>
<h1></h1>

<ol>

 <li>Make a 20 ̴45 seconds video.</li>

</ol>

First 10  ̴30 seconds for playing the video.

Last 10  ̴15 seconds for introducing the features of the video and technique you have used.

<ol start="2">

 <li>Theme : Explosion</li>

 <li>Must include</li>

</ol>

(1). At least an object

(2). The states before explosion and after explosion

*Use GLSL to do this homework, otherwise you’ll get zero points.

<h1>Recording tools</h1>

<ol>

 <li>Screen recording : OBS : <a href="https://obsproject.com/">https://obsproject.com/</a></li>

 <li>Introduce your video :</li>

</ol>

(1). PowerPoint

(2). Other video editing tools

<h1>Something you can do</h1>

Ex :

<ol>

 <li>Particle system</li>

 <li>Camera movement</li>

 <li>Find resources (models, textures,…..) on the internet</li>

 <li>Other creative ideas…</li>

</ol>

<h1>Particle system example</h1>

You can define a particle with:

<ol>

 <li>Position: The particle’s position</li>

 <li>Speed: The particle’s speed</li>

 <li>Fade: The time step of particle’s fading</li>

 <li>Life: The life of the particle</li>

</ol>

Life = Life – Fade

If Life &lt; 0

The life cycle of the particle is end, reset the particle.

<h1>Particle system example</h1>

<ol>

 <li>Initialize your particles.</li>

 <li>You can use some random value for the speed of each particle.</li>

</ol>

<h1>Particle system example</h1>

<ol>

 <li>After initializing the particle system, send the particles’ initial positions and life into the shader by the method used in HW2 and HW3.</li>

 <li>Use the same method used in HW2 and HW3 to display the particles.</li>

</ol>

Draw the particles in points :

glDrawArrays(GL_POINTS, 0, 20000);

<h1>Particle system example</h1>

In fragment shader, you can give the particle different colors according to the particle’s life.

<h1>Particle system example</h1>

Remember to update the particles’ life and positions each frame. And resend them to the VBO.

<h1>Particle system example</h1>

<ol>

 <li>Because this is just a rough implementation written by TA,</li>

</ol>

(Just some flying points…not really an explosion) you can’t get the high score by totally using the same method with this particle example.

<ol start="2">

 <li>Try to use some technique about adding textures, handling multiple particle systems, particle physics …</li>

 <li>Make a good story for your explosion video to get higher votes.</li>

</ol>

<h1>Score</h1>

<ol>

 <li>Creativity (20%)</li>

 <li>Richness (20%)</li>

 <li>Integrity (30%)</li>

 <li>Votes from classmates (30%)</li>

</ol>

(We will provide a Google sheet and let you choose 5 best videos )

<h1>Others</h1>

<ol>

 <li>Upload your video to Youtube (must be anonymous), and upload your video link to New e3.</li>

 <li>The deadline is at 11:55 pm on January 10.</li>

 <li>If you submit your homework late, the score will be 0.</li>

</ol>