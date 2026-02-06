# Blender LabPBR
Lets you import / export the labPBR format in Blender!

## Node Groups
the list of nodes included in the blender poject file

### LabPBR Extractor
Extracts PBR properties from LabPBR textures

### LabPBR Compressor
Compresses PBR properties into LabPBR textures

### Principled LabPBR
Converts LabPBR textures into a fully functional Principled BSDF

### LabPBR to AOV Output
Exports LabPBR textures into AOV channels

the channels being:
1. `color` LabPBR Specular
2. `value` LabPBR S Alpha
3. `color` LabPBR Normal
4. `value` LabPBR N Alpha

AOV channels must be added manually to a project file at `View Layer > Shader AOV` (AOV channels are already included in the project file in this repository)


# References
- LabPBR v1.3 - Shaderlabs LabPBR Material Standard https://shaderlabs.org/wiki/LabPBR_Material_Standard
- Demo textures - Embrace Pixels https://modrinth.com/resourcepack/embrace-pixels