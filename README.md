# blender-topology-check
Blender 4.2 geometry nodes project to check face vertices count

## Usage
This geometry nodes setup is used to set the vertex color of faces with different vertex counts.

$${\color{yellow}NEEDED}$$
!! Make sure to go into Vertex Paint then back to Object Mode, else "Attributes" data wont exist on the object !!

Currently 3, 4, 5, 6, and 7 vertex count is setup
## Color Code
* Blue: 3 vertex
* Green: 4 vertex
* Orange: 5 vertex
* Red: 6 vertex
* Magenta: 7 vertex
* Black: 8+ vertex

## Geometry Node Features
![image](https://github.com/user-attachments/assets/c8fead22-2eee-49c6-bd45-d00ea4574bba)

## Enabled
This will enable / disable this geometry node group. Can be used to passthrough the modifier list without effecting the object

## Use Collection
You can set this to true if you have a specific collection that holds your meshes for debugging. If false the collection is skipped for using the current object as a mesh to check

## Collection
If Use Collection is enabled this will be the source collection to check meshes

## Debug Material
This can be set if you have a custom material you want to use for debugging instead of the included vertex color setup

![image](https://github.com/user-attachments/assets/5ae961c2-a88b-4851-8200-27b55531c20e)
