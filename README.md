# Spicetify Private
Custom theme for Spicetify.
My goal was to make it look good on small touch screen (confirmed to work well on 5.5 inch).


Install spicetify and run those commands to install theme
```
spicetify --help
git clone git@github.com:tmakuch/SpicetifyPrivate.git %appdata%/spicetify/Themes/SpicetifyPrivate
spicetify backup
spicetify config current_theme SpicetifyPrivate
spicetify config color_scheme dark
spicetify apply
```

## Custom playlists icons
I've replaced some folder icons in library view with custom icons. This is first sections after root variables. Icons are applied based on folder names.

Icons stored in variables ending with -icons8 are pulled from icons8.com site.