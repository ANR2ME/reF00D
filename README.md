# reF00D - By FAPS Team
# Please use: https://github.com/SKGleba/0syscall6/releases

the French - @CelesteBlue123 

the American - @dots_tb 

the 【Ｐｒｉｎｃｅｓｓ　ｏｆ　Ｓｌｅｅｐｉｎｇ】 - @PoSsvkey

With @juliosueiras and TheRadziu - @AluProductions

## Updated keys.bin:
https://forum.devchroma.nl/index.php/topic,44.0.html

## What it does:
  It allows you to run modules such as games or system apps that require a FW different from your own. This includes thing such as 3.69 games or 3.51 apps.
## How to use:
  1. Add reF00D.skprx path to your taihen config.txt or use Autoplugin to install it.
  Note for devs: The release version does not work with plugin loader and must be used in taihen config.txt
  2. Make sure that reF00D is installed AFTER NoNpDRM in this config.txt.
  3. Put latest keys.bin file into ur0:/tai/keys.bin. (https://www.mediafire.com/download/re0m6768u0n67up) (updated as of PSVita FW 3.73. Might not work for higher FWs if keys are changed)
  4. Reboot. Enjoy !
  
  NOTE: rePatch module loading will take priority over reF00D. If a module is in the rePatch folder, it will be loaded first and reF00D will not attempt to decrypt it.
  
## Troubleshooting:
  Q: I've installed this plugin but games still error with **C1-6703-6** code.  
  A: This error means that vita still couldn't run games/apps. This, in return, means reF00D plugin is not loaded, which might be caused by:
- Bad TAI configuration, for example typo in reF00D line, putting it into wrong section of tai configuration, or using wrong tai configuration file,
- Misplaced or missing keys.bin file. It has to be `ur0:tai/keys.bin`.
  
## Special thanks:
Team Molecule for feeding the p00r.

To motoharu, aerosoul, TheFloW, xerpi, St4rk, Mathieulh, zecoxao for having reversed a part of the PSVita and made useful tools.

To Silica for his mental illness (actually caring about PSM) which made us realize the headers weren't always in order. 

To sys for being sys.

## Testing team:
amadeus, Samilop Iter, Thibobo, Yoti, Waterflame, Z3R0
