#AccioJOb Placement Readiness-June First Major Project
## Airline_Reservation_System

#Highlights of Project-
  
  The project includes a UI, also known as GUI (Graphical User Interface), which consists of buttons, text fields, and other graphical elements used to interact with the user.
  
  The GUI will be built using the Java Swing library.
  
  Task division: Front end and back end.
  
  *Front End- 
  
    Mainframe creation
  
    Features in the mainframe: Add customer, search customer, add flights, book flight, generate ticket.
  
    Menu bar and menu items: Hovering over menu items displays options.

    Internal frame: Different from a normal frame, related to the mainframe.

    Virtual desktop screen.
    
    JInternalFrame is used instead of a regular frame to keep menu item screens within the main window.

  *Back End-

    MySQL Workbench is used for creating the Airline_Reservation_System project database.

    admin, customer, flight, and ticket tables were created.

    GUI was connected with the database.

 *Connection of Front End and Back End

   Bridge (driver) was required to connect frontend and backend of the project.

   JDBC driver was used to connect Java with MySQL for the project.

   Customer, Flight, Admin and Ticket IDs where Auto Generated.


#Working of Project-
  table creation for Database-
   
    *Table 1- Admin Table (includes- AdminID, FirstName, LAstName, Username, Password)

    ![table1](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/a50c7c60-944a-43f5-ad93-d80d8d54cccf)

    *Table 2- Customer Table (includes- CustomerId, FirstName, LastName, Passport No, NationalID, Address, Gender, D.O.B)

    ![table2](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/fe35ba17-52c9-42a3-ab7f-e806ac1ce0c9)

    *Table 3- Flight Table (includes- FlightID, FlightName, Arrival, Departure, Duration, Seats, Fare, D.O.F)

    ![table 3](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/fca5b87b-4e5b-49b9-98ce-f3090aad10f0)

    *Table 4- Ticket Table (includes- TicketID, FlightID, CustomerID, Arrival, Departure, FirstName, LastName, Gender, Contact)

    ![table4](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/0801c937-9f82-43d6-989b-9f2963c501f2)























    
