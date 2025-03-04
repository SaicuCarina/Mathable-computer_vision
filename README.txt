1. the libraries required to run the project including the full version of each library

The code is written in Jupyter Notebook with the following libraries:

OpenCV version: 4.9.0
NumPy version: 1.26.0
OS module is part of Python Standard Library
Python version: 3.10.11 (tags/v3.10.11:7d4cc5a, Apr  5 2023, 00:38:17) [MSC v.1929 64 bit (AMD64)]

2. how to run each task and where to look for the output file.

I numbered each cell in my code. Cells 1 through 9 contain all the functions used in Task 1 and Task 2. 
While working on my project, I ran each cell manually, rather than executing the entire code at once.

Task 1 and Task2:

For these tasks, I use cell 10. It is important to correctly adjust the folder paths in the code. Below are the folders defined at the top of the cell:

training_folder = "antrenare" - Replace "antrenare" with the name of the test folder containing 200 photos (4 games) and 4 .txt files with the moves for each game.
auxiliary_image_path = "imagini_auxiliare/01.jpg" - This path points to an image of the board without any tokens. I did not include this file in my solution ZIP since it was provided as part of the assignment.
template_folder = "cifre" - This folder contains templates of numbers after some modifications. It is used for the second task and is included in the solution ZIP.
output_dir = "fisiere_solutie/464_Saicu_Carina" - This is the directory where the solution files are saved. If the directory does not exist, the code automatically creates it.

After running this cell, the folder fisiere_solutie/464_Saicu_Carina will contain 200 .txt files corresponding to Task 1 and Task 2."

Task 3:

For this task I use cell 11. It is important to correctly adjust the folder paths in the code. Below are the folders defined at the top of the cell:

solution_folder = "fisiere_solutie/464_Saicu_Carina" - This folder contains the solution files generated in Task 1 and Task 2. These files are needed for iteration in this task.
training_folder = "antrenare" - Replace "antrenare" with the name of the test folder containing 200 photos (4 games) and 4 .txt files with the moves for each game.
output_folder = "fisiere_solutie/464_Saicu_Carina" - This is the directory where the solution files are saved. In the same directory as task 1 and task 2.

After running this cell, the folder fisiere_solutie/464_Saicu_Carina will contain 204 txt files for all tasks.

CELL 12:

I added the provided "evaluare_solutie" code to this cell to test my solution. Since I am working in Python Jupyter, this was the most efficient way to verify that the evaluation code works with my solution files.
My code works when the test directory contains 200 photos (50 for each game) and 4 .txt files with the turns.