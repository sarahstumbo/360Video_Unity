# 360Video_Unity
A sample project on how to playback a 360 video in Unity using the 5.6 Video Player component. 

Steps:
1) Create a sphere set the position to (0,0,0)
2) Scale the sphere up to (50,50,50)
3) Make Sure Camera is centered in middle of sphere
4) Create new material – Change Shader Ulit TextureInsideUnlitColor. This shader flips the normals of the material, so that the material will wrap around the inside of the game object rather than the outside.
5) Apply new material to Sphere
6) Drag 360 Video onto the Sphere to create Video Componenet

7) Either integrate with a VR headset or add Mouse Follow script onto camera to simulate VR
8) Press play and you have 360 video playback in unity

