# TerrainGeneration
Follows Sebastian Lague's procedural terrain generation series 

## About 

Creates height maps from 2D Perlin noise. Uses those height maps and user defined settings to create a color map from the height map which is then applied to a plane. 
Creates a mesh and uses the height map to offset vertices so the 2D height map appears 3D. Has an endless mode to spawn and hide meshes in chunks around a player and adjust the LOD of them according to how far away the player is from them
