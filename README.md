Port of [Zenburn](http://slinky.imukuppi.org/zenburnpage/) to CSS, TextMate,
Sublime Text, and Xcode.

![Zenburn CSS Demo](http://media.colinta.com/zenburn/css.png "Zenburn CSS Demo")
![Zenburn HTML Demo](http://media.colinta.com/zenburn/html.png "Zenburn HTML Demo")
![Zenburn Python Demo](http://media.colinta.com/zenburn/python.png "Zenburn Python Demo")
![Zenburn Ruby Demo](http://media.colinta.com/zenburn/ruby.png "Zenburn Ruby Demo")

# Sublime Text

Install "zenburn" via Package Control, and open Preferences.  Use any theme you like, I found `Adaptive` works well:

###### Preferences.sublime-settings
```json
{
    "color_scheme": "Packages/zenburn/zenburn.tmTheme",
    "theme": "Adaptive.sublime-theme"
}
```

# iterm

`Preferences > Profiles > [Default profile] > Colors > Load Presets... > [zenburn.itermcolors]`

# SCSS

###### zenburn.scss

# TextMate

###### zenburn.tmTheme

# Xcode

###### zenburn.xccolortheme

```bash
mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes
cp zenburn.xccolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

![Zenburn Xcode Demo](http://media.colinta.com/zenburn/xcode.png "Zenburn Xcode Demo")

# Apple Terminal

###### zenburn.terminal
