# Design 04 - Minimalist (Unix Developer Aesthetic)

**Commit:** 46af3a2
**Date:** Minimalist redesign
**Status:** Current Active Design

## Overview

Complete minimalist redesign inspired by Unix developer personal sites. This design strips away all decorative elements to focus entirely on content with a clean grayscale aesthetic. Influenced by sites like daveeddy.com and other systems developer portfolios.

## Features

### Minimalist Elements
- No terminal decorations
- Clean, centered layout (650px max)
- Monospace typography
- Grayscale color palette
- Generous whitespace
- Subtle hover effects
- Content-first approach

### Technical Features
- Ultra-lightweight code (~213 lines total CSS)
- Fast loading times
- Excellent performance
- Full accessibility
- SEO optimized
- Mobile responsive
- Clean HTML structure

## Design Elements

### Color Scheme
```css
--background: #fafafa;     /* Light gray background */
--text: #1a1a1a;          /* Almost black text */
--secondary: #666;         /* Medium gray for secondary */
--border: #e0e0e0;        /* Light gray borders */
--white: #fff;            /* Pure white for cards */
```

### Typography
- Font: Monaco, 'Courier New', monospace
- Light weight (300-400)
- Negative letter spacing
- Clean hierarchy
- Readable sizes

### Visual Effects
1. **Grayscale Images** - Profile and cards in grayscale
2. **Color on Hover** - Images show color when hovered
3. **Border Transitions** - Borders darken on hover
4. **Subtle Indent** - Links shift right on hover
5. **Arrow Fade** - Arrow appears on hover

### Layout
- No header (terminal hidden via CSS)
- Clean centered content
- Simple link list with borders
- Minimal card design
- Subtle footer divider

## Files

- `index.html` - Simplified HTML structure
- `reset.css` - Minimal base styles (48 lines)
- `style.css` - Main styles (167 lines)
- `card.css` - Simple cards (84 lines)

## Code Reduction

Compared to previous designs:
- **Terminal Linux:** 459 lines → **Minimalist:** 213 lines
- 53% reduction in code
- Removed all decorative effects
- Simplified structure
- Cleaner, more maintainable

## Technical Details

### Hidden Elements
Terminal header and prompts still in HTML but hidden via CSS:
```css
.terminal-header {
    display: none;
}

.terminal-prompt {
    display: none;
}
```

### Link Behavior
```
Default:   ────────────────
Hover:     ──────────────── →
          (indent + arrow)
```

### Image Effects
- Default: `filter: grayscale(100%)`
- Hover: `filter: grayscale(0%)`

## Performance

- Minimal CSS (~3KB)
- No complex animations
- Fast rendering
- Excellent Lighthouse scores
- Instant page loads

## How to Use

Simply open the root `index.html` - this is the current active design.

```bash
python -m http.server 8000
```

## Design Philosophy

This design embraces:
- **Less is more** - Remove everything unnecessary
- **Content first** - Focus on information, not decoration
- **Unix philosophy** - Do one thing well
- **Developer aesthetic** - Clean, functional, professional
- **Performance** - Fast and lightweight

## Influences

- Dave Eddy's personal site
- Unix/Linux developer portfolios
- Minimalist web design movement
- Text-based interfaces
- Academic personal pages

## Typography Choices

Monaco was chosen for:
- Clean monospace appearance
- Better readability than Courier
- Professional developer feel
- Excellent on retina displays

## Notes

- **Most code-efficient** of all designs
- **Fastest loading** time
- **Easiest to maintain**
- **Most accessible**
- **Professional and timeless**
- **Won't age poorly**

## Why This Design?

After cycling through bold, colorful designs:
1. Started simple (Original)
2. Went bold (Terminal Green)
3. Got professional (Fedora Blue)
4. Returned to simplicity (Minimalist)

The minimalist approach:
- Puts content first
- Reduces distraction
- Improves readability
- Shows maturity
- Ages well
- Loads fast
- Easy to maintain

## Future Considerations

This design can easily:
- Add dark mode toggle
- Include blog posts
- Add project showcases
- Integrate timeline
- Still maintain simplicity

---

**Design created on:** 2025-12-15
**Status:** Active
**Philosophy:** Simple, functional, timeless
