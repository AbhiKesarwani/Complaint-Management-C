# Complaint-Management-C
This project is a Complaint Management System, developed as the end-semester project for the Data Structures and Algorithms course. The system is designed to handle complaints efficiently using various data structures such as stacks, queues, and linked lists. It provides portals for students, problem solvers, and the Vice Chancellor to manage complaints.  
# Features  

1. Student Portal
   
   File Complaints: Students can file complaints by providing details such as type, description, and priority.

   Track Complaints: Students can track their complaints using a unique complaint ID.  

   View Complaint History: Students can view all the complaints they have filed, along with their current status.
   
3. Problem Solver Portal
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

# Data Structures Used  

   Array: To store and manage complaints in memory for easy access.  

   Queue: To handle unsolved complaints in a First-In-First-Out (FIFO) manner.  

   Stack: To manage solved complaints with a Last-In-First-Out (LIFO) approach.  

   Linked List: To store rejected complaints dynamically.  

   File I/O: Persistent storage of complaints in a CSV file.  

# File Structure  

   complaints.csv: Used to store complaints persistently. Contains complaint details such as ID, student ID, type, description, priority, status, and comments.  

 
   main.c: The main implementation file containing all the logic and functionality.    
      
# Installation and Usage
Prerequisites  

   C Compiler (e.g., GCC)  

   Basic understanding of C programming and data structures.  

# How the Program Works  

Workflow  

File Complaint: A new complaint is enqueued to the unsolved queue and written to the complaints.csv file.  

Resolve Complaint: High-priority complaints are resolved first and pushed to the solved stack.  

Reject Complaint: Rejected complaints are stored in a linked list for future reference.  

Persist Data: Complaints are stored in the complaints.csv file to ensure data is not lost between program runs.   
![File complaint](https://github.com/user-attachments/assets/894d1763-6d5c-412e-9424-c4d5501d61ad)   
File Complaint  

![Solve complaint](https://github.com/user-attachments/assets/7b9de718-6778-4a4e-84ea-eb9c5e6051fd)  
Solve Complaint  

![Reject Complaint](https://github.com/user-attachments/assets/57731f98-1bfe-462b-9d9d-d8b3a3858206) 
Reject Complaint  

![Password Cahnge](https://github.com/user-attachments/assets/c6195c0f-80f5-4aac-97ef-9880c2dd6aa2)  
Password Change  

![Vice Chancellor View](https://github.com/user-attachments/assets/be112c5e-9c87-4125-b370-881fe1bed467)
Vice Chacellor View  

![Vice Chancellor Comment](https://github.com/user-attachments/assets/bb22d840-6de3-4753-b5ee-f8461782769d)
Vice Chancellor Comment  



# Future Improvements  

Add a graphical user interface (GUI) for better user experience.  

Implement search and filter functionalities.  

Add notification systems for complaint updates.    








