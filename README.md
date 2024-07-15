# Real-Time Employee Attendance and Work Hour Tracking System

## Overview
This project is a Real-Time Employee Attendance and Work Hour Tracking System that leverages Python, Tkinter, OpenCV, dlib, and Firebase for efficient and accurate tracking of employee attendance and work hours. The system uses face detection technology to identify employees and log their work hours.

## Features
- **Real-time face detection**: Uses OpenCV and dlib for accurate face detection.
- **User interface**: Built with Tkinter for easy interaction.
- **Database integration**: Uses Firebase to store attendance records and work hours.
- **Voice interaction**: Includes voice recognition and interaction using `pyttsx3` and `speech_recognition` libraries.

## Installation

### Prerequisites
- Python 3.x
- Tkinter
- OpenCV
- dlib
- Firebase
- `pyttsx3`
- `speech_recognition`

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/sayanroy1230/Real_time_Employee_Attendance_and_Work_Hour_Tracking-System.git
    cd Real_time_Employee_Attendance_and_Work_Hour_Tracking-System
    ```

2. Install the required libraries:
    ```bash
    pip install opencv-python dlib firebase pyttsx3 speech_recognition
    ```

3. Set up Firebase:
    - Create a Firebase project.
    - Add your Firebase credentials and database URL to the project.

## Usage
1. Run the main application:
    ```bash
    python main.py
    ```

2. Use the Tkinter interface to register employees, log attendance, and track work hours.

3. The system will use face detection to identify employees and log their work hours in real-time.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, please contact sayanroy1230.
