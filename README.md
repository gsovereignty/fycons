# fycons

### Font Awesome icons for Fyne
#### Usage
`go get github.com/gazhayes/fycons`

Then simply import the library and start using it, for example:

```
import "github.com/gazhayes/fycons"

tabitem := widget.NewTabItemWithIcon("Settings", fycons.Regular_cogs, settingsPage())
```

#### Finding the right icon

All icons can be seen here: https://fontawesome.com/icons?d=gallery

Font Awesome includes 4 different styles of icons:
1. duotone, 
2. light, 
3. regular, 
4. solid.

All of these icons are available and are exported as follows:

`fycons.Duotone_x` [Available icons](https://fontawesome.com/icons?d=gallery&s=duotone)   
`fycons.Light_x` [Available icons](https://fontawesome.com/icons?d=gallery&s=light)   
`fycons.Regular_x` [Available icons](https://fontawesome.com/icons?d=gallery&s=regular)   
`fycons.Solid_x` [Available icons](https://fontawesome.com/icons?d=gallery&s=solid)   
`fycons.Brands_x` [Available icons](https://fontawesome.com/icons?d=gallery&s=brands)   

Simply replace the `x` with the name of the icon.

For example, [`fas fa-blind`](https://fontawesome.com/icons/blind?style=solid) is exported as `Solid_blind`. `fas` = Font Awesome Solid.  

If there is a `-` in the Font Awesome icon name, it is exported here without this `-` character. For example, [`fas fa-audio-description`](https://fontawesome.com/icons/audio-description?style=solid) is exported as `Solid_audiodescription`.

##### White Icons
In addition, there is a 5th set of icons included in this package: it is the `regular` icon set from above, but is rendered in white instead of the original black. These are available as `fycons.White_x` and can be used with any icon names [here](https://fontawesome.com/icons?d=gallery&s=regular).
