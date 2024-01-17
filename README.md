# Multi Object Tracking using OpenCV

## Overview

This project demonstrates how to perform multiple object tracking in a video using OpenCV. The code is designed to be easy to understand and adaptable for different tracking scenarios. Users can draw bounding boxes around objects of interest, and the code will track those objects throughout the video.

## Author

- **Author:** Manish Kumar

## Getting Started

### Prerequisites

- [Python](https://www.python.org/) installed (version 3.x recommended)
- [OpenCV](https://opencv.org/) library installed (`pip install opencv-python`)
- [Random](https://docs.python.org/3/library/random.html) module (usually included in Python standard library)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/selfmanish01/multi-object-tracking-opencv.git
   ```

2. Change into the project directory:

   ```bash
   cd multi-object-tracking-opencv
   ```

3. Run the main script:

   ```bash
   python main.py
   ```

## Usage

1. Ensure your video file (`myvideo.mp4` in this example) is in the same directory as the code.
2. Run the script and follow the on-screen instructions to draw bounding boxes around objects of interest.
3. Press 'q' to start object tracking.
4. The output video will be saved as `myvideo_object_tracking.mp4` in the same directory.

## Configuration

- Edit `desired_tracker` variable in the code to choose the desired tracking algorithm (e.g., 'CSRT', 'KCF', etc.).
- Adjust `file_size` and `output_frames_per_second` variables according to your video file's specifications.

## Tracking Algorithms

The code supports various tracking algorithms provided by OpenCV. You can experiment with different algorithms by changing the `desired_tracker` variable in the code.

- 'BOOSTING'
- 'MIL'
- 'KCF'
- 'TLD'
- 'MEDIANFLOW'
- 'GOTURN'
- 'MOSSE'
- 'CSRT'

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the [OpenCV](https://opencv.org/) community for providing robust computer vision tools.

Feel free to fork, modify, and use this code for your own projects!

Contact me - selfmanish01@gmail.com
