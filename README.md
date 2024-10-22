# MiniDataBase Project

## Overview

MiniDataBase is a simple database management system implemented using a B+ Tree data structure. It allows for insertion, searching, deletion, and display of student records, which are stored in text files. 

Each student record includes:
- Roll Number (unique identifier)
- Name
- Age
- Marks
- The records are stored in individual text files using the student's Roll Number as the file name.

## Features

- **Insert** a student record.
- **Search** for a student record by Roll Number.
- **Display** the B+ Tree structure:
  - Hierarchical display.
  - Sequential display.
- **Delete** a student record by Roll Number.

## Requirements

- C++ Compiler (e.g., g++, Visual Studio)
- B+ Tree library (`B+ Tree.h`)

## How to Run

1. **Clone the repository** (if hosted in a repo):
    ```bash
    git clone https://github.com/your-repo/minidatabase.git
    ```

2. **Compile the code**:
    ```bash
    g++ main.cpp -o minidatabase
    ```

3. **Run the program**:
    ```bash
    ./minidatabase
    ```

4. Follow the interactive prompts to insert, search, display, or delete records.

## Usage

- **Insert a record**:
    1. Select option `1` for insertion.
    2. Enter the Roll Number, Name, Age, and Marks.
    3. The record will be stored in a file in the `DBFiles` directory.

- **Search a record**:
    1. Select option `2` for search.
    2. Provide the Roll Number.
    3. The program will display the corresponding record if found.

- **Print the B+ Tree**:
    1. Select option `3` for display.
    2. Choose between Hierarchical or Sequential display of the B+ Tree.

- **Delete a record**:
    1. Select option `4` for deletion.
    2. Choose a Roll Number from the displayed tree to delete the corresponding record.

- **Exit**: Choose option `5` to quit the program.

## Notes

- The maximum number of child nodes and leaf nodes in the B+ Tree can be customized at the start of the program.
- The program saves each record as a `.txt` file in the `DBFiles/` folder using the Roll Number as the filename.

