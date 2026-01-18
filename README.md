# CSE423_Computer-Graphics
🎮 A 2D grid-based mining / treasure hunt game built using **Python** and **PyOpenGL**.  
The game uses classic **midpoint line and circle drawing algorithms** and GLUT for rendering and interaction.

## 🎮 Features
- 2D OpenGL rendering using points and lines
- Drill and hammer tools with keyboard controls
- Brick-based map with hidden bombs and treasures
- Score and life system
- Mouse and keyboard interaction

## 🛠 Requirements
- Python 3.10+
- PyOpenGL
- PyOpenGL_accelerate
- FreeGLUT (for Windows)

## 📦 Installation

### 1. Install Python packages
```bash
pip install PyOpenGL PyOpenGL_accelerate
```

### 2. Install FreeGLUT (Windows)
Download FreeGLUT from:  
https://www.transmissionzero.co.uk/software/freeglut-devel/

Copy `freeglut.dll` into:
- the project folder **or**
- `C:\Windows\System32`

### 3. Run the game
```bash
python game.py
```

(If `python` does not work on Windows, use `py game.py`)

## 🎮 Controls
- Arrow keys – Move drill / hammer
- Mouse click – Break bricks
- Space – Pause / Resume
- Mouse buttons – UI controls

## 📚 Concepts Used
- Midpoint line drawing algorithm
- Midpoint circle drawing algorithm
- OpenGL primitives (GL_POINTS)
- Event-driven programming with GLUT

## 📄 License
This project is for educational purposes.

