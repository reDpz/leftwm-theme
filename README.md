# Left-wm theme

*this is a fork of "basic_polybar"*

## Differences
This theme is slightly different from the others, it will not start your compositor, your notification manager and etc. **It only restarts polybar**. This is because if I'm ever configuring my wm it's very rare for me to change my compositor settings, not to mention picom auto-updates on changes.

To start your applications on boot please use `~/.xinitrc`.

## Install instructions
To install copy the file to `~/.config/leftwm/themes/`

Then create a symlink, symlink the `leftwm-theme` folder to `current`

Or if you dont care then just rename the folder to `current`.

Theme should work with multiple monitors, remember that the appearance of the tags is configured via `template.liquid` and `sizes.liquid` not polybar.
