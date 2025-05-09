# Contributing to ProXIcons

Welcome to the ProXIcons open-source project! We're thrilled that you're considering contributing to our growing collection of developer-friendly icons.

ProXIcons is built by the community, for the community. Whether you're an experienced designer, a developer, or a newcomer eager to help, there's a place for you here.

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [Ways to Contribute](#ways-to-contribute)
3. [Contribution Guidelines](#contribution-guidelines)
4. [Creating and Submitting Icons](#creating-and-submitting-icons)
5. [Improving Documentation](#improving-documentation)
6. [Pull Request Process](#pull-request-process)
7. [Code of Conduct](#code-of-conduct)
8. [Need Help?](#need-help)

---

## Getting Started

### 1. Fork the Repository
Click the **Fork** button on the top right of the [ProXIcons GitHub page](https://github.com/ProgrammerKR/ProXIcons). This creates your own copy of the repository.

### 2. Clone the Forked Repository
```bash
git clone https://github.com/ProgrammerKR/ProXIcons.git
cd ProXIcons
```

### 3. Create a Feature Branch
```bash
git checkout -b feature/your-feature-name
```

---

## Ways to Contribute

- Add new SVG icons
- Optimize or improve existing icons
- Fix bugs or improve structure
- Improve or expand the documentation
- Create web-based demos or integrations
- Suggest new ideas or open issues for discussion

---

## Contribution

Thank you for your interest in contributing! To ensure consistency and quality, please follow the guidelines below when designing icons or making code/documentation changes.

---

### Icon Design Guidelines

To maintain a clean, unified, and professional look across all icons in the project, please adhere to the following standards:

- **Format**: Use SVG (Scalable Vector Graphics) format only. This ensures scalability and a smaller file size.
- **Canvas Size**: Keep your icon within a `24x24` or `32x32` pixel canvas. Make sure the design is centered and fits well within the canvas.
- **Style**:
  - Use consistent line widths (typically 1.5 or 2px) across all icons.
  - Ensure pixel-perfect alignment to avoid blurry rendering at small sizes.
  - Maintain a consistent visual language (rounded vs. sharp corners, stroke caps, etc.).
- **Naming Convention**:
  - Use all lowercase letters.
  - Separate words with dashes (`-`) instead of underscores or camelCase.
  - Example: `calendar-check.svg`, `user-profile.svg`
- **Optimization**:
  - Clean up your SVG files before submitting.
  - Use [SVGO](https://github.com/svg/svgo) or [SVGOMG](https://jakearchibald.github.io/svgomg/) to remove unnecessary metadata and reduce file size.

---

### Coding & Documentation Guidelines

If you’re submitting or modifying code, components, or documentation:

- **Code Quality**:
  - Write clean, readable, and consistent code that matches the existing style.
  - Avoid duplications and keep functionality modular.
- **Documentation**:
  - Add documentation for any new icons, components, or features in the `docs/` directory.
  - If you add a new icon, consider updating the `docs/index.html` with usage examples or previews.
- **Testing**:
  - Thoroughly test your changes locally to ensure everything functions as expected.
  - Avoid breaking changes unless absolutely necessary (and clearly document them).

---

## Creating and Submitting Icons

To contribute a new icon, please follow these steps:

1. **Design** your icon according to the [Icon Design Standards](#icon-design-standards).
2. **Save** the file in SVG format.
3. **Place** the SVG inside the `icons/` directory.
4. **Name** your file using lowercase letters and dashes (e.g., `chat-bubble.svg`).
5. **Preview & Test**:
   - Open the SVG in a browser or editor to confirm proper rendering.
   - Check that it appears sharp and centered at both small and large sizes.
6. **Optional Documentation**:
   - Add a usage example or preview to `docs/index.html` if applicable.
   - Include a short description if the icon’s purpose isn't obvious.
7. **Commit & Submit**:
   - Use a clear commit message like: `Add: new icon 'chat-bubble'`.
   - Push your changes and open a pull request describing your addition.
     
---

## Improving Documentation

You can help us by enhancing documentation:
- Fixing typos or grammar
- Adding examples or explanations
- Creating usage guides or tutorials
- Updating icon references

Documentation is located primarily in the `docs/` folder.

---

## Pull Request Process

1. Ensure your branch is up to date with `main`:
```bash
git pull origin main
```

2. Commit your changes with a clear message:
```bash
git add .
git commit -m "Add: new icon 'star-outline'"
```

3. Push your branch and open a Pull Request:
```bash
git push origin feature/your-feature-name
```

4. Wait for review. We may ask for changes before merging.

---

## Code of Conduct

We follow a **friendly, inclusive, and respectful** code of conduct.
Please be respectful in all interactions and communications.

---

## Need Help?

If you're stuck or unsure, don't hesitate to:
- Open an [issue](https://github.com/ProgrammerKR/ProXIcons/issues)
- Reach out via discussions
- Tag your PRs with questions

Thank you for being a part of the ProXIcons community! Your contribution makes a difference.

— *Team ProXentix*
