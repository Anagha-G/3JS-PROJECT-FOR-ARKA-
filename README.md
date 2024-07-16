# 3JS-PROJECT-FOR-ARKA-
This project is a 2D scene created using Three.js. It allows users to interactively create an n-sided polygon, copy the polygon, and reset the scene. The project demonstrates usage of object-oriented programming (OOP) principles and structured code.

## Features

1. **Ground Plane**: 
   - White-colored plane facing the camera.
   - Contains grid lines (not a static image).

2. **Polygon Creation**:
   - Users can create vertices of an n-sided polygon by clicking the left mouse button.
   - A "Complete" button finalizes the polygon creation.
   - The polygon has a distinct color different from the ground.
   - The edges of the polygon are highlighted with a different color.

3. **Copy Polygon**:
   - A "Copy" button creates a replica of the created polygon.
   - The replica follows the cursor until placed with a left mouse click.
   - Multiple replicas can be created.
   - If no polygon is created, the "Copy" button does nothing.

4. **Reset Scene**:
   - A "Reset" button clears all polygons and resets the scene.

5. **Object-Oriented Design**:
   - Separate class for the polygon.
   - Each copied polygon creates a new object instance.

## Technologies Used

- HTML
- CSS
- Vanilla JavaScript
- Three.js library

## Getting Started

### Prerequisites

To run this project locally, you need to have:

- A modern web browser
- A local server setup (optional but recommended for file access issues)
