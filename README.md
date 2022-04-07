![Material Theme for Bear Screenshot](https://github.com/r3volution11/material-theme-bear-notes/blob/main/resources/material-bear-theme-hero.jpg?raw=true)

# Material Theme for Bear Notes (macOS)

Based on the most epic theme for Visual Studio Code made by @equinusocio, [Material Theme](https://material-theme.site). It's a great theme with beautiful colors and plenty of themes to keep things fresh and current.

Bear uses XML for their themes which is easy to modify and create your own. That said, some **easy** "hacking" is involved as they do not officially support third party themes.

Instructions are included below. It's a short list, don't worry.

## Updates

**2/21/22** - Went through and created proper Big Sur style icons for all themes. Check the Sketch file if you'd like to alter them to your liking.\
**2/20/22** - Long time no see. Updated Default (Cobalt) theme to make sidebar icons more in sync with other themes. Also added vector app icon to `resources/material-bear-theme.sketch` for those that would like to modify it.

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

![Material Theme for Bear Screenshot](https://github.com/r3volution11/material-theme-bear-notes/raw/master/resources/material-bear-theme-icons-banner.jpg)

- First copy/paste the icon image to the app through the Finder info panel. This ensures the icon works when Bear is not open: [Guide](http://osxdaily.com/2013/06/04/change-icon-mac/)
- Second, to work while open you must edit Bear's Assets.car file (`/Applications/Bear.app/Contents/Resources/Assets.car`) using [Theme Engine](https://github.com/alexzielenski/ThemeEngine). Create a backup of `Assets.car` to another location, create a new copy and and open with ThemeEngine. Replace all related icon images by pasting into the right location (`Assets.car/AppIcon [theme-name]`). After you're finished copy the modified Assets.car file to `/Applications/Bear.app/Contents/Resources/Assets.car` overwriting the file that is there (password will be required).
- When finished **enable** the "App icon matches theme" option in Bear's Themes preferences panel.

## Important Notes

Unfortunately after each Bear update you may have to do this process over again. Be sure to keep these files available locally or, I recommend, to clone the repo so you can more easily keep up to date. I use this theme so I intend to keep it up to date as Bear is updated.

If I miss anything...

## Bugs, Issues or Feedback

If you have any ideas or notice issues please let me know by adding an [Issue](https://github.com/r3volution11/bear-theme-material-palenight/issues).

❤️

**Note:** I did not create [Bear (macOS/iOS/etc.)](https://bear.app) or the Material Theme color scheme, palette or anything related unless specified otherwise. I am not affiliated with their creators in any manner.
