# melon-4
A theme for [Trilium Notes](https://github.com/zadam/trilium), (>= 0.48.x) "_a hierarchical note taking application with focus on building large personal knowledge bases_". 

I really like this application and its many features. At the same time I felt like it needed some visual _overhaul_ for lack of better terms. I am trying to achieve a consistent look and feel. Sometimes things break (e.g. due to updates of the application) - please don't hesitate to file an issue!

## Screenshots
### Main Window
![screenshot1](/screenshots/scrn4_01.png "More info below!")


## Theme Installation

### Please follow the official instructions [here](https://github.com/zadam/trilium/wiki/Themes).

#### In a nutshell:
Install the theme by following these steps:
- copy the (**raw**) content of ![trilium-theme-melon-4.css](https://raw.githubusercontent.com/raphwriter/trilium-theme-melon/master/melon-theme-4.css)
- paste it into a new trilium **code** note (type: CSS) named "melon-theme-4"
- add a new attribute to the melon-theme-4 note `(Alt + A)`
  - either copy & paste `#appTheme=melon-4` to the node's attributes
  - or use the UI with these settings
    - Type: Label
    - Name: appTheme
    - Value: melon4
    - inheritable: _not ticked_
- go to Menu > Options
- select it as your new theme

## Additional Fonts
To get the full experience you need to install some additional fonts.
- The web font files (.woff) have to be imported into the theme note (right click on theme note, select _Import into note_)
- the _customResourceProvider_ attribute needs to be added to every font file you want to use
- the respective attribute _value_ should be _fonts/Font-File-Name.woff_

### Example Attributes (use to copy&paste)

```
#originalFileName=FiraCode-Regular.woff #customResourceProvider="fonts/FiraCode-Regular.woff"

```

