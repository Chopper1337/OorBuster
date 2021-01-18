# OOR Buster
Fixes out of range error and black screen when overclocking BenQ 144Hz monitors

## My Changes
* Removed launch parameters feature
* Removed anything AMA related

This version does not add anything to the original. I don't know if this will help other XL2411P owners but it worked for me :)

I had issues on my XL2411P with the latest release (1.4) of OOR Buster, it would dismiss the "Out of Range" error as expected but the screen would remain black.

From some testing, it seems to have been related to AMA, which is something I don't use. I have removed it completely from this version. Due to me not knowing C++, I wasn't sure how to adapt the launch parameters feature from the original to this version, so I just removed that feature also.

I use this version of [OORB](https://github.com/Chopper1337/OorBuster/releases/tag/1.4.1) and [HotkeyResolutionChanger](https://funk.eu/hrc/) to switch between 1080p 144Hz and 960p 190Hz.

## Details
Restores your current OSD language (fixes Out of Range error), picture mode (fixes black screen) and AMA setting after hitting over 144Hz on your BenQ 144Hz monitor. The OSD language and picture mode is cached upon launching the app, so if you switched your picture mode (e.g. from Standart to FPS1) and wish to use it, before switching to overclocked refresh rate right click the OOR Buster icon in tray and hit _Reload_.

  
### To launch with Windows (important if you keep overclock at all times):
Put the .exe into 
```
%ProgramData%\Microsoft\Windows\Start Menu\Programs\StartUp
```

## Credits
Blur Busters: https://blurbusters.com

Original project: https://github.com/hleVqq/OorBuster

### Forum thread:
https://forums.blurbusters.com/viewtopic.php?f=8&t=5544
