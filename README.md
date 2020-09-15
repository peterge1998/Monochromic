# All credits go to [CTalvio/Monochromic](https://github.com/CTalvio/Monochromic)!

# Monochromic
A custom theme for Jellyfin mediaserver created using CSS overrides. 

`cd /usr/lib/jellyfin/jellyfin-web/`

`git clone https://github.com/peterge1998/Monochromic/`

To use the theme copy paste the line below into "Dashboard>General>Custom CSS" and click save, it will apply immediately server-wide to all users on top of any theme they may be using. To remove the theme, clear the "Custom CSS" field and then click save.
`@import url('https://$your-hostname$/web/Monochromic/default_style.css');`


## Features
- Uses the same font as the JF logo everywhere
- Blurred backdrops
- Squared aesthetic with rounded corners (optionally corners so sharp you might get an eye poked out)
- Works well on mobile
- Strives to theme every element
- More compact
- Smaller and squared cast info
- Customizable accent color+

## Add-ons

There are some additional options, that allow for an accent color, or removed rounding. These are added immediately after the default import line.

```css
@import url('https://$your-hostname$/web/Monochromic/sharp_style.css');
```

Removes corner rounding. In fact, squares off  every rounded corner JF ever had.

```css
@import url('https://$your-hostname$/web/Monochromic/jfblue_style.css');
```

Restore some of the jellyfin blue accenting.

```css
@import url('https://$your-hostname$/web/Monochromic/customcolor_style.css');
:root {--accent: replaceme;}
:root {--hoveraccent: replaceme80;}
```


## Screenshots

![one](screenshots/1.png)
![two](screenshots/2.png)
![three](screenshots/3.png)
