1.  Project Overview
The Medicine Checker System is a simple console-based application written in Python that allows users to manage a local database of medicine information. Users can search for medicine details, add new medicines, update existing records, remove medicines, and view a list of all items.

2.  Prerequisites
To run the Python script, you must have the following installed on your system:

Operating System: Any modern operating system (Windows, macOS, Linux).

Python: Python 3.x is required. The code uses standard input/output and dictionary operations available in all versions of Python 3.

3.  Dependencies
The provided script uses only built-in Python features and does not require any external third-party libraries.

No pip install commands are necessary.

4.  Execution Steps
To run the Medicine Checker System:

Save the Code: Save the provided Python code into a file named, for example, medicine_checker.py.

Open Terminal/Command Prompt: Navigate to the directory where you saved the file.

Run the Script: Execute the file using the Python interpreter:

Bash

python medicine_checker.py Interact: The system will display a main menu. Enter the corresponding number (1–6) for the action you wish to perform and follow the on-screen prompts.

5.  Code Structure & Functionality
The script is structured around a global dictionary (medicines) acting as the database and several functions to manage the data:

medicines (Dictionary): Holds all medicine data.

search_medicine(name): Looks up a medicine by name and prints its details.

add_medicine(): Prompts the user for details and adds a new medicine to the database.

update_medicine(): Allows modification of existing medicine details.

remove_medicine(): Deletes a medicine entry from the database.

show_all_medicines(): Prints a list of all medicines currently in the database.

main(): Contains the main loop for the menu-driven interface.
