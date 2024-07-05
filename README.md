# Social Distance Detection Project

This project implements a social distance detector using Python libraries such as OpenCV, NumPy, and SciPy. It analyzes video data to detect instances where social distancing is not being maintained.

## Prerequisites

Before running the project, ensure that Python 3 is installed on your system. You can download Python 3 from the official website: https://www.python.org/downloads/.

## Getting Started

Follow these steps to set up and run the social distance detection project:

### 1. Clone the Repository

First, clone the repository to your local machine or download the source code:

git clone [repository-link]
cd [repository-folder]

Replace [repository-link] and [repository-folder] with the actual URL of the repository and the name of the folder, respectively.

### 2. Set Up the Environment

Create a Python virtual environment and activate it:

python3 -m venv venv  # Create a virtual environment named venv
source venv/bin/activate  # Activate the virtual environment

### 3. Install Dependencies

Install the required Python libraries specified in the requirements.txt file:

pip install -r requirements.txt

### 4. Run the Detector

Execute the social distance detector with the following command:

time python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1

This command analyzes the pedestrians.mp4 video file and outputs the results to output.avi. The --display 1 option enables the display of the output video in a window.

## Credits

This project is based on the foundational work by [Abdullah Shoumik](https://github.com/abd-shoumik). The current implementation has been adapted and modified for additional functionalities by referencing his original work.
