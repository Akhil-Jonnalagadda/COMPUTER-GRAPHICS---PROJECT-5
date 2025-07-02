# Geometric Shape Drawing Tool with HTML5 Canvas

## About the Code

- This program allows users to draw geometric shapes like **lines**, **circles**, **ellipses**, and curves such as **Bezier**, **B-Spline**, and **Hermite** on an HTML5 canvas using mathematical algorithms.
- Implements:
  - **DDA algorithm** for drawing lines
  - **Midpoint algorithm** for circles and ellipses
  - Mathematical formulas for rendering advanced curves
- Supports two rendering methods:
  - One using **Canvas built-in primitives** for smooth and consistent rendering.
  - Another using **point-by-point drawing** for precise control and customization.
- Users can:
  - Input **radius**, **control points**, and **coordinates**
  - Adjust **line color** and **thickness** via a **color picker** and **number input**

## Issues Faced

- Faced difficulty implementing **Undo and Redo**, as canvas state didn't always return correctly to the previous state.
- Handling invalid or empty user inputs sometimes caused shapes to fail rendering.
- Drawing smooth curves like **Bezier** and **Hermite** had challenges applying the correct color, line width, and maintaining a white canvas background for saving images.

## Lessons Learned

- Learned mathematical drawing algorithms like **Midpoint** and how to apply **parametric equations** for accurate geometric rendering.
- Implemented **canvas state saving using `toDataURL()`** to manage Undo and Redo functionality.
- Gained hands-on experience with Canvas API functions such as:
  - `lineTo()`
  - `arc()`
  - `ellipse()`
  - `bezierCurveTo()`
- Improved user interaction by integrating:
  - **Color picker**
  - **Line width input**
  - **Image saving functionality**
- Reorganized codebase by separating logic for drawing, input handling, and canvas state tracking for better clarity and maintainability.

## Remaining Bugs

- There are **no remaining bugs** in the current version.
- All features including:
  - Shape drawing
  - Color selection
  - Line thickness adjustment
  - Undo/Redo
  - Clear canvas
  - Image saving
  are working correctly and without issues.

## Additional Functionalities

- Added extra tools for:
  - **Undo**
  - **Redo**
  - **Clear Canvas**
  - **Color Picker**
  - **Line Width Control**
  - **Save as PNG**
- Implemented two distinct rendering approaches:
  - One using **manual algorithms**
  - One using **Canvas built-in functions** for smoother output

---

## How to Run

1. Download or clone the repository.
2. Open the HTML file in any modern web browser.
3. Use the available UI tools to:
   - Draw shapes
   - Select colors and line thickness
   - Undo/Redo changes
   - Clear or save the canvas as PNG
