# Style Guide

## Color Palette

### Primary Colors
- **Orange Gradient**: `#FF6900` to `#E15D00` - Used for headers, accents, and key highlights
- **Telstra Blue**: `#00b0eb` - Brand color for Telstra-related elements
- **Dark Gray**: `#2d3748` to `#4a5568` - Executive summary background and headings
- **White**: `#FFFFFF` - Primary background
- **Light Gray**: `#f8f9fa` - Section backgrounds and subtle elements

### Text Colors
- **Primary Text**: `#333333` - Main body text
- **Secondary Text**: `#555555` - Job descriptions
- **Muted Text**: `#666666` - Dates and secondary information

## Typography

### Font Stack
```css
font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
```

### Font Sizes
- **Name**: 3em (2.2em on mobile)
- **Section Titles**: 1.8em
- **Job Titles**: 1.3em
- **Body Text**: 1em baseline
- **Small Text**: 0.9em

### Font Weights
- **Light**: 300 (Name header)
- **Regular**: 400 (Body text)
- **Semi-Bold**: 600 (Subheadings)
- **Bold**: 700 (Section titles, job titles)

## Layout Structure

### Container
- **Max Width**: 210mm (A4 paper width)
- **Background**: White with subtle shadow
- **Margin**: Centered with auto margins

### Grid System
- **Main Content**: Flexbox layout
  - Sidebar: 1 flex unit (min 300px)
  - Work Experience: 2 flex units
- **Education Grid**: Auto-fit grid with minimum 250px columns

## Visual Elements

### Borders & Shadows
- **Box Shadow**: `0 0 30px rgba(0,0,0,0.1)` for main container
- **Achievement Cards**: Left border 4px solid orange
- **Border Radius**: 
  - Small: 3px (editable elements)
  - Medium: 8-10px (cards)
  - Large: 20px (contact badges)

### Interactive Elements
- **Hover Effect**: Orange tint `rgba(255, 105, 0, 0.1)`
- **Focus State**: 2px solid orange outline
- **Edit Indicator**: Pencil icon on hover

## Responsive Breakpoints

### Desktop
- Default styles apply

### Tablet (`max-width: 768px`)
- Single column layout
- Reduced font sizes
- Stack contact information

### Mobile (`max-width: 480px`)
- Further reduced padding
- Optimized font sizes
- Simplified layout

## Print Styles

### Page Setup
- **Size**: A4
- **Margins**: 0.5 inches
- **Font Size**: 12px base

### Layout Adjustments
- Two-column layout preserved (35% / 65% split)
- Remove interactive elements
- Hide edit indicators
- Prevent page breaks inside sections

## Design Principles

### Visual Hierarchy
1. Name and title most prominent
2. Section headers clearly distinguished
3. Job titles stand out within experience
4. Supporting text subdued but readable

### Consistency
- Uniform spacing between sections
- Consistent color usage for similar elements
- Standardized bullet points with orange checkmarks

### Accessibility
- High contrast ratios for text
- Clear visual separation between sections
- Readable font sizes
- Semantic HTML structure