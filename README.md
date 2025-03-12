# Fruit File Manager

This Python script is designed to manage a text file, `fruits.txt`, where users can either read the contents of the file or append new fruits to it.

## Requirements

- Python 3.x
- No external libraries are required, only the built-in `os` module.

## Functionality

The program allows the user to interact with a file, `fruits.txt`, through the following options:

1. **Read File**: View the contents of `fruits.txt`. If the file is empty, the program will notify the user.
2. **Append File**: Add a new fruit to the end of the file. The user will be prompted to enter a fruit name.
3. **Exit**: Exit the application.

## Usage

1. **File Check**: The program first checks if `fruits.txt` exists in the current directory.
   - If the file exists, the user is presented with options.
   - If the file does not exist, the user will be notified.

2. **Choose an Option**:
   - **Option 1: Read file** - Displays the contents of the `fruits.txt` file. If it's empty, a message is shown.
   - **Option 2: Append file** - Adds a new fruit to the file. The user is asked to input the fruit name.
   - **Option 3: Exit** - Exits the program.

## How to Run

1. Clone or download the repository.
2. Make sure `fruits.txt` is located in the same directory as the script.
3. Open a terminal and run the script:
   ```bash
   python fruit_file_manager.py
   ```
4. Follow the on-screen prompts to choose the file options.

## Example Workflow

1. **Check File**: 
   ```bash
   File exists!
   File options
   1. Read file
   2. Append file
   ```
   
2. **Read File**:
   ```bash
   Choose option from file options: 1

   Printing content...
   Apple
   Banana
   Orange
   ```
   
3. **Append File**:
   ```bash
   Choose option from file options: 2
   Enter fruit to add: Grape
   Fruit added successfully!
   ```

4. **Exit**:
   ```bash
   Choose option from file options: 3
   Exiting application...
   ```

## Notes

- The script checks for the existence of the file before proceeding. If the file doesn't exist, an error message is shown, and the user is asked to choose an option again.
- Each fruit entered will be appended to a new line in the `fruits.txt` file.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

This README should help explain the functionality of your script and guide users on how to use it effectively. Let me know if you'd like any additions or changes!
