HW3

Kevin Teng Wu

Student ID: 1405521

Part A------------------------------

This part is extra credit.  As per requirements, I made SDF text from 3 different fonts, using their jsons and atlas pngs.  

They are animated in various ways, and you can change the buffer and gamma of them.  




Part B-------------------------------

For Part B, I did 4 SDF objects. 

It is a little hard to tell the phong lighting, but there are two lights (one blue and one green) that are moving back in forth.

The easiest way to tell that the there are phong lights is looking at the bottom-right object.  You can see the glare of the lights moving and the color of the lights changing.  Or you can look at the code.  It's in the fragment shader, too.


I have a morphing object in the top right.  10 seconds is too slow, so its an animation in 1-2 seconds instead.

I did the extra credit for this too, and put on a lava texture.  Easiest way to tell, surprisingly, is looking at the top-left object.  You can see the texture moving and bending WITH the SDF object.  

Part C----------------------------

For part C, I did Melting Effect.  That is, a object solid which melts into an object. You can read the PDF, but the gist of it is that melting is very slow and smart vertex displacement in the vertex shader.  