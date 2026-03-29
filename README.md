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

1. Problem Statement
In both domestic and small-scale clinical environments, managing medication safely is a significant challenge. Users often face three primary issues:
Information Fragmentation: Critical safety data like side effects and contraindications (precautions) are often printed in tiny fonts on physical packaging that is easily lost.
Inventory Blindness: Without a digital record, users may not realize a life-saving medication is in "Low Stock" until an emergency occurs.
Human Error: Incorrect dosages or the accidental mixing of medications with restricted substances (like alcohol) can lead to severe health complications.
There is a clear need for a centralized, lightweight digital repository that provides instant access to pharmaceutical safety data and inventory status.
2. Scope of the Project
The scope of this project is to develop a functional Command Line Interface (CLI) prototype that manages a local database of medicines. The project boundaries include:
Data Retrieval (Read): Implementing a high-speed search algorithm to fetch specific medicinal profiles using unique string keys.
Dynamic Updating (Create): Allowing the user to expand the database during a live session by inputting new medicinal entries.
Information Visualization: Formatting technical data (Dosage, Uses, Side Effects) into a readable, structured console output.
Validation Logic: Ensuring the system remains stable by handling "Not Found" queries and normalizing user input (case-insensitivity).
Optimization: Using Python’s Dictionary (Hash Map) structure to ensure the system scales efficiently without performance lag.
3. Target Users
This system is designed for a diverse set of stakeholders who require quick, reliable access to medicine data:
Students & Researchers: Particularly those in fields like Bioengineering or Pharmacology who need a tool to organize drug profiles for projects or study.
Home Caregivers: Individuals managing multiple prescriptions for family members who need to verify dosages and check for "Low Stock" alerts.
Small Clinic Administrators: Medical staff in low-resource settings who require a simple, no-cost digital alternative to manual paper logging.
First Aid Responders: People needing a quick reference for the primary "Uses" of a medicine during non-emergency situations (e.g., distinguishing between an antihistamine and a painkiller).

