# VLogLFalseColor
## False color profiles to use in VLog-L cameras like the Lumix GH5.
False color is a technique used in many video cameras to get accurate information about the exposure of each part of the frame, and the lighting ratios between them.The brightness of each pixel is map to a different color, so you can guess instantly the level of each pixel. Darker areas are usually mapped to colder colors, and bright areas are mapped to hot colors.

This is a false color LUT to be used in Panasonic Lumix cameras with Vlog-L color profiles, tweaked using a GH5.
I found that other false color profiles available for the GH5 a little confusing, with muted colors or unclear boundaries between colors.
So I made one tailored to my specific needs. I tweaked it a lot, and now that I'm happy with the result I share it with the community so other VLog-L users can benefit from it.

![False color usage example](/FalseColor_example.jpg)

### Characteristics
* It's specifically designed and tested in a GH5 with Vlog-L. I don't know if it behaves properly in other VLog-L cameras or with the full VLog ones (like varicam).
* The Vlog-L maps all colors between 7.3 and 80 IRE, so the color mapping respects that.
* The Middle Gray (18% Gray, or Zone V) is mapped to 42 IRE, in a dark grey.
* The skin tones (lit parts) go from 42 to 55
* The reflective white, or White 90% is mapped to 61 IRE (that means a well lit white paper or a white wall in direct light).
* On yellow and orange you should have only specular highlights, strong reflections, or some dimmed practical lights.
* Red marks the white clipping so it's reserved for strong practical lights, or the sun, or anything you know will be irrevocably clipped.
* Below the Middle Gray you have a green zone, that's for the soft shaded areas, 1 stop below lit skin.
* dark cyan indicates deeper shadow, but still with lots of texture and detail. That's 2 stops below middle gray.
* in the blue zones you start to loose  texture and detail. It's for the deep shadows, or darker colors.
* Blue/purple means almost clipped, too much noise, little detail, these will not stand much pushing.
* Deep purple is black clip

This is a reference card with this info plotted in table form. 
The rightmost column indicates the level at which the noise starts to become a problem at each ISO. This is of course very subjective and based on my own footage-noise-tolerance (if that thing exists), and tested in my own GH5 in an extremely unscientific environment. 
Use at your own risk.

![Color table](/FLS_21FD_ref.png)

### Installation
1. Go to Releases https://github.com/g3ntile/VLogLFalseColor/releases/ and download the latest version.
2. It's a zip, so uncompress it
3. copy the .VLT file in the zip to an SD card that your Lumix camera can read
4. Put the card in your Lumix camera and, if it's a GH5 go to the menu "V-LogL View Assist, inside the menu with the camera icon next to an "M" (in other cameras the procedure may be different, consult your manual)
5. Select "Read LUT File
6. assign the FLS_21FD Lut to any of the 5 custom slots.
7. Go to LUT Select and select it
8. You can save your settings, False Color included as one of the 5 customizable memories in the camera, labeled C1, C2, C3-1, C3-2 and C3-3 for convenience.
9. I also assigned a quick button to "LUT Monitor Display" in the page 11/20 of the custom Fn buttons set. That toggles between plain log view and LUT, so you can easily turn on and off your False Color mode, even while recording.
