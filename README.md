# LOCKEDME.COM

### **LockedMe - Virtual Key for Repositories**

Simple Java Console based program to allows user to input menu options for

Displaying File/Folder structure
    Search for File/Folder recursively.
        Add/Delete File/Folder recursively.


### **View project locally**

To try out the project in your local machine:
clone this repository using git clone
Open the folder from Eclipse/IntelliJ
Open LockedMeMain.java and Run


### **Component Hierarchy**

     File            |           Description
     ----------------|----------------------------------------------------------------------------
  LockedMeMain.java  |  This component contains the Main method. It's the entry point of the program
---------------------| -------------------------------------------------------------------------------
MenuOptions.java	 |  This component contains methods for displaying menu options.
 --------------------| --------------------------------------------------------------
HandleOptions.java	 |  This component contains methods for handling different options from user input and calls respective methods from FileOperations.
 --------------------| ----------------------------------------------------------------------------------------------------------------------------------
FileOperations.java  |  This component defines all the operations required for displaying, searching, deleting and adding files/folder. 
---------------------| -----------------------------------------------------------------------------------------------------------------


To track below deliverables -

#### Specification document - Product's capabilities, appearance, and user interactions

##### Data Structures where sorting and searching techniques are used,file handling ,exceptional handling.

######  Generic features and operations available: 

  1)  Retrieving the file names in an ascending order_

  2)  Business-level operations:_

       Option to add a user specified file to the application

        Option to delete a user specified file from the application

        Option to search a user specified file from the application

        Navigation option to close the current execution context and return to the main context

  3)  Option to close the application_[Phase 1 project output.pdf](https://github.com/Tanmay8399/LockedMe.com/files/8111204/Phase.1.project.output.pdf)_

######  Code designed to display the welcome screen. It displays:

Application name and the developer details

The details of the user interface such as options displaying the user interaction information

Features to accept the user input to select one of the options listed

The first option returns the current file names in ascending order. The root directory can be either empty or contain few files or folders in it.

The second option returns the details of the user interface such as options displaying the following:

Add a file to the existing directory list

Delete a user specified file from the existing directory list

Search a user specified file from the main directory

Option to navigate back to the main context

There is a third option to close the application.

Implemented the concepts such as exceptions, collections, and sorting techniques for source code optimization and increased performance
