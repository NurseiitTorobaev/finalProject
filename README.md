Hello! This is my final project as a freshman.

## PURPOSE

This code is useful for pet's adoption centres. This database allows adding, removing and marking adopted pets! You also can print the list of all pets. Code was written with file handling, so you can save the data for next launches. 

## DESIGN CHOICES

1. Terminal-based interface is simple and accessable for all users.
2. The main menu organizes functionalities into seven options, making it easy for users to navigate and perform desired actions.
3. The option to clear the screen after each action allows terminal to remain clary.

## CODE OVERVIEW

To store data about pet's code use data structures. Each pet has it's own name, age, breed and description, also they can be marked if pet is adopted.

    - Pet: Represents individual pets with attributes such as name, breed, age, description, adoption status, and adoption date.
    - Date: A struct to represent dates, used for adoption dates.
    
Functions:

    - printMenu(): Displays the main menu options.
    - newPet(): Adds new pet giving it a name, breed, age and etc.
    - adoptPet(): Marks pet as adopted and writes adoption date.
    - prinPet(): Print the list of all pets with their profile and index.
    - deletePet(): Deletes a pet from the vector based on the given index.
    - savePetsToFile(): Saves pet data to a specified file. You are required to write the name for the file.
    - loadPetsFromFile(): Loads pet data from a specified file. You are required to write the name of the file to load.

Input/Output:
    - Input is handled through cin for user interactions, while output is displayed using cout.
    - File input/output operations are used to save and load pet data.

Test Files:
    - You can load each test txt files to check how the program works.
