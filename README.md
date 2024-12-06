# Attendance Management System with Face Recognition

## Overview
The **Attendance Management System** is a Python application that uses face recognition technology to automate student attendance tracking. It incorporates OpenCV for face detection and recognition, and a Tkinter-based graphical interface for ease of use. Key features include capturing images for training, real-time face recognition, and efficient management of attendance records.

---

## Features
- **Face Recognition**: Automatically detects and recognizes students' faces to mark attendance.
- **Image Capture**: Take and save images for training the recognition model.
- **Manual Attendance**: Option to manually enter attendance records.
- **CSV Export**: Export attendance data to a CSV file.
- **Database Integration**: Store and manage attendance data in a MySQL database.

---

## Technologies Used
- **Python**
- **OpenCV**
- **Tkinter**
- **NumPy**
- **Pandas**
- **MySQL**
- **Pillow**

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/attendance-management-system.git
cd attendance-management-system
```

### 2. Install Dependencies
Make sure Python is installed, then install the required packages:
```bash
pip install -r requirements.txt
```

### 3. Set Up MySQL Database
- Create a MySQL database to store attendance records.
- Update the database connection details in the code as necessary.

### 4. Download Haarcascade
Download the Haarcascade XML file for face detection from the [OpenCV GitHub repository](https://github.com/opencv/opencv) and place it in the project directory.

---

## Usage

### 1. Capture Images
- Run `main_Run.py` to launch the GUI.
- Enter the student's enrollment number and name.
- Click **"Take Images"** to capture their face images.

### 2. Train the Model
- After capturing images, click **"Train Images"** to train the face recognition model.

### 3. Automatic Attendance
- Select **"Automatic Attendance"** to start the face recognition process using the webcam.

### 4. Manual Attendance
- Use the **"Manually Fill Attendance"** option to manually mark attendance.

### 5. View Registered Students
- Access the admin panel to view the list of registered students and their details.

---

## Directory Structure
```plaintext
Attendance Management System with Face Recognition/
│
├── TrainingImage/               # Directory for training images
├── TrainingImageLabel/          # Directory for saved trained models
├── StudentDetails/              # Directory for student details CSV
├── Attendance/                  # Directory for attendance records
├── haarcascade_frontalface_default.xml  # Haarcascade for face detection
├── requirements.txt             # Required Python packages
├── main_Run.py                  # Main application file
├── training.py                  # Script for training the recognition model
├── testing.py                   # Script for testing face recognition
├── mini_app.py                  # Simple GUI for capturing images
├── app.py                       # Streamlit app for attendance visualization
└── README.md                    # Project documentation
```

---

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
Special thanks to:
- **OpenCV** for face detection and recognition.
- **Tkinter** for creating the GUI.
- **NumPy** and **Pandas** for data manipulation.
- **MySQL** for database management.

---

For any inquiries, feel free to contact **[your email]**.
