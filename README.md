Library By Kurt Blair
Java project for a library system using object oriented program for different items a library would lend like books and electronics.

Every Item has the following:


ID

Name


Additionally, each device has a different rental Cost. This number represents the cost of renting the device per day.

Book items have the following extra information:


Authors

Publisher

Year


To apply late fees a method called getLateFees was implemented to take the number of late days as an input and gives the rental cost which differs based on the type of the item:


Item: no implementation, since an item has to be either a device or a book.

Device: fee= $2/day + %10 of rental cost

Book: fee = $0.5/day

Adaptor: fee = $2.5/day  + %15 of rental cost

Laptop: fee = $5/day  + %20 of rental cost

Textbook: fee = $1/day

Magazine: fee = $0.75/day

The Rental was created to add new transaction. The Rental stores an Item, customer ID and number of rentals days and number of days late as attributes.  

The library system, which is another Class, has a collection of rental transactions. The class has two methods:


AddTransaction: adds new transaction to the collection

GetTotalLateFees: calculates and returns the total lates fees of all rented items in the library.

GetTotalRentalCosts: calculates and returns the total rental costs of all rented devices in the library.



My grade was an A+ on this assignment.

