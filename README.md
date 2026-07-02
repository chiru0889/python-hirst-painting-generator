# 🎨 Hirst Painting Generator

A creative Python project that generates beautiful dot paintings inspired by famous artist Damien Hirst's style using the Turtle graphics module. This program extracts colors from an image and creates stunning abstract art.

## ✨ Features

- **Color Extraction**: Automatically extracts colors from reference images
- **Random Generation**: Creates unique paintings each time
- **Turtle Graphics**: Uses Python's built-in Turtle module for drawing
- **Artistic Output**: Generates colorful dot paintings with professional appearance
- **Customizable**: Easy to modify size, dots, and colors

## 🎯 Project Highlights

- RGB color extraction and analysis
- Random positioning and color selection
- Algorithmic art generation
- Clean, well-commented code
- Interactive visualization

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Graphics**: Turtle Module
- **Image Processing**: Pillow (PIL)
- **Concepts**: Lists, Loops, Random module, Coordinates

## 📋 Prerequisites

- Python 3.6+
- Pillow library (for image processing)

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/chiru0889/python-hirst-painting-generator.git
cd python-hirst-painting-generator
```

### 2. Install Dependencies
```bash
pip install pillow
```

### 3. Run the Program
```bash
python hirst_painting.py
```

## 📖 How It Works

### Step 1: Image Analysis
The program loads a reference image and extracts all unique colors using Pillow.

### Step 2: Color Storage
Colors are stored in a list for random selection during drawing.

### Step 3: Random Generation
The Turtle graphics module randomly places colored dots across the canvas using:
- Random X and Y coordinates
- Random color selection
- Consistent dot size

### Step 4: Visualization
The final painting is displayed in a Turtle window showing the generated artwork.

## 📂 Project Structure

```
python-hirst-painting-generator/
├── hirst_painting.py    # Main program
├── image.jpg           # Reference image
├── README.md           # Documentation
└── .gitignore         # Git ignore file
```

## 💻 Code Example

```python
import turtle
from colorsys import rgb_to_hsv
from PIL import Image

# Extract colors from image
def extract_colors(image_path):
    img = Image.open(image_path)
    colors = []
    # Extract RGB values...
    return colors

# Generate painting
def generate_painting(colors):
    screen = turtle.Screen()
    painter = turtle.Turtle()
    # Draw dots with random colors...
    turtle.done()
```

## 🎨 Customization Options

### Change Canvas Size
```python
screen.setup(width=800, height=600)  # Modify dimensions
```

### Adjust Dot Size
```python
painter.dot(15)  # Change dot radius
```

### Modify Grid
```python
# Adjust spacing between dots
x_positions = range(-300, 300, 50)
y_positions = range(-300, 300, 50)
```

## 📊 Output Example

The program generates a grid of colorful dots:
- Grid size: Customizable (typically 10x10 to 20x20 dots)
- Colors: Extracted from reference image
- Style: Abstract, artistic appearance
- Window: Interactive Turtle canvas

## 🎓 Learning Outcomes

This project teaches:
- 📚 Image processing with Pillow
- 🐢 Turtle graphics programming
- 🔄 Loop and list operations
- 🎲 Random number generation
- 🌈 Color theory and RGB values
- 🎨 Algorithmic art generation

## 🚀 Future Enhancements

- [ ] Add gradient colors between dots
- [ ] Implement click-to-draw functionality
- [ ] Save generated painting as image
- [ ] Add animation effects
- [ ] Create multiple style options
- [ ] Add user input for customization
- [ ] Performance optimization for large grids

## 🐛 Troubleshooting

### Turtle window not appearing?
- Make sure you have a display (GUI environment)
- Check that Turtle module is installed: `pip list | grep turtle`

### Image not found error?
- Verify image file is in the same directory
- Check image file format and path

### Slow performance?
- Reduce grid size
- Decrease number of dots
- Use smaller image files

## 📝 License

This project is licensed under the MIT License - feel free to use and modify it!

## 🔗 Resources

- [Python Turtle Documentation](https://docs.python.org/3/library/turtle.html)
- [Pillow Image Library](https://pillow.readthedocs.io/)
- [Damien Hirst Art](https://www.damienhirst.com/)

## 👨‍💻 Author

**Chiru**
- GitHub: [@chiru0889](https://github.com/chiru0889)
- Focus: Python Learning & Artistic Programming

## 💬 Feedback

Have suggestions or found bugs? Feel free to:
- Open an issue on GitHub
- Submit a pull request
- Contact via GitHub

---

### ⭐ Enjoying This Project?
If you like this project, please give it a **star** and share it with fellow Python enthusiasts!

**Created with ❤️ and Python**