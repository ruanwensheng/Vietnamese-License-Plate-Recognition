# Vietnamese-License-Plate-Recognition

An end-to-end solution for detecting and recognizing Vietnamese license plates using computer vision and deep learning techniques.

## Methodology

The system implements a 4-stage pipeline:

1. **License Plate Detection**  
   Utilizes YOLO Tiny v3 for robust plate localization

2. **Character Segmentation**  
   Employs image processing algorithms to isolate individual characters

3. **Character Classification**  
   Custom CNN model for accurate character recognition

4. **Format Validation**  
   Handles both single-line and double-line plate formats

## Installation

### Requirements
- Python 3.6 or later
- OpenCV
- TensorFlow/Keras
- Other dependencies:

```bash
pip install -r library_vers.txt


## Usage

### Quick Start
To process a single image:

```bash
python main.py --image_path=/path/to/your/image.jpg

