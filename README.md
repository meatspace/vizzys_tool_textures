# Vizzys tool textures and fixes pack
ℹ️ More dev textures & stock texture fixes for your hearts desire. (Half-life 2, etc)

⚠️ Ive added SDK_ prefix to every shader (this is for Mapbase, remove if not using mapbase)

changelog:


---
- [x] added sprites fix folder by Ceuzera 
https://steamcommunity.com/sharedfiles/filedetails/?id=2928705791

see picture: https://steamuserimages-a.akamaihd.net/ugc/2262557817124643928/594FA6B36ABD1D538EF5D12872EF626E4C41953E/

- [x] Added plaster folder, fixes the hl2 plaster walls with _c17 underscores (they had $envmap when the non _c17 versions did not)
- [x] Added combine_fluorescent.vmt

(a combine-themed blue edit of a default light texture) by Jimonions https://steamcommunity.com/id/jim-onions

I recommending adding this to your lights.rad like so it gives off light: lights/combine_fluorescent	169 223 252 50

- [x] Added debugwhite.vtf fix by somefooloutthere: https://steamcommunity.com/sharedfiles/filedetails/?id=2909615148
- [x] Added toolsinvisibleladder_fix.vmt from siryodajedi on VMC discord 
(uses forgotten alpha channel, no longer stops VIS / Bullets. %compileInvisible 1 added by me)

Added some momentum mod stuff: https://momentum-mod.org/  
- [x] tools/toolsblack_fix.vmt (Unlitgeneric, so no lightmap, added $nodecal 1 )
- [x] tools/toolswhite_fix.vmt (Unlitgeneric, so no lightmap, added $nodecal 1 )
- [x] trigger_teleport.vmt (a unique teleport texture instead of using tools/trigger if you want)

- [x] Added obb_parallax.vtf / .vmt by lenship2 
https://github.com/StrataSource/Portal-2-Community-Edition/discussions/1779  .vmt edited by me.

(ofc u can just use the regular trigger texture, but this is unique)
- [x] added enhanced source grid textures to dev/ folder
- [x] added vent dev texture to dev/ folder by sitkinator  (map labs discord)
- [x] added dev textures by marco198 into /marco198 folder (outcast discord)
- [x] added dev textures by kalimando into /kalimando folder
- [x] added tilefloor016a_fixed.vmt, citadel_metalwall072c_fixed.vmt from Minerva Metastasis
- [x] added metalgate002a_alphatest, metalfence003a_alphatest.vmt (use $alphatest instead of $translucent)
- [x] added metalfence004a_noladder.vmt (the same except you cant climb it)
