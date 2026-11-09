# Project Name: Rolodex Management System

## Project Description
The Dental Supply Inventory Manager is a Java-based console application designed to help manage and track supply inventory in a dental office. The application allows users to add, view, search, update, and delete inventory records. The application uses SQLite for persistent data storage, allowing contact information to be stored when the program ends. 

## Project Tasks
- **Task 1: Set up the development environment**
- Set up Visual Studio Code for Java development
- Add the SQLite JDBC driver to the project
- Create a GitHub repository
- **Task 2: Design the application**
- Identify the purpose and functionality of the application
- Determine how users will interact with the application
- Plan the classes, methods, and relationships between the classes to build the application
- **Task 3: Develop the contact class and implement object-oriented programming concepts**
- Create an abstract Supply superclass to store shared supply information
- Implement DisposableSupply and ReusableSupply subclasses using inheritance
- Create constructors, getters/setters, and methods for managing supply information
- Use abstraction, inheritance, and polymorphism to organize supplies
- Create a InventoryOperations interface
- **Task 4: Develop the user interface**
- Create a console-based menu for the user to interact with the application
- Create options to view, search, add, update, and delete supplies
- Receive and validate user input
- Display supply information
- **Task 5: Connect to a database and implement CRUD functionality**
- Create a SQLite database to store supply information
- Establish a database connection using JDBC
- Create a supplies table
- Use SQL statements and prepared statements to interact with the database
- Use CRUD operations to add, retrieve, search, update, and delete supplies from the database
- Prevent duplicate supply entries
- **Task 6: Test the application**
- Test each menu option and database operation
- Verify supply information is save and retrieved
- Identify and correct errors
- **Task 7: Deploy the application**
- Create project documentation and README file
  
## Project Skills Learned
- Java programming and application development
- Object-oriented programming concepts and principles
- Interitance, abstraction, polymoprhism, and composition
- Creating and using interfaces
- Using constructors, getters/seters, and access specifiers
- Working with a SQLite database
- Writing SQL statements and using CRUD operations
- Writing documentation

## Language Used
- Java: Used to develops the application and implement object-oriented concepts
- SQL: Used to create the database table and perform database operations
- SQLite: Used for persistent data storage
- JDBC: Used to establish a connection between the Java application and  SQLite

## Development Process Used
- Iterative development: This application was developed in stages
- Object-oriented design: classes and interfaces were used to improve code organization and maintenance
- Testing and debugging: Features were tested throughout the development process to identify and correct errors and to create a user-friendly flow during user interaction
  
## Notes
- VS Code can be used to open the project
- SQLite JDBC driver is included in the lib folder
- Run App.java file to start the application
- The application will create a SQLite database file if one isn't created already, but one should be included in this project
- The Supplies table will be created automatically when the application starts
  
## Link to Project
# Project Name: Rolodex Management System

## Project Description
The Rolodex Management System is a Java-based console application designed to help users organize and manage their contacts. The application allows users to add, view, search, update, and delete contact records. Contacts are organized into three categories: Friend, Family, and Business. The application uses SQLite for persistent data storage, allowing contact information to be stored when the program ends. 

## Project Tasks
- **Task 1: Set up the development environment**
- Set up Visual Studio Code for Java development
- Add the SQLite JDBC driver to the project
- Create a GitHub repository
- **Task 2: Design the application**
- Identify the purpose and functionality of the application
- Determine how users will interact with the application
- Plan the classes, methods, and relationships between the classes to build the application
- **Task 3: Develop the contact class and implement object-oriented programming concepts**
- Create an abstract Contact superclass to store shared contact information
- Implement Business, Family, and Friend subclasses using inheritance
- Create constructors, getters/setters, and methods for managing contact information
- Use abstraction, inheritance, and polymorphism to organize contacts
- Create a RolodexOperations interface
- Use composition to connect the Rolodex class with the database operations class
- **Task 4: Develop the user interface**
- Create a console-based menu for the user to interact with the application
- Create options to view, search, add, update, and delete contacts
- Receive and validate user input
- Display contact information
- **Task 5: Connect to a database and implement CRUD functionality**
- Create a SQLite database to store contact information
- Establish a database connection using JDBC
- Create a contacts table
- Use SQL statements and prepared statements to interact with the database
- Use CRUD operations to add, retrieve, search, update, and delete contacts from the database
- Prevent duplicate contact entries
- **Task 6: Test the application**
- Test each menu option and database operation
- Verify contact information is save and retrieved
- Identify and correct errors
- **Task 7: Deploy the application**
- Create project documentation and README file
  
