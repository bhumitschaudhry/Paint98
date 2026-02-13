# Paint98

<div align="center">
  <img src="https://64.media.tumblr.com/bcecc9d0eecba75cb2819ee913bef41f/38d18be98b33dd57-65/s1280x1920/904afda303bd7848d8fe67052fda6b423ffe7e00.png" alt="Paint98 Logo" width="200">
  
  A web-based recreation of the classic Microsoft Paint from Windows 98
</div>

## Overview

Paint98 is a faithful recreation of the iconic Microsoft Paint application from Windows 98, built entirely with HTML, CSS, and JavaScript. Experience the nostalgia of classic digital art creation with this pixel-perfect clone.

## Features

### Drawing Tools

- **Free-Form Select** - Select irregular shapes
- **Select** - Rectangle selection tool
- **Eraser/Color Eraser** - Erase parts of your drawing
- **Fill With Color** - Flood fill tool
- **Pick Color** - Eyedropper to sample colors from canvas
- **Magnifier** - Zoom in/out (1x, 2x, 6x, 8x)
- **Pencil** - Freehand drawing
- **Brush** - Brush strokes with adjustable sizes
- **Airbrush** - Spray paint effect
- **Text** - Add text to your canvas
- **Line** - Draw straight lines with adjustable width
- **Curve** - Draw curved lines
- **Rectangle** - Draw rectangles (outline, filled, or filled with border)
- **Polygon** - Draw custom polygons
- **Ellipse** - Draw ellipses and circles
- **Rounded Rectangle** - Draw rectangles with rounded corners

### Menu Options

#### File
- New (Ctrl+N)
- Open (Ctrl+O)
- Save (Ctrl+S)
- Save As
- Print (Ctrl+P)
- Exit

#### Edit
- Undo (Ctrl+Z) / Redo (Ctrl+Y)
- Cut (Ctrl+X) / Copy (Ctrl+C) / Paste (Ctrl+V)
- Clear Selection (Esc)
- Select All (Ctrl+A)

#### View
- Toggle Tool Box
- Toggle Color Box
- Toggle Status Bar
- Zoom levels

#### Image
- Flip/Rotate (horizontal, vertical, 90°, 180°, 270°)
- Stretch/Skew
- Invert Colors
- Attributes (canvas size, units, color mode)
- Clear Image

#### Colors
- Edit Colors - Full color picker with HSL and RGB input

#### Help
- Help Topics
- About Paint

### Color Palette

- 28-color default palette
- Custom color slots (16 slots)
- Full HSL/RGB color picker
- Left-click to set foreground color
- Right-click or Ctrl+click to set background color

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/paint98.git
   ```

2. Open `index.html` in your web browser

That's it! No build process or dependencies required.

## Usage

1. **Select a tool** from the toolbar on the left
2. **Choose colors** from the color palette at the bottom
3. **Draw** on the white canvas area
4. **Use menu options** for advanced operations like flipping, stretching, or saving

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl+N | New file |
| Ctrl+O | Open file |
| Ctrl+S | Save file |
| Ctrl+P | Print |
| Ctrl+Z | Undo |
| Ctrl+Y | Redo |
| Ctrl+X | Cut |
| Ctrl+C | Copy |
| Ctrl+V | Paste |
| Ctrl+A | Select All |
| Esc | Clear Selection |

## Technical Details

- **No external dependencies** - Pure HTML, CSS, and JavaScript
- **Canvas-based rendering** - Uses HTML5 Canvas for all drawing operations
- **Undo/Redo support** - Up to 20 levels of undo history
- **Responsive design** - Window adapts to screen size
- **Authentic Windows 98 styling** - Pixel-perfect recreation of the UI

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

This project is for educational and nostalgic purposes. Microsoft Paint is a trademark of Microsoft Corporation.

## Credits

- Logo from [oldwindowsicons on Tumblr](https://oldwindowsicons.tumblr.com/post/654367700013957120/windows-98-paint)
- Inspired by the original Microsoft Paint from Windows 98
