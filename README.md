# Collection Manipulator – Student Data Organizer

A simple Python console-based project for managing student information using different **Python collection data types**.

This project was created as a practice project to understand how lists, dictionaries, tuples, and sets can be used together in a practical application.

## About the Project

The **Student Data Organizer** allows users to add, view, update, delete, and search student information through a menu-driven program.

Each student's information is stored in a dictionary, while all student records are maintained in a list.

The project demonstrates how different collection types can be used for different purposes:

* **List** – stores multiple student records
* **Dictionary** – stores information about each student
* **Tuple** – stores Student ID and Date of Birth
* **Set** – stores unique subjects

## Features

* Add a new student
* Display all students
* Update student information
* Keep existing values when no new value is entered
* Delete a student using Student ID
* Display subjects for a specific student
* Remove duplicate subjects automatically using a set
* Search students using Student ID
* Exit the program through the menu

## Data Structures Used

A student is stored using a dictionary:

```python
student = {
    "id": stud_id,
    "name": name,
    "age": age,
    "grade": grade,
    "dob": dob,
    "subjects": subjects
}
```

All student records are stored in a list:

```python
students = []
```

### Collection Types

| Collection | Used For                           |
| ---------- | ---------------------------------- |
| List       | Storing multiple student records   |
| Dictionary | Storing individual student details |
| Tuple      | Student ID and Date of Birth       |
| Set        | Storing unique subjects            |

## Example

When adding a student, the program accepts information such as:

```text
Student ID : 101
Name : Rahul
Age : 20
Grade : A
Date of Birth : 2006-05-15
Subjects : Python, Java, Database
```

The subjects are converted into a set, so duplicate subjects are automatically removed.

## Menu

```text
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Student Subjects
6. Exit
```

## Concepts Practiced

This project helped me practice:

* Variables
* Input and output
* Type casting
* Conditional statements
* `while` loops
* `for` loops
* Lists
* Dictionaries
* Tuples
* Sets
* String methods
* `break` and `continue`
* Updating dictionary values
* Deleting list elements using `del`
* Searching through collections
* Menu-driven programming

## Update Feature

The update section allows the user to change:

* Name
* Age
* Grade
* Subjects

Student ID and Date of Birth remain unchanged.

If the user presses **Enter** without entering a new value, the existing value is retained.

## Project Explanation

I have also created an explanation video covering the project structure, collection data types, and the main features of the program.

🎥 **Explanation Video:** [Watch the Project Explanation](YOUR_VIDEO_LINK)

## Repository

You can clone this project using:

```bash
gh repo clone vaidika-ghoghari/project_3_collection_manipulator
```

## Project Structure

```text
project_3_collection_manipulator/
│
├── collection_manipulator.py
└── README.md
```

## Future Improvements

Some features I may add in the future:

* Input validation
* Handling invalid numeric input
* Preventing duplicate Student IDs
* Sorting students
* Saving student data to a file
* Loading saved data when the program starts
* A more advanced user interface

## Connect With Me

* **LinkedIn:** [Vaidika Ghoghari](https://www.linkedin.com/in/vaidika-ghoghari-2196a534a)
* **Email:** [ghogharivaidika@gmail.com](mailto:ghogharivaidika@gmail.com)

## Author

**Vaidika Ghoghari**

BCA Student | Python Learner | Aspiring Developer

---

> This project is part of my Python practice and focuses on understanding and applying Python collection data types in a practical program.
