# Move More, Feel Better

## About This Project

This project is a responsive feature story about how movement can support physical and mental well-being. I created it with HTML and CSS to practice page flow, responsive layouts, positioning, layering, and CSS shapes.

## What I Used

- Semantic HTML5
- CSS Grid and Flexbox
- Responsive media queries
- Relative, absolute, and sticky positioning
- `z-index` and custom layer variables
- `clip-path` for decorative shapes
- `shape-outside` for wrapped text
- `@supports` for browser fallbacks
- Keyboard focus styles

## Project Files

- `index.html` - Main feature story
- `styles.css` - Page design and responsive layout
- `composition-plan.html` - Explanation of my layout decisions
- `support-fallback-record.html` - Browser support and fallback information
- `test-record.html` - Testing results
- `feature.svg` - Main illustration
- `portrait.svg` - Portrait image
- `screenshots/` - Testing screenshots

## Assignment Requirements

- **L1:** Content is organized in a clear reading order.
- **L2:** The page uses normal document flow.
- **L3:** Grid, Flexbox, and media queries create the responsive layout.
- **L4:** Relative, absolute, and sticky positioning are used.
- **L5:** Layering, clipping, CSS shapes, and fallbacks are included.
- **L6:** Planning, support, and testing records are provided.

## Testing

I tested the page at 320px, 768px, and 1280px. I also checked it at 200% zoom, with keyboard navigation, with CSS disabled, and with longer content.

The HTML passed validation. The CSS validator flagged `shape-outside` and `shape-margin`, but these are valid CSS Shapes properties. They are placed inside an `@supports` rule so the page still has a readable fallback in browsers that do not support them.

## Documentation

- [Composition Plan](composition-plan.html)
- [Support and Fallback Record](support-fallback-record.html)
- [Test Record](test-record.html)

## How to View

Open `index.html` in a modern web browser.