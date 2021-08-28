# VLogLFalseColor
## False color profiles to use in VLog-L cameras like the Lumix GH5.
False color is a technique used in many video cameras to get accurate information about the exposure of each part of the frame, and the lighting ratios between them.and
The Lumix GH5 cameras with the VLog-L upgrade installed can use LUTs to better preview the flat looking log images.
The false color LUTs map the brightness of each pixel to a different color, so you know instantly the level of each pixel. Darker areas are usually mapped to colder colors, and bright areas are mapped to hot colors.
after a while using some of the standard ones out there, I found those profiles a little confusing, with muted colors or unclear boundaries between colors.
So I made a profile tailored to my specific tastes and needs. I tweaked it a lot, and now that I'm happy with the result I share it with the community so other VLog-L users can benefit from it.
* It's specifically designed and tested in a GH5 with Vlog-L. I don't know if it behaves properly in other VLog-L cameras or with the full VLog ones (like varicam).
* The Vlog-L maps all colors between 7.3 and 80 IRE, so the color mapping respects that.
* The Middle Gray (10% Gray, or Zone V) is mapped to 42 IRE, in a dark grey.
* The skin tones (lit parts) go from 42 to 55
* The reflective white (that is like a white paper or a white wall well lit, called White 90%) is mapped to 61 IRE.
* Above that on yellow and orange you should have only specular higlights, strong reflections, or practical light sources.
* Red is clipping so it's reserved for direct light sources or the sun, or anything you know will be irrevocably clipped

Reference card for using the FLS_FA False Color LUT profile for exposing video in VLog-L cameras like the Lumix GH5.
![Color table](/FLS_21FD_ref.png)

