# Face Recognition Based Attendance Management System

This project is a simple implementation of a Face Recognition based Attendance Management System using Python and tkinter for the GUI. The system allows users to register students (ID and Name), capture images for training, train the model, and then recognize faces in real-time to mark attendance.

## Features

- Registration: Enter student ID and Name.
- Capture Images: Capture multiple images of a student for training.
- Training: Train the face recognition model using captured images.
- Recognition: Recognize faces in real-time from webcam feed and mark attendance.
- Attendance Report: Generates a CSV report with student IDs, names, date, and time of attendance.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- tkinter (comes with Python, no need to install separately)
- numpy (`pip install numpy`)
- pandas (`pip install pandas`)
- Pillow (`pip install Pillow`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/attendance-management-system.git
   cd attendance-management-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```bash
   python attendance_system.py
   ```

2. Follow the GUI instructions to:
   - Enter student ID and Name.
   - Capture student images.
   - Train the model.
   - Start recognizing faces and marking attendance.

3. Press `Quit` to exit the application.


## Contributors

- Mohammed Saqlain Patel 
- Mohammed Shoaib 

## License

This project is licensed and copyrights reserved - see the [LICENSE](LICENSE) file for details.
