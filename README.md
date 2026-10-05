 Bus Route Management System

 Title

Bus Route Management System Using Singly Linked List in C++

 Problem Statement

To develop a Bus Route Management System that stores and manages bus route information such as bus number, source, and destination.

The system allows the user to:

- Add a new bus route
- Display all bus routes
- Search for a bus
- Delete a bus route
- Exit the program

A Singly Linked List is used to store and manage bus records dynamically.

 Objectives

- To manage bus route information efficiently.
- To add new bus routes dynamically.
- To display all available bus routes.
- To search for a particular bus using its bus number.
- To delete a bus route.
- To understand the practical implementation of a Singly Linked List.
- To perform insertion, traversal, searching, and deletion operations.

 Data Structure Used

Singly Linked List

Each node contains:

+-------------------------------+
| Bus No | Source | Destination |
+-------------------------------+
|           Next Pointer        |
+-------------------------------+

The "next" pointer connects one bus record to the next bus record.

⚙️ Operations

Operation| Description
Add Bus| Adds a new bus to the linked list
Display Buses| Displays all stored bus routes
Search Bus| Searches for a bus using its bus number
Delete Bus| Deletes a bus from the linked list
Exit| Terminates the program

 Algorithm

1. Start the program.
2. Define a "Bus" structure containing bus number, source, destination, and next pointer.
3. Initialize "head" as "NULL".
4. Display the main menu.
5. Ask the user to select an operation.
6. Add a new bus node at the end of the linked list.
7. Display all bus records by traversing the linked list.
8. Search for a bus using its bus number.
9. Delete the required bus node.
10. Repeat the menu until the user selects Exit.
11. Stop the program.

📊 Flowchart

              ┌─────────────┐
              │    START    │
              └──────┬──────┘
                     ↓
          ┌──────────────────┐
          │ Create Linked    │
          │     List         │
          └────────┬─────────┘
                   ↓
          ┌──────────────────┐
          │   Display Menu   │
          └────────┬─────────┘
                   ↓
           ┌─────────────────┐
           │  Select Choice  │
           └───────┬─────────┘
             ┌─────┼─────┬────────┬────────┐
             ↓     ↓     ↓        ↓        ↓
           Add   Display Search  Delete   Exit
             │     │     │        │        │
             └─────┴─────┴────────┘        ↓
                       │                 ┌──────┐
                       ↓                 │ STOP │
                Display Menu            └──────┘

 Sample Output

===== BUS ROUTE MANAGEMENT =====
1. Add Bus
2. Display Buses
3. Search Bus
4. Delete Bus
5. Exit

Enter your choice: 1

Enter Bus Number: 101
Enter Source: Pune
Enter Destination: Mumbai
Bus added successfully!

Enter your choice: 2

Bus Routes:
Bus No: 101 | Pune -> Mumbai

Enter your choice: 3

Enter Bus Number to Search: 101
Bus Found!
Route: Pune -> Mumbai

Enter your choice: 4

Enter Bus Number to Delete: 101
Bus deleted successfully!

Enter your choice: 5
Program ended.
