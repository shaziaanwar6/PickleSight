# PickleSight

**Computer Vision-Based Pickleball Player Pose Estimation and Movement Analysis**

PickleSight analyzes player movements in pickleball videos using computer vision and deep learning.

## Features

- Human pose estimation using YOLOv8n-Pose
- Player tracking using ByteTrack
- Joint angle calculation
- Body-distance measurements
- Keypoint filtering and EMA smoothing
- Annotated video generation
- CSV export of keypoints and movement metrics

## Technologies Used

- Python
- YOLOv8n-Pose
- Ultralytics
- ByteTrack
- OpenCV
- NumPy
- Pandas
- FFmpeg
- Google Colab

## How It Works

1. Upload a video.
2. Detect human body keypoints.
3. Track players across video frames.
4. Filter unreliable keypoints and smooth movement.
5. Calculate joint angles and body-distance measurements.
6. Generate an annotated video and export metrics to CSV.

## Project Files

- `PickleSight_clean.ipynb` — Main project notebook.
- `README.md` — Project documentation.

## Limitations

- Estimates 2D body keypoints, not a true 3D skeleton.
- Measures distances in image pixels, not real-world units.
- Does not currently include ball tracking, racket tracking, or shot classification.

## Author

**Shazia Anwar**

Computer Vision | Deep Learning | Python
