# Fusion-tools
 Macros pour Blackmagic Fusion


 ## Macros

### BL
**bl_Bytes:**
Converts the picture in another byte space. This is of course a simple simulation as Natron works only in 32 floating point color space.

**bl_Compress:**
A common color correction function that pushes the low color to a value and the high color to one another. While tempting to made a color matching between 2 picture this Macro might be really usefull.

**bl_Expand:**
Does the exact reverse of the Compress node. It stretches the color between to low and high color values.

**bl_Monochrome:**
Same as the Shake's Monochrome node. You can play independently with the 3 color components.

**bl_Solarize:**
Solarize effect.

### FILTER
**Sharpen_C:**
Sharpen filter.

**CH_FrequencySeparation:**
Frequency separation filter.

### LP
**L_Fuse:**
Luma Picture's merge node.

### LUT
**LinearToHSL:**
Converts an image from Linear to HSL colorspace.

### PXF
**PxF_Bandpass:**
Extract detail from an image. Useful to make plates easier to track.

**PxF_Distort:**
Generate glass-like refraction effects using a deformation map. Can also be used to grow edges on tricky chroma keys by using the alpha to deform the RGB channels. 

**PxF_HueSat:**
Simple hue and saturation adjustment by adding constants to pixel values in HSL colorspace.