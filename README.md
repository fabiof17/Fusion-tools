# Fusion-tools
 Macros pour Blackmagic Fusion


 ## Macros

### BL
**bl_Bytes:**
Converts the picture in another byte space. This is of course a simple simulation as Natron works only in 32 floating point color space.

**bl_Solarize:**
Solarize effect.

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