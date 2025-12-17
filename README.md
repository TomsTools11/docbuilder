# DocBuilder

A landing page and portal for a suite of AI-powered document generation tools that help professionals create creative briefs, style guides, and product requirements documents in minutes.

## Overview

DocBuilder serves as a hub for three AI-powered document generation tools:

### 🎨 Creative Brief Builder
Generate comprehensive creative briefs from marketing assets using AI.
- Upload marketing assets (images, PDFs, documents)
- AI analyzes and extracts key information
- Get structured briefs in minutes

**[Live App](https://brief-builder.netlify.app/)** | **[GitHub](https://github.com/TomsTools11/creative-brief-builder)**

### 📐 Style Guide Generator
Automatically generate professional brand style guides from any website.
- Enter any website URL
- Extract colors, typography, and design patterns
- Download a complete style guide instantly

**[Live App](https://styleguidegenerator-production.up.railway.app/)** | **[GitHub](https://github.com/TomsTools11/styleguidegenerator)**

### 📋 PRD Builder
Create detailed product requirements documents with AI assistance.
- Define features and user stories
- AI helps structure specifications
- Export professional PRD documents

**[Live App](https://prd-builder.netlify.app/)** | **[GitHub](https://github.com/TomsTools11/prd-builder)**

## Features

- **Asset Analysis** - Upload images, PDFs, and marketing materials for AI analysis
- **URL Extraction** - Extract design patterns and brand elements from websites
- **AI-Powered** - Intelligent analysis and document generation
- **Professional Output** - Beautifully formatted, downloadable documents
- **Instant Results** - Generate documents in under 60 seconds
- **Brand Consistency** - Maintain consistent branding across all documents

## Tech Stack

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Custom properties, flexbox, grid, responsive design
- **SVG** - Vector graphics for images and icons
- **Netlify** - Static site hosting

No build tools or JavaScript frameworks required - pure HTML/CSS for simplicity and performance.

## Project Structure

```
docbuilder/
├── index.html              # Main landing page
├── styles.css              # All styling with design tokens
├── README.md               # This file
├── PROGRESS.md             # Development progress log
│
├── Assets/
│   ├── tt9.svg                         # Header logo
│   ├── docbuilder-logo.svg             # Footer logo
│   ├── brief-builder-image.svg         # Tool preview
│   ├── style-guide-generator-image.svg # Tool preview
│   └── PRD-screenshot.svg              # Tool preview
│
└── Documentation/
    └── brief-builder.netlify.app-style-guide.pdf
```

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/TomsTools11/docbuilder.git
   cd docbuilder
   ```

2. Open `index.html` in your browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve
   ```

3. Visit `http://localhost:8000`

### Making Changes

Edit the HTML and CSS files directly - no build step required. The site uses CSS custom properties (design tokens) for easy theming:

```css
/* Primary colors */
--color-accent-primary: #2383E2;
--color-bg-dark: #1F1F1F;
--color-bg-light: #FFFFFF;

/* Typography */
--font-size-display: 48px;
--font-size-body: 14px;
```

## Deployment

The site is deployed automatically via Netlify. Any push to the main branch triggers a new deployment.

To deploy your own version:
1. Fork this repository
2. Connect to Netlify
3. Deploy (no build settings required)

## Design System

The landing page follows a consistent design system with:

- **Color Palette**: Blue accent (#2383E2) with dark/light backgrounds
- **Typography**: System font stack for optimal performance
- **Spacing**: 4px base unit scale (4, 8, 12, 16, 20, 24, 32, 40, 48, 64px)
- **Border Radius**: 8px buttons, 12px cards, 100px badges
- **Responsive Breakpoints**: 640px, 768px, 1024px

## Accessibility

- Skip-to-content link for keyboard navigation
- Semantic HTML structure (header, main, footer, nav, section)
- Proper heading hierarchy
- Focus indicators on interactive elements
- ARIA labels where needed
- Respects `prefers-reduced-motion`

## Related Projects

| Project | Description | Links |
|---------|-------------|-------|
| Creative Brief Builder | AI-powered creative brief generator | [Live](https://brief-builder.netlify.app/) / [GitHub](https://github.com/TomsTools11/creative-brief-builder) |
| Style Guide Generator | Website-to-style-guide tool | [Live](https://styleguidegenerator-production.up.railway.app/) / [GitHub](https://github.com/TomsTools11/styleguidegenerator) |
| PRD Builder | Product requirements document generator | [Live](https://prd-builder.netlify.app/) / [GitHub](https://github.com/TomsTools11/prd-builder) |

## Author

**Tom Panos** - [tom-panos.com](https://tom-panos.com)

Made with love in Milwaukee, WI

## License

This project is open source and available under the [MIT License](LICENSE).
