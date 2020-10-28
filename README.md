# fycons

### Font Awesome icons for Fyne
#### Usage
`go get github.com/gazhayes/fycons`

Then simply import the library and start using it, for example:

```
import "github.com/gazhayes/fycons"

tabitem := widget.NewTabItemWithIcon("Settings", fycons.Regular_cogs, settingsPage())
```

#### Finding the right icons
There are five different styles of icons: 
1. duotone, 
2. light, 
3. regular, 
4. solid, and
5. white (this is `regular` but renders white instead of black).

These are exported as `Duotone_x` where `x` is the Font Awesome name for the icon.

For example, `fas fa-blind` is exported as `Solid_blind` (fas = font awesome solid).  

In addition, there are brand icons. These are exported as `Brands_x`.  

If there was a `-` in the Font Awesome icon name, it is exported here without it. For example:  
`fas fa-audio-description` will be exported as `Solid_audiodescription`.
