# Shadertoy Assets

 All the built-in assets from shadertoy.com in one convenient place. 
 
 The shadertoy API no longer lets you fetch these, and you have to get them from somewhere, so here is somewhere, maybe. 
 
Includes 71 files:
- 22 textures (.png and .jpg files)
- 6 cubemaps (each with 6 faces, .jpg and .png files)
- 2 volumes (.bin files)
- 4 videos (.webm and .ogv files)
- 7 music tracks (.mp3 files)

Does not include:
- Shadertoy gui assets (logos, buffer placeholders, etc, which are not used in shaders.)

**To use these files with the API, simply copy the media folder into your assets folder and point links from https://www.shadertoy.com/media to your new local assets/media folder instead.**

There's also a folder called sorted, which contains the same 71 files sorted in a more legible way. More useful to humans, much less useful to the API. **You probably only need to ship /media.** 

_All files belong to shadertoy.com and I believe are under a licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License._

# Info You Should Know
- Shadertoy's new cloudflare protections make it very difficult to access these files in the way the API intends, so you need a local copy. That is probably why you are here.
- The API shows only the first face of a cubemap for cubemap textures. The other five can be had by appending _1, _2, _3, _4 and _5 to the filename.
- The API **lies** about the resolution for video textures, you should probably use the actual file's resolution.

