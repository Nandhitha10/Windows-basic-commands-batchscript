# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="561" height="37" alt="image" src="https://github.com/user-attachments/assets/abf9ab8e-d30a-425a-a8d1-a063e280a538" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="620" height="32" alt="image" src="https://github.com/user-attachments/assets/d5f6775a-89bb-49c2-9ff3-c189d1b018d2" />

## COMMAND AND OUTPUT
Create the file Rose.txt

<img width="672" height="344" alt="image" src="https://github.com/user-attachments/assets/b71b3700-ef9f-4c82-8b57-f9fa6454cf48" />


## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection

<img width="730" height="97" alt="image" src="https://github.com/user-attachments/assets/58f5638c-2f6b-49fd-91c0-e979d6e79929" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="755" height="253" alt="image" src="https://github.com/user-attachments/assets/8e7b7b9d-f6b4-4e85-89fa-6379c7190247" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="755" height="240" alt="image" src="https://github.com/user-attachments/assets/31a6e8f8-122c-436f-8ed2-272ab971677e" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="534" height="1144" alt="image" src="https://github.com/user-attachments/assets/c92cab55-70eb-4e1d-94a7-ba3c4b1f30ac" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="650" height="1127" alt="image" src="https://github.com/user-attachments/assets/9eff3dc8-ed95-4b6c-a394-ed2b19f8b056" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="680" height="186" alt="image" src="https://github.com/user-attachments/assets/ad5bd02c-dfea-444b-b548-a8a944cef655" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="651" height="75" alt="image" src="https://github.com/user-attachments/assets/c78e6659-f190-441c-aba7-0344ea5a30c3" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="696" height="191" alt="image" src="https://github.com/user-attachments/assets/5bb3bc98-37c4-497c-a66e-9e45eef6f142" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="491" height="178" alt="image" src="https://github.com/user-attachments/assets/8671281a-acf3-4747-aa4e-b1bb86d1a096" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="238" height="60" alt="image" src="https://github.com/user-attachments/assets/7ba02b07-12db-4347-8f96-2bece5a1c687" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="291" height="118" alt="image" src="https://github.com/user-attachments/assets/a42f8677-a1bf-4140-b5cd-5f113b4a4d1f" />


# RESULT:
The commands/batch files are executed successfully.