## Project Skills Learned
- Java programming and application development
- Object-oriented programming concepts and principles
- Interitance, abstraction, polymoprhism, and composition
- Creating and using interfaces
- Using constructors, getters/seters, and access specifiers
- Working with a SQLite database
- Writing SQL statements and using CRUD operations
- Writing documentation

## Language Used
- Java: Used to develops the application and implement object-oriented concepts
- SQL: Used to create the database table and perform database operations
- SQLite: Used for persistent data storage
- JDBC: Used to establish a connection between the Java application and  SQLite

## Development Process Used
- Iterative development: This application was developed in stages
- Object-oriented design: classes and interfaces were used to improve code organization and maintenance
- Testing and debugging: Features were tested throughout the development process to identify and correct errors and to create a user-friendly flow during user interaction
  
## Notes
- VS Code can be used to open the project
- SQLite JDBC driver is included in the lib folder
- Run App.java file to start the application
- The application will create a SQLite database file if one isn't created already, but one should be included in this project
- The Contacts table will be created automatically when the application starts
  
## Link to Project
https://github.com/layjen6644/dental-supply-manager

## License
This project was created as part of an assignment at ECPI for educational purposes. No license was required.

## Project Summary
The Dental Supply Manager was developed to provide a simple way to organize and maintain dental supplies. The application allows users to track disposable and reusable supplies, monitor quantities, and identify supplies that need to be reordered. 

I chose this project because of my experience in the dental field. Inventory management is an important part of maintaining an organized dental office and I wanted to develop an application that could be useful in the real-world. 

The application was developed using object-oriented programming principles. I separated the application into different classes so that each class had it's own responsibility. 
- The abstract Supply superclass contains shared properties and methods for dental supplies.
- The DisposableSupply and ReusableSupply subclasses inherit from the Supply class and provide their own implementations of the getSupplyType() method. This also demonstrates polymorphism.
- The InventoryOperations interface defines the operations available to manage supplies. The InventoryManager classes implements this interface and uses composition by containing a DatabaseManager object.
- DatabaseManager handles the SQL statements used to create the Supplies table and perform database operations.
- SQLiteDatabase establishes the database connection.
- The App class provides the user interface via a menu-driver console application.

## What Went Well
One aspect that went well was organizing the application into separate classes. This helped me keep the code organized and easier to maintain as it grew each week. Integrating the SQLite database using the JDBC also went well. Providing different classes to handle separate things kept my code easy to maintain and understand. 

## Challenges and Areas of Improvement
One of area that I found more challenging was learning the SQL statements and how to use them in Java to interact with the database. I do need more practice with this. 

## Implementation Mapping
- Inheritance: DisposableSupply and ReusableSupply extend the abstract Supply superclass
- Abstract class: Supply is an abstract superclass containing shared supply information and an abstract method getSupplyType()
- Polymorphism: Both subclasses override the getSupplyType() method and the application uses Supply references to work with the subclasses
- Encapsulation: Supply fields are private and accessed through getters/setters
- Constructors: Constructors initialize supply information in the superclass and subclasses
- Interface: InventoryOperations defines methods implemented by InventoryManager
- Composition: InventoryManager contains and uses a DatabaseManager object
- Database connectivity: SQLiteDatabase establishes a connection to the database using JDBC
- CRUD operations: The application supports adding, viewing, searching, updating, and delete supplies
- Input validation: The App class validates user input, including IDs, quantities, supply types, and blank fields

## Conclusion
Completing this project helped me develop a better understanding of how object-oriented programming concepts can be applied to a practical application. It also gave me experience with integrating relational database with Java using JDBC and SQLite. 

I was able to take an idea based on a real-world need and turn it into a function application. This project gave me the foundation using Java in the future. 
