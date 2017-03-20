Library By Kurt Blair
Java project for a library system using object oriented program for different items a library would lend like books and electronics.

Every Item has the following:

ID
Name
Additionally, each device has an extra information, rentalCost. This number represents the cost of renting the device per day.

Book items have the following extra information:

Authors
Publisher
Year
To apply late fees, implement a method getLateFees that takes the number of late days as an input. The implementation differs based on the type of the item:

Item: no implementation, since an item has to be either a device or a book.
Device: fee= $2/day + %10 of rental cost
Book: fee = $0.5/day
Adaptor: fee = $2.5/day  + %15 of rental cost
Laptop: fee = $5/day  + %20 of rental cost
Textbook: fee = $1/day
Magazine: fee = $0.75/day
To represent a rental transaction, create a class Rental that stores an Item, customer ID and number of rentals days and number of days late as attributes.  

The library system, which is another Class, has a collection of rental transactions. The class has two methods:

AddTransaction: adds new transaction to the collection
GetTotalLateFees: calculates and returns the total lates fees of all rented items in the library.
GetTotalRentalCosts: calculates and returns the total rental costs of all rented devices in the library.
All classes should be defined in one package named library
You have to define at least 7 classes
All attributes are defined as private
You have to use inheritance
You have to use polymorphism
One class should be defined as abstract with one abstract method.
Define for every class the following:
Constructors:
Copy constructor
Constructor with all the attributes
Override the equals method
Override the toString method
Override the Clone method
Setters methods with appropriate checking (e.g. no negative ID, no empty names)
Getters methods
Item IDs are not passed through constructors and there is no setter method for it. The ID is set using a static integer variable that is incremented every time an Item is created. 
Look at ArrayList class to keep a collection of rentals
