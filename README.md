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

## COMMAND AND OUTPUT
<img width="935" height="89" alt="image" src="https://github.com/user-attachments/assets/d7cdc6fb-486f-4d52-a12a-6fc9a8b9b630" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="951" height="94" alt="image" src="https://github.com/user-attachments/assets/ac36dfa0-a8aa-4767-9d1f-5c9ce5056028" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="942" height="342" alt="image" src="https://github.com/user-attachments/assets/a0583b66-3e3f-4bd9-a387-9f07f85181e9" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="961" height="122" alt="image" src="https://github.com/user-attachments/assets/c6d86756-f0dd-4488-bff3-4f4983b470e8" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="947" height="130" alt="image" src="https://github.com/user-attachments/assets/89e1809d-73ae-42c0-91b4-2de341ce9790" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="949" height="221" alt="image" src="https://github.com/user-attachments/assets/5735daed-af64-4bae-9b5c-2e346ce704a5" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="946" height="787" alt="image" src="https://github.com/user-attachments/assets/1979e444-466f-43ad-8483-bfaa641e4122" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="946" height="787" alt="image" src="https://github.com/user-attachments/assets/7521be60-eae8-4514-aa4e-352953b7e9a7" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="943" height="186" alt="image" src="https://github.com/user-attachments/assets/5659c4c9-0d35-4035-a91a-00c12778432e" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="952" height="93" alt="image" src="https://github.com/user-attachments/assets/fae40500-e236-4faa-aa5e-af228a096eaa" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="954" height="945" alt="image" src="https://github.com/user-attachments/assets/bbae70fe-f20b-4387-9cbf-e976ff059746" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="955" height="193" alt="image" src="https://github.com/user-attachments/assets/03282656-3604-4c65-92ed-cbb2d4e97ebe" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="950" height="119" alt="image" src="https://github.com/user-attachments/assets/6ce64098-64c4-4ab0-adb7-4756ca120a47" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="936" height="414" alt="image" src="https://github.com/user-attachments/assets/2bc0a186-d521-4d8c-a444-7acbd08454f1" />


# RESULT:
The commands/batch files are executed successfully.
