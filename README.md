1.Problem Statement:

Managing library books manually becomes difficult when the number of books increases. It is necessary to add, display, search, issue, return, and delete book records efficiently. The Library Book Management System uses a Circular Linked List in C++ to manage book records dynamically. It stores the Book ID, Book Name, Author Name, and Book Status and allows users to perform different operations through a menu-driven program.

2.Introduction:

A Library Book Management System is a simple application used to maintain library book records. In this project, a Circular Linked List is used to store book information. Each node contains book details and a pointer to the next node. The last node points back to the first node, forming a circle. The user can add new books, display all books, search for a book, issue a book, return a book, and delete a book. This project helps us understand the practical application of linked lists in data structures.

3.Short Theory:

What is a Circular Linked List?

A Circular Linked List is a type of linked list in which the last node points to the first node instead of pointing to NULL.

Node Structure:

Each node contains the following information: Book ID: Unique identification number of the book. Book Name: Name of the book. Author Name: Name of the author. Book Status: Available or Issued. Next Pointer: Address of the next node.

Why Use a Circular Linked List?

It supports dynamic memory allocation. It allows book records to be added and deleted dynamically. The last node connects back to the first node. The list can be traversed continuously in a circular manner.

4.Algorithm:

1.Start the program.

2.Define a node containing Book ID, Book Name, Author Name, Book Status, and a pointer to the next node.

3.Initialize the circular linked list as empty. Display the main menu.

4.Select an operation from the menu.

5.o add a book, create a new node and insert it into the circular linked list.

6.To display books, traverse the list and display all book details.

7.To search for a book, compare the entered Book ID with each node.

8.To issue a book, change its status to Issued if it is available.

9.To return a book, change its status to Available if it is issued.

10.To delete a book, find the required node and remove it from the list.

11.Repeat the menu until the user selects Exit. Stop the program.

5.Step-by-Step Working:

Step 1: Start the program The program starts with an empty circular linked list.

Step 2: Display the menu The program displays options for adding, displaying, searching, issuing, returning, and deleting books.

Step 3: Add a book The user enters the Book ID, Book Name, and Author Name. The program creates a new node and inserts it into the list.

Step 4: Display books The program traverses the circular linked list and displays all book records.

Step 5: Search for a book The user enters a Book ID. The program searches the list and displays the book details if the book is found.

Step 6: Issue a book If the book is available, its status changes to Issued.

Step 7: Return a book If the book is issued, its status changes to Available.

Step 8: Delete a book The program removes the node containing the specified Book ID.

Step 9: Exit The program stops when the user selects Exit.

6.Sample Input:

Enter your choice: 1

 Enter Book ID: 101
 Enter Book Name: Data Structures
 Enter Author Name: Rajiv Sharma

Enter your choice: 1

 Enter Book ID: 102
 Enter Book Name: C++ Programming
 Enter Author Name: Bjarne Stroustrup

Enter your choice: 2

7.Sample Output:

===== LIBRARY MANAGEMENT SYSTEM =====

Add Book
Display Books
Search Book
Issue Book
Return Book
Delete Book
Exit
Enter your choice: 1

 Enter Book ID: 101 
 Enter Book Name: Data Structures
 Enter Author Name: Rajiv Sharma

Book added successfully!

After adding two books, select Display Books:

===== Library Books =====

Book ID : 101 Book Name : Data Structures Author : Rajiv Sharma Status : Available
Book ID : 102 Book Name : C++ Programming Author : Bjarne Stroustrup Status : Available
Output for Issuing a Book:

Enter your choice: 4

Enter Book ID to issue: 101

Book issued successfully!

Output for Searching a Book:

Enter your choice: 3

Enter Book ID to search: 101

Book Found! Book ID : 101 Book Name : Data Structures Author : Rajiv Sharma Status : Issued

8.Advantages:

1.Dynamic Size: The list can grow or shrink as books are added or deleted.

2.Memory Efficient: Memory is allocated when a new book is added.

3.Easy Insertion: New book records can be added without shifting other records.

4.Circular Traversal: The last node connects back to the first node.

5.Easy Management: Users can add, search, issue, return, and delete books.

9.Disadvantages:

1.Extra Memory: Each node requires additional memory for a pointer.

2.Sequential Searching: Searching generally requires checking nodes one by one.

3.Complex Implementation: Insertion and deletion require careful pointer handling.

4.Infinite Loop Risk: Incorrect traversal conditions can cause an infinite loop.

5.No Direct Access: A book cannot be accessed directly by its position as in an array.

10Applications:

1.School and college library management.

2.Book rental systems.

3.Maintaining book collections.

4.Small library record management.

5.Learning circular linked list operations.

11.Conclusion:

The Library Book Management System is successfully implemented using a Circular Linked List in C++. It allows users to add, display, search, issue, return, and delete book records. This project demonstrates the use of pointers, structures, dynamic memory allocation, and circular linked list operations in a real-life application. It also helps students understand how linked lists can be used to manage data dynamically.
