# Fusion-tools
 Macros pour Blackmagic Fusion


 ## Macros

### BL/Color
**[bl_Bytes](/Macros/BL/Color/bl_Bytes)** : Converts the picture in another byte space. 

**[bl_Compress](/Macros/BL/Color/bl_Compress)** : A common color correction function that pushes the low color to a value and the high color to one another. While tempting to make a color matching between 2 picture this Macro might be really usefull.

**[bl_Expand](/Macros/BL/Color/bl_Expand)** : Does the exact reverse of the Compress node. It stretches the color between to low and high color values.

**[bl_Monochrome](/Macros/BL/Color/bl_Monochrome)** : Same as the Shake's Monochrome node. You can play independently with the 3 color components.

### BL/Morphological
**bl_mf_Binary :** Modify binary mask.

**bl_mf_DirectionalBlur :** Modify binary mask with additional directional blur.

**bl_mf_Occlusion :** Modify binary mask with additional dilate/erode.

**bl_mf_ShapeSofter :** Modify binary mask with additional blur.

### BL/Stylize
**[bl_Solarize](/Macros/BL/Stylize/bl_Solarize)** : A clone of the Shake's solarize command.

### BL/Warp
**[bl_ChromaticAberation](/Macros/BL/Warp/bl_ChromaticAberation)** : A simple chromatic aberation tool.

### COLOR
**Firefly_Killer :**
Removes fireflies, very bright, nervously jumping around pixels.

### FILTER
**CH_FrequencySeparation :**
Frequency separation filter.

**Learn_Matrix :**
Apply a Matrix Filter 3x3 to your image

**Sharpen_C :**
Sharpen filter.

### LP (Luma Pictures)
**L_Fuse :**
Fuse is a replacement for the merge(over) node. Functions for light wrap and hue wrap onto the foreground.

### LUT
**LinearToHSL :**
Converts an image from Linear to HSL colorspace.

### MERGE
**AdditiveKeyer :**
Another Additive Keyer with a few added tweaks. Much of the tool was taken from the great article by rafal kaniewski.

### PXF
**PxF_Bandpass :**
Extract detail from an image. Useful to make plates easier to track.

**PxF_Distort :**
Generate glass-like refraction effects using a deformation map. Can also be used to grow edges on tricky chroma keys by using the alpha to deform the RGB channels. 

**PxF_HueSat :**
Simple hue and saturation adjustment by adding constants to pixel values in HSL colorspace.

**PxF_KillSpill :**
Remove red/green/blue spill.

**PxF_MergeWrap :**
An "over" with built-in back and front light wrap.

**PxF_ScreenClean :**
Use a clean plate to clean up blue/red/green screens.

### TRANSFORM
**ScanSlice :**
Slice an image in 4 independant directions.

### Warp
**PushPixel :**
A simple push pixel tool.