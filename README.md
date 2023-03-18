## Project Descripiton
This app is designed to provide a user-friendly system for airport employees to track flights and assist customers with finding available flights and relevant details such as airline, meal plans, and space left on a flight.

The app includes a PostgreSQL database schema and a C++ API that allows airport employees to interact with the database. The API's user interface includes a list of commands that airport employees can use to retrieve information about flights, update flight information, and insert new information such as creating new flights, adding passengers, and adding cargo.

Overall, this app aims to improve the customer experience at the airport by enabling airport employees to more easily and efficiently track flights and assist customers with finding available flights and relevant details.

## Implemented Function

●	exit - exits program
●	help - lists all commands
Retrieve Information:
●	arrive <icao> - lists flights leaving from <icao>
●	depart <icao> - lists flights leaving to <icao>
●	list - lists every active flight
●	mealTypes <flight-number> - lists all the categories of meals on a flight
●	meals <flight-number> - lists all the meals on a flight
●	status <flight-number> - gets information about a flight
Update Information:
●	delay <flight-number> <delay("hh:mm:ss")> - delay a plane
●	changeStatus <flight-number> <status> - change status of the plane
●	changeDestination <flight-number> <new destination> - updates the new destination  
●	changeArrival <flight-number> <new origin> - updates the new origin
Insert Information:
●	create <flight-number>, <departure("hh:mm:ss")>, <arrival("hh:mm:ss")>, <gate((A or B or C)##)>, airplane(“”), destination(ICAO), <origin(ICAO)>, <airline(“”)>
●	passenger <flight-number> - adds or removes number of passengers
●	addCargo <flight-number> [cargo-weight lb] [passenger-barcode] takes in a flight number and barcode and adds Cargo
Delete
●	removeCargo <flight-number> [passenger-barcode] - takes in a barcode and flight number and removes the referenced cargo
![image](https://user-images.githubusercontent.com/46549862/226073244-1c4e9ad0-737b-432b-9b8c-89481a380668.png)


## To build
Required packages: postgresql postgresql-contrib libpq-dev libpqxx-dev

# Ubuntu 
make new (to create database, will need further action aside from make)
make run

## Functionality
help - lists all commands
exit - exits the application

