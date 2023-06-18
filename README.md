# Hotel_Management_System

HOTEL MANAGEMENT SYSTEM

INTRODUCTION
We chose the hotel industry as our domain. We tried to implement basic Python concepts and build an application which could help the hotels in managing their day to day activities. The application can perform activities like booking a room, letting customers order food, totalling their bill, checking their payment status and recording all these activities.

PURPOSE OF THE PROJECT
The purpose of the project is to understand how python can be used in real-world scenarios, in this case, hotels. The aim was to develop a program which is more user friendly and even stores data for the future use of both the customer and the hotel admins. The main purpose of this assignment was to make us understand how simple components like loops, lists, operators, conditional statements, user defined functions, etc can be used to develop programs which makes our day to day lives easier and these tedious process efficient. The project also gives us a glimpse into how data is can be storted in different way. 

PROGRAM DESCRIPTION AND STEPWISE EXPLANATION
1) 1) Libraries used:
- datetime: we used the 'datetime' module to take check-in and check-out dates from the user side and also to provide the number of days of their stay.
- random: we used 'random' library to create a random room number for every hotel room assigned to the customer of the Hotel(Christ_Lodging).
- pandas: we used pandas to work with our dataset. We used pandas 'pd.dataframe' to convert our data(list) to the dataframe and then to a CSV file using (df.to_csv).
- IPython.display: we used the display function from this particular module in order to display our CSV file to check the entries that we made to be saved and accessed in future.
2) List Declaration
   We defined the following lists.
   - name :- It is a list which has the name of all the customers
   - phone_no :- It is a list which has the phone number of all the customers
   - address :- It has the permanent address of where the customers belong
   - check_in :- It is a list which has the check-in dates of the customers
   - check_out :- It is a list which consists of information about when the customers are checking out
   - room :- It is a list which has the type of room each customer stayed in
   - price :- The list has data about the price of the room they stayed in
   - room_no :- It is a list which has the information of the room number each customer stayed in
   - cust_id :- It is a unique customer ID which is assigned to each customer
   - Num_days :- The number of days each customer stayed, which is calculated using check-in and check-out date
   - rc :- It is the amount of money each customer spent at the restaurant during their stay
   - p :- It is the payment status. If p = 0, payment is not made and if p = 1, then payment has been made
   - r :- It is a list which has the individual food item's price which is then used to calculate the final price  
4) Functions Defined
   - date():- The function is used to check if the user has put a valid date or not, i.e., if the date exists or not. It is called in the booking function where the number of days are calculated using datetime library. 
   - Booking() 
   - Rooms_Info()
   - Menu_Card()
   - Payment_portal()
   - BK_Records()
   - addto()
   - Display()
   - Christ_Lodging()
     
PROGRAM DESCRIPTION
We used lists to store the data and by using pandas converted the data into csv file, which we can access in future for reference or billing.
 



















