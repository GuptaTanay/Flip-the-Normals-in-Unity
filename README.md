# Flip-the-Normals-in-Unity
This project is used to flip the normals of an object to play 360 degree video inside the sphere.


<br>
Step 1: Create a Sphere and scale it to (100,100,100) and place it to (0,0,0) . Now place the camera at (0,0,0).
<br>
Step 2: Drag and drop your 360 degree video file into asstes folder and then drop your video file on the sphere.
<br>
Step 3: The video file will be on the outer surface on the sphere and you will not be able to see anything because the normals are outside the sphere.
<br>
Step 4: Create a Shaders folder in your Asstes and then, drag and drop this file to your project.
<br>
Step 5: Now create  a material and from the Inspector and then from the Shader in the Inspector. Go to the Custom> Flip Normals.
<br>
Step 6: Drop this material on to the sphere and now Save and click on Play.
<br>
Step 7: Now you will see your 360 degree video running.
