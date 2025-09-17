# CSS Learning Hub

A comprehensive collection of interactive CSS examples and live demos designed to help students master CSS concepts through hands-on learning.

## About

This repository contains a static HTML + CSS website that showcases web topics through live demonstrations and exact code examples. Each example page includes:

- **Live Demo**: Working HTML/CSS examples you can interact with
- **Exact Code**: The precise HTML and CSS used to create each demo
- **Learning Notes**: Key concepts, best practices, and important gotchas

## Structure

```
.
├─ README.md
├─ index.html                  # Home (navigation hub)
├─ examples/
│  ├─ overflow-visibility.html
│  ├─ z-index-opacity.html
│  ├─ borders.html
│  ├─ text-properties.html
│  ├─ css-units.html
│  ├─ web-fonts.html
│  ├─ google-fonts.html
│  ├─ typography.html
│  ├─ links-states.html
│  ├─ multi-column.html
│  ├─ pseudo-selectors.html
│  ├─ vendor-prefixes-reset.html
│  ├─ transitions-transforms.html
│  ├─ css-variables.html
│  ├─ viewport-meta.html
│  ├─ fluid-layouts.html
│  ├─ flexible-images.html
│  ├─ media-queries.html
│  ├─ breakpoints.html
│  ├─ mobile-first.html
│  ├─ responsive-layout.html
│  ├─ accessibility-performance.html
│  └─ common-mistakes.html
└─ assets/
   ├─ css/
   │  ├─ reset.css            # CSS reset for browser consistency
   │  ├─ main.css             # Site-wide styles and design system
   │  └─ examples.css         # Shared styles for example pages
   ├─ fonts/
   │  └─ README.txt           # Placeholder for custom fonts
   └─ img/
      └─ README.txt           # Placeholder for sample images
```

## How to View

1. **Open in Browser**: Simply open `index.html` in any modern web browser
2. **Local Server** (recommended): Use a local development server for best experience
3. **Responsive Testing**: Use browser DevTools responsive mode to test different screen sizes

### Quick Start

```bash
# Clone or download the repository
# Navigate to the project directory
# Open index.html in your browser
```

## Learning Modules

### CSS 2: Electric Boogaloo
- [Overflow & Visibility](examples/overflow-visibility.html) - Control content overflow and element visibility
- [Z-index & Opacity](examples/z-index-opacity.html) - Master layering and transparency
- [Borders](examples/borders.html) - Explore border styles, widths, and colors
- [Text Properties](examples/text-properties.html) - Control typography and text appearance
- [CSS Units](examples/css-units.html) - Understand px, %, em, rem, vh, vw units
- [Web Fonts (@font-face)](examples/web-fonts.html) - Embed custom fonts
- [Google Fonts](examples/google-fonts.html) - Integrate Google Fonts
- [Typography Scale](examples/typography.html) - Create consistent typography

### CSS Menus, Pseudo Selectors, Transitions
- [Link States](examples/links-states.html) - Style :link, :visited, :hover, :active
- [Multi-column Layout](examples/multi-column.html) - Create newspaper-style layouts
- [Pseudo Selectors](examples/pseudo-selectors.html) - Master :first-child, :nth-child, etc.
- [Vendor Prefixes & Reset](examples/vendor-prefixes-reset.html) - Cross-browser compatibility
- [Transitions & Transforms](examples/transitions-transforms.html) - Smooth animations
- [CSS Variables](examples/css-variables.html) - Use custom properties

### Responsive Web Design
- [Viewport Meta](examples/viewport-meta.html) - Essential mobile viewport tag
- [Fluid Layouts](examples/fluid-layouts.html) - Flexible, responsive layouts
- [Flexible Images](examples/flexible-images.html) - Make images responsive
- [Media Queries](examples/media-queries.html) - Apply different styles by screen size
- [Breakpoints](examples/breakpoints.html) - Define consistent breakpoints
- [Mobile-first](examples/mobile-first.html) - Build responsive designs mobile-first
- [Responsive Layout](examples/responsive-layout.html) - Complete responsive layout example
- [Accessibility & Performance](examples/accessibility-performance.html) - Ensure accessible, performant designs
- [Common Mistakes](examples/common-mistakes.html) - Learn from common responsive design mistakes

## Learning Checklist

- [ ] **CSS Fundamentals**: Master basic properties and selectors
- [ ] **Layout & Positioning**: Understand box model, flexbox, and grid
- [ ] **Typography**: Create readable, accessible text
- [ ] **Responsive Design**: Build mobile-first, responsive layouts
- [ ] **Animations**: Add smooth transitions and transforms
- [ ] **Accessibility**: Ensure your CSS is accessible to all users
- [ ] **Performance**: Write efficient, fast-loading CSS
- [ ] **Browser Compatibility**: Handle cross-browser differences
- [ ] **Modern CSS**: Use CSS Grid, Flexbox, and custom properties
- [ ] **Best Practices**: Follow CSS coding standards and conventions

## Contributing

Want to add your own example pages? Here's how:

### Naming Conventions
- Use kebab-case for file names: `my-example.html`
- Place all example pages in the `examples/` directory
- Follow the existing page template structure

### Page Template
Each example page should include:
1. **Header**: Site title and breadcrumb navigation
2. **Introduction**: Brief explanation of the concept
3. **Live Demo**: Working HTML/CSS example
4. **Code Sections**: Exact HTML and CSS used
5. **Notes**: Key concepts and best practices
6. **Footer**: Navigation to previous/next examples

### Code Style
- Use semantic HTML5 elements
- Follow the existing CSS custom properties system
- Include proper accessibility attributes
- Test on multiple browsers and devices
- Keep examples focused and educational

### Adding Assets
- Place fonts in `assets/fonts/`
- Place images in `assets/img/`
- Update the README if adding new asset types

## Design System

This site uses a consistent design system built with CSS custom properties:

### Colors
- `--bg`: Background color
- `--surface`: Surface color for cards and containers
- `--text`: Primary text color
- `--muted`: Secondary text color
- `--brand`: Brand/accent color
- `--border`: Border color

### Spacing
- `--space-1` through `--space-8`: Consistent spacing scale
- Use relative units (rem) for scalability

### Typography
- `--fs-xs` through `--fs-4xl`: Font size scale
- `--font-sans`: Sans-serif font stack
- `--font-mono`: Monospace font stack

### Border Radius
- `--radius-1` through `--radius-3`: Consistent border radius scale

## Browser Support

This site is designed to work in all modern browsers:
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## License

MIT License - feel free to use this project for learning, teaching, or as a starting point for your own CSS examples.

## Acknowledgments

- Built with modern CSS best practices
- Inspired by the need for hands-on CSS learning resources
- Designed to be accessible and inclusive
- Created for students, by students

---

**Happy Learning!** 🎨

Start with the [home page](index.html) and explore the examples that interest you most. Each page is self-contained and includes everything you need to understand the concept.
