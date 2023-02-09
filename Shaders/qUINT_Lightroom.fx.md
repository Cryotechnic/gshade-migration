---
icon: info
tags: [qUINT]
---
## Shader Information
This shader provides a comprehensive set of color grading algorithms, modeled after industry applications such as Adobe Lightroom.

## Error
!!!danger
`Preprocessor Error: Could not open file in filepath: [filepath]` Makes the shader un-loadable and unavailable for use in shader presets.
!!!
## Status
!!!success
**Fixed**! Updated file available: [!file](https://cdn.discordapp.com/attachments/1072537310924652676/1072541648602529822/qUINT_lightroom.fx)
<br>**Fix:** Outdated shader version for current version of ReShade (Reshade 4). Updating the preset to the latest version of ReShade fixes the issue.
Furthermore, the user should ensure that they have the following files present inside their shader directory:
```
|-- reshade-shaders
    |-- qUINT_lightroom.fx
    |-- qUINT_motionvectors.fx
    |-- qUINT_common.fxh
```
!!!
