# Lane and Object Detection

## Overview

This project implements lane and object detection using computer vision techniques. The system processes video input to identify lane markings and detect objects such as vehicles and pedestrians.

## Repository Contents

- `main.py`: The main script that processes video input for lane and object detection.
- `Finalutils.py`: Contains utility functions used in the detection process.
- `challenge_video.mp4` and `project_video.mp4`: Sample videos for testing the detection algorithms.
- `requirements.txt`: List of required dependencies for the project.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/GlenFonceca/Lane-and-Object-Detection.git
   cd Lane-and-Object-Detection
   ```

2. **Create and activate a virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the lane and object detection:

```bash
python3 main.py
```

By default, the video input path is set in the code. If you want to use a different video, update the path in `FinalLane.py`. For real-time detection using a webcam, set the video path to `0` in the code.

## Results

Here are some example results of the lane and object detection system:

### Lane Detection Output
![Lane Detection](results/lane_detection.png)

### Object Detection Output
![Object Detection](results/object_detection.png)

## Dependencies

The project requires the following Python packages:

- `ultralytics`
- `opencv-python`
- `numpy`

Ensure these packages are installed in your environment.

## Acknowledgments

This project utilizes open-source computer vision libraries and is inspired by various tutorials and research papers in the field of autonomous driving and computer vision.

## License

This project is open-source and available under the MIT License.

