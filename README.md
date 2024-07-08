# 🎨 gioDesign 

This is my design line for future projects, here I will leave the colors I am interested in using in the future. It is very much based on Apple design, but many times the documentation is only found for Figma or Sketch, that's why I decided to gather all the components that matter to me personally here. ☀️

## Color Palette

The color palette has been carefully selected to provide adequate contrast and a consistent appearance. The main colors used in this project are:

### Grays
| Color       | Hex       | RGB              | Color Preview          |
|-------------|-----------|------------------|------------------------|
| White       | `#FFFFFF` | (255, 255, 255)  | ![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+) |
| Light Gray  | `#DDDDDD` | (221, 221, 221)  | ![#DDDDDD](https://via.placeholder.com/15/DDDDDD/000000?text=+) |
| Gray        | `#AAAAAA` | (170, 170, 170)  | ![#AAAAAA](https://via.placeholder.com/15/AAAAAA/000000?text=+) |
| Dark Gray   | `#777777` | (119, 119, 119)  | ![#777777](https://via.placeholder.com/15/777777/000000?text=+) |
| Darker Gray | `#444444` | (68, 68, 68)     | ![#444444](https://via.placeholder.com/15/444444/000000?text=+) |
| Black       | `#000000` | (0, 0, 0)        | ![#000000](https://via.placeholder.com/15/000000/000000?text=+) |

### Main Colors
| Color     | Hex       | RGB              | Color Preview          |
|-----------|-----------|------------------|------------------------|
| Pink      | `#ff2d55` | (255, 45, 85)    | ![#ff2d55](https://via.placeholder.com/15/ff2d55/000000?text=+) |
| Purple    | `#5856d6` | (88, 86, 214)    | ![#5856d6](https://via.placeholder.com/15/5856d6/000000?text=+) |
| Orange    | `#ff9500` | (255, 149, 0)    | ![#ff9500](https://via.placeholder.com/15/ff9500/000000?text=+) |
| Yellow    | `#ffcc00` | (255, 204, 0)    | ![#ffcc00](https://via.placeholder.com/15/ffcc00/000000?text=+) |
| Red       | `#ff3b30` | (255, 59, 48)    | ![#ff3b30](https://via.placeholder.com/15/ff3b30/000000?text=+) |
| Teal Blue | `#5ac8fa` | (90, 200, 250)   | ![#5ac8fa](https://via.placeholder.com/15/5ac8fa/000000?text=+) |
| Blue      | `#007aff` | (0, 122, 255)    | ![#007aff](https://via.placeholder.com/15/007aff/000000?text=+) |
| Green     | `#4cd964` | (76, 217, 100)   | ![#4cd964](https://via.placeholder.com/15/4cd964/000000?text=+) |

## 🔤 Font Family

In order of importance

- apple-system
- system-ui
- BlinkMacSystemFont
- Segoe UI
- Roboto
- Helvetica Neue
- Arial

```css
:root {
    --fonts: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}
```

## 🌑 Shadows
```css
--shadow: 0px 4px 32px 0px rgba(0, 0, 0, 0.1);
```
## Full CSS </>

```css
:root {
    --white: #FFFFFF;
    --light-gray: #DDDDDD;
    --gray: #AAAAAA;
    --dark-gray: #777777;
    --darker-gray: #444444;
    --black: #000000;

    --pink: #ff2d55;
    --purple: #5856d6;
    --orange: #ff9500;
    --yellow: #ffcc00;
    --red: #ff3b30;
    --teal-blue: #5ac8fa;
    --blue: #007aff;
    --green: #4cd964;

    --fonts: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;

    --shadow: 0px 4px 32px 0px rgba(0, 0, 0, 0.1);
}
