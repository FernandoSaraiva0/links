# Design 02 - Terminal Linux (Green Theme)

**Commit:** f91b5d9
**Date:** Terminal Linux implementation
**Status:** Archived

## Overview

Complete redesign with a terminal/Linux aesthetic featuring a bold green (#00ff00) color scheme. This design brought personality and technical identity to the page with terminal prompts, animations, and hacker-inspired visual effects.

## Features

### Visual Effects
- Terminal header with macOS-style window controls
- Terminal command prompts (root@fernando:~#)
- Typewriter animation on subtitle
- CRT scanlines effect
- Screen flicker animation
- Green neon glow effects

### Technical Features
- Full SEO optimization with meta tags
- Open Graph and Twitter cards
- Schema.org structured data
- Accessibility with ARIA labels
- Recommendations card section
- Responsive design

## Design Elements

### Color Scheme
```css
--primary-green: #00ff00;      /* Neon green */
--cyan: #00d9ff;               /* Accent cyan */
--background: #0a0a0a;         /* Deep black */
--terminal-bg: #1a1a1a;        /* Terminal background */
```

### Typography
- Font: 'Courier New', monospace
- Glowing text shadows on headings
- Typewriter animation effect
- Terminal-style prompts

### Animations
1. **Typewriter Effect** - Subtitle appears character by character
2. **Blink Caret** - Blinking cursor effect
3. **Scanlines** - CRT monitor simulation
4. **Flicker** - Subtle screen flicker
5. **Hover Shine** - Light sweep on link hover

### Layout
- Terminal window header at top
- Centered content with prompts
- Glowing link borders
- Card grid for recommendations
- Terminal-style footer

## Files

- `index.html` - Complete HTML structure with SEO
- `reset.css` - Base styles with terminal effects
- `style.css` - Main component styles
- `card.css` - Recommendation cards

## Technical Details

### Terminal Prompts
```
root@fernando:~# cat profile.txt
root@fernando:~# ls -la ./links/
root@fernando:~# cat recommendations.md
root@fernando:~# echo "Made with ❤"
```

### Link Structure
Each link has:
- Icon (Font Awesome)
- Label text
- Arrow indicator (→)
- Hover effects with glow
- Sliding shine animation

## Performance

- Larger CSS due to effects (~280 lines style.css)
- Multiple animations running
- More visual processing
- Still fast and responsive

## How to Use

1. Open `index.html` in a browser
2. Or serve locally:
```bash
cd design/02-terminal-linux
python -m http.server 8000
```

## Design Philosophy

This design was inspired by:
- Linux terminal interfaces
- Hacker/developer culture
- Retro CRT monitors
- Matrix-style aesthetics
- DevOps/Infrastructure identity

## Notes

- High visual impact
- Very distinctive look
- Reflects technical role
- Can be overwhelming for some users
- Performance is still good despite effects

## Why It Changed

While visually striking, this design was replaced with Fedora Linux theme for a more professional appearance while maintaining the terminal aesthetic.

---

**Design archived on:** 2025-12-15
