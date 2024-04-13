# Bus Passenger Counter using YOLOv8
## By Damilola Esan

## Project Overview
The Bus Passenger Counter is a computer vision project that employs the YOLOv8 object detection algorithm to count the number of passengers inside a bus. By utilizing real-time video feed analysis, the system accurately tracks individuals within the bus and provides a count of the passengers. This project can be valuable for transportation management, safety monitoring, and optimizing passenger services.

## Prerequisites
- Python 3.x
- OpenCV
- Pandas
- Ultralytics
- cvzone

## Installation
* Clone this repository to your local machine.
* Install the required dependencies using the following command:
`pip install -r requirements.txt`

## Usage
Ensure your video file (e.g., VID_20240124085431.mp4) is placed in the project directory.

1. Run the main script to process the video file:
`main.py`
- This script will download the YOLOv8 model file `yolov8s.pt` if not already present from Ultralytics repository and place it in the project directory.

2. The application window titled "Bus Passenger Counter" will display the video feed with passenger count.

## Customization
* Modify the `area1` variable to define the region of interest (ROI) where passenger counting will occur.
* Adjust parameters and thresholds according to your specific use case in the script.

## Contributions
Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

For any questions or inquiries, please visit my **[website](https://www.bit.ly/damiesan)**.