Library By Kurt Blair

Java project for a library system using object oriented program for different items a library would lend like books and electronics. Every Item has a Name and an ID. Additionally, each device has a different rental cost. This number represents the cost of renting the device per day.


Book items have the following extra information:


Authors

Publisher

Year


To apply late fees a method called getLateFees was created to take the number of late days as input and output the rental cost which differs based on the type of the item:


Device: fee= $2/day + %10 of rental cost

Book: fee = $0.5/day

Adaptor: fee = $2.5/day  + %15 of rental cost

Laptop: fee = $5/day  + %20 of rental cost

Textbook: fee = $1/day

Magazine: fee = $0.75/day

The Rental class was created to add new transactions. The Rental class stores an Item, customer ID and number of rentals days and number of days late as attributes. The library system, which is another class, has a collection of rental transactions.


AddTransaction: adds new transaction to the collection

GetTotalLateFees: calculates and returns the total lates fees of all rented items in the library.

GetTotalRentalCosts: calculates and returns the total rental costs of all rented devices in the library.

