# Design Guidelines

## Brand Identity

### Colors
- **Primary**: #3498db (Blue)
- **Secondary**: #2ecc71 (Green)
- **Accent**: #e74c3c (Red)
- **Background**: #f8f9fa (Light Gray)
- **Text**: #333333 (Dark Gray)

### Typography
- **Headings**: Montserrat, sans-serif
- **Body**: Open Sans, sans-serif
- **Code**: Fira Mono, monospace
- **Base font size**: 16px
- **Line height**: 1.6

## Layout

### Grid System
- Use CSS Grid for page layouts
- Use Flexbox for component layouts
- Maintain 12-column grid structure when possible
- Standard gutter width: 20px

### Spacing
- Base unit: 8px
- Use multiples of the base unit for all spacing:
  - Extra small: 8px (1×)
  - Small: 16px (2×)
  - Medium: 24px (3×)
  - Large: 32px (4×)
  - Extra large: 48px (6×)

### Breakpoints
- **Mobile**: < 576px
- **Tablet**: 576px - 992px
- **Desktop**: > 992px

## Components

### Buttons
- Height: 40px
- Padding: 8px 16px
- Border radius: 4px
- Transitions: 0.2s ease-in-out
- States: default, hover, active, disabled

### Cards
- Border radius: 8px
- Box shadow: 0 2px 4px rgba(0,0,0,0.1)
- Padding: 24px
- Max width: 400px

### Navigation
- Desktop: Horizontal menu
- Mobile: Hamburger menu with slide-out drawer
- Active state indicator: 2px underline

## Images

### Hero Images
- Desktop: 1600×600px
- Mobile: 800×600px
- Format: WebP with JPEG fallback
- Optimization: Compress all images to < 200KB

### Content Images
- Max width: 800px
- Format: WebP with JPEG fallback
- Always include alt text
- Lazy load images below the fold

## Accessibility

### Color Contrast
- Text must have a contrast ratio of at least 4.5:1 against its background
- Large text (18pt+) must have a contrast ratio of at least 3:1

### Interactive Elements
- Focus states must be clearly visible
- Touch targets should be at least 44×44px
- Include hover and focus effects for all interactive elements

### Semantic Structure
- Use proper heading hierarchy (H1 → H6)
- Use semantic HTML elements (nav, main, section, article, etc.)
- Include ARIA attributes where appropriate

## Animation

### Transitions
- Duration: 200-300ms
- Timing function: ease-in-out
- Properties to animate: opacity, transform

### Hover Effects
- Subtle scale: transform: scale(1.05)
- Color shifts with transitions
- Avoid animations that cause layout shifts

## Code Style

### CSS
- Follow BEM naming convention:
  - Block: `.card`
  - Element: `.card__title`
  - Modifier: `.card--featured`
- Use CSS custom properties for theme values
- Organize properties alphabetically

### HTML
- Use 2 space indentation
- Use lowercase for element names and attributes
- Use double quotes for attribute values
- Close all tags properly