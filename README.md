# BattleForgeToDDCs
### About
This is a simple mass-converter for Battle Forges .DRS Models. Goal is to create a universal file (GLTF) for use in multiple DDCs like Blender, Maya, Houdini, 3dsMax, etc...

<img src="https://i.gyazo.com/51a830c1b9aaefcafeedaf3ecd8edee8.png" alt="ice_barrier_gltf" width="400" height="400">

> Ice Barrier in GLTF


### How to use
- Renamve the dev_env.json.example to dev_env.json
- Edit the Path to the master folder of all DRS (It will search all subfolders for .drs files)

### Dependencies
- [pfp](https://github.com/d0c-s4vage/pfpu)
- [pygltflib](https://gitlab.com/dodgyville/pygltflib)

### To-Do
- [x] DRS Parsing & Reading
- [X] Convert DRS Geometry (Points, Faces) to GLTF
- [ ] Add Decal, Damage Model and Model into one GLTF File
- [ ] Convert Normals, UVs, (TBD: Tangents) to GLTF
- [ ] Embed Textures, Materials and Gemetry into single GLB File (Binary GLTF) -> Basically Plug-And-Edit
- [ ] Joints, Animations

### Credit
- CrazyCockerell (QuickBMS Script for mass-exporting of Battle Forges PAK-Files!)
- bobfrog (pfp-DRS-Template & awseome prework!)
- solcrow (Help + Awesome Unity Viewer and Exporter - Shown that its possible + Animation pfp-SKA-parse templates)
- [Skylords Reborn Team](https://forum.skylords.eu/) (In general for keeping the Game alive!)
