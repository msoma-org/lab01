# Part A - Account Creation


## 0: Creating a GitHub account

Go to [github.com](https://github.com/) and create an account. After you have verified your email, create an empty repository in your new account, and name it **bootcamp**

# Part B - Terminal Commands
  

## 1: Our first command

Write a command that prints out the string “hello, world”. Extra credit: As in Listing 1, do it two different ways, both with and without using quotation marks.

>>> print (Hello, World)
Print ("Hello, World")

## 2: Cleaning up

Clear the contents of the current tab.

The clear() method removes contents of the current tab.
## 3: Listing

What’s the command to list all the files (and directories) on your Desktop directory? 

Ensure you have switched to the Desktop as the current directory using the cd command then use listdir command to list all files and directories.
listdir Desktop 

## 4: Making directories

Make the directory **bootcamp** on your Desktop and, within it, the directory **labs** (i.e., ~/Desktop/bootcamp/labs).

Use mkdir command while ensuring the Desktop is the current directory.
C:/Desktop   mkdir  bootcamp/labs

## 5: Navigating directories

Change to your Desktop, then change to bootcamp directory, and then the lab directory.
Cd /Desktop/bootcamp/labs

## 6: Creating files

Create an empty file called file01 in the lab directory. 
C:/Desktop/bootcamp/labs   touch file01.py

## 7: Deleting directories

What is the command used to remove a directory named **food** and everything inside it. 
os.rmdir(C:/Desktop/food) method in Python is used to delete the food directory
# Part C - Github 

## 8: Download the GitHub desktop application

Download the [GitHub desktop application](https://desktop.github.com/).

## 9: Pushing work to GitHub

Using the GitHub desktop application, push your code to your new repository.
