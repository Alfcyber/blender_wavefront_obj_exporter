# blender_wavefront_obj_exporter
enable singel vertex group export in blender wavefront exporter
This change makes it possible to export individual vertex per groups (e.g. one Vertex per Group) 
tested with Blender 2.79 in .obj format. 
The index of the vertex starts at 0 and is declared with 'i'.
It was useful for me to better animate meshes.
