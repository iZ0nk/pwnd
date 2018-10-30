# BO4 Performance Adjustments Brief

This is a reference guide on editing the CODBO4 config.ini file to help improve FPS and reduce input lag.

## Please Note

I am in no way liable for issues caused by changes you decide to make. Do not make changes you do not understand.
This is NOT a direct config.ini replacement file and should only be used as a reference point.

### Additional Notes

Must overwrite config.ini in both locations shown below.
Locations will vary depending on where the game is installed.
"[User Profile Directory]" will be the a set of 16 random numbers/letters IE: 00000000002ccdab.

```
C:\Program Files (x86)\Call of Duty Black Ops 4\players\
C:\Program Files (x86)\Call of Duty Black Ops 4\players\[User Profile Directory]\
```

### CORE Adjustments

Below is the list of adjustments made specifically to add horsepower to the games FPS while reducing input lag.


```
//Horizontal field of view in degrees assuming 16:9 aspect ratio
fov = "110" // 60 to 120

//Vsync only applies in fullscreen
vsync = "0" // 0 or 1

//LOD's to drop on models, lower numbers are higher quality
mesh_quality = "1" // 0 to 2

//0 - Force 2x anisotropic filtering, 1 - Per material, 2 - Force 16x anisotropic filtering
texture_filter = "2" // 0 to 2

//Number of mips to drop on streamed textures, lower numbers are higher quality
texture_quality = "2" // 0 to 3

//Number of mips to drop on effects and dynamic decals, lower numbers are higher quality
texture_quality_fx = "1" // 0 to 3

//Number of mips to drop on reflections, lower numbers are higher quality
texture_quality_probes = "1" // 0 to 2

//Number of mips to drop on sun shadows, lower numbers are higher quality
texture_quality_baked_sun_shadows = "1" // 0 to 1

disable_dynamic_light_shadows = "1" // 0 or 1

disable_dynamic_sun_shadows = "1" // 0 or 1

//Particle shadow support
fx_shadows = "0" // 0 or 1

//Resolution of spot light shadows
spot_shadow_texture_size = 128" // 128 to 8192

//Resolution of omni (point) light shadows
omni_shadow_texture_size = "128" // 128 to 2048

//Enable multi-sampled soft shadows
shadow_filtering = "0" // 0 or 1

//Enabled order-independent transparency
oit = "0" // 0 or 1

//Maximum number of overlapping transparency layers
oit_layers = "12" //  8, 9, 12, or 16

//Screen-space ambient occlusion method
ssao_technique = "Disabled" //  Disabled, GTAO Low Quality, GTAO Medium Quality, GTAO High Quality, or GTAO Ultra Quality

//Anti-aliasing technique
aa_technique = "None" //  None, FXAA, SMAA 1x, Filmic SMAA 1x, SMAA T2x, or Filmic SMAA T2x

//Per-object motion blur
motion_blur = "Off" //  Off, Auto, or On

//Better lighting for skin
subsurface_scattering = "0" // 0 or 1

//Enable screenspace reflection
ssr = "0" // 0 or 1

//Enable viewmodel self shadowing
shadow_viewmodel_self = "Off" //  Off, Sun Only, Spot Only, or All

dedicated_player_shadow = "Off" //  Off, Sun Only, Spot Only, or All

//Number of pixel in screen required to be culled, lower numbers are higher quality
auto_cull_radius = "1" // 0 to 10

//1 for low quality ambient lighting, 0 for normal
local_ambient_lighting = "0" // 0 or 1

//Set to zero to force auto-detect to run at startup
auto_detect_has_run = "0" // 0 or 1
```

## n00b

* **Lloyd Bailey** - ```w0lf``` - [iZ0nK](https://github.com/iZ0nk)