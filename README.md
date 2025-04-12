# GoalZone-Configurator ⚽🎯
A user-friendly desktop tool to define and save goal regions on football pitch images for post analysis

## **Features**  
- 🖼️ **Upload pitch images** from camera feeds or local files.  
- 🟦 **Select rectangular goal regions** with drag-and-drop.  
- ✂️ **Auto-generate cropped images** of selected regions.  
- 🔳 **Define precise polygons** (4-point) within cropped goal images.  
- 📁 **Save configurations** in JSON format.  

## **Tech Stack**  
- **GUI**: Tkinter (Python)  
- **Image Processing**: OpenCV  
- **Data Serialization**: JSON  

## Demo
[![Demo Video](./GoalZone-Test.mp4)](./GoalZone-Test.mp4)

## **Installation**  
```bash
git clone https://github.com/yourusername/goalzone-configurator.git
cd goalzone-configurator
pip install -r requirements.txt  # Includes opencv-python, Pillow, and tkinter
