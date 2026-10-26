# Student Grade Management System

An application developed using Java, JavaFX, and Scene Builder to simplify student record management and grade tracking.
The application allows users to register students, assign grades, calculate averages, and view academic performance reports through a user-friendly interface.

## Features

- **Login System:** User authentication.
- **Dashboard:** Easy navigation between application windows.
- **Add Student:** Register new students using their ID and name.
- **Add Grades:** Assign and update grades for registered students.
- **Student Records:** Display student information and grades using TableView.
- **Average Calculation:** Automatically calculate the average of recorded grades.
- **Performance Reports:** Display total students, highest grade, lowest grade, and overall average.
- **File Handling:** Store and retrieve student data using text files.

## Technologies Used

- Java
- JavaFX
- Scene Builder
- FXML
- CSS
- Maven
- File I/O

## Application Structure

The project follows a structured approach using separate classes for application logic, controllers, and student data.

## Component Description

| App.java | Application entry point and scene navigation |
| PrimaryController.java | Login functionality |
| SecondaryController.java | Dashboard navigation |
| NewStudent.java | Student registration |
| AddGradesController.java | Grade management and average calculation |
| Student.java | Student data model |
| ViewStudentsController.java | Displays student records |
| ViewReportController.java | Generates academic performance reports |

## How It Works

1. Users log in to access the system.
2. The dashboard provides navigation to different features.
3. Student information is saved in `students.txt`.
4. Grades are assigned to existing students and updated in the same file.
5. Student records are displayed using JavaFX TableView.
6. The system calculates averages and generates performance reports.

## Running the Project

1. Clone or download the repository.
2. Open the project in Apache NetBeans or another Java IDE with Maven support.
3. Make sure Java and JavaFX dependencies are configured.
4. Run the application using the JavaFX Maven plugin:

```bash
mvn clean javafx:run
```

## Project Type

University Group Project – JavaFX Desktop Application

Developed to demonstrate event-driven programming, multi-window navigation, file handling, and object-oriented programming concepts.
