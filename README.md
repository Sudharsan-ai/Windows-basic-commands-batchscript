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
```
mkdir Mylab
```
![alt text](<Screenshot 2025-05-18 173954.png>)

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
COPY CON Myfile.txt
A clock in a office can never get stolen
Too many employees watch it all the time
```
![alt text](<Screenshot 2025-05-18 175101.png>)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
dir Myfile.txt

```
![alt text](<Screenshot 2025-05-18 175129.png>)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
mkdir Backup

copy myfile.txt Backup

```

![alt text](<Screenshot 2025-05-18 175142.png>)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
move "C:\Users\sutha\Desktop\ex08\Windows-basic-commands-batchscript\MyLab" "C:\Users\sutha\Desktop\ex08\Windows-basic-commands-batchscript\Documents"

```
![alt text](<Screenshot 2025-05-18 180549.png>)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

## COMMAND

```
notepad 1.bat
```
@echo off
set name=John
echo Hello, %name%!
pause

```
1.bat

```

## OUTPUT


![alt text](<Screenshot 2025-05-18 180651.png>)


# RESULT:
The commands/batch files are executed successfully.

