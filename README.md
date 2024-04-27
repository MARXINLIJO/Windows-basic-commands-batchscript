# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/dd05995f-7276-4a30-8e86-d378793ac468)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/68627424-5840-4369-8dcd-d746714709c8)
![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/f2034c85-cbd5-4efc-a5c3-8470c74937fe)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/4ed57e06-17c9-4bd5-8576-a39e09f9e45d)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
 mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/bbad4b2a-fb1b-43ac-9e5c-20fad07e71fd)

![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/ee912e65-6373-4542-ba4d-75a6557c36d3)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/14cfbd6c-3a95-4c12-9ef4-16a9895e0c33)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!


## OUTPUT

![image](https://github.com/MARXINLIJO/Windows-basic-commands-batchscript/assets/145742540/8c1a2035-76da-4530-99b5-6606c1ea4b09)

# RESULT:
The commands/batch files are executed successfully.

