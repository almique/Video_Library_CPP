# Video_Library_CPP
Authors:
- Anuranjan Dubey 
- Pranjal Das 
- Abhishek Kumar Saxena
- Krishna Ballav Narayan Singh 

# Data structures and concepts used:-
1. Array
2. File handling
3. Linked list
4. Binary search tree
5. OOPS(classes and objects)

# About the project :-

It's a video library management system. It has the following options
1) Album issue - Issues a customer album of his/her choice.
2) Album deposit- Submits the album isuued to the respective customer.
3)Administrator menu -
           i)  Create customer record 
          ii)  Display all customer record
          iii) Display specific customer record
          iv) Modify customer record
           v)  Delete customer record
           vi) Create new album
          vii) Display all albums
         viii) Display specific album
          ix) Modify album
           x) Delete album
4)  Operations on Sorting of album- Sorts the index no.'s of albums using BST
5) Exit - To exit

# Functions used :-
1) main() - Show the name of project and asks for password . Validates the password and show the functions mentioned above for the user to access.
2) write_Video_Index()-  This function is used to add albums. 
3) display_spb(char n[])- This function show details of album whose index is entered by the user.
4) modify_Video_Index() - This function allows the user to modify the details of the desired album.
5)delete_Video_Index() - This allows the user to delete particular album using it's index no. 
6) display_allb() - This function is used to display all the albums.
7) Video_Index_issue() - This function is used to issue a particular album to a particular album.
8) Video_Index_deposit() - This function is used to deposit a album by customer and it also calculates fine upon the no. days exceeded .
9) write_customer() -    This function is used to add customer's record. 
10) display_sps(char n[])- This function show details of customer whose customer no. is entered by the user.
11) modify_customer() -This function allows the user to modify the details of the respective customer.
12) delete_customer() -This allows the user to delete particular customer's details using it's index no.
13)display_alls() - - This function is used to display all the customer record.
14) BSToprtr() - This function is used to sort the index no.'s of albums.
15) admin_menu() - Displays all the menu options as mentioned under Administrator menu. 
16) intro() - Gives the intro of the project .
