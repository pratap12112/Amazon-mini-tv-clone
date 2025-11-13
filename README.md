# Amazon MiniTV Clone

This project is a static recreation of the Amazon MiniTV landing page. It delivers a carousel hero section, horizontally scrolling content rows, and a footer that mirrors the look and feel of the original service.

## Tech Stack
- HTML (`PrimeTv.html`) for the page structure
- CSS (`PrimeTv.css`) for layout and styling
- Vanilla JavaScript (`Prime.js`) for the slideshow and auto-scrolling carousels

## Project Structure
```
AMAJON_WEB_PROJECT/
├── PrimeTv.html
├── PrimeTv.css
├── Prime.js
├── ASSESTS/
│   ├── movies_images/
│   ├── saipallavi/
│   ├── logo/
│   ├── LastPage/
│   └── ...
└── .vscode/
```

> Note: Asset paths in the HTML and CSS assume the `PrimeTv.html` file is served from the project root. Keep the directory structure intact or update the paths accordingly.

## Getting Started
1. Clone or download the repository.
2. Ensure all files from the `ASSESTS` directory remain in place (image paths are relative).
3. Open `PrimeTv.html` in a modern browser (Chrome, Edge, Firefox, etc.). No build step is required.

## Features
- Sticky navigation bar with primary links
- Image slideshow with previous/next controls
- Multiple horizontally scrolling “trending” sections with hover scaling
- Footer with promotional graphics and social icons

## Customization Tips
- Replace images in `ASSESTS` with your own content. Use the same filenames or update the references in `PrimeTv.html`/`PrimeTv.css`.
- Tweak colors, spacing, or animation speeds in `PrimeTv.css` to match your branding.
- Extend `Prime.js` to fetch slide data dynamically or to enhance carousel behavior if needed.

## VS Code Settings
A minimal `.vscode/settings.json` is provided for workspace-level customization. Edit as desired or remove if you prefer your global editor defaults.

## License
This project is provided for educational and demonstration purposes. Review and comply with Amazon’s branding and content usage policies if you plan to publish or share the page.


