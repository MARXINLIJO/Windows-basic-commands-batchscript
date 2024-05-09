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
![alt text](<Screenshot 2024-05-09 214334.png>)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![alt text](<Screenshot 2024-05-09 214347.png>)
![alt text](<Screenshot 2024-05-09 214359.png>)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![alt text](<Screenshot 2024-05-09 214413.png>)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
 mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup

![alt text](<Screenshot 2024-05-09 214419.png>)
![alt text](<Screenshot 2024-05-09 214429.png>)
## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![alt text](<Screenshot 2024-05-09 214438.png>)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!


## OUTPUT

![alt text](<Screenshot 2024-05-09 214447.png>)
# RESULT:
The commands/batch files are executed successfully.

