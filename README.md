# rename_files.py
Assignment 1
README for File Renaming Program Introduction
This program helps you rename all files in a folder in a sequential order (1, 2, 3,
etc.). It works by taking the folder path as input and renaming the files in the folder without changing their file extensions.
Features
•	Renames files in a folder sequentially (e.g., 1.jpg, 2.txt, etc.).
•	Ignores subfolders and only renames files.
•	Handles errors like missing folder or permission issues. Requirements
•	Python 3.x
•	os module (included by default in Python) How to Use
1.	Run the Program: Start the program by running the script.
2.	Provide the Folder Path: When prompted, enter the path of the folder containing the files you want to rename. Ensure the folder path is correct.
3.	Renaming Process: The program will:
o	Check if the folder exists.
o	List all the files in the folder and sort them alphabetically.
o	Rename each file sequentially (1, 2, 3, etc.).
o	Print any errors if files cannot be renamed. Error Handling
•	Non-Existing Folder: If the folder doesn't exist, the program will notify you.
•	Not a Folder: If the provided path is not a folder, it will show an error.
•	Empty Folder: If there are no files in the folder, the program will inform you.
•	Permission Issues: If there is a permission error while renaming a file, the program will show a message.
Example
If you have the following files in a folder:
•	image1.png
•	document.txt
•	photo.jpg
The program will rename them to:
•	1.png
•	2.txt
•	3.jpg
Code Explanation
1.	Check if the folder exists: It verifies if the folder path is valid.
2.	List files: It lists only the files (ignores subfolders).
3.	Sort files alphabetically: The files are sorted to maintain order.
4.	Rename files: Each file is renamed in the format 1.extension, 2.extension, etc.
5.	Error handling: The program checks for errors during the renaming process. How to Run
1.	Save the script as assignment1.py.
2.	Open your terminal or command prompt.
3.	Run the script with the following command:
Copy code
python assignment1.py
4.	Enter the folder path when prompted.
