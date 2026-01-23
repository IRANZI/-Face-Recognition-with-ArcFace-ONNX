# Face Recognition with ArcFace ONNX and 5-Point Alignment

A modular, CPU-only face recognition system using ArcFace ONNX model with 5-point facial landmark alignment. Features clean code with descriptive naming, suitable for education and practical use on laptops/desktops.

## Setup

1. Install dependencies: `pip install opencv-python numpy onnxruntime scipy tqdm mediapipe`
2. Initialize project: `python init_project.py`

## Usage

- Enroll: `python -m src.enroll`
- Recognize: `python -m src.recognize`
- Test modules: `python -m src.camera`, `python -m src.detect`, etc.

## License

Educational and non-commercial use encouraged.
