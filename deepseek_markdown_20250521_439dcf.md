# License Plate Recognition (Vietnam)

This project presents a method for Vietnamese license plate recognition consisting of 4 main steps:

1. **License plate detection** using YOLO Tiny v3
2. Character segmentation using image processing algorithms
3. Character classification with a custom CNN model
4. License plate format validation (single or double-line plates)

## Installation

### Prerequisites
- Python 3.6+
- Required packages:

```bash
pip install -r requirements.txt