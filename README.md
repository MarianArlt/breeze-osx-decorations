# breeze-osx-decorations
Aurorae window decorations for the KDE Plasma desktop environment.

Tested with Plasma 5.8.2
Based on the existing theme [Evolvere Light Pure Circle](https://github.com/franksouza183/EvolvereSuit/tree/master/aurorae-themes/EvolvereLightPureCircle) by [Frank Souza](https://github.com/franksouza183).

This is best used together with the default breeze themes. The default border width (config settings set to "normal") is 8px. This is by intention. It makes for a consistent design throughout any application.

If you would like to lower this value you can easily change the **[Layout]** section of *Breeze-OSXrc* namely the values of `BorderBottom`, `BorderLeft`, `BorderRight` and `TitleEdgeBottom`.
If you would like to use this theme without borders set the config settings to "tiny" and `TitleEdgeBottom` in *Breeze-OSXrc* to `0`.
Either of this might throw off paddings which would need additional adjustments in the same file.
