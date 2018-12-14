![Material Palenight for Bear Screenshot](http://r3v.in/92KgIQ/Screen-Shot-2018-12-07-03-00-54.72.png)

# Material Palenight Theme for Bear Notes (macOS)

Based on the most epic theme for Visual Studio Code made by @equinusocio, [Material Theme](https://github.com/equinusocio/vsc-material-theme).

Bear uses XML for their themes which makes it rather easy to create your own. Unfortunately they do not support third party themes. To install this theme you must name and copy over a theme included with Bear. I chose Dark Graphite.

Installing this theme requires some good ol' copy / pasting within the Bear app's package contents.

## Theme Install Instructions

1. If open, quit Bear.
2. Go to your Applications folder.
3. Locate and Right-Click on Bear. Select "Show Package Contents."
4. Navigate to `Contents/Resources`. 
5. Create backups for `Dark Graphite App Theme.theme` and `Dark Graphite Text Theme.theme`.
6. Overwrite those files with the ones included within this repo.
7. Open Bear and make sure Dark Graphite is the selected theme.

## Icon Install Instructions

I've also created a Bear app icon replacement. Making sure the icon is always displayed requires the following:

<img src="http://r3v.in/W1qTze/dock-icon-2x.png" width="100">

- First, Update `Contents/Resources/AppIcon.icns` with the icon files included (`resources/dock-icon*.png`).
  - Use [LiteIcon](https://freemacsoft.net/liteicon/)
  - or Copy/Paste through Finder Info Panel - [Guide](http://osxdaily.com/2013/06/04/change-icon-mac/)

- Second, to work while open you must edit Bear's Assets.car file (`/Applications/Bear.app/Contents/Resources/Assets.car`) using [Theme Engine](https://github.com/alexzielenski/ThemeEngine). Be sure to replace both images in `Assets.car/AppIcon Dark Graphite`.
- When finished **enable** the "App icon matches theme" option in Bear's Themes preferences panel.

## Bugs or Issues

Due to the nature of this theme I can offer little support. This is just me modifying the app to fit the theme I use in other apps and letting everyone interested in on the fun. If you have any ideas or notice any issues please let me know by adding an [Issue](https://github.com/r3volution11/bear-theme-material-palenight/issues).

❤️


**Note:** I did not create Bear or the Material Palenight Theme color palette and am not affiliated with their creators in any manner.
