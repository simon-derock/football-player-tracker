# Football Player Re-identification

This project is a computer vision system to detect, track, and re-identify football players in a video.

## Setup and Execution

### 1. Environment Setup

It is recommended to use a virtual environment to manage dependencies.

```bash
python3 -m venv myvenv
source myvenv/bin/activate
```

### 2. Install Dependencies

Install the required Python libraries using pip:

```bash
pip install -r requirements.txt
```

### 3. Running the System

To process the example video (`data/input/15sec_input_720p.mp4`), run the following command:

```bash
python3 main.py
```

The processed video will be saved as `output/tracked_output.mp4`.

### 4. Configuration

The `config.yaml` file contains parameters for the system, such as detection thresholds and tracking settings. You can modify this file to adjust the system's behavior.

## Dependencies

The project requires the following major dependencies:

*   **OpenCV**: For video processing and image manipulation.
*   **PyTorch**: For the player detection and re-identification models.
*   **YOLOv5**: Used for player detection.
*   **NumPy**: For numerical operations.
*   **scikit-learn**: For utility functions.

A full list of dependencies is available in `requirements.txt`.