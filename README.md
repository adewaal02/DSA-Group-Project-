# DSA Group Project 

<img src="https://github.com/user-attachments/assets/6945dcf3-711f-4911-8a39-e2a0395cbb0b" width="600" height="300">

<details>
  <summary> Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
        <li><a href="#built-with">Built With</a></li>
     <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

## Download Source Code
You can download the project files here: https://github.com/adewaal02/DSA-Group-Project-/blob/ecdb38e5dce816b3a424bfa43019152406136be9/PhonebookProject_Final.zip
> [IMPORTANT!] Final version of the program. Please use this to review.
NB! Change file path in to local machine directory path, under Source package --> model --> Phonebook.java

E.g. "C:\\Users\\Campb\\OneDrive\\Documents\\NetBeansProjects\\PhonebookProject\\contacts.txt" 

## About The Project 

This project implements a basic mobile phonebook application for a Namibian telecommunications company, focusing on efficient phonebook operations using simple linear data structures like arrays and linked lists. The application is designed to handle key operations such as:

* Inserting a contact
* Searching for a contact
* Displaying all contacts
* Deleting a contact
* Updating a contact
* (Optional) Sorting contacts for faster search
  
* Additionally, the project includes an analysis of the search algorithm's efficiency. While the application leverages basic data structures, there is room to explore more advanced techniques such as hash tables and tries.


Modules and Functions
The application is divided into the following modules, each performing specific functions:


Contact Management Module:

Insert Contact: Adds a new contact to the phonebook.
Search Contact: Searches for a contact by name.
Display All Contacts: Displays all contacts stored in the phonebook.
Delete Contact: Deletes a contact by name.
Update Contact: Updates a contact’s phone number.
Sort Contacts: Sorts the contacts alphabetically by name.
File Handling Module:

Save Contacts to File: Saves all contacts to a file in CSV format.
Load Contacts from File: Loads contacts from a file and inserts them into the phonebook.
Efficiency Module:

Analyze Search Efficiency: Measures and outputs the time taken to search for a contact.
-Isaiah Mjumira



## Built With:

<img src="https://github.com/user-attachments/assets/96af4364-76cb-4774-a345-15780ba17724" width="400" height="150">


* Apache NetBeans


## Usage

The usage of this mobile phonebook application is to efficiently manage and manipulate contact information. Users of the application can perform essential phonebook operations such as:

1. **Insert Contact**: Add new contacts to the phonebook, storing details such as names and phone numbers.
2. **Search Contact**: Quickly search for a specific contact by name or phone number.
3. **Display All Contacts**: View all contacts stored in the phonebook.
4. **Delete Contact**: Remove a contact from the phonebook.
5. **Update Contact**: Modify the details of an existing contact (e.g., updating phone numbers or names).
6. **Sort Contacts** (optional): Organize contacts alphabetically or based on other criteria for easier navigation.
7. **Analyze Search Algorithm Efficiency**: Measure and analyze the performance of the search function to understand its time complexity and optimize for better results.

This application is primarily designed for users who need a straightforward, efficient solution to manage contact information with basic functionalities, leveraging simple data structures for ease of use and implementation. It could be useful in environments where advanced database systems aren't required, such as in basic mobile systems or small-scale telecom operations.

## Modules & Funtions

### Modules
1. Contact Management
   - Handles the creation, search, deletion, and updating of contacts.
   
2. Search Optimization
   - Focuses on analyzing the efficiency of search operations.
   
3. Display and Organization
   - Manages displaying and sorting contacts.
   
4. Data Persistence
   - Deals with saving and loading contacts to/from a file.

### Functions

1. Insert Contacts: 
- Function checks if the contact already exists by comparing names (ignoring case).
  - If the contact doesn't exist, it creates a new `Contact` object and adds it to
the list.
  - Feedback is provided via a success or error message.

2. Search Contacts:
- Function: Searches for a contact by name and returns their phone number.
  - The function loops through the phonebook, checking for a match by name.
  - If found, it displays the contact’s details; otherwise, it outputs "Contact not
found."

3. Delete Contacts: 
- Function: Deletes a contact from the phonebook by name.
  - The function uses an iterator to safely remove the contact while looping
through the list.
  - It provides feedback if the contact is deleted or not found.
  
4. Update Contacts:
- Function: Updates an existing contact's phone number.
  - Searches for the contact by name, and if found, updates the phone number.
  - Provides feedback on whether the update was successful, or the contact
wasn't found.

5. Analyza Search Efficiency
- Function: Analyses how efficient the search operation is by measuring the
time taken.
  - Measures the time taken for the search operation by using system
timestamps.
  - Outputs the search time in milliseconds.
  
6. Display All Contacts: 
- Function: Displays all contacts stored in the phonebook.
  - Checks if the phonebook is empty. If it is, it displays an error message.
  - Otherwise, it prints each contact’s name and phone number.
  
7. Sort Contacts:
- Function: Sorts the contacts alphabetically by name.
  - This function uses the `Comparator` to sort the contacts list alphabetically
by name.
  - A success message is displayed once the sorting is complete.

8. Save Contacts to File: 
- Function: Saves all contacts to a file for persistence.
  - Saves each contact’s name and phone number to a file in CSV format.
  - Handles potential IO exceptions and provides error messages if needed
 
## Pseudocodes and Flowcharts

* [Pseudocode.pdf](https://github.com/user-attachments/files/17369219/002A.Pseudocode.pdf)

* [View File Containing Flowcharts](https://github.com/adewaal02/DSA-Group-Project-/blob/main/Flowcharts%&%Pseudocodes/)

## Contributing

### Contibutor Insights 

<a href="https://github.com/adewaal02/DSA-Group-Project-/graphs/contributors"> </a>
