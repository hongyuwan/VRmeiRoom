# VRRoom
Developing a VR game room using Unity Engine with Unity XR Plugin Framework. 

Followed Unity tutorial https://learn.unity.com/course/create-with-vr?uv=2020.3

Platform: Oculus Quest2
<img width="1325" alt="截屏2023-03-19 下午5 41 49" src="https://user-images.githubusercontent.com/85655086/226221970-1263ab5d-2323-4ebb-a055-a00b4934f4b6.png">


portfolio 
https://hongyuwan.sites.northeastern.edu/2023/03/19/vr-game-room-unity/

This project mainly has 5 parts:

XR manager

--XR interaction Manager

--XR Device Simulator (for running and debugging on PC)

--Input Action Manager

STATIC Objects:

--all the objects in this scene(like books, TV, Food, chair, plant, etc)

-- SkyBox (background building)

LIGHTING System:

--Directional Light (Realtime, *from top of this scene)

-- Point Light on the ceiling of the room(Realtime)

--Fireplace Light

Spot Light(Baked)

--Lamp on the table Light

Spot Light(Baked)

DYNAMIC Objects:

All the dynamic objects in this scene can be grabbed by user(interaction), like camera, Tennis ball, phone, notebook, etc.

INTERFACE

Principal Canvas( for show instruction)
