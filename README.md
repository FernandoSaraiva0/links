# Fernando Saraiva

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-black?style=flat-square&logo=github)](https://fernandosaraiva0.github.io/links/)
[![License](https://img.shields.io/badge/License-MIT-black.svg?style=flat-square)](LICENSE)

> Personal links page with minimalist design

## About

A clean, minimalist personal links page inspired by Unix developer aesthetic. Simple, functional, and focused on content.

### Features

- **Minimalist Design**: Clean, distraction-free interface
- **Monospace Typography**: Monaco/Courier for that developer feel
- **Grayscale Color Scheme**: Black, white, and shades of gray
- **Responsive**: Works on all devices
- **Fast**: Lightweight and optimized
- **Accessible**: Proper HTML semantics and ARIA labels

## Demo

Live site: [fernandosaraiva0.github.io/links](https://fernandosaraiva0.github.io/links/)

## Stack

- HTML5
- CSS3
- Font Awesome Icons
- GitHub Pages

## Project Structure

```
links/
├── index.html              # Main page
├── assets/
│   ├── css/
│   │   ├── reset.css      # Reset and base styles
│   │   ├── style.css      # Main styles
│   │   ├── card.css       # Card components
│   │   └── font-awesome.* # Icons
│   └── images/            # Images and assets
└── README.md              # This file
```

## Color Palette

```css
/* Minimalist grayscale palette */
--background: #fafafa;      /* Light background */
--text: #1a1a1a;            /* Dark text */
--secondary: #666;          /* Secondary text/icons */
--border: #e0e0e0;          /* Borders and dividers */
--white: #fff;              /* Card backgrounds */
```

## Usage

1. Clone the repository:
```bash
git clone https://github.com/fernandosaraiva0/links.git
```

2. Open `index.html` in your browser or use a local server:
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

3. Customize:
   - Edit `index.html` for your links and info
   - Modify `assets/css/style.css` for styles
   - Replace `assets/images/profile.jpeg` with your photo

## Customization

### Update Links

Edit the links section in `index.html`:

```html
<a class="link" href="YOUR_LINK_HERE" target="_blank">
    <i class="fa fa-icon-name"></i>
    <span>Link Name</span>
    <span class="link-arrow">→</span>
</a>
```

### Change Colors

Modify the CSS variables in `assets/css/reset.css` and `assets/css/style.css`.

### Update Profile

Replace `assets/images/profile.jpeg` with your own photo.

## Credits

- Inspired by [LinkFree](https://github.com/MichaelBarney/LinkFree) by Michael Barney
- Design aesthetic inspired by Unix developer sites
- Icons by [Font Awesome](https://fontawesome.com/)

## Author

**Fernando Saraiva**

Infrastructure & DevOps Engineer

- 📧 fernandotiweb@gmail.com
- 🐙 [@fernandosaraiva0](https://github.com/fernandosaraiva0)
- 💼 [LinkedIn](https://www.linkedin.com/in/fernandosaraivadesigner/)
- 📝 [Substack](https://fernandosaraiva.substack.com/)

## License

MIT License - feel free to use and modify.

---

**Made with simplicity in mind**
