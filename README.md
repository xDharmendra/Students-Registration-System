# Student Registration System

## Overview

The Student Registration System is a GUI application built using Python's Tkinter library, designed to manage student registration data. This system allows for the registration of student details, including personal information, class information, and parent details. It also provides functionalities to upload and display profile pictures, search for existing records, update information, and clear the form.

## Features

- **Automatic Registration Number**: Automatically generates a unique registration number for each new student.
- **Student Details**: Input and save details such as name, date of birth, class, gender, religion, skills, and parent information.
- **Profile Picture Upload**: Upload and display a profile picture associated with the student's record.
- **Search Functionality**: Search for a student by their registration number and display their details.
- **Update Existing Records**: Update details for an existing student record.
- **Clear Form**: Clear all input fields and reset the form for new entries.
- **Save Data**: Save student details and profile pictures to an Excel file and directory respectively.

## Technologies Used

- **Python**: Programming language used to develop the application.
- **Tkinter**: Python library used for building the graphical user interface (GUI).
- **Pillow**: Python Imaging Library (PIL) used for image processing.
- **Openpyxl**: Library used for reading and writing Excel files.
- **Pathlib**: Library used for handling file paths.

## Installation

1. **Clone the Repository**:
   git clone [repository-url](https://github.com/xDharmendra/Students-Registration-System.git)
   
3. **Install Dependencies**:Ensure you have Python installed. You can install the required packages using pip:

      ```bash
         pip install -r requirements.txt

## Run the Application 
         python Students-Registration-System.py

## Usage

- **Registration**: Enter the student's details, including personal information, class, skills, and parent details.
- **Upload Image**: Use the "Upload" button to select and upload a student's profile picture.
- **Save Data**: Click "Save" to store the student's information in the Excel file.
- **Search**: Use the "Search" functionality to retrieve and view existing student records.
- **Update**: Modify student details and save the changes.
- **Reset**: Clear the form fields to enter new student information.
- **Exit**: Close the application using the "Exit" button.

## File Structure

- `student_registration.py`: Main Python script containing the Tkinter GUI and application logic.
- `Student_data.xlsx`: Excel file that stores the registered student data.
- `Images/`: Directory containing default and uploaded student images.
- `requirements.txt`: List of required Python packages.

## Dependencies

- **Python 3.x**
- **Tkinter**
- **Pillow** (for image handling)
- **openpyxl** (for Excel file handling)

## Contributing

If you want to contribute to this project, feel free to fork the repository and submit a pull request.

## Acknowledgments

- **Tkinter** for providing the GUI framework.
- **Pillow** for image processing.
- **openpyxl** for Excel file management.
