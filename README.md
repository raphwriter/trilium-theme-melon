# melon-3
A theme for [trilium](https://github.com/zadam/trilium)

melon-3 should be compatible with trilium 0.42.x

## Screenshots
![](/screenshots/trilium-theme-melon-3_5.png)

## Screenshots (slightly out of date, esp. colours)
### Note View
![screenshot1](/screenshots/trilium-theme-melon-3_3.png "Note View")

### Book View
![screenshot2](/screenshots/trilium-theme-melon-3_1.png "Book View")

### Zen View
![screenshot3](/screenshots/trilium-theme-melon-3_2.png "Zen View")




## Theme Installation
Install the theme by following these steps:
- copy the (raw) content of _trilium-theme-melon.css_
- paste it into a new trilium note named "melon-theme-3"
- add a new attribute to the melon-theme note (Alt + A)
  - Type: Label
  - Name: appTheme
  - Value: _empty_
  - inheritable: _not ticked_
- go to Menu > Options
- select it as your new theme

Further instructions can be found [here](https://github.com/zadam/trilium/wiki/Themes)

## Additional Fonts
- The web font files (.woff) have to be imported into the theme note (right click on theme note, select _Import into note_)
- the _customResourceProvider_ attribute needs to be added to every font file you want to use
- the respective attribute value should be _fonts/Font-File-Name.woff_

![fontsetup](/screenshots/trilium-theme-melon-3_4_fonts.png "Font Setup")


## Old Versions
The old version can be found in these branches [trilium-0.4.x](https://github.com/raphwriter/trilium-theme-melon/tree/trilium-0.4.x), [trilium-0.3.8](https://github.com/raphwriter/trilium-theme-melon/tree/trilium-0.3.8)
