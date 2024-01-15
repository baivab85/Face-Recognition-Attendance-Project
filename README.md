# Face-Recognition-Attendance-Project
Open_CV Project
Welcome to the Face Recognition with Attendance Project! This project utilizes face recognition technology to automate the attendance process. It is implemented using Jupyter Notebook and relies on a CSV file (Microsoft Excel compatible) for storing the attendance records.

Requirements
To run this project, you need the following dependencies:

Python 3.x
Jupyter Notebook
OpenCV
NumPy
Pandas
You can install the required packages using the following command:
       pip install jupyter opencv-python numpy pandas
Project Structure
img/: Store the images of individuals for whom you want to track attendance.
attendance.csv: CSV file to store the attendance records.
face_recognition_attendance.ipynb: Jupyter Notebook containing the implementation of face recognition and attendance tracking.

Project Structure
img/: Store the images of individuals for whom you want to track attendance.
attendance.csv: CSV file to store the attendance records.
face_recognition_attendance.ipynb: Jupyter Notebook containing the implementation of face recognition and attendance tracking.

Usage
Clone or download the project repository.
Place the images of individuals in the img/ folder.
Run the face_recognition_attendance.ipynb notebook in Jupyter.
Follow the instructions in the notebook to perform face recognition and record attendance.

Instructions
Add Images: Place the images of individuals in the img/ folder. Ensure the images are clear and recognizable.
Run the Notebook: Execute the cells in the face_recognition_attendance.ipynb notebook one by one.
Face Recognition: The notebook uses OpenCV for face recognition. It will identify faces in the images and compare them with the stored images in the img/ folder.
Attendance Recording: The attendance of recognized individuals will be recorded in the attendance.csv file.
Review Attendance: You can review attendance records in the CSV file or use the provided analysis tools.

Notes
Ensure that the images in the img/ folder are of good quality and contain only the faces of individuals.
The project uses a simple face recognition approach; it may require further tuning for larger datasets or more complex scenarios.
License
This project is licensed under the MIT License.

Feel free to customize and adapt the project according to your needs. If you encounter any issues or have suggestions for improvement, please create an issue in the repository.


The attendance records will be stored in the attendance.csv file.
