# ProXIcons
[![GitHub stars](https://img.shields.io/github/stars/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons/network)
[![GitHub license](https://img.shields.io/github/license/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons/pulls)
[![GitHub last commit](https://img.shields.io/github/last-commit/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons)
[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons)
[![GitHub language count](https://img.shields.io/github/languages/count/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons)
[![Top language](https://img.shields.io/github/languages/top/ProgrammerKR/ProXIcons.svg)](https://github.com/ProgrammerKR/ProXIcons)
[![Maintenance](https://img.shields.io/maintenance/yes/2025.svg)](https://github.com/ProgrammerKR/ProXIcons)

---

_High Quality, Modern, and Lightweight Open Source Icons_

**ProXIcons** is a clean, developer-friendly iconset crafted for modern web, app, and design projects. With over 1500+ icons and a focus on performance, ProXIcons is your go-to icon library for any creative need.

## What's New

### v1.4.4
- Version conflict resolved and metadata updated
- Improved build system and development scripts
- Optimized SVG handling using `svgo`
- Minor internal fixes for better stability

### v1.3.0
- Initial release with 1500+ unique icons
- Supports regular, solid, and brand variants
- Includes Web Component for seamless integration

---
  
## Installation

To install via npm:

```bash
npm install proxicons --save
```

Import the module:

```javascript
import 'proxicons';
```

## Usage

### Using via CSS

1. Include the stylesheet in your HTML `<head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/proxicons@latest/css/proxicons.min.css">
```

2. Use the icons with classes `px`, `pxs`, and `pxl`:

```html
<i class="px px-lightbulb"></i>
<i class="pxs px-lightbulb"></i>
<i class="pxl px-github"></i>
```

### Using via Web Component

```html
<script src="https://cdn.jsdelivr.net/npm/proxicons@latest/dist/proxicons.js"></script>
```

Example usage:

```html
<prox-icon name="lightbulb"></prox-icon>
<prox-icon type="solid" name="lightbulb"></prox-icon>
<prox-icon type="logo" name="github"></prox-icon>
```

#### Attributes

```html
<prox-icon
    type="regular|solid|logo"
    name="icon-name"
    color="blue|red|..."
    size="xs|sm|md|lg|40px"
    rotate="90|180|270"
    flip="horizontal|vertical"
    border="square|circle"
    animation="spin|tada|..."
    pull="left|right"
></prox-icon>
```

## Contributors

Thanks to all contributors who help maintain and improve this project!

## License

- Icons: CC 4.0
- Fonts: SIL OFL 1.1
- Other Files: MIT

[Read the full license here](https://github.com/ProgrammerKR/ProXIcons/blob/main/LICENSE)

## Contributing

Pull requests and contributions are welcome! Caught an issue or have an idea? [Open an issue](https://github.com/ProgrammerKR/ProXIcons/issues) or [edit the README](https://github.com/ProgrammerKR/ProXIcons/edit/main/README.md)
