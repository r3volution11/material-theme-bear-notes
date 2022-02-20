![Material Theme for Bear Screenshot](https://github.com/r3volution11/material-theme-bear-notes/raw/master/resources/material-bear-theme-hero.jpg)

# Material Theme for Bear Notes (macOS)

Based on the most epic theme for Visual Studio Code made by @equinusocio, [Material Theme](https://github.com/equinusocio/vsc-material-theme). It's a great theme with beautiful colors and plenty of themes to keep things fresh and current.

Bear uses XML for their themes which is easy to modify and create your own. That said, some **easy** "hacking" is involved as they do not officially support third party themes.

Instructions are included below. It's a short list, don't worry.

## Updates

**2/20/22** - Long time no see. Updated Default (Cobalt) theme to make sidebar icons more in sync with other themes. Also added vector app icon to `resources/material-bear-theme.sketch` for those that would like to modify it.

**8/5/19** - All themes appear to work fine with Bear v1.7.

**2/21/19** - 🌟🌟 `Darker` now available!

**2/20/19** - 🌟 `Lighter` and `Ocean` themes now available. **Feedback appreciated.**

## To Do - Theme Variants

- [x] Pale Night
- [x] Default
- [x] Lighter
- [x] Ocean
- [x] Darker

## How to Install

To work properly, each Material Theme variant is built over themes already included within Bear itself.

#### Backup Files First

1. If open, quit Bear.
2. Go to your Applications folder.
3. Locate and Right-Click on Bear. Select "Show Package Contents."
4. Navigate to `Contents/Resources`.
5. Create backups for all `*.theme` files.

#### Copy Material Theme(s) To Bear

1. Clone or [Download](https://github.com/r3volution11/material-theme-bear-notes/releases) the latest release and extract.
2. Copy `themes/[variant]/[theme-name].theme` files you'd like to use to `Bear.app/Contents/Resources`.
3. Open Bear, go to preferences, and activate `[theme-name]` under Themes panel.

## Icon Install Instructions

I've created Bear app icon replacements for each theme variant. The Bear developers decided to make icons a little tougher to customize as well. Thankfully, not too hard. To install and ensure the theme icon is always displayed requires the following:

<img src="http://r3v.in/W1qTze/dock-icon-2x.png" width="100">

- First, Update `Contents/Resources/AppIcon.icns` with the icon files included (`themes/[theme-name]/icon*.png`).
  - Use [LiteIcon](https://freemacsoft.net/liteicon/)
  - or Copy/Paste through Finder Info Panel - [Guide](http://osxdaily.com/2013/06/04/change-icon-mac/)

- Second, to work while open you must edit Bear's Assets.car file (`/Applications/Bear.app/Contents/Resources/Assets.car`) using [Theme Engine](https://github.com/alexzielenski/ThemeEngine). Be sure to replace both images in `Assets.car/AppIcon [theme-name]`.
- When finished **enable** the "App icon matches theme" option in Bear's Themes preferences panel.

## Important Notes

Unfortunately after each Bear update you may have to do this process over again. Be sure to keep these files available locally or, I recommend, to clone the repo so you can more easily keep up to date. I use this theme so I intend to keep it up to date as Bear is updated.

If I miss anything...

## Bugs, Issues or Feedback

If you have any ideas or notice issues please let me know by adding an [Issue](https://github.com/r3volution11/bear-theme-material-palenight/issues).

❤️

**Note:** I did not create [Bear (macOS/iOS/etc.)](https://bear.app) or the Material Theme color scheme, palette or anything related unless specified otherwise. I am not affiliated with their creators in any manner.
