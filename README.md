#AccioJob Placement Readiness-June First Major Project
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


login page-

![login](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/86accc1f-5d8f-40d8-9515-c974b03d99bc)


Main page (includes- Customers, Flights, Tickets, Admin menues)-

![main](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/5d0125a0-6b79-48e6-9364-4829a9ab48de)


Add Customer and its database update-

![AddCust1](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/9f8f6352-c35e-46c5-ae7d-3f32108c9fb4)
![cust](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/4d77f55a-3fbc-4f9d-8aa3-800eb6a7b368)


Search Customer-

![searchCust](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/fddb1040-6efd-4606-b4fe-edc3bcb38bfc)


Add flight and its database update-

![AddFlight](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/5c6dc9f2-71cf-4321-9f2a-f3c0acc4fa0a)
![flt](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/ddb66671-97e6-4fc9-beca-cbc50f34344a)


Book Flight and its databse update-

![bookticket](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/f67fe2c2-09d2-4aa6-ba6f-9443a13cf312)
![tkt](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/3ba2fa1c-33e2-4170-8bca-d40b776fa682)


View Ticket-

![viewtkt](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/d0a375a8-0526-4acf-918f-29742bce7dba)


Add Admin and its database update-

![addadmin](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/9337d59e-b783-4ad5-8290-f5767b6a42a8)
![admin](https://github.com/ayanahmad01/Airline_Reservation_System/assets/136154821/577e6986-f254-43a4-9eac-860ec4eea5ed)

