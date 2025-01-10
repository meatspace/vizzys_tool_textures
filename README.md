# Vizzys tool textures and fixes pack
ℹ️ More dev textures & stock texture fixes for your hearts desire. (Half-life 2, etc)

⚠️ Ive added SDK_ prefix to every shader (this is for Mapbase, remove if not using mapbase)

---
changelog:

- [x] added sprites fix folder by Ceuzera https://steamcommunity.com/sharedfiles/filedetails/?id=2928705791

see picture: https://steamuserimages-a.akamaihd.net/ugc/2262557817124643928/594FA6B36ABD1D538EF5D12872EF626E4C41953E/

- [x] Added plaster folder, fixes the hl2 plaster walls with _c17 underscores (they had $envmap when the non _c17 versions did not)
- [x] Added combine_fluorescent (a combine blue edit of a default light texture) by Jimonions https://steamcommunity.com/id/jim-onions

I recommending adding this to your lights.rad like so it gives off light: lights/combine_fluorescent	169 223 252 50

- [x] Added toolsblockbullets_fix.vmt (Same as Tools/ToolsBlockBullets, but doesn't cut visleaves.)
- [x] Added debugwhite fix by somefooloutthere: https://steamcommunity.com/sharedfiles/filedetails/?id=2909615148
- [x] Added toolsinvisibleladder_fix from siryodajedi on VMC discord (uses alpha channel, no longer stops VIS/Bullets. I added %compileInvisible 1)
- [x] Added toolsbutton from siryodajedi, I think. (a unique button texture instead of using tools/toolstrigger or tools/toolsinvisible)

Added some momentum-mod stuff: 
- [x] tools/toolsblack_fix (Unlitgeneric so no lightmap, I added $nodecal 1)
- [x] tools/toolswhite_fix (Unlitgeneric so no lightmap, I added $nodecal 1)
- [x] trigger_teleport (a unique teleport texture instead of using tools/trigger)
- [x] Added obb_parallax by lenship2 (.vmt edit by me) https://github.com/StrataSource/Portal-2-Community-Edition/discussions/1779 

(a unique parallax obb texture instead of using tools/trigger)
- [x] added enhanced source grid textures to dev/ folder
- [x] added vent dev texture to dev/ folder by sitkinator  (map labs discord)
- [x] added many dev textures by marco198 into /marco198 folder (outcast discord)
- [x] added many dev textures by kalimando into /kalimando folder
- [x] added tilefloor016a_fixed, citadel_metalwall072c_fixed from Minerva Metastasis
- [x] added metalgate002a_alphatest, metalfence003a_alphatest (use $alphatest instead of $translucent)
- [x] added metalfence004a_noladder (the same except you cant climb it)

