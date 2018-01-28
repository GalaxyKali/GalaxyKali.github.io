HW1

Kevin Teng Wu

Student ID: 1405521

Part A--------------------------------

For Part A, I have three objects with different shaders.
	-One is a crystal with an icy texture shader
	-One is a fan with phong lighting + texture shader
	-One is a stone lantern with a varying wireframe shader.

Three lights move in the scene accordingly as followed:
-fanMesh.material.uniforms.light1_pos.value = new THREE.Vector3(2* Math.sin(time * 0.002), 4.0, 0.0);
-fanMesh.material.uniforms.light2_pos.value = new THREE.Vector3(0.0, 4* Math.sin(time * 0.003), 0.0);
-fanMesh.material.uniforms.light3_pos.value = new THREE.Vector3(0.5, 0.0, -3* Math.sin(time * 0.002));

That is, one light moves left and right above the fan, one light moves up and down, and another light moves back and forth along the z axis.


Part B--------------------------------

For Part B, I used the sharpen kernel:

(0, -1, 0,
-1, 5, -1,
 0, -1, 0)

And you can move your mouse left and right to see the change in effect.  For this, please look carefully.  The sharpening of the image does work


Part C------------------------------

For Part C, I have 27 states of different colors, randomly placed in a texture.  You can see the images for the in_process and final states.  I am most proud of this kind of cellular automata.


Part D-------------------------------

For the visual effect I chose, I used the Legend of Zelda-The Wind Waker's ocean, which is a undulating mesh with an animated texure shader.  

