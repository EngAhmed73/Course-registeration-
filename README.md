# Course Registration System – CMPS303 Term Project

## Project Overview

This Java-based Course Registration System simulates a simplified university registration platform. It allows users to manage student enrollment in courses using custom data structures including a hash table of courses, a binary search tree for enrolled students, and a linked queue for waiting lists.

## Technologies Used

- Language: Java
- Concepts: Object-Oriented Programming, Custom Data Structures (Tree, Queue, Hash Table)
- File Handling: Object Serialization for persistent storage

## How to Run

1. **Open the project in your Java IDE** (e.g., Eclipse or IntelliJ).
2. **Locate the `Main` class** (the class containing the `main()` method).
3. **Run the `Main` class** to start the interactive menu-based application.
4. On first run, the program will create a new data file. On subsequent runs, it will automatically load existing data (if present).

## Features

- **Add Course**: Insert a new course into the TreeHashTable.
- **Add Student**: Enroll a student into a course or place them in the waiting list if the course is full.
- **Drop Student**: Remove a student from a course and enroll waiting students if space allows.
- **Raise Capacity**: Increase the course capacity and move students from the waiting list to enrolled.
- **Print Students**: Display enrolled students (in-order traversal of the tree).
- **Student’s Courses**: List all courses a student is enrolled in.
- **Data Persistence**: Automatically saves and loads the TreeHashTable to/from a file.

## Project Structure

- `Student.java` – Contains student ID and name.
- `Course.java` – Represents a course with CRN, name, capacity, enrolled students (Tree), and waiting list (Queue).
- `TreeHashTable.java` – Custom hash table implementation to manage courses and student registrations.
- `Main.java` – Main class that runs the user interface and manages interactions.

## Notes

- The `Tree` and `LinkedQueue` classes are taken from course materials and must not be modified.
- The hash function uses CRN as the key. Collision handling is implemented via open addressing.
- Exception handling is included to manage invalid inputs or operations (e.g., non-existent students or courses).

## Authors

- [Ahmed (me )]
- [Kareem]
- [Wael  ]
- [Amro  ]

> *Names are listed in the comment section at the top of the `Main.java` file as per course guidelines.*

## Submission Details

- Submitted as an exported Java project ZIP.
- Includes screenshots demonstrating program execution.
- Deadline: **Saturday, 03/05/2025 at 11:59 PM**

## License

This project is submitted as part of CMPS303 coursework and is subject to academic honesty policies.

