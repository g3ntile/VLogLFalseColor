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
* The reflective white (that is like a white paper or a white wall well lit, called White 90%) is mapped to 61 IRE.
* Above that on yellow and orange you should have only specular higlights, strong reflections, or practical light sources.
* Red is clipping so it's reserved for direct light sources or the sun, or anything you know will be irrevocably clipped.
* Below the Middle Gray you have a green area for the brighter shaded areas, 1 stop below lit skin.
* dark cyan indicate deeper shadow, but still lots of texture and detail.
* in the blue zones you start to loose  texture and detail.
* Blue/purple is almost clipped, too much noise, little detail, these will not stand much pushing.
* Deep purple is black clip

This is a reference card with this info plotted in table form. 
The rightmost column indicates the level at which the noise starts to become a problem at each ISO. This is of course very subjective and based on my own footage-noise-tolerance (if that thing exists), and tested in my own GH5 in an extremely unscientific environment. 
Use at your own risk.

![Color table](/FLS_21FD_ref.png)

### Installation
To install this profile download the .VLT file from this repo and load it in your GH5.
(Section under development)
