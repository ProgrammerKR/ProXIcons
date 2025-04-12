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

### **ProXIcons** is a clean, developer-friendly iconset crafted for modern web, app, and design projects. With over 1500+ icons and a focus on performance, ProXIcons is your go-to icon library for any creative need.

## What's New in ProXIcons

### v1.4.4 (Latest Release)

- Minor bug fixex for Performance & Readability
- JavaScript Support: Full type definitions for better developer experience.
- Performance Boost: Reduced bundle size by 15% with advanced SVG optimization.
- Accessibility: Improved ARIA support for screen readers.
- New Variants: Added outline and duotone styles.

### v1.4.3

- Fixed version conflicts and updated metadata.
- Enhanced build system with faster development scripts.
- Optimized SVG handling using svgo for smaller file sizes.
- Minor bug fixes for cross-browser compatibility.

### v1.3.0

- Initial release with 1500+ unique icons.
- Introduced regular, solid, and brand variants.
- Added Web Component for easy integration.

---
  
## Installation

#### ProXIcons offers multiple ways to integrate into your project. Choose the method that suits your workflow!

### Via npm

```bash
npm install proxicons --save
```

Import the module:

```javascript
import 'proxicons';
```

### Via CDN

Include the stylesheet in your HTML <head>:

````html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/proxicons@latest/css/proxicons.min.css">
````


Or include the JavaScript for Web Components:

````html
<script src="https://cdn.jsdelivr.net/npm/proxicons@latest/dist/proxicons.min.js"></script>
````


### Manual Download

Download the latest release from GitHub Releases and include the files manually:

`css/proxicons.min.css` for CSS-based icons.

`proxicons.min.js` for Web Components.


## Usage

ProXIcons is designed for flexibility, supporting both CSS classes and Web Components with extensive customization options.

### Using via CSS

1. Include the ProXIcons stylesheet (via CDN or local file):

````html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/proxicons@latest/css/proxicons.min.css">
````

2. Add icons using the px, pxs, pxl classes:
````html
<!-- Regular icon -->
<i class="px px-lightbulb"></i>

<!-- Solid icon -->
<i class="pxs px-lightbulb"></i>

<!-- Large brand icon -->
<i class="pxl px-github"></i>

<!-- Outline icon -->
<i class="pxo px-lightbulb"></i>
````

3. Customize with utility classes:

````html
<i class="px px-lightbulb px-spin px-lg px-blue"></i>
````

### Using via Web Component

Include the ProXIcons script:

````html
<script src="https://cdn.jsdelivr.net/npm/proxicons@latest/dist/proxicons.min.js"></script>
````

Use the <prox-icon> element:

````html
<!-- Basic icon -->
<prox-icon name="lightbulb"></prox-icon>

<!-- Solid variant -->
<prox-icon type="solid" name="lightbulb"></prox-icon>

<!-- Brand logo with customization -->
<prox-icon type="logo" name="github" size="lg" color="purple" animation="spin"></prox-icon>
````

### Web Component Attributes

The `<prox-icon>` Web Component supports the following attributes:

| **Attribute** | **Values** | **Description** |
|---------------|------------|-----------------|
| `type`        | `regular`, `solid`, `outline`, `logo`, `duotone` | Icon style variant |
| `name`        | e.g., `lightbulb`, `github`, `proxy` | Icon name (see gallery for full list) |
| `color`       | e.g., `blue`, `red`, `#FF5733`, `rgb(0,0,0)` | Icon color |
| `size`        | `xs`, `sm`, `md`, `lg`, `xl`, or `40px` | Icon size (relative or absolute) |
| `rotate`      | `90`, `180`, `270` | Rotate icon in degrees |
| `flip`        | `horizontal`, `vertical` | Flip icon orientation |
| `border`      | `square`, `circle` | Add a border shape around the icon |
| `animation`   | `spin`, `tada`, `pulse`, `bounce` | Apply an animation effect |
| `pull`        | `left`, `right` | Float icon to the left or right |

### Using in Frameworks

ProXIcons integrates seamlessly with popular frameworks:

#### React:

````jsx
import 'proxicons';
function App() {
  return <i className="px px-lightbulb px-lg"></i>;
}
````

#### Vue:

````vue
<template>
  <prox-icon name="lightbulb" type="solid" size="lg" color="blue"></prox-icon>
</template>
<script>
import 'proxicons';
</script>
````

#### Angular:

````html
<prox-icon name="lightbulb" type="outline" size="md"></prox-icon>
````

Ensure the script is included in `angular.json`


## Icon Customizer (Comming Sooon) 

#### Try our Interactive Icon Customizer to preview and generate icons in real-time:

- Visit ProXIcons Customizer.

- Adjust colors, sizes, styles, and animations.

- Download customized icons as SVG, PNG, or code snippets.


## ProXIcons Icon Preview

