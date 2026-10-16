# Enhancement Two: Algorithms and Data Structures

## ABCU Advising Assistance Program

This project is a C++ course advising program I originally developed for CS 300 Data Structures and Algorithms. For my CS 499 capstone, I returned to the program to improve how it handles prerequisite information and help users determine an appropriate order for taking courses.

### Improvements Made

- Added validation to check whether prerequisites exist in the course catalog.
- Added depth-first search (DFS) to detect circular prerequisite relationships.
- Added a recommended course order using topological ordering.
- Continued using a hash table for efficient course lookups.
- Added handling for invalid course data.

### Testing

I tested the program using a missing prerequisite, a circular prerequisite relationship, and a valid course list to verify the recommended course order. I also retested the original course search and course-list features to confirm they still worked after the enhancements.

The enhancement narrative includes five screenshots documenting these tests.

### Project Files

- **Original CS 300 Project:** The original C++ program and course-data CSV before enhancement.
- **Enhanced CS 499 Project:** The updated C++ program, Visual Studio project files, and test CSV files.
- **Enhancement Two Narrative:** A Word document explaining the algorithms, testing, course outcomes, and reflection.
