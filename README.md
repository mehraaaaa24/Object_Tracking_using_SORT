# Object Tracking using SORT (Simple Online and Realtime Tracker)

This project demonstrates how to use the SORT (Simple Online and Realtime Tracker) algorithm using Hungarian algorithm for object tracking in video streams.
Video Link for Demo:- https://youtu.be/Gl2PSfvJgN0

## Installation

### Step 1: Clone the Repository

Clone this repository to your local machine:
```
[git clone https://github.com/mehraaaaa24/Object_Tracking_using_SORT.git
cd Object_Tracking_SORT
```
### Step 2: Create and Activate a Virtual Environment

To avoid dependency conflicts, it is recommended to use a virtual environment:

On Windows:
```
python -m venv venv
venv\Scripts\activate
```
On macOS/Linux:
```
python3 -m venv venv
source venv/bin/activate
```
### Step 3: Install Required Dependencies

Install all necessary Python packages using:
```
pip install -r requirements.txt
```
## Usage
### Step 1: Start Jupyter Notebook

Launch Jupyter Notebook from the terminal:
```
jupyter notebook
```
### Step 2: Open the Notebook

In the Jupyter interface, navigate to and open the file YOLO_pip.ipynb.
### Step 3: Run the Cells

Execute all the cells in the notebook to perform object detection on the input images. The notebook includes instructions and code for running the YOLOv5 model.

## Output

The tracker outputs bounding boxes with assigned object IDs and respective colour in each frame.

Visualized tracking results are displayed frame by frame with unique IDs assigned to objects.

## Project Structure
    tracking_course: Contains the images for tracking and the YOLOv5 model
    Tracking_with_SORT.ipynb: Contains the jupyter notebook to be executed
    out_hungarian.mp4: Output video showcasing the object tracking 
    out_hungarain_good.mp4:Output video showcasing enhanced tracking that considers age of object before disallocating their ID's
    requirements.txt: Contains list of python dependencies for the project

## Acknowledgements

This project leverages the SORT tracking algorithm, Kalman Filters, and the Hungarian Algorithm for efficient and real-time object tracking.
SORT Algorithm:- https://arxiv.org/abs/1602.00763
