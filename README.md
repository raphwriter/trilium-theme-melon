# melon-3
A theme for [Trilium Notes](https://github.com/zadam/trilium), "_a hierarchical note taking application with focus on building large personal knowledge bases_". 

I really like this application and its many features. At the same time I felt like it needed some visual _overhaul_ for lack of better terms. I am trying to achieve a consistent look and feel. Sometimes things break (e.g. due to updates of the application) - please don't hesitate to file an issue!

## Screenshots
### Main Window
![screenshot1](/screenshots/scrn01.png "More info below!")
### Zen Mode
![screenshot2](/screenshots/scrn02.png "More info below!")
### Main Window with open Panels
![screenshot3](/screenshots/scrn03.png "More info below!")

## Theme Installation

![screenshot5](/screenshots/scrn05.png "Setup")

Install the theme by following these steps:
- copy the (**raw**) content of ![trilium-theme-melon-3.css](https://raw.githubusercontent.com/raphwriter/trilium-theme-melon/master/trilium-theme-melon-3.css)
- paste it into a new trilium **code** note (type: CSS) named "melon-theme-3"
- add a new attribute to the melon-theme-3 note (Alt + A)
  - either copy & paste ```#appTheme``` to the node's attributes
  - or use the UI with these settings
    - Type: Label
    - Name: appTheme
    - Value: _empty_
    - inheritable: _not ticked_
- go to Menu > Options
- select it as your new theme

Further instructions and information on themes can be found [here](https://github.com/zadam/trilium/wiki/Themes)

## Additional Fonts
To get the full experience you need to install some additional fonts.
- The web font files (.woff) have to be imported into the theme note (right click on theme note, select _Import into note_)
- the _customResourceProvider_ attribute needs to be added to every font file you want to use
- the respective attribute _value_ should be _fonts/Font-File-Name.woff_

### Example Attributes (use to copy&paste)

```
#originalFileName=FiraCode-Regular.woff #customResourceProvider="fonts/FiraCode-Regular.woff"

```

### Example Screenshot
![screenshot3](/screenshots/scrn04.png "Font Setup")
