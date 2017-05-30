# breeze-osx-decorations
Aurorae window decorations for the KDE Plasma desktop environment.

![Preview Screenshot of the window theme](https://raw.githubusercontent.com/MarianArlt/breeze-osx-decorations/master/Preview.jpeg)

Tested with Plasma 5.8.2
Based on the existing theme [Evolvere Light Pure Circle](https://github.com/franksouza183/EvolvereSuit/tree/master/aurorae-themes/EvolvereLightPureCircle) by [Frank Souza](https://github.com/franksouza183).

This is best used together with the default breeze themes. The default border width (config settings set to "normal") is 8px. This is by intention. It makes for a consistent design throughout any application. All buttons got subtle indicators for their actions just like the recent OSX versions do, only a little less dominant.

Preferably installed via **System Settings** > **Window Decorations** > **Get New Decorations**.
If you want to install it manually clone this repo and put the *Breeze-OSX* folder into `~/.local/share/aurorae/themes`.

If you would like to lower the border value you can easily change the **[Layout]** section of *Breeze-OSXrc* namely the values of `BorderBottom`, `BorderLeft`, `BorderRight` and `TitleEdgeBottom`.
If you would like to use this theme without borders set the config settings to "tiny" and `TitleEdgeBottom` in *Breeze-OSXrc* to `0`.
Either of this might throw off paddings which would need additional adjustments in the same file.

### Changelog

*v1.1*  
· Fixed clipping issues on maximized windows.  
· Cleaned up border paths of the inactive decoration.
