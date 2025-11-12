## Read a File and Handle Errors 
This program tries to open and read a file named sample.txt, printing its contents line by line.
If the file does not exist, it gracefully displays an error message rather than crashing the application. 
This is accomplished using Python’s try-except structure, which specifically catches FileNotFoundError and other general exceptions, making the program reliable when handling file I/O tasks.

## Write and Append Data to a File
This program begins by taking user input and writing it to a file named output.txt. 
Next, it prompts the user for additional input, which is appended to the same file, preserving existing content. 
Finally, it reads and displays the entire file’s contents line by line. 
The step-by-step process demonstrates safe writing, appending, and reading techniques in Python, ensuring both user inputs are correctly stored and shown as intended.
