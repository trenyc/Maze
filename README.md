# Maze

To download the unity package for my Maze please visit this dropbox link:
https://www.dropbox.com/s/lpm7k559z12e7mg/mazepacakge.unitypackage?dl=0

To be able to hear the sound effects, on a windows machine you can simply play it in oculus with this build
https://www.dropbox.com/s/f8eh0oqhic18ywd/TrenycMaze.exe?dl=0

The maze has you get a key from a scary growling bear and then use the key to go through  a door to eventually find the win zone. 
You can see the screencast video here: https://youtu.be/D1ILVTttfRo

One thing to note is I am using spatial audio the bear growls louder as you get closer.

Probably the challenge I had was getting the teleport smooth, as it would flicker when doing other raycasting. 
To get around this I needed to change the raycast mask to only the teleport.
As for developing the world I used prefab floor tiles froma musuem pack I had. These were smaller tiles than Snaps, 
so I had to select many as group a copy the tiles to make my path.  The Progrids made everything smooth and easy.
I kept the interactables the same as the teaching video. Adding the spatial audio was pretty smooth, I did have to add
a ceiling above the scary bear to make his growl deafening when you really close to the bear. I also had to add meshes
to the book cases so that corner has all the sound bouncing off the surfaces to to make it reallly loud.

I used some paid packages for the decor and the spatial audio feature

I used SoundToolkit to do spatial audio: https://assetstore.unity.com/packages/tools/audio/soundtoolkit-136305

I used Art gallery Vol.3 - exhibition hall for the walls ceilings and some decor:
 https://assetstore.unity.com/packages/3d/environments/art-gallery-vol-3-exhibition-hall-201703




 
