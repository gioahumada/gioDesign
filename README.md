
# 🎨 gio Design 

This is my design line for future projects, here I will leave the colors I am interested in using in the future. It is very much based on Apple design, but many times the documentation is only found for Figma or Sketch, that's why I decided to gather all the components that matter to me personally here. ☀️

## First palette

| Color             | Hex                    | RGB |
| ----------------- | ---------------------- | - |
| Blue 1 | ![#005AD6](https://via.placeholder.com/10/005AD6?text=+) #005AD6 | 0, 90, 214
| Blue 2 | ![#007AFF](https://via.placeholder.com/10/007AFF?text=+) #007AFF | 0, 122, 255|
| Grey | ![#767679](https://via.placeholder.com/10/767679?text=+) #767679 | 118, 118, 121 |

## Alternative palette

| Color             | Hex                    | RGB |
| ----------------- | ---------------------- | - |
| Pink | ![#ff2d55](https://via.placeholder.com/10/ff2d55?text=+) #ff2d55 | 255, 45, 85
| Purple | ![#5856d6](https://via.placeholder.com/10/5856d6?text=+) #5856d6 | 88, 86, 214|
| Orange | ![#ff9500](https://via.placeholder.com/10/ff9500?text=+) #ff9500 |  255, 149, 0 |

Dumped from here https://colorswall.com/palette/40133



## 🔤 Font Family

In order of importance

- apple-system
- system-ui
- BlinkMacSystemFont
- Segoe UI
- Roboto
- Helvetica Neue
- Arial
## CSS Style


**Import colors from First Palette :**
```
:root {
  --color-blue-1-rgb: 0, 90, 214;
  --color-blue-2-rgb: 0, 122, 255;
  --color-grey-rgb: 118, 118, 121;
  --focus-ring: 0px 0px 0px 4px rgba(var(--color-blue-2-rgb), 0.6);
}
```
*To use remember the var()*

**Fonts Family**

```
font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
    text-rendering: geometricPrecision;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
```

**Shadow**
```
box-shadow: 0px 4px 32px 0px rgba(0, 0, 0, 0.1);
```

**Buttons**
```
margin: 7px;
border-radius: 16px;
```
## Soon

- Light/dark mode toggle colors

