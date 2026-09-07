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

<img width="307" height="45" alt="image" src="https://github.com/user-attachments/assets/947d1ba0-7122-46f2-a389-2009445d59bd" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="312" height="35" alt="image" src="https://github.com/user-attachments/assets/243d1a20-15aa-4e96-beb4-d3b1d0ac8b7d" />

## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="527" height="362" alt="image" src="https://github.com/user-attachments/assets/5958b646-320c-47b9-b42c-3e6508e4a3dd" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="330" height="52" alt="image" src="https://github.com/user-attachments/assets/b770dd52-d001-4e3f-beb5-b162f68afb6c" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="416" height="52" alt="image" src="https://github.com/user-attachments/assets/6f185bcc-77c9-4f67-ab81-c352f3981e75" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="310" height="35" alt="image" src="https://github.com/user-attachments/assets/487fce79-15f0-4db5-8b6e-d77b32dfb80d" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="361" height="65" alt="image" src="https://github.com/user-attachments/assets/9f8fd8a4-e324-42f6-8fa1-7838477dbf01" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="333" height="722" alt="image" src="https://github.com/user-attachments/assets/25810920-4dd2-42c1-9378-eb0ee1eae35b" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="325" height="123" alt="image" src="https://github.com/user-attachments/assets/bdded0da-ece0-46d4-902c-d096ef110a8e" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="225" height="52" alt="image" src="https://github.com/user-attachments/assets/c63850e1-b7a3-432c-b6da-e011bf9b4440" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="366" height="125" alt="image" src="https://github.com/user-attachments/assets/abdcb630-f9c3-4bf2-831f-700b5260ea74" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="162" height="95" alt="image" src="https://github.com/user-attachments/assets/ca43af5d-c7ee-49aa-8f99-be5578b98ddd" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="298" height="62" alt="image" src="https://github.com/user-attachments/assets/dac7114e-60e9-49d8-9e69-8b586db3d735" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="252" height="370" alt="image" src="https://github.com/user-attachments/assets/70644f9a-42ee-4810-857c-83a297509f3d" />


# RESULT:
The commands/batch files are executed successfully.

