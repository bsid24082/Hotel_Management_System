# Hotel_Management_System

HOTEL MANAGEMENT SYSTEM

INTRODUCTION
We chose the hotel industry as our domain. We tried to implement basic Python concepts and build an application that could help hotels manage their day-to-day activities. The application can perform activities like booking a room, letting customers order food, totalling their bill, checking their payment status and recording all these activities.

PURPOSE OF THE PROJECT
The project aims to understand how Python can be used in real-world scenarios, in this case, hotels. The aim was to develop a more user-friendly program that even stores data for the future use of both the customer and the hotel admins. The main purpose of this assignment was to make us understand how simple components like loops, lists, operators, conditional statements, user-defined functions, etc,  can be used to develop programs which make our day-to-day lives easier and these tedious processes efficient. The project also gives us a glimpse into how data can be stored in different ways. 

PROGRAM DESCRIPTION AND STEPWISE EXPLANATION
1) 1) Libraries used:
- datetime: we used the 'datetime' module to take check-in and check-out dates from the user side and also to provide the number of days of their stay.
- random: we used the 'random' library to create a random room number for every hotel room assigned to the customer of the Hotel(Christ_Lodging).
- pandas: we used pandas to work with our dataset. We used pandas 'pd.dataframe' to convert our data(list) to the dataframe and then to a CSV file using (df.to_csv).
- IPython.display: we used the display function from this particular module to display our CSV file to check the entries we made to be saved and accessed in future.
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
   - p :- It is the payment status. If p = 0, payment is not made, and if p = 1, then payment has been made
   - r :- It is a list with the individual food item's price, which is then used to calculate the final price.
 
     
4) Functions Defined

   -> date():-The function is used to check if the user has put a valid date, i.e., whether the date exists. It is called in the booking function, where the number of days is calculated using the datetime library.
     
   -> Booking(): The function takes check-in and check-out dates from the user according to their stay. This function then asks the user about the different types of rooms available at the Lodging Services, and once picked by the user, it takes the user's information like Name, Phone number, Address and etc. Once the user enters these details, we confirm the Booking and give them their Unique Booking Ids and Customer-Id.
   -> Rooms_Info(): This function basically contains all the information about the rooms and the amenities/ facilities provided by Lodging Services. We have defined five different types of rooms and mentioned all the details for the same.
     
  -> Menu_Card(): This function contains the food items offered by Christ Lodging, and by calling this function, it asks for the unique Customer Id and then keeps populating our restaurant bills which in the end get added to the final bill that will be our outstanding amount.
  
   -> Payment_portal(): The function contains the outstanding amount our customer must pay while checking out. The restaurant charges linked to that Customer ID are added to the Room price, and a Grand Total is provided after calling the function. It asks for various payment methods like UPI, Credit/Debit cards or old-fashioned Cash...Once the customer agrees to the bill generated and enters "yes", the payment gets processed, and a confirmation message is printed.

   ->  BK_Records(): 
   ->  addto(): 
   ->  Display():
   ->  Christ_Lodging(): This function is the main function body which calls all the above user-defined functions, and then, by taking the values from the user, executes the program and gives us the interface experience to interact with our code and help us book hotel rooms and also keep track of booking and providing the bills and payment portals.
     

 



















