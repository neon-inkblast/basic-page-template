# Web page starter template repo

A simple for starting a standalone web page

## Contents

- [Features](#features)
- [Usage](#usage)
- [File Structure](#file-structure)
- [CSS Themes](#css-themes)

<br />  
  
    
## Features

- đ HTML boilerplate `index.html` file with resources linked.
- đ¨ Default CSS
  - âĒ Simple `reset.css` file for standardising cross-browser.
  - đ Sensible defaults in `styles.css`.
- đˇââī¸ Built-in CSS Theme
  - đ Dark and đ Light modes
  - âšī¸ Contextual colours
  - đ Prebuilt button styles
  - đ Demo page
- đĨī¸ JS `script.js` file.
- đ  Oxygen google font as default.
- đ Placeholder favicon.
- đ 3 free-to-use image assets.

<br />

## Usage

When starting a new project, delete the `_template` folder. It is used to hold meta files for this README and the CSS theme demonstration files.

You can also delete any of the files under `assets/images` that you aren't using, and the files under `assets/css/theme` if you're not using the built-in theme.

<br />

## File structure

Project follows a clean standard for a standalone web page. See screenshot below for an example of the folder structure.
![Project screenshot](./_template/file_layout.png "Screenshot of template file structure in VS Code")

<br />

## CSS Themes

Project now has built-in dark and light themes. To see a demonstration of them in action, have a look at the page found under `_template/demo.html`

### Usage

To use the built-in themes, include the `base.css` file found in `assets/css/theme`.

```html
<link rel="stylesheet" href="assets/css/theme/base.css" />
```

To use prebuilt button styles, also include `assets/css/theme/buttons.css`. This must come after `main.css` in the stylesheet order.

```html
<link rel="stylesheet" href="assets/css/theme/buttons.css" />
```

### Dark Theme

![Dark screenshot](./_template/dark_theme.png "Screenshot of example page in Dark theme")

### Light Theme

![Light screenshot](./_template/light_theme.png "Screenshot of example page in Light theme")

<br />

Made with đĢ by Ben
ÂŠī¸2021
