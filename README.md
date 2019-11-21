# IntroToProg-Python-Mod07

Introduction
This assignment demonstrates the ability for one to use functions to read and manipulate files and error handling. As part of the error handling process, this assignment demonstrates how to pickle and un-pickle data. In this script the user is asked for an ID and a name. These two items are stored in a list and then manipulated. A user can create a new file or load an existing one.

Operation and Error Handling
The images on the left show the GUI of the script. The user is asked for an ID and a name. The first figure is reading from an already existing file. The second figure is demonstrating the error handling when there is no current file available. 

The Script and Functions
The while loop below is where the main program is located. There are a few functions that are ran, each for a specific purpose. The while loop contains the welcome screen where the user is asked for data, the menu giving the user a choice, picking functions (stu_pickles) and unpicking functions (tommy_pickles). When a user is asked to enter a choice, that answer is used by the if loop to determine if it is going to save to a file or read from existing data.

Saving and Reading Data
The user will be prompted to save or read to a file. This function will pass a file name and the list of data. It will use the file name to name the file and write the data. The figure on the right will read the data using a file name that the user is asked for. If there are errors they will be caught by the exceptions.

Summary
In summary, we created a script that will open and manipulate files chosen by the user. This assignment demonstrates the ability and the usefulness of pickling and unpickling. Also, this assignment demonstrates how useful and essential error handling is.
