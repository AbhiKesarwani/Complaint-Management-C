# Complaint-Management-C
This project is a Complaint Management System, developed as the end-semester project for the Data Structures and Algorithms course. The system is designed to handle complaints efficiently using various data structures such as stacks, queues, and linked lists. It provides portals for students, problem solvers, and the Vice Chancellor to manage complaints.  
# Features  

1. Student Portal
   
      File Complaints: Students can file complaints by providing details such as type, description, and priority.

      Track Complaints: Students can track their complaints using a unique complaint ID.  

      View Complaint History: Students can view all the complaints they have filed, along with their current status.  

2. Problem Solver Portal
View Unsolved Complaints: View complaints that have not been resolved.

Solve Complaints: Mark complaints as solved (priority-based handling).  

Reject Complaints: Reject unsolved complaints.  

View Rejected Complaints: Access the list of rejected complaints stored in a linked list.  

View Solved Complaints: View resolved complaints stored in a stack.  

Change Password: Update the portal password.  

3. Vice Chancellor Portal
View Complaints: Access lists of unsolved, solved, and rejected complaints.

Add Comments: Add comments to any complaint for follow-up or further instructions.   

Change Password: Update the portal password.   

Data Structures Used  

Array: To store and manage complaints in memory for easy access.  

Queue: To handle unsolved complaints in a First-In-First-Out (FIFO) manner.  

Stack: To manage solved complaints with a Last-In-First-Out (LIFO) approach.  

Linked List: To store rejected complaints dynamically.  

File I/O: Persistent storage of complaints in a CSV file.  

File Structure  

complaints.csv: Used to store complaints persistently. Contains complaint details such as ID, student ID, type, description, priority, status, and comments.  

 
main.c: The main implementation file containing all the logic and functionality.  

