# Quick Sign App

A simple web-based drawing application that allows users to draw on a canvas, change colors, adjust stroke width, clear the canvas, and save or retrieve their drawings.

## Features
- **Drawing on Canvas**: Click and drag to draw lines.
- **Color Picker**: Choose different stroke colors.
- **Canvas Background Color**: Change the background color of the canvas.
- **Adjustable Line Width**: Modify the thickness of the strokes.
- **Clear Canvas**: Erase everything on the canvas.
- **Save Drawing**: Save the drawing as an image file and store it in local storage.
- **Retrieve Drawing**: Load the saved drawing from local storage.

## Technologies Used
- **HTML**: Structure of the application.
- **CSS**: Basic styling.
- **JavaScript**: Canvas drawing functionality and event handling.

## Installation & Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/canvas-drawing-app.git
   ```
2. Open `index.html` in a web browser.
3. Start drawing on the canvas.

## How to Use
1. **Select a color** using the color picker to change the stroke color.
2. **Adjust stroke width** using the font size slider.
3. **Change canvas background** using the background color picker.
4. **Draw** by clicking and dragging the mouse.
5. **Save your drawing** by clicking the save button.
6. **Retrieve saved drawing** by clicking the retrieve button.
7. **Clear the canvas** using the clear button.

## Code Overview
- The app listens for mouse events (`mousedown`, `mousemove`, `mouseup`) to track drawing actions.
- Uses `CanvasRenderingContext2D` to draw lines.
- Saves the canvas content using `localStorage` with `toDataURL()`.
- Retrieves the saved image and redraws it on the canvas.

## Future Enhancements
- Add support for touch events on mobile devices.
- Implement an undo/redo functionality.
- Add shape-drawing options (rectangles, circles, etc.).

## License
This project is open-source and available under the [MIT License](LICENSE).

