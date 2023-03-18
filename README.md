## Project Descripiton
This app is designed to provide a user-friendly system for airport employees to track flights and assist customers with finding available flights and relevant details such as airline, meal plans, and space left on a flight.

The app includes a PostgreSQL database schema and a C++ API that allows airport employees to interact with the database. The API's user interface includes a list of commands that airport employees can use to retrieve information about flights, update flight information, and insert new information such as creating new flights, adding passengers, and adding cargo.

Overall, this app aims to improve the customer experience at the airport by enabling airport employees to more easily and efficiently track flights and assist customers with finding available flights and relevant details.

## To build
Required packages: postgresql postgresql-contrib libpq-dev libpqxx-dev

# Ubuntu 
make new (to create database, will need further action aside from make)
make run

## Functionality
help - lists all commands
exit - exits the application

