![Material Palenight for Bear Screenshot](http://r3v.in/92KgIQ/Screen-Shot-2018-12-07-03-00-54.72.png)

# Material Palenight Theme for Bear Notes (macOS)

Based on the most epic theme for Visual Studio Code made by @equinusocio, [Material Theme](https://github.com/equinusocio/vsc-material-theme).

Bear uses XML for their themes which makes it rather easy to modify and create your own. Unfortunately some "hacking" is involved as they do not support third party themes.

Installing requires some good ol' copy / pasting within Bear app's package contents. Nothing flashy.

## Updates

**12/28/18** - I've already created themes and icons for all Material Theme variants. `Lighter` is will be available soon.
**12/27/18** - Happy Holidays everyone! The Default theme is ready for use. Pale Night was slightly tweaked as well.
**12/14/18** – Work on support for all Material Theme variants has begun.. stay tuned!

## Theme Install Instructions

Each Material Theme variant I've created has a different name used to replace a theme within Bear itself. So far I've created Pale Night [`/themes/palenight`] and Default [`/themes/default`]

1. If open, quit Bear.
2. Go to your Applications folder.
3. Locate and Right-Click on Bear. Select "Show Package Contents."
4. Navigate to `Contents/Resources`.
5. Create backups for all `*.theme` files.
6. Copy the `themes/[theme-name].theme` files you'd like to use to this location.
7. Open Bear, go to preferences, and make sure `[theme-name]` is the selected theme.

## Icon Install Instructions

I've also created Bear app icon replacements for each theme (so far). Making sure the icon is always displayed requires the following:

<img src="http://r3v.in/W1qTze/dock-icon-2x.png" width="100">

- First, Update `Contents/Resources/AppIcon.icns` with the icon files included (`themes/[theme-name]/icon*.png`).
  - Use [LiteIcon](https://freemacsoft.net/liteicon/)
  - or Copy/Paste through Finder Info Panel - [Guide](http://osxdaily.com/2013/06/04/change-icon-mac/)

- Second, to work while open you must edit Bear's Assets.car file (`/Applications/Bear.app/Contents/Resources/Assets.car`) using [Theme Engine](https://github.com/alexzielenski/ThemeEngine). Be sure to replace both images in `Assets.car/AppIcon [theme-name]`.
- When finished **enable** the "App icon matches theme" option in Bear's Themes preferences panel.

## Bugs or Issues

This is just me modifying the app to fit the theme I use in other apps and letting everyone interested in on the fun. If you have any ideas or notice any issues please let me know by adding an [Issue](https://github.com/r3volution11/bear-theme-material-palenight/issues).

❤️


**Note:** I did not create Bear or the Material Palenight Theme color palette and am not affiliated with their creators in any manner.
