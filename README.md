### My personal DWM config

![Dwm](https://github.com/CrisitoJ/dwm/blob/main/example.png)
![Dwm](https://github.com/CrisitoJ/dwm/blob/main/example2.png)


I Recommend to save /dwm on .config 

Patches:
- [autostart](https://dwm.suckless.org/patches/autostart/dwm-autostart-20200610-cb3f58a.diff)
- [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/dwm-actualfullscreen-20211013-cb3f58a.diff)
- [focusadjacenttag](https://dwm.suckless.org/patches/focusadjacenttag/dwm-focusadjacenttag-6.3.diff)
- [fullgaps](https://dwm.suckless.org/patches/fullgaps/dwm-fullgaps-6.4.diff)
- [resetlayout](https://dwm.suckless.org/patches/resetlayout/dwm-resetlayout-6.2.diff)

Personal dependencies:
- [picom](https://wiki.archlinux.org/title/picom)
- [feh](https://wiki.archlinux.org/title/Feh)
- [sxhkd](https://wiki.archlinux.org/title/Sxhkd)
- [slstatus](https://tools.suckless.org/slstatus/)
- [Hurmit Nerd Font](https://www.programmingfonts.org/#hermit)


Set up the autostart.sh
```bash
mv autostart.sh ~/
```
Download the [wallpaper](https://www.wallpaperbetter.com/en/hd-wallpaper-uelhc) and move it to ~/wallpapers

```bash
mv wallpaperName ~/wallpapers
```
if you prefer to save the wallpaper in another directory, modify the path of the 2 line of the autostart line

Set up your own browser keybind on line 64
```bash
#Change the brave word if u use another browser
static const char *browser[] = { "brave", NULL };
```