Here’s a quick look at some beautiful, pixel-perfect icons from **ProXIcons**

| **Icon Name** | **Preview** | **Variants Available** |
|---------------|-------------|-------------------------|
| `lightbulb`   | `<prox-icon name="lightbulb">` | Regular, Solid, Outline |
| `github`      | `<prox-icon name="github">`    | Logo, Solid |
| `proxy`       | `<prox-icon name="proxy">`     | Regular, Outline, Duotone |
| `cloud`       | `<prox-icon name="cloud">`     | Regular, Solid, Outline |

> Browse the Full Icon Gallery to explore all 1500+ icons with searchable filters.

Visit the [Full Icon Gallery](https://codepen.io/Prog-Kanishk-Raj/pen/ByaXdmq) to explore 50 sample icons.


## Contributing

We love contributions! Whether it's adding new icons, fixing bugs, or improving documentation, your help makes ProXIcons better.

### How to Contribute

1. Fork the repository.

2. Clone your fork:

````bash
git clone https://github.com/your-username/ProXIcons.git
````

3. Install dependencies:

````bash
npm install
````

4. Make changes and test locally:

````bash
npm run dev
````

5. Submit a pull request with a clear description.


## Contribution Ideas

We’d love your help to make **ProXIcons** even better! Whether you're a designer, developer, or enthusiast, here are some great ways to contribute:

- **Found a bug?** [Report it here](https://github.com/ProgrammerKR/ProXIcons/issues)
- **Have a feature idea?** [Suggest it here](https://github.com/ProgrammerKR/ProXIcons/issues/new)
- **Ready to dive in?** [Read our Contribution Guide](./CONTRIBUTING.md)

### Ways You Can Contribute

- **Design New Icons**: Submit original SVG icons following our [Icon Guidelines](./ICON_GUIDELINES.md)
- **Fix Bugs**: Help resolve open issues from the [Issues page](https://github.com/ProgrammerKR/ProXIcons/issues)
- **Add Translations**: Help localize the Customizer UI to more languages
- **Build New Features**: Add animations, export options (like WebP), or integrate with more frameworks
- **Improve Docs**: Enhance the documentation, examples, or tutorials

Every contribution counts — big or small!

#### Read our Contributing Guide (./CONTRIBUTING.md) for detailed steps.


### Our Amazing Contributors

Thanks to everyone who’s helped shape ProXIcons! 

[Insert dynamic contributor list or avatars]

> Want to see your name here? Contribute today!


## Development Setup

For developers looking to work on ProXIcons locally:

1. Clone the repo:

````bash
git clone https://github.com/ProgrammerKR/ProXIcons.git
````

2. Install dependencies:

````bash
npm install
````

3. Run the development server:

````bash
npm run dev
````

4. Build for production:

````bash
npm run build
````

### Available Scripts

- npm run dev: Start the development server with hot reloading.
- npm run build: Generate minified CSS and JS bundles.
- npm run test: Run unit tests with Jest.
- npm run lint: Check code style with ESLint.
- npm run svgo: Optimize SVG icons


## Community & Support

- Join our growing community to share ideas, get help, or showcase your projects using ProXIcons

- Discord: Join our Discord server for real-time discussions.

- GitHub Discussions: Participate in Discussions for feature requests and Q&A.

- Twitter/X: Follow us at ```@Prog_KanishkRaj``` for updates and tips.

- Email: Reach out at `programmerkr.123@gmail.com` for direct support.


### Reporting Issues

- Found a bug? Open an issue with details (OS, browser, steps to reproduce).

- Have a feature idea? Submit a feature request.


## License

ProXIcons is fully open-source with permissive licenses:

- **Icons**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **Fonts**: [SIL OFL 1.1](https://scripts.sil.org/OFL)
- **Code & Other Files**: [MIT License](https://opensource.org/licenses/MIT)

[View Full License](https://github.com/ProgrammerKR/ProXIcons/blob/main/LICENSE)


## Why Choose ProXIcons?

- Lightweight: Optimized SVGs and minimal CSS/JS footprint (~50KB minified).

- Flexible: Supports CSS, Web Components, and framework integrations.

- Customizable: Extensive options for colors, sizes, animations, and more.

- Community-Driven: Built with input from developers and designers worldwide.


## Roadmap

Here’s what’s coming next for ProXIcons:

- Icon Customizer v2 with export to Figma and Sketch.

- CLI tool for batch icon generation.

- Support for animated SVG icons.

- Localization for Customizer UI (Spanish, French, etc.).

- Integration with design tools like Adobe XD.


Check our Roadmap for progress and vote on features!


## Acknowledgments

- Inspired by FontAwesome, Feather Icons, and Boxicons.

- Special thanks to our contributors and users for their feedback and support.


ProXIcons is more than an icon library—it’s a community-driven tool to make your projects shine. Star the repo, contribute, or share your creations with us! 

Back to Top (#proxicons)
