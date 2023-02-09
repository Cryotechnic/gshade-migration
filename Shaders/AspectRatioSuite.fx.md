---
icon: info
tags: [ars]
---
## Shader Information
This shader provides functionality to allow the user to tweak the aspect ratio of the rendered game.

## Error
!!!danger
- `Error x3047: 'GetAspectRatio': function return cannot have any qualifiers` 
- `Error x3000: syntax error: unexpected 'identifier'`
- `Error x3013: no matching function overload for 'GetAspectRatio'`
All of the above errors will cause the shader to fail to compile and thus not get loaded by ReShade.
!!!
## Status
!!!success
Fixed! There are multiple possible solutions for this issue. Therefore, this section is sorted from easiest to hardest. 
+++ Reinstall Shader Package 
The easiest way to fix this issue is to completely reinstall the ReShade shader package. This package is available for download here:
[!file](https://kagamine.tech/shade/fixed_shaders.zip) 
+++ Reinstall ReShadeUI.fxh
Replace the `ReShadeUI.fxh` file with the original one:
[!file](https://raw.githubusercontent.com/crosire/reshade-shaders/slim/Shaders/ReShadeUI.fxh)
+++
From here, you can follow the [Migration Guide](https://cryotechnic.github.io/gshade-migration/migration_guide/#7-download-this-zip-file-extract-it-and-move-all-of-those-fxfxh-files-into-your-reshade-shadersshaders-folder) to complete the reinstallation process!
!!!
