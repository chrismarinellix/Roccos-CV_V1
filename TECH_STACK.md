# Tech Stack

## Overview
This CV is built as a single-page, client-side application using pure web technologies with no build process or dependencies.

## Core Technologies

### HTML5
- Semantic HTML structure
- ContentEditable API for in-browser editing
- Meta tags for responsive viewport

### CSS3
- **Layout Systems**:
  - Flexbox for main content structure
  - CSS Grid for education section
  - Absolute positioning for print layout

- **Modern Features**:
  - Linear gradients for backgrounds
  - Box shadows for depth
  - Backdrop filters for glass effects
  - CSS transforms and transitions
  - Media queries for responsive design
  - Print-specific styles with @media print

- **CSS Variables**: None (inline styles for simplicity)

### JavaScript
- None required - fully functional without JS
- All interactivity handled through HTML5 contenteditable

## Features

### Editing Capability
- **ContentEditable**: Native HTML5 attribute
- **Visual Feedback**: CSS hover and focus states
- **No Save Mechanism**: Changes are browser-session only

### Responsive Design
- **Mobile-First**: Responsive from 320px to 4K
- **Breakpoints**: 
  - Mobile: < 480px
  - Tablet: < 768px
  - Desktop: > 768px

### Print Optimization
- **A4 Format**: Optimized for standard paper size
- **Page Break Control**: Prevents breaking inside sections
- **Column Preservation**: Maintains layout structure

## Architecture

### File Structure
```
/
├── index.html          # Single HTML file with embedded styles
├── STYLE.md           # Style documentation
├── TECH_STACK.md      # This file
└── README.md          # Project documentation (if needed)
```

### Styling Approach
- **Embedded Styles**: All CSS in `<style>` tag
- **BEM-like Naming**: Semantic class names
- **Utility Classes**: Minimal, mostly semantic

### Data Structure
- **Static Content**: Hard-coded in HTML
- **No Database**: All content inline
- **No API Calls**: Completely self-contained

## Browser Support

### Modern Browsers (Full Support)
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Core Features Required
- Flexbox
- CSS Grid
- Linear Gradients
- ContentEditable
- Media Queries

## Performance

### Optimization
- **No External Resources**: No fonts, images, or libraries
- **Single HTTP Request**: Everything in one file
- **Inline SVG**: Pattern background as data URI
- **No JavaScript**: Zero parsing/execution overhead

### Load Time
- **Page Weight**: ~35KB uncompressed
- **Time to Interactive**: < 100ms
- **First Contentful Paint**: Immediate

## Deployment

### Hosting Requirements
- Static file hosting only
- No server-side processing needed
- No build process required

### Platforms
- **GitHub Pages**: Direct HTML serving
- **Netlify**: Automatic deployment from Git
- **Vercel**: Static site hosting
- **Any Web Server**: Apache, Nginx, etc.

## Development

### Tools Needed
- Text editor only
- No build tools
- No package managers
- No transpilation

### Local Development
```bash
# Open directly in browser
open index.html

# Or use simple HTTP server
python -m http.server 8000
# OR
npx serve
```

## Advantages

1. **Zero Dependencies**: No npm packages or libraries
2. **Instant Updates**: Edit and refresh
3. **Maximum Performance**: No overhead
4. **Universal Compatibility**: Works anywhere HTML works
5. **Easy Maintenance**: Single file to manage
6. **Version Control Friendly**: Plain text diffs

## Limitations

1. **No Persistence**: Edits don't save permanently
2. **No Dynamic Data**: Static content only
3. **Limited Interactivity**: Basic editing only
4. **No Component Reuse**: All code inline

## Future Enhancements (Optional)

### Possible Additions
- Local Storage for edit persistence
- Print button with JS
- PDF generation
- Dark mode toggle
- Animation effects
- External font loading

### Would Require
- JavaScript for functionality
- Build process for optimization
- Additional dependencies